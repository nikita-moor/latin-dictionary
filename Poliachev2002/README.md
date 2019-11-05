# Russian-Latin Dictionary, Poliachev (2002)

Here are source files of the dictionary. If you are looking for the release, see [official site][1].


## Source file mark-up and content notes

Four characters `[]%_` are used exclusively for mark-up:

* square brackets ([]) frame words flexion
* hash sign (%) marks abbreviations, such as `%adj.%`
* underscore (_) is used for italic text, such as `_or_`

Definitions (translations) are always written in one line
some articles contain sub-definitions starting with number "1. "
see "адрес" for example

Examples have the following structure:

```
+ russian_text latin_text
```

in rare cases raw XML format is used (11 lines in total):

```xml
<ex>
  <ex_orig>«ликтор» называется так от слова «ligare»</ex_orig>
  <ex_tran>“lictor” a “ligando” appellatur</ex_tran>
</ex>
```

inter-dictionary references are coded as separate lines
starting with the keyword `см.`:

```
см. булка
```

## Source:

Поляшев М. П. Большой русско-латинский словарь. 2002. URL: <http://linguaeterna.com/ru/lexi.php>.


## License

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://licensebuttons.net/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>


[1]: https://nikita-moor.github.io/dictionaries/dictionaries/Poliachev2002.html
