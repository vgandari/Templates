LaTeX Templates
=========

This repository contains my LaTeX document templates.
This file contains standards for my documents written in LaTeX.

Conventions
==========

Follow file naming convention in each module template listed below
Use prefixes for file names listed below, followed by the topic
Use \include{} to include files that call files by \input{} and when page break is desired (e.g. chapters)
Files meant to be called with \input{} should not call a second file.
Keep a list of unique equation, figure, and chapter/section headers.

File Naming Convention
----------------------

File Prefixes:

### Section/Layout (Main Matter)

+ abs - abstract
+ chp - chapter
+ sec - section
+ sub - subsction
+ sol - solution
+ res - results
+ con - conclusions

### Content

+ doc - document info (headings, etc)
+ ftn - footnote
+ sdn - sidenote (depending on layout?)
+ lis - list
+ cod - code listing (with language name as suffix)
+ fig - figure
+ tab - table
+ frm - presentation slide (frame)
+ exm - example

+ ref - reference (to be cited)
+ Qa_ - unanswered question
+ QA_ - question with answer

### Troubleshooting

+ sym - symptom
+ cau - cause
+ res - resolution


### Math

+ mot - motivation
+ obj - objective
+ giv - given information, initial/boundary conditions
+ def - definition
+ prt - properties
+ der - derivation
+ prb - problem in standard form
+ thm - theorem
+ lem - lemma with corresponding theorem(s) in file name
+ cor - corollary with corresponding theorem(s) in file name
+ eqn - equation
+ rem - remark
+ fac - fact
+ mre - main result

### Appendix

+ prf - proof
+ bib - bibliography (all references)
+ jor - journal for solutions in progress

Layout
------

Figure location
Header/footer
Margins

Packages
--------

Single header file for each document type

Fonts
-----

Must be able to configure fonts for each element individually
