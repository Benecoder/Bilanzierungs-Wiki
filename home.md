Hier liegt die Dokumentation zu der CO2 Bilanzierung.

* [CRF 1 Energy](CRF1/CRF1.md)
* [CRF 2 Industrial Processes and product use](CRF2/CRF2.md)
* [CRF 3 Agriculture](CRF3/CRF3.md)
* [CRF 4 LULUCF](CRF4/CRF4.md)
* [CRF 5 Waste](CRF5/CRF5.md)

# Die Bilanzierung
Die Bilanzierung ist ein Tool um die Szenarien für die direkten Treibhausgasemissionen über die nächsten 15 Jahre zu berechnen.
Dabei werden die die Emissionen mit den zugrundeliegenden volkswirtschaftlichen Größen, sogeannnten Aktivitätsdaten, verbunden.
Es werden alle direkten Emissionen bilanziert, die innerhalb der Grenzen der Bundesrepublik anfallen.
Emissionen, die bei der Produktion von Importgütern anfallen, werden genauso ignoriert wie Emissionen von Produkten, die für den Export bestimmt sind. 

# Die Methodik
Die Berechnung schreibt die Emissionskategorien aus dem nationalen Emissionsinventar (NIR) 2021 weiter.
Dabei werden 174 Emissionskategorien differenziert, die jedes Jahr am 15.4 zusammen mit einem Teil der Aktivitätsdaten für das vor-vor-Jahr veröffentlicht werden.
Der Inventarbericht liegt als [Excel Tabelle](https://unfccc.int/documents/210532) und in einer [ausführlichen Dokumentation](https://unfccc.int/documents/226313) vor.
Die Methodik ist international standartisiert und folgt den [Vorgaben des IPCC](https://www.ipcc-nggip.iges.or.jp/public/2006gl/index.html).

Für die Bilanzierung wurde erst die Emissionsstatistik aus dem Jahr 2019 nachvollzogen.
Als Ausgangspunkt für die Aktivitätsdaten wird im Rahmen der Bilanzierung auf die Statistiken aus dem NIR zurück gegriffen, wenn diese Vorliegen.
In Fällen in denen der Detailgrad in den Daten des NIR nicht ausreicht, werden alternative Datenquellen genutzt.
Im nächsten Schritt werden dann die Aktivitätsdaten fortgeschrieben und so eine Prognose über die Emissionen der nächsten 15 Jahre berechnet.
Die Rechnung erfolgt in 7 verschränkten Escel sheets.
Die Annahmen, die ein bestimmtes Szenario ausmachen werden direkt in den Excel Tabellen eingestellt.
Die Ergebnisse können dann aus den Tabellen und Diagramme abgelesen werden

Die Emissionenkategorein sind wiederum in Überkategorien zusammengefasst. s.o.

# Wichtige Grundlagen

Insbesondere soll durch dieses Modell die Möglichkeit Deutschland ab 2035 klimaneutral zu machen aufgezeigt werden.
Daher laufen die Zeitreihen zunächst für die nächsten 15 Jahre.
Es werden dabei nicht alle Treibhausgase aus dem NIR sondern zunächst ausschließlich CO2, CH4, N2O und eine Sammlung von F-Gasen berücksichtigt.
Für die Umrechnung in CO2-Äquivalente werden folgende global-warming Faktoren genutzt.

| | CO2 | CH4 | N2O | F-Gase |
|-|-|-|-|-|
|t CO2e / t Gas|1|25|298|-|
