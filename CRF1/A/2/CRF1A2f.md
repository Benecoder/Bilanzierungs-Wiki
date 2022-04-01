# CRF 1.A.2.f Non-metallic minerals

In 1.A.2.f werden die Verbrennungsemissionen aus der Herstellung von nicht-metallischen Mineralien, hauptsächlich Zementklinker (größtenteils ein Calciumsilikat), aber auch Kalk, Dolomit, und Glas abgedeckt. In 1.A.2.f werden dabei ausschließlich die energetischen Emissionen zur Prozesswärmebereitstellungen behandelt. Bei der Brennung von Mineralen wird Kohlenstoffdioxid aus dem Gestein gelöst. Die Produktion dieser Gase ist eine sogenannte Prozessemission und ein integraler Teil der Produktion. Die Modellierung dieser Emissionen wird in 2.A behandelt.

## Modellanahmen
Für die Zementbrennung ist ein enormer Bedarf an thermischer Energie bei hoher Temperatur notwendig.
Eine nachhaltige Deckung dieses Bedarfs ist daher nur mithilfe von elektrischer Energie möglich.
Alternativ könnte die Nutzung von Biomasse, die Nutzung von Wärmepumpen in Kombination mit industrieller Abwärme oder die Verbrennung von E-Fuels berücksichtigt werden.
Die prävalenten Flächennutzungskonflikte und der landwirtschaftliche Schaden, der bei der Nutzung von Biomasse unvermeidbar ist, verbietet allerdings einen starken Anstieg in der Verbrennanung von Biomasse.
Die hohen Temperaturen die für die Zementbrennung erforderlich sind machen auch die Nutzung von industrieller Abwärme unmöglich, weil der Wirkungsgrad von Wärmepumpen bei derartigen Temperaturdifferenzen [verschwindend gering ist.](https://www.fv-ies.ch/fileadmin/FV-IES/Literaturstudie_Hochtemperatur_Waermepumpen.pdf)
E-Fuels fungieren nur als Medium für vorher gewonnen elektrische Energie und eine Nutzung zur Bereitstellung thermischer Energie stellt eigentlich nur eine sehr ineffiziente Nutzung von grünem Strom dar. 
Insgesamt wird also von einem Brennstoffwechsel zu erneuerbaren Energieträgern und einer direkten Elektrifizierung des übrigen Energiebedarfs ausgegangen.

Die Aktivitätsdaten und Emissionsfaktoren für die Produktion von Zementklinker, Kalk, Dolomitkalk können aus den Tabellen 180, 181 und 182 des nationalen Inventarberichts 2019 entnommen werden.
Genauso liegen auch die Energieträger differenziert nach Typ im NIR vor.

Im Modell ist die Veränderung im Bedarf der produzierten Stoffe (Beton, Kalk, Dolomit und Glas) einstellbar.
Zusätzlich ist der Anteil von Zemenklinker am Zement und der Anteil des Zements im Beton veränderbar.
Darüber hinaus kann die Veränderung der Energieträgernutzung eingestellt werden.
Der Energieverbrauch pro produzierter Tonne Zement, Kalk oder Glas wird jeweils als konsant angenommen.
Die Lücke zum Energiebedarf der durch die produzierte Menge vorgegeben wird, wird dann automatisch durch elektrische Energie geschlossen. (vor 2024 mit Biomasse)
Die Emissionsfaktoren werden differenziert nach Treibhausgas (CO2, CH4 und N2O) aus dem NIR übernommen und als konstant angenommen.
