# Literatur

In diesem Repository findet ihr alle Informationen zu Literatur. Ihr findet hier Informationen zur Literaturrecherche sowie eine Sammlung eurer Literatur. Ihr speichert eure Literatur in einer [BibTex-Datei](https://de.wikipedia.org/wiki/BibTeX). 

## BibTex
BibTex ist nichts anderes als ein Dateiformat, in welchem Literaturquellen gespeichert werden. Wir verwenden BibTex, damit wir uns nicht um die Formatierung der Literaturquellen kümmern müssen. In unserem Fachbereich zitieren wir nach **APA**. Da die Zitierung nicht immer ganz einfach ist, lassen wir uns die Arbeit übernehmen. Am Ende habt ihr ein wohl formatiertes Dokument. 

BibTex folgt einer eigenen Syntax. Ihr müsst diese nicht auswendig lernen. Ein erster Blick ist allerdings hilfreich:

```
@book{noddings2016,
  title={Philosophy of education},
  author={Noddings, Nel},
  year={2016},
  publisher={Westview Press}
}
```

In der Datei [bibliography.bib](https://github.com/seminar-bildungssysteme-ss2016/themen/blob/master/bibliography.bib) sammelt ihr diese Quellen. Ihr müsst hierfür lernen, wie ihr BibTex Quellen erstellt. Folgende Quellen sind hierbei hilfreich:

* [Hier](http://www.literatur-generator.de/) könnt ihr die Quellen nach **ISBN** und anderen Suchkriterien erstellen.
* Unter [Google Scholar](https://scholar.google.de/) könnt ihr Fachartikel recherchieren und euch unter **Zitieren** die BibTex Quelle angeben lassen.
* Solltet ihr unter diesen Seiten nicht fündig werden, könnt ihr eure Quelle unter [dieser](http://truben.no/latex/bibtex/) Seite erstellen.

### Vorgehen
Sobald ihr eine Quelle in euer Dokument einbindet, erstellt ihr die zugehörige Quelle in der Datei [bibliography.bib](https://github.com/seminar-bildungssysteme-ss2016/themen/blob/master/bibliography.bib). Innerhalb eures Dokumentes müsst ihr euch auf diese Quelle beziehen: Wenn ich zum Beispiel die obere Quelle einbinden möchte (**noddings2016**), würde ich es wie folgt schreiben:

```
@noddings2016 sagt, Bildung ist sehr wichtig. Das deutsche Bildungssystem ist föderal aufgebaut [@noddings2016]. "Philosophy of education is the philosophical study of education and its problems" [@noddings2016, p. xiii]. 
```

Mehr Information über die Einbindung der Quellen findet ihr [hier](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html#citations). 

