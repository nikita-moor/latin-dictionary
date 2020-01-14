# Intro

Here are some notes about the content and format of the "A Greek-English Lexicon" (Liddell & Scott, 1940) you could find in the [Perseus repository][1].

File `_map.py` is a part of the Python library [betacode][2]. Greek text coding standart in the Perseus repository differs from the [TLG Beta Code Manual][3], so one need substitute mapping table with our variant based on the [Greek Betacode to Unicode Transformations][4] guide.

[1]: https://github.com/PerseusDL/lexica/tree/master/CTS_XML_TEI/perseus/pdllex/grc/lsj
[2]: https://github.com/matgrioni/betacode
[3]: http://www.tlg.uci.edu/encoding/BCM.pdf
[4]: https://github.com/PerseusDL/tei-conversion-tools/wiki/Greek-Betacode-to-Unicode-Transformations


# Tags used in entryFree

## grammar

* orth - normal form of the word
* itype - inflectional class
* gen - gender
* number - text: sg., pl., dual
* pron
* pos - part of speech: Adv., Subst., Adj.
* tns - tense: aor., pres., fut., [...]
* per - person: 1, 2, 3, 1st, 2nd, [...]
* mood - mood: inf., indic., subj., part.
* subc - subcategorization: Dep.

## semantic

* gramGrp
  - gram
* sense - definition
  - @level: 0-4
* xr - cross-reference
  - lbl - some note
  - ref - referenced word
* cit
  - quote
  - bibl
* bibl
  - biblScope
  - author
  - title (also child of entryFree, sense)
* pb - page beginning
* placeName
* date
* name

## content

* foreign - @lang: la, greek
* num - greek numerals
* abbr
* tr (replace to "dict_tr") - translation of the word
* etym
* hi - highlighted: sup, bold, ital
* sic (grc.lsj.perseus-eng11.xml) - incorrect original text
* corr (grc.lsj.perseus-eng11.xml) - correction of `sic` text

## betacode

Following nodes could contain betacode:

* any node with @lang="greek"
* num

