---
title: "Prüfsummen"
---

<div class="pageNavigation">
<div style="float:left;">
   [◀️ Home](index.md)
</div>
<div style="float:right;">
  [Installation ▶️](installation.md)
</div>
</div>

---------------
__Inhalt__
* TOC
{:toc}
---------------

Um sicher zu gehen, das die Installationsdatei unverändert ist und sich in dem Zustand befindet wie sie erzeugt wurde, ist es ratsam eine MD5 Prüfsumme zu erzeugen und mit der in der Tabelle unter zu vergleichen. Wenn die Prüfsummen identisch sind, ist alles in Ordnung und die Datei wurde nicht verändert, um z.B. Schadsoftware einzuschleusen. Falls die Prüfsumme jedoch abweicht, löschen Sie bitte die Installationsdatei und laden Sie diese direkt von der offiziellen [Download-Seite](https://www.sortingthoughts.de/blog/de/download/) herunter.
Um mehr über Prüfsummen zu erfahren, besuchen Sie bitte [Wikipedia.org](http://de.wikipedia.org/wiki/Checksum).

## Version 2.0.0

| Dateiname | SHA-1 Prüfsumme | MD5 Prüfsumme
|:--------|:-------:|:-------:|
| SortingThoughts-Installer_2.0.0.exe | ec3ccf3efcc723d88cebc2912ba6d14d7db4438a | 6e8c44fe3f5782e9662cd6ef27de3777  |
| SortingThoughts-2.0.0.dmg | fc254359ec17a1e454656107fa00bf2e8933a3e5 | 50468d4dde88a67b8557350e627e9c66 |

## Version 1.4.0

| Dateiname | MD5 Prüfsumme |
|:--------|:-------:|
| ST-32bit-setup-v1-4-0.exe | b59a6d591b9cd65b806239bc2512163e |
| ST-32bit-v1-4-0.dmg | 74111fd51306b48e2dc7d8d543337ab4 |
| ST-64bit-setup-v1-4-0.exe | e89dab1a21ef797ed805217f4feb9708 |
| ST-64bit-v1-4-0.dmg | 1d75b512a70177d234b76ad3b53ef7ce |
| ST-Tiger-32bit-v1-4-0.dmg | 7865a9a98971407a49b7c866669a9944 |

## Prüfsumme unter macOS erzeugen
Das Terminal Programm öffnen, mit dem cd Befehl zum Verzeichnis wechseln indem sich die Datei befindet und dann den md5 Befehl benutzen:

```
    cd Downloads
    md5 ST-64bit-v1-0-2.dmg
```

oder für SHA-1

```
    shasum -a 1 ST-v2-0-0.dmg
```

## Prüfsumme unter Windows erzeugen
Unter Windows gibt es verschiedene Programme mit denen man einen Prüfsumme erzeugen kann, z.B. [HashCheck](https://github.com/gurnec/HashCheck/releases).

---------------

<div class="pageNavigation">
<div style="float:left;">
   [◀️ Home](index.md)
</div>
<div style="float:right;">
  [Installation ▶️](installation.md)
</div>
</div>
