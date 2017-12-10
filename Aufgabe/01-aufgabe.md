



# Aufgabe

Setzen Sie das beiliegende Design für die Website der fiktiven Type Foundry
»Lettercase« mithilfe von HTML und CSS bis zum 05.12.2017 um.

Kontrollieren Sie die Umsetzung anhand von Screenshots. Referenzbrowser für
diese Aufgabe ist die aktuelle Version von Google Chrome. Verwenden Sie die
Developer Tools im Browser, insbesondere bei unerwarteten Ergebnissen.

Weitere Anweisungen befinden sich in folgenden Dateien:

* 02-setup.md
* 03-home.md
* 04-typefaces.md
* 05-contact.md



## Design

Die beigefügte Schriftdatei ArbutusSlab-Regular.ttf ist für die korrekte
Darstellung des Designs zu installieren. Diese Schriftdatei ist für die
technische Umsetzung   n i c h t   zu verwenden.

Verwenden Sie unter Windows ggf. die Schrift »Lucida Sans Unicode« anstatt
»Lucida Grande« in Illustrator.

Beachten Sie die Anmerkungen in der Ebene »Annotations«. Der Raster ist anhand
der Ebenen »Grid« und »Nested form grid« ersichtlich.

Die benötigten Bilder befinden sich bereits in »assets/images«.



## CSS-Struktur

Um die Stildeklarationen übersichtlich zu halten, sind die Stylesheets
thematisch auf mehrere CSS-Dateien (»Partials«) aufgeteilt. Diese werden in
»main.css« importiert, welche als einzige CSS-Datei direkt im HTML verlinkt ist.

* main.css: Importiert alle CSS-Partials
* scaffolding.css: Für das »Grundgerüst« der Website (all jene Stile, die
  thematisch nicht in die folgenden Partials passen)
* buttons.css: Für Stile, die Buttons betreffen
* footer.css: Für Stile, die den Footer betreffen
* forms.css: Für Stile, die Formulare betreffen
* grid.css: Für den 12 Column Grid
* header.css: Für Stile, die den Header betreffen
* type.css: Für typographische Stile



## Allgemeine Arbeitsschritte

* Längenangaben im Design verstehen sich als   v i s u e l l e   Abstände,
  die dafür erforderlichen Werte im CSS können davon abweichen.

* Verwenden Sie für Links, deren Ziel nicht existiert href="#".

* Verwenden Sie die »width« und »height« Attribute in Bildern, sowie das »alt«
  Attribut mit den angegebenen alternativen Bildtexten.

* Für alle CSS-Klassen ist die »lisp-case« Namenskonvention zu verwenden
  (zb .teaser, .typeface-details, …).

* Fassen Sie – wenn möglich – gemeinsame Stildeklarationen zusammen
  (DRY – don’t repeat yourself), zB:
  h1, h2 {
    color: #333;
  }

* Verwenden Sie die W3C Validatoren, um das Markup und die Stylesheets zu
  überprüfen!