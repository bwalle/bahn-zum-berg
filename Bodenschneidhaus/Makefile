mkfile_path := $(abspath $(lastword $(MAKEFILE_LIST)))
current_dir := $(notdir $(patsubst %/,%,$(dir $(mkfile_path))))
document_base = $(current_dir)


all: $(document_base).pdf $(document_base).odt

%.pdf: %.md
	pandoc -o $@ $<

%.odt: %.md
	pandoc -o $@ $<

.PHONY: clean
clean:
	rm $(document_base).odt $(document_base).pdf
