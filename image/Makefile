
.PHONY: all

%.eps: %.svg
	inkscape -S $*.svg -E $*.eps

all: alg.eps hdd1.eps hdd2.eps

clean:
	rm *.eps
