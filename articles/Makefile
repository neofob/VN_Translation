# Silly Makefile for the unicode UTF8 html files
# Author: Tuan T. Pham
# Last updated: 03/14/12 refractored files into different dirs

ALL_DIRS=CFR CSM Economist ForeignAffairs NPR Others TheAtlantic

all:
	-for d in $(ALL_DIRS); do (cd $$d; make all ); done

clean:
	-for d in $(ALL_DIRS); do (cd $$d; make clean ); done
