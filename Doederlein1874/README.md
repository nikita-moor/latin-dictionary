# Döderlein's Hand-book of Latin Synonymes

Dictionary of **Latin** synonyms with explanations on **English** in XDXF format.


## Exemplum

Femina; Mulier; Uxor; Coniunx; Marita

1. **Femina** (φυομένη) denotes woman with regard to her physical nature and sex, as bringing forth, in opp. to _mas_; whereas **mulier** (from mollis), woman, in a physical point of view, as the weaker and more tender sex, in opp. to _vir_; whence **femina** only can be used for the female of an animal. 
2. **Mulier** denotes also the married woman, in opp. to _virgo_, Cic. Verr. ii. 1; whereas **uxor** and **conjux**…


## Sources

This dictionary bases on the English edition of "Döderlein's Hand-book of Latin Synonymes" published in 1875 and transcribed for Gutenberd project in 2010:
    
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein's Hand-book of Latin Synonymes._ Warren F. Draper, 1875. URL: <https://archive.org/details/dderleinshandbo00arnogoog> \[Accessed 24 February 2019\].
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein’s Hand-Book of Latin Synonymes by Ludwig von Doederlein_, 2010. Edited by Hope L. & Spehar I. Gutenber project. URL: <http://www.gutenberg.org/ebooks/33197> \[Accessed 24 February 2019\].


## Usage guidelines

This project is aimed at transforming the dictionary into [XDXF format][1] campatible with computer dictionary shells, such as [GoldenDict][2] (Windows/Linux/Mac) or [Alpus][3] (Android). Besides, existing tools make it possible to translate XDXF into other popular formats, such as DSL for [ABBYY Lingvo][4] or Slob for [Aard2][5].

[GoldenDict][2] dictionary application supports normalization of input words (pæne > paene; prāva > pravus). We recommend using ["Latin spelling and hyphenation dictionaries"][6] in combination with our Döderlein's dictionary.

Default formatting styles for XDXF in GoldenDict do not fit well this dictionary (such as big intervals between keywords), one could use optional `article-style.css` improving layout and fixing existing issues (lists numeration indents). See application's [FAQ][7] for setting up.


## States and limitations

XDXF edition of the Döderlein's dictionary is made in aid of students of Latin courses, so its formatting may diverge from the original book. Correct transcript of the dictionary as it was published [could be retrived][8] from the Gutenber project.

Normalization of input words (pæne > paene; prāva > pravus; amavit > amo) in GoldenDict is based on Huspell library, which in turns requires dictionary of lemmas. In this project we use the most complete [Latin morphology dictionary][6] built by Karl Zeiler and Jean-Pierre Sutto. Keywords of the Döderlein's dictionary should be harmonized with the hunspell's output: "iuv" spelling; no ligatures (æ/œ); no macrones; verbs in 1st person singular form.

We tried to extract as much of machine readable information as possible, so the dictionary in XDXF format is almost logical. Handling of literal sources was made only in part, transforming quotations into examples (`<ex>`) requires complex approach and was postponed for future, considering difficulty of the problem and insignificance of the result. Imbedded styling (`<c c="#color">`) is used only (and exclusively) for Greek words. Also, three non-lexical articles were included to represent information about the dictionary: ABOUT_DOEDERLEIN, DOEDERLEIN_INTRO, and DOEDERLEIN_PREFACE.

In order to fully reproduce original book, edition with Greek keys was prepared (`Doederlein1874_Greek.zip`). However, its practical use is questinable and for ordinal students of Latin courses we recommend downloading simple Latin version (`Doederlein1874.zip`). _Download section to be made with release._


## License

ToDo: Creative Commons or other compatible with Guttenberg…


## Work in progress

* [x] initial release
* [x] dictionary keys: replace æ/œ/j to ae/oe/i
* [x] resolve abbreviation for literary sources to their full forms (still unknown: Cic. ap. Colum.; Cic. Civ.; Cic. Cœl.; Cic. N. T.; Cic. Quint.; Lucil. Fr. Sat.; Quintil. Decl. ult.)
* [x] convert references to the Döderlein's grand "Lateinische Synonyme und Etymologieen" into Internet links
* [x] split articles into sub-definitions
* [x] Greek words are highlighted by color
* [x] add 3 auxiliary articles: ABOUT_DOEDERLEIN, DOEDERLEIN_INTRO, DOEDERLEIN_PREFACE
* [x] fix em-dash symbols
* [x] GoldenDict CSS styles
* [x] add Greek keys (if needed)
* [ ] dictionary keys: lemmatization (amare > amo; annales > annalis) — **65% WIP**
* [ ] add missing keys: 1) from lines "XXX, see YYY"; 2) from articles' text (see "abolere" for "delere")


[1]: https://en.wikipedia.org/wiki/XDXF
[2]: https://en.wikipedia.org/wiki/GoldenDict
[3]: https://play.google.com/store/apps/details?id=com.ngcomputing.fora.android
[4]: https://www.abbyy.com/en-us/lingvo_mobile_dictionary/
[5]: https://play.google.com/store/apps/details?id=aarddict.android
[6]: https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries
[7]: http://goldendict.org/wiki/index.php/FAQ#How_do_I_change_the_font_used_for_the_articles.3F_Or_alter_its_appearance_in_any_other_way.3F
[8]: http://www.gutenberg.org/ebooks/33197
