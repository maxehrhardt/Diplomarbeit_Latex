
* Institutsvorlage des IEEH für die Erstellung von Diplomarbeiten *

Autor: Matthias Klatt
Co-Autor: Philipp Stachel, Max Domagk

letzte Änderungen: 05.11.2012


In Zusammenarbeit der Assistenten des Instituts wurde diese Vorlage
für die Erstellung von Diplomarbeiten erstellt, wohlwissentlich dass
es auch eine Vorlage im Corporate Design gibt. Diese Vorlage wurde
nach den Vorgaben zum Erstellen von Wissenschaftlichen Arbeiten der
Fakultät ET/IT und Wünschen und Angaben von Prof. Schegner gestaltet.

Das Dokument besteht aus der Hauptdatei "diplomarbeit.tex" im
Wurzelverzeichnis. Im Ordner "Reserviert" befinden sich Dateien, die
entweder garnicht oder nur ein einziges Mal editiert werden
müssen. Die Datei, die zwingend einmal editiert werden muss um die
persönlichen Daten einzutragen ist die "Reserviert/titel_angaben.tex".

Sämtliche inhaltlichen Angelegenheiten befinden sich im Ordner "Inhalt".
Dazu gehören:

- die Kurzfassung auf deutsch (kurzfassung.tex) und englisch (abstract.tex)
- eine allgemeine Einleitung (einleitung.tex)
- das Symbolverzeichnis (symbole.tex)
- die Zusammenfassung (zusammenfassung.tex)
- das Literaturverzeichnis (literatur)
- Abbildungen für den Anhang (anhang.tex)
- und der Inhalt (zB kapitel1.tex)

Die Abbildungen (*.png) werden am besten im Ordner
"Inhalt/Abbildungen" oder nach Kapiteln sortiert (wird empfohlen)
z.B. unter "Inhalt/Abbildungen/Kapitel1" abgelegt.

Falls nur ein bestimmtes Kapitel editiert wird, so kann einfach die
Zeile "\input{Reserviert/anfang}" und alle uninteressanten Kapitel
auskommentiert werden. Um den Kompilierungsvorgang weiter zu
beschleunigen kann in der documentclass der Entwurfsmodus (draft=true)
gesetzt werden.

Zwischendurch können die Arbeitsordner von den von LaTeX erstellten
temporären Dateien mittels des Skriptes "cleanup.bat" aufgeräumt werden.

Viel Erfolg beim Setzen der Arbeiten!
