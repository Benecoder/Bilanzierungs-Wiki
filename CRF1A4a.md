# Commercial / Institutional

## Modellannahmen

Die direkten Emissionen bei Nichtwohngebäuden entstehen durch die Verbrennung von Brennstoffen gehen zu einem großen Teil auf die
Bereitstellung von Raumwärme zurück. Auch die übrigen Emissionen entstehen bei der Bereitstellung von thermischer Energie.
Der Bedarf an thermischer Energie wird in einer übergreifenden Rechnung für alle Emissionsektoren und bestimmte Temperaturklassen 
sortiert.

### Raumwärme
Die Raumwärme wird in der überreifenden Rechnung der Temperaturklasse unter 100° eingeordnet. Der thermische Raumwärmebedarf ist das Produkt aus dem spezifischen Heizwärmebedarf pro m² in kWh/m²a und der
bewohnten Fläche in m². Die Entwicklung der Fläche der Nicht-Wohn-Gebäude in öffentlichen und privaten Gebäuden
können getrennt entwickelt werden. Genauso kann eine Zeitreihe für den spezifische Raumwärmebedarf der öffentlichen und 
der privaten Nichtwohngebäude vorgegeben werden. Nicht-wohngebäudefläche ist gegeben in der 
[Studie zum Klimaneutraler Gebäudebestand 2050.](https://www.umweltbundesamt.de/sites/default/files/medien/1410/publikationen/2017-11-06_climate-change_26-2017_klimaneutraler-gebaeudebestand-ii.pdf)
Die Datenlage bei Nichtwohngebäuden ist deutlich schlechter als bei Wohngebäuden. Es ist daher ausschließlich eine 
Trennung nach öffentlichen und nicht-öffentlichen Gebäuden möglich. So können Maßnahmen, die die vorgezogene Sanierung
von öffentlichem Gebäudebestand betreffen abgebildet werden.

Es wird angenommen, dass ein Wohngebäude, das nach 2015 einmal saniert wurde, bis 2050 kein weiteres mal 
saniert werden muss. Gegeben eine Sanierungsrate `p`, einem spezifischen Heizenergiebedarf `S` vor der Sanierung und 
einem spezifischen Heizenergiebedarf `S'` nach der Sanierung gibt sich der gesamte spezifische Heizenergiebedarf nach 
einem Jahr als `(1-p)S+pS'`. Nach n Jahren liegt der Heizwert bei `(1-np)S+pnS`. 

Die freien Variablen die gewählt werden können sind:
* Die Gebäudefläche öffentlicher und privater Nichtwohngebäude im Jahr 2035
* Die Sanierungsrate öffentlicher Gebäude bis ins Jahr 2035 
* Die Sanierungsrate privater Gebäude bis ins Jahr 2035
* Die spezifische Heizwärme öffentlicher Gebäude nach der Sanierung
* Die spezifische Heizwärme privater Gebäude nach der Sanierung

### Warmwasser
Die Bereitstellung von Warmwasser wird in der übergreifenden Rechnung in der Temperaturklasse unter 100° eingeordnet. 
Aus dem gesamten Warmwasser Energiebedarf im Jahr 2015 und dem Bestand an Fläche in Nichtwohngebäuden wird ein spezifischer
Warmwasser Energiebedarf für nichtwohngebäude in kWh/m² berechnet. Dieser wird linear bis 2035 reduziert. Aus der für die
Raumwärme berechneten Wohnfläche lässt sich so ein Energiebedarf für Warmwasser vorhersagen. Diese Rechnung 
wird getrennt nach öffentlichen und privaten Gebäuden durchgeführt.

Die freien Variablen die gewählt werden können sind:
* Die spezifische Warmwasserbedarf im Jahr 2035 für öffentliche Gebäude.
* Der spezifische Warmwasserbedarf im Jahr 2035 für private Gebäude.

### Prozesswärme
Die übrige Prozesswärme wird in der übergreifenden Rechnung in der Temperaturklasse 100° bis 200° eingeordnet.
Wie in der [Datenbasis zur Bewertung von Energieeffizienzmaßnahmen in der Zeitreihe 2005 – 2014.](https://www.umweltbundesamt.de/sites/default/files/medien/1968/publikationen/2017-01-09_cc_01-2017_endbericht-datenbasis-energieeffizienz.pdf)
dargestellt wird, sind die Effizienzgewinne in der Prozesswärme des GHD Sektors wahrscheinlich Größtenteils ausgeschöpft.
Daher wird die benötigte Prozesswärme bis 2035 als konstant angenommen.

## Szenario
