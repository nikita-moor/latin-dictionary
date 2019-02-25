# Döderlein's Hand-book of Latin Synonymes

Dictionary of **Latin** synonyms with explanations on **English** in XDXF format.


## Introduction

This dictionary bases on the English edition of "Döderlein's Hand-book of Latin Synonymes" published in 1875 and transcribed for Gutenberd project in 2010:
    
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein's Hand-book of Latin Synonymes._ Warren F. Draper, 1875. URL: <https://archive.org/details/dderleinshandbo00arnogoog> \[Accessed 24 February 2019\].
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein’s Hand-Book of Latin Synonymes by Ludwig von Doederlein_, 2010. Edited by Hope L. and Spehar I. Gutenber project. URL: <http://www.gutenberg.org/ebooks/33197> \[Accessed 24 February 2019\].

This project is aimed at transforming the dictionary into [XDXF format][1] campatible with computer dictionary shells, such as [GoldenDict][2] (Windows/Linux) or [Alpus][3] (Android). Besides, existing tools make it possible to translate XDXF into other popular formats, such as DSL for [ABBYY Lingvo][4] or Slob for [Aard2][5].


## Work in progress

* [x] initial release
* [x] dictionary keys: replace æ/œ/j to ae/oe/i
* [x] resolve abbreviation for literary sources to their full form (still unknown: Cic. ap. Colum.; Cic. Civ.; Cic. Cœl.; Cic. N. T.; Cic. Quint.; Lucil. Fr. Sat.; Quintil. Decl. ult.)
* [x] convert references to the Döderlein's grand "Lateinische Synonyme und Etymologieen" into Internet links
* [x] split articles into sub-definitions
* [ ] dictionary keys: change nouns to singular form
* [ ] dictionary keys: change verbs to form of 1st person ind. (amare > amo)
* [ ] add missing keys: 1) from lines "XXX, see YYY"; 2) from articles' text (see "abolere" for "delere")
* [ ] add Greek keys (if needed)


## Usage guidelines

[GoldenDict][2] dictionary application supports normalization of input words (pæne > paene; prāva > pravus). We recommend using ["Latin spelling and hyphenation dictionaries"][6] in combination with our Döderlein's dictionary.


## States and limitations

XDXF edition of the Döderlein's dictionary is made in aid of practical use by students of Latin courses, so its formatting may diverge from the original book. Correct transcript of the [dictionary as it was published](http://www.gutenberg.org/ebooks/33197) could be retrived from the Gutenber project.

Normalization of input words (pæne > paene; prāva > pravus; amavit > amo) in GoldenDict is based on Huspell library, which in turns requires dictionary of lemmas. In this project we use the most complete [Latin morphology dictionary][6] built by Karl Zeiler and Jean-Pierre Sutto. Keywords of the Döderlein's dictionary should be harmonized with the hunspell's output: "iuv" spelling; no ligatures (æ/œ); no macrones; verbs in 1st person singular form.

[1]: https://en.wikipedia.org/wiki/XDXF
[2]: https://en.wikipedia.org/wiki/GoldenDict
[3]: https://play.google.com/store/apps/details?id=com.ngcomputing.fora.android
[4]: https://www.abbyy.com/en-us/lingvo_mobile_dictionary/
[5]: https://play.google.com/store/apps/details?id=aarddict.android
[6]: https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries
