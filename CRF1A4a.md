# Commercial/Institutional

## Modellannahmen

### Raumwärme
Der thermische Raumwärmebedarf ist das Produkt aus dem spezifischen Heizwärmebedarf pro m² in kWh/m²a und der
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

## Szenario
