

FIG=$(wildcard *.svg)
PNG=$(patsubst %.svg,%.png,$(wildcard *.svg))

all: $(PNG)

%.png: %.svg
	inkscape $(basename $@).svg  -D -d 300 -e $@
	
clean:
	rm -rf $(EPS) $(PDF)

