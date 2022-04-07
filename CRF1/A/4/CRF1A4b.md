# CRF 1.A.4.b Residential

## Modellannahmen

Die direkten Emissionen bei privaten Gebäuden durch die Verbrennung von Brennstoffen gehen zu einem großen Teil auf die
Bereitstellung von Raumwärme zurück. Auch die übrigen Emissionen entstehen bei der Bereitstellung von thermischer Energie.
Wird die themrische Energie in zentralen Anlagen erzeugt und als Fernwärme verteilt, so erfolgt die Bilanzierung im Rahmen von 1.A.1.a, da diese Anlagen oft auch als kombinierte Kraft-Wärme-Kopplungsanlagen betrieben werden und auch Strom erzeugen.
1.A.4.b ist auf die Emissionen aus Wohngebäuden beschränkt; Verbrennung in öffentlichen Gebäuden für Gewerbe, Handel und Dienstleistungsemissionen werden in 1.A.4.b abgedeckt.


## Modellanahmen

Die Modellierung erfolgt in zwei Schritten.
Erst wird die Entwicklung des Energiebdarfs basiert auf der Sanierung und dem Rück und Zubau von Wohnfläche berechnet.
Dann wird die Entwicklung der Energieträger abgebildet, die diesen Energiebedarf decken.

### Energiebedarf Raumwärme

Der thermische Raumwärmebedarf ist das Produkt aus dem spezifischen Heizwärmebedarf pro m² in kWh/m²a und der bewohnten Fläche in m².
Die Verteilung der Wohngebäudefläche und der der gesamte Energiebedarf ist gegeben in der [Datenbasis zur Bewertung von Energieeffizienzmaßnahmen in der 
Zeitreihe 2005 – 2014](https://www.umweltbundesamt.de/sites/default/files/medien/1968/publikationen/2017-01-09_cc_01-2017_endbericht-datenbasis-energieeffizienz.pdf).
Jeweils differenziert nach Gebäudealter.
Daraus lässt sich der spezifische Raumwärmebedarf nach Gebäudealter berechnen.
Im Modell kann eingestellt werden, welchen spezifischen Energiebedarf ein Gebäude nach der Sanierung aufweist und welcher Anteil der Wohnfläche in jedem der Folgejahre saniert wird; ebenfalls differenziert nach Gebäudealter.
Außerdem kann der Rück und Zubau von Wohnfläche, differenziert nach Gebäudealter eingestellt werden.
So lässt sich die Entwicklung der Wohnfläche und des spezifischen Raumwärmebedarfs in den Folgejahren abbilden.

Insgesamt können so Besonderheiten der Sanierungsrate genau abbilden.
Beispielsweise ist der spezifische Heizwert bei Gebäuden von vor 1980 deutlich schlechter als bei Gebäuden nach 1980.
Die Sanierungsrate bei Gebäuden, die vor 1918 errichtet wurden ist erwartungsgemäß niedriger und selbst wenn solche Gebäude saniert werden, sind sie 
danach nicht so energetisch effizient, wie modernere Gebäude. Bei neueren Gebäuden mit Baujahr nach
2010 ist die Sanierungsrate deutlich geringer und wenn saniert wird, ist der Gewinn in der Energieeffizienz gering.


### Energiebedarf Warmwasser
Der Energiebedarf für die Warmwassererzeugung differenziert nach Gebäudealter kann ebenfalls aus der [Datenbasis zur Bewertung von Energieeffizienzmaßnahmen in der Zeitreihe 2005 – 2014](https://www.umweltbundesamt.de/sites/default/files/medien/1968/publikationen/2017-01-09_cc_01-2017_endbericht-datenbasis-energieeffizienz.pdf) entnommen werden.
Im Modell kann die Veränderung im Warmwasserenergiebedarf differenziert nach Jahren für die Folgejahre eingestellt werden.
So können beispielsweise Effizienzgewinne durch einen geringeren Wasserbedarf beim Durschen abgebildete werden.

### Energiebedarf übrige Prozesswärme
Die übrige Prozesswärme im privaten Sektor entsteht in der Regel beim Kochen und macht nur einen kleinen Anteil am gesamten Energiebedarf aus.
In der übergreifenden Rechnung wird die Prozesswärme zwischen 100° und 200° eingeordnet. Da keine Maßnahmen auf die Reduktion 
des Prozesswärmebedarfs abzielen wird angenommen, dass dieser Bedarf bis 2035 konstant bleibt. 

### Deckung des Energiebedarfs
Bei der Deckung des Wärmeenergiebedarfs werden perspektivisch nur noch vier Energieträger eine Rolle spielen. 

* Direkte Stromnutzung oder stromgestützte Wärmebereitstellung, Nutzung eines naheliegenden Wärmereservoirs (z.B. Solar, Grundwasser, Luft) mit Hilfe von strombetriebenen Wärmepumpen; insgesamt mehr als 1kWh Wärme pro kWh Strom
* Verbrennung von Biomasse, hierbei werden nur die nicht-CO2 Emissionen im NIR angerechnet.
* Fernwärme

Für das Jahr 2019 werden die Aktivitätsdaten für die fossilen Energieträger aus dem NIR übernommen.
In der Zeile 66 der AGEB Energiebilanz wird außerdem ein Wert für die Nutzung von Fernwärme in Wohngebäuden gegeben.
Die Lücke zum Energiebedarf wird dann mithilfe der stromgestützten Energieträgern geschlossen.
Die Entwicklung der Nutzung der fossilen Energieträger kann im Modell eingestellt werden.
Treibhausgasemissionen wurden basiert auf den Aktivitätsdaten und den spezifischen Emissionsfaktoren aus dem NIR berechnet.
Es werden dabei die CO2, CH4 und N2O Emissionen berücksichtigt.
Bei der Deckung des Energiebedarfs <100° sollen Wärmepumpen in Zukunft eine prominente Rolle spielen.
Außerdem kann der Strombedarf der stromgestützten Wärmebereitstellung berechnet werden.
Die netto Arbeitszahl aller elektrischen Heizsysteme zusammen kann im Modell eingestellt werden. 
Der Strombedarf entkoppelt sich somit mehr und mehr von der Menge an Raumwärmeneergie die damit gedeckt werden kann. 
Insgesamt kann so eine Veränderung der Energieträger für die Wärmebreutstllung z.B. durch den Einbau von Wärmepumpen abgebildet werden.
