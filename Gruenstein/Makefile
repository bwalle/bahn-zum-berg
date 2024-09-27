all: Gruenstein.pdf Gruenstein.odt

%.pdf: %.md
	pandoc -o $@ $<

%.odt: %.md
	pandoc -o $@ $<
