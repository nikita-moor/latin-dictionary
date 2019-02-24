# Döderlein's Hand-book of Latin Synonymes

Dictionary of **Latin** synonyms with explanations on **English** in XDXF format.


## Introduction

This dictionary bases on the English edition published in 1875 and transcribed for Gutenberd project in 2010:
    
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein's Hand-book of Latin Synonymes._ Warren F. Draper, 1875. URL: <https://archive.org/details/dderleinshandbo00arnogoog> \[Accessed 24 February 2019\].
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein’s Hand-Book of Latin Synonymes by Ludwig von Doederlein_, 2010. Edited by Hope L. and Spehar I. Gutenber project. URL: <http://www.gutenberg.org/ebooks/33197> \[Accessed 24 February 2019\].

This project is aimed at transforming the dictionary into [XDXF format][1] campatible with computer dictionary shells, such as [GoldenDict][2] (Windows/Linux) or [Alpus][3] (Android). Besides, existing tools make it possible to translate XDXF into other popular formats, such as DSL for [ABBYY Lingvo][4] or Slob for [Aard2][5].


## Changelog

1. Initial release
2. Replacing æ/œ to ae/oe (only in keys) in correspondence to the Huspell's Latin dictionary
3. Resolve abbreviation for literary sources to their full form


## ToDo

4. Convert references to the Döderlein's grand "Lateinische Synonyme und Etymologieen" into Internet links
1. Dictionary keys: change nouns to singular form
1. Dictionary keys: change verbs to form of 1st person ind. (amare > amo)
1. Dictionary keys: replace "j" to "i" in keys
1. Add missing keys (from lines "XXX, see YYY")
1. Add Greek keys (if needed)


## Usage guidelines

[GoldenDict][2] dictionary application supports normalization of input words (pæne > paene; prāva > pravus). We recommend using ["Latin spelling and hyphenation dictionaries"][6] in combination with our Döderlein's dictionary.


## States and limitations

XDXF edition of the Döderlein's dictionary is made in aid of practical use by students of Latin courses, so its formatting may diverge from the original book. Correct transcript of the [dictionary as it was published](http://www.gutenberg.org/ebooks/33197) could be retrived from the Gutenber project.

Normalization of input words (pæne > paene; prāva > pravus; amavit > amo) in GoldenDict is based on Huspell library, which in turns requires dictionary of lemmas. In this project we use the most complete [Latin morphology dictionary][6] built by Karl Zeiler and Jean-Pierre Sutto. Keywords of the Döderlein's dictionary should be harmonized with the hunspell's output: "iuv" spelling; without "æ" and "œ"; without macrones; verbs in 1st person singular.

[1]: https://en.wikipedia.org/wiki/XDXF
[2]: https://en.wikipedia.org/wiki/GoldenDict
[3]: https://play.google.com/store/apps/details?id=com.ngcomputing.fora.android
[4]: https://www.abbyy.com/en-us/lingvo_mobile_dictionary/
[5]: https://play.google.com/store/apps/details?id=aarddict.android
[6]: https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries
