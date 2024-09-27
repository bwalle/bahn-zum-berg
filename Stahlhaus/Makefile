all: Stahlhaus.pdf Stahlhaus.odt

%.pdf: %.md
	pandoc -o $@ $<

%.odt: %.md
	pandoc -o $@ $<
