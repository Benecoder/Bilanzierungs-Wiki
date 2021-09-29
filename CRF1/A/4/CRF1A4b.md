# Residential

## Modellannahmen

Die direkten Emissionen bei privaten Gebäuden durch die Verbrennung von Brennstoffen gehen zu einem großen Teil auf die
Bereitstellung von Raumwärme zurück. Auch die übrigen Emissionen entstehen bei der Bereitstellung von thermischer Energie.
Der Bedarf an thermischer Energie wird in einer übergreifenden Rechnung für alle Emissionssektoren und bestimmte Temperaturklassen 
sortiert.

### Energiebedarf Raumwärme
Raumwärme wird in der übergreifenden Rechnung in der Temperaturklasse unter 100° eingeordnet. Der thermische Raumwärmebedarf ist das Produkt aus dem spezifischen Heizwärmebedarf pro m² in kWh/m²a und der
bewohnten Fläche in m². Sowohl die Entwicklung des Wohnflächenbestands als auch die Entwicklung der
spezifischen Heizwärme wurde getrennt nach Altersklasse der Wohngebäude durchgeführt. Die Verteilung der 
Wohngebäudefläche ist gegeben in der [Datenbasis zur Bewertung von Energieeffizienzmaßnahmen in der 
Zeitreihe 2005 – 2014.](https://www.umweltbundesamt.de/sites/default/files/medien/1968/publikationen/2017-01-09_cc_01-2017_endbericht-datenbasis-energieeffizienz.pdf)
So lassen sich Besonderheiten der Sanierungsrate genau abbilden. Beispielsweise ist der spezifische Heizwert bei 
Gebäuden von vo 1980 deutlich schlechter als bei Gebäuden nach 1980. Die Sanierungsrate bei Gebäuden, die vor
1918 errichtet wurden ist erwartungsgemäß niedriger und selbst wenn solche Gebäude saniert werden, sind sie 
danach nicht so energetisch effizient, wie modernere Gebäude. Bei neueren Gebäuden mit Baujahr nach
2010 ist die Sanierungsrate deutlich geringer und wenn saniert wird, ist der Gewinn in der Energieeffizienz gering.

Es wird angenommen, dass ein Wohngebäude, das nach 2015 einmal saniert wurde, bis 2050 kein weiteres mal 
saniert werden muss. Gegeben eine Sanierungsrate `p`, einem spezifischen Heizenergiebedarf `S` vor der Sanierung und 
einem spezifischen Heizenergiebedarf `S'` nach der Sanierung gibt sich der gesamte spezifische Heizenergiebedarf nach 
einem Jahr als `(1-p)S+pS'`. Nach n Jahren liegt der Heizwert bei `(1-np)S+pnS`.

Die freien Variablen die gewählt werden können sind:
* Die Wohnfläche aus einer bestimmten Altersklasse im Jahr 2035 in mio. m²
* Die Sanierungsrate bis ins Jahr 2035
* Die spezifische Heizwärme des Gebäudes einer bestimmten Altersklasse nach der Sanierung

### Energiebedarf Warmwasser
Warmwasser wird in der übergreifenden Rechnung in der Temperaturklasse unter 100° eingeordnet. Auch der Bedarf an Energie zur Bereitstellung von Warmwasser wird nach Altersklassen modelliert. Es wird angenommen, dass
sich der Warmwasserbedarf proportional zur Veränderung der Wohnfläche der entsprechenden Altersklasse verändert. 
Darüber hinaus wird bei Gebäuden von vor 2020 der Energiebedarf um weitere 5% reduziert. Bei Neubauten nach 2020
wird der Energiebedarf bis 2035 um geringere Werte reduziert. 

### Energiebedarf übrige Prozesswärme
Die übrige Prozesswärme im privaten Sektor entsteht in der Regel beim Kochen und macht nur einen kleinen Anteil am gesamten Energiebedarf aus.
In der übergreifenden Rechnung wird die Prozesswärme zwischen 100° und 200° eingeordnet. Da keine Maßnahmen auf die Reduktion 
des Prozesswärmebedarfs abzielen wird angenommen, dass dieser Bedarf bis 2035 konstant bleibt. 

### Deckung des Energiebedarfs
Bei der Deckung des Wärmeenergiebedarfs werden perspektivisch nur noch vier Energieträger eine Rolle spielen. 

* Direkte Stromnutzung; 1kWh Raumwärme pro 1kWh Strom
* Stromgestützte Wärmebereitstellung, Nutzung eines naheliegenden Wärmereservoirs (z.B. Solar, Grundwasser, Luft) mit Hilfe von strombetriebenen Wärmepumpen; >1kWh Raumwärme pro 1kWh Strom
* Verbrennung von Biomasse, entstehende Emissionen müssen durch negative Emissionen im CRF 4 Sektor ausgeglichen werden.
* Fernwärme, Emissionen aus der Erzeugung von Wärme entstehen in der Regel in KWK anlagen und einigen wenigen exklusiven Wärmeerzeugern und werden im CRF Sektor 1.A.1.a bilanziert.

Treibhausgasemissionen wurden basiert auf den Aktivitätsdaten und den spezifischen Emissionsfaktoren aus dem Nationalen Inventarbericht von 2021 berechnet.
Bei der Deckung des Energiebedarfs <100° sollen Wärmepumpen in Zukunft eine prominente Rolle spielen.
Es wurde daher eine Schätzung über die effektive kombinierte Arbeitszahl aller stromgestützte Wärmesyststeme getroffen, die über die Jahre veränderlich ist.
Der Strombedarf entkoppelt sich somit mehr und mehr von der Menge an Raumwärmeneergie die damit gedeckt werden kann. 

Die Emissionen aus der vorliegenden Modellierung übersteigen die Emissionswerte aus dem NIR weil die Biomasseverbrennung nicht als Klimaneutral gewertet wird.
Ohne die Emissionen der Biomasseverbennung stimmen die Zahlen für 2019 auf wenige Prozentpunkte überein.

Eine Reihe von Variablen können frei gewählt werden, jedoch nicht alle, da jeweils die letzte Wahl durch die vorhergeganegene Hochrechnung der Energieeffizienz beschränkt wurde.
* Reduktionsgeschwindigkeit der verschiedenen fossilen Energieträger. Fossile Energieträger sind:
  * Solid Fuels
  * Liquid Fuels
  * Gaseous Fuels
* Ausbauziele der Fernwärmekapazität
* Ausbaugeschwindigkeit der stromgestützten Wärmesysteme
* Abschätzung der Arbeitszahlen der Wärmepumpen

## Szenario