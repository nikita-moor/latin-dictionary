# Döderlein's Hand-book of Latin Synonymes

Dictionary of **Latin** synonyms with explanations on **English**, in XDXF format. [Download](https://github.com/nikita-moor/latin-dictionary/releases/tag/doederlein1874-6).

## Exemplum

[![puella-small](https://user-images.githubusercontent.com/13879891/54175983-eb50b500-449d-11e9-8c00-a9869ef148aa.png)](https://user-images.githubusercontent.com/13879891/54175982-eb50b500-449d-11e9-9620-ad1bbec759e0.png) [![lacrimare-small](https://user-images.githubusercontent.com/13879891/54175880-944ae000-449d-11e9-888a-281afb307037.png)](https://user-images.githubusercontent.com/13879891/54175878-944ae000-449d-11e9-92c5-a27193247c62.png)


## Sources

This dictionary bases on the English edition of "Döderlein's Hand-book of Latin Synonymes" published in 1875 and transcribed for Gutenberd project in 2010:
    
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein's Hand-book of Latin Synonymes._ Warren F. Draper, 1875. URL: <https://archive.org/details/dderleinshandbo00arnogoog> \[Accessed 24 February 2019\].
1. Von Döderlein, L.; Taylor, S. H. & Arnold, H. H. _Döderlein’s Hand-Book of Latin Synonymes by Ludwig von Doederlein_, 2010. Edited by Hope L. & Spehar I. Gutenber project. URL: <http://www.gutenberg.org/ebooks/33197> \[Accessed 24 February 2019\].


## Usage guidelines

This project is aimed at transforming the dictionary into [XDXF format][1] compatible with computer dictionary shells, such as [GoldenDict][2] (Windows/Linux/Mac) or [Alpus][3] (Android). Besides, existing tools make it possible to translate XDXF into other popular formats, such as DSL for ABBYY Lingvo or Slob for Aard2.

[GoldenDict][2] dictionary application supports normalization of input words (pæne > paene; prāva > pravus). We recommend using ["Latin spelling and hyphenation dictionaries"][6] (by Karl Zeiler and Jean-Pierre Sutto); version of the dictionary prepared by [Konrad Kokoszkiewicz][9] should be compatible too.

Default formatting styles for XDXF in GoldenDict do not fit well this dictionary (such as big intervals between keywords), one could use optional `article-style.css` improving layout and fixing existing issues (lists numeration indents). See application's [FAQ][7] for setting up.


## States and limitations

XDXF edition of the Döderlein's dictionary is made in aid of students of Latin courses, so its formatting may diverge from the original book. Exact transcript of the dictionary as it was published [could be retrived][8] from the Gutenber project.

Dictionary keys were normalized (`pæne > paene`, `vicini > vicinus`, `amare > amo`) in accordance with [Latin morphology dictionary][6] built by Karl Zeiler and Jean-Pierre Sutto for Hunspell: "iuv" spelling without ligatures (æ/œ). About 300 keys were added to make indexing more convinient, these keys represent infrormation already existing in the articles and add nothing to the content (e.g. "olor" and "olidus" were added to "olere").

Greek keys are added as stub article "For αβγ see abc". It is not very convenient, so to open the corresponding article user need to make additional click, but prevents bloating of the keywords lists (i.e. visual design problem). I am not competent in Greek language, so all Greek keys are left without normalization or any change, and save their form as is in the text.

We tried to extract as much of machine readable information as possible, so the dictionary in XDXF format is almost logical. Handling of literal sources was made only in part, transforming quotations into examples (`<ex>`) requires complex approach and was postponed for future, considering difficulty of the problem and insignificance of the result. Imbedded styling (`<c c="#color">`) is used only and exclusively for Greek words. Also, three non-lexical articles were included to represent information about the dictionary: ABOUT_DOEDERLEIN, DOEDERLEIN_INTRO, and DOEDERLEIN_PREFACE.


## Errata

Typos found and fixed in the text of the edition of 1863 (line numbers by the transcript):

1. "sodes" to "sordes", line #5583
1. "prædia" to "prædæ", line #7236
1. "diutunus" to "diuturnus", line #7333

Reference "(295.)" in "casus" article was resolved to "(v. 295.)".

Small changes in formatting (such as change of bold to italic) were made in the articles discussing following words: "numen", "tellus", "ludicrum", "restituere", "pigritia", "perperam", "sacer".


## License

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://licensebuttons.net/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>


## ToDo (in the distant future)

* [ ] fix lemmatizing process for "j"-spelling
* [ ] develop smarter algorithm for authors detection


[1]: https://en.wikipedia.org/wiki/XDXF
[2]: https://en.wikipedia.org/wiki/GoldenDict
[3]: https://play.google.com/store/apps/details?id=com.ngcomputing.fora.android
[6]: https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries
[7]: http://goldendict.org/wiki/index.php/FAQ#How_do_I_change_the_font_used_for_the_articles.3F_Or_alter_its_appearance_in_any_other_way.3F
[8]: http://www.gutenberg.org/ebooks/33197
[9]: http://www.obta.uw.edu.pl/~draco/
