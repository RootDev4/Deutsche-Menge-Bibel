# Die Bibel (Hermann Menge Übersetzung)

Dieses Repository enthält die gemeinfreie Bibelübersetzung nach Hermann Menge. Vielen Dank an [renehamburger](https://github.com/renehamburger/Menge-Bibel) für das Bereitstellen der Menge-Bibel als Markdown.

## API

Die Bibel kann über die [jsDelivr](https://www.jsdelivr.com) API abgefragt werden.

```bash
https://cdn.jsdelivr.net/gh/RootDev4/Deutsche-Menge-Bibel@main/books/{buch_id}/{kapitel}.json
```

### Kapitel
Beispiel: 1\. Kapitel des Buches 1. Mose (Genesis)
```bash
https://cdn.jsdelivr.net/gh/RootDev4/Deutsche-Menge-Bibel@main/books/GEN/1.json
```

### Verse
```json
{
  "chapter": 1,
  "verses": [
    {
      "verse": 1,
      "text": "Im Anfang schuf Gott den Himmel und die Erde;"
    },
    {
      "verse": 2,
      "text": "die Erde war aber eine Wüstenei und Öde, und Finsternis lag über der weiten Flut, und der Geist Gottes schwebte (brütend) über der Wasserfläche."
    },
    {
      "verse": 3,
      "text": "Da sprach Gott: »Es werde Licht!«, und es ward Licht."
    },
    ...
  ]
}
```

## Bücher
### Altes Testament – Der Pentateuch (Die 5 Bücher Mose)

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `GEN` | 1. Mose | Genesis | 50 | 1533 |
| `EXO` | 2. Mose | Exodus | 40 | 1212 |
| `LEV` | 3. Mose | Leviticus | 27 | 859 |
| `NUM` | 4. Mose | Numbers | 36 | 1288 |
| `DEU` | 5. Mose | Deuteronomy | 34 | 956 |

### Altes Testament – Geschichtsbücher

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `JOS` | Josua | Joshua | 24 | 658 |
| `JDG` | Richter | Judges | 21 | 618 |
| `RUT` | Ruth | Ruth | 4 | 85 |
| `1SA` | 1. Samuel | 1 Samuel | 31 | 811 |
| `2SA` | 2. Samuel | 2 Samuel | 24 | 695 |
| `1KI` | 1. Könige | 1 Kings | 22 | 817 |
| `2KI` | 2. Könige | 2 Kings | 25 | 719 |
| `1CH` | 1. Chronik | 1 Chronicles | 29 | 942 |
| `2CH` | 2. Chronik | 2 Chronicles | 36 | 821 |
| `EZR` | Esra | Ezra | 10 | 280 |
| `NEH` | Nehemia | Nehemiah | 13 | 406 |
| `EST` | Esther | Esther | 10 | 167 |

### Altes Testament – Lehr- und Weisheitsbücher

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `JOB` | Hiob | Job | 42 | 1070 |
| `PSA` | Psalmen | Psalms | 150 | 2529 |
| `PRO` | Sprüche | Proverbs | 31 | 915 |
| `ECC` | Prediger | Ecclesiastes | 12 | 222 |
| `SNG` | Hohelied | Song of Solomon | 8 | 117 |

### Altes Testament – Große Propheten

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `ISA` | Jesaja | Isaiah | 66 | 1289 |
| `JER` | Jeremia | Jeremiah | 52 | 1364 |
| `LAM` | Klagelieder | Lamentations | 5 | 154 |
| `EZK` | Hesekiel | Ezekiel | 48 | 1273 |
| `DAN` | Daniel | Daniel | 12 | 357 |

### Altes Testament – Kleine Propheten

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `HOS` | Hosea | Hosea | 14 | 197 |
| `JOL` | Joel | Joel | 4 | 73 |
| `AMO` | Amos | Amos | 9 | 146 |
| `OBA` | Obadja | Obadiah | 1 | 21 |
| `JON` | Jona | Jonah | 4 | 47 |
| `MIC` | Micha | Micah | 7 | 105 |
| `NAM` | Nahum | Nahum | 3 | 47 |
| `HAB` | Habakuk | Habakkuk | 3 | 56 |
| `ZEP` | Zephanja | Zephaniah | 3 | 53 |
| `HAG` | Haggai | Haggai | 2 | 38 |
| `ZEC` | Sacharja | Zechariah | 14 | 211 |
| `MAL` | Maleachi | Malachi | 3 | 55 |

### Neues Testament – Evangelien

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `MAT` | Matthäus | Matthew | 28 | 1070 |
| `MRK` | Markus | Mark | 16 | 678 |
| `LUK` | Lukas | Luke | 24 | 1151 |
| `JHN` | Johannes | John | 21 | 876 |

### Neues Testament – Geschichtsbuch

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `ACT` | Apostelgeschichte | Acts | 28 | 1006 |

### Neues Testament – Paulusbriefe

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `ROM` | Römer | Romans | 16 | 433 |
| `1CO` | 1. Korinther | 1 Corinthians | 16 | 436 |
| `2CO` | 2. Korinther | 2 Corinthians | 13 | 256 |
| `GAL` | Galater | Galatians | 6 | 149 |
| `EPH` | Epheser | Ephesians | 6 | 155 |
| `PHP` | Philipper | Philippians | 4 | 104 |
| `COL` | Kolosser | Colossians | 4 | 95 |
| `1TH` | 1. Thessalonicher | 1 Thessalonians | 5 | 89 |
| `2TH` | 2. Thessalonicher | 2 Thessalonians | 3 | 47 |
| `1TI` | 1. Timotheus | 1 Timothy | 6 | 113 |
| `2TI` | 2. Timotheus | 2 Timothy | 4 | 83 |
| `TIT` | Titus | Titus | 3 | 46 |
| `PHM` | Philemon | Philemon | 1 | 25 |

### Neues Testament – Weitere Briefe

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `HEB` | Hebräer | Hebrews | 13 | 303 |
| `JAS` | Jakobus | James | 5 | 108 |
| `1PE` | 1. Petrus | 1 Peter | 5 | 105 |
| `2PE` | 2. Petrus | 2 Peter | 3 | 61 |
| `1JN` | 1. Johannes | 1 John | 5 | 105 |
| `2JN` | 2. Johannes | 2 John | 1 | 13 |
| `3JN` | 3. Johannes | 3 John | 1 | 15 |
| `JUD` | Judas | Jude | 1 | 25 |

### Neues Testament – Prophetisches Buch

| ID | Deutsch | Englisch | Kapitel | Verse |
| --- | --- | --- | --- | --- |
| `REV` | Offenbarung | Revelation | 22 | 404 |

---

## Lizenz
Die Bibel in der Übersetzung von Hermann Mengeist nach deutschem Urheberrecht seit 2010 gemeinfrei und ist damit in Deutschland frei von Schutzrechten ([Public Domain Mark 1.0](https://creativecommons.org/publicdomain/mark/1.0/deed.de)).

Du kannst die Texte und auch diese API-Schnittstelle damit kostenfrei und lizenzfrei verwenden.