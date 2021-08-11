# 

## Modellannahmen

### Raumwärme
Der thermische Raumwärmebedarf ist das Produkt aus dem spezifischen Heizwärmebedarf pro m² in kWh/m²a und der
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

## Szenario