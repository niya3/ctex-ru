# -*- coding: koi8-r -*-
#
# ���������� �������� program
#
# 2012 (c)  �.�. ������ 
#

include ../rules.mk

PICS := make-up-text-size.eps

all: $(PICS) 

make-up-text-size.eps:  make-up-text-size.tex ../structheader.tex
	$(PREFIX)$(LATEX) make-up-text-size.tex
	$(PREFIX)$(DVIPS) -E make-up-text-size.dvi -o make-up-text-size.eps


include ../rules-post.mk

