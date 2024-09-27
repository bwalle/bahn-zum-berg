all: Blaueishuette.pdf Blaueishuette.odt

%.pdf: %.md
	pandoc -o $@ $<

%.odt: %.md
	pandoc -o $@ $<
