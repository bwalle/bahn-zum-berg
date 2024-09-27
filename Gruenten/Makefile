all: Gruenten.pdf Gruenten.odt

%.pdf: %.md
	pandoc -o $@ $<

%.odt: %.md
	pandoc -o $@ $<
