



# Setup



## Grid

Erstellen Sie einen auf Flexbox basierenden modularen 12 Column Grid:
Container-Gesamtbreite 970px (effektiver Satzspiegel 940px), 30px Spaltenabstand
(Gutter).

Der Container ist bereits vorhanden, fügen Sie noch folgende Elemente hinzu:

* Row

* Columns

* Verwenden Sie für Prozentwerte mit Kommastellen die CSS »calc()« Funktion.



## Typographie

* Schriftart: "Lucida Grande", "Lucida Sans Unicode", sans-serif

* Schriftgröße 14px

* Zeilenhöhe 20px

* Setzen Sie den Blauton für Links entsprechend der Designvorlage.

* Entfernen Sie die Unterstreichung im Normalzustand der Links, im Hover-Zustand
  sollen Links unterstrichen sein (Ausnahme: Links im Header und in Headlines)

* Binden Sie den Google Font »Arbutus Slab« von fonts.google.com mit der
  CSS-Methode in allen HTML-Dateien ein.

* Definieren Sie für H1 und H2 als Schriftart:
  "Arbutus Slab", Georgia, serif

* Definieren Sie für alle Headlines #333 als Schriftfarbe.

* Definieren Sie die Stile für H1, H2, H3 und Paragraph laut der
  Designvorlage.



## Header

* Geben sie dem <header> Element die Klasse »navbar«.

* Ersetzen Sie den Text »Lettercase« durch das Bild »logo.svg«.

* Übernehmen Sie die Breite und Höhe aus der SVG-Datei (im Editor öffnen) für
  die Bild-Attribute »width« und »height«.

* Geben Sie »Lettercase« als alternativen Bildtext an.

* Verwenden Sie für die Links in der Navigation eine ungeordnete Liste.

* Schachteln Sie die Liste in ein für Navigationen geeignetes semantisches
  HTML5-Element

* Setzen Sie das Layout der Navbar mithilfe von Flexbox um (dafür sind mehrere
  geschachtelte Flex-Container notwendig).

* Wandeln Sie die Links in der Navbar in Block-Level Elemente um.

* Setzen Sie die Klasse »active« auf das <li> des jeweils aktuellen Links.

* Fixieren Sie die Navbar in der linken oberen Ecke des Viewports
