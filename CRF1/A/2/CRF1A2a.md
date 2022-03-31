# CRF 1.A.2.a Iron and Steel

Modellannahmen:

Basiert auf welchen Daten werden die Emissionen im Jahr 2019 berechnet?
Welche Werte sind im Modell veränderbar?
Was wird als konstant angenommen?
Welche Entwicklung lässt sich durch die Veränderung dieser Werte jeweils mittelbar abbilden?
Wie werden in den Folgejahren die Emissionen berechnet?


Die Emissionen aus der Eisen und Stahlerzeugung sind über eine Vielzahl von Emissionskategorien verteilt.
In 1.A.2.a werden die Brennstoffemissionen in Abgrenzung zu den Prozessemissionen in 2.C.1 und den Flüchtigen Emissionen aus 1.B.1.b aufgeführt.
Ein Großteil der direkten Emissionen aus der Stahlindustrie entstehen bei der Oxygenstahl Produktion in Hochöfen.(Erläuterung siehe unten)
Die Hochöfen sind dabei in der Regel Teil von integrierten Hüttenwerken in denen unter anderem auch die rohe Steinkohle zu Koks weiterverarbeitet wird.
Die Emissionen aus Kokerein werden in der CRF Kategorie 1.A.1.c aufgeführt.
[Was in Deutschland von der Koksproduktion noch übrig ist,](https://www.chemie.de/lexikon/Liste_von_Kokereien_in_Deutschland.html) findet in Hüttenkokerein zu nachgelagerten Stahlproduktion statt.
In der unterliegenden Rechnung sind daher die Emissionen in 1.A.1.c an die Aktivitätsdaten der Hochofen-Stahlproduktion gekoppelt, werden allerdings seperat aufgeführt.

## Modell Annahmen

Die Emissionene für 1.A.1.c werden getrennt nach verschiedenen Stahlproduktionstechniken berechnet.
Für die Folgejahre kann die Produktion von Hochofenstahl, Elektrostahl und Eisenschwemme aus CH4 oder H2 Direktreduktion berechnet werden.

### Hochofenroute
Rund 70% oder 27.7 mio. t Rohstahl wurden 2019 über die Hochofenroute produziert. (NIR 2021, S.326)
[Die Produktion umfasst dabei mehrere Schritte](https://www.bmwi.de/Redaktion/DE/Downloads/E/energiewende-in-der-industrie-ap2a-branchensteckbrief-stahl.html), die allerdings in der Regel in einem integrierten Hüttenwerk lokal gebündelt ablaufen.
In einem ersten Schritt wird die Steinkohle unter Sauerstoffausschluss zu Koks gebacken, um den Schwefelanteil im Brennstoff zu senken.
Dabei entweichen die brennbaren sogenannten Kokereigase.
Diese werden in KWK Anlagen zur Erzeugung von Strom und Wärme für die Kokerei und den übrigen Produktionsablauf genutzt.
Das Eisenerz wird gesintert und pelletiert, wozu ebenfalls thermische Energie aufgebracht werden muss.
Die Mischung aus Koks und Eisenerz wird dann im Hochofen erhitzt.
[Insgesamt kann so der gesamte Strombedarf der Hochofenroute aus Eigenproduktion gedeckt werden.](https://www.bmwi.de/Redaktion/DE/Downloads/E/energiewende-in-der-industrie-ap2a-branchensteckbrief-stahl.html)


#### Die Methodik des NIR
Aus dem hochintegrierten Prozess in dem Brennstoffe mehrmals verwandelt werden ergeben sich eine Vielzahl von unterschiedlichen Emissionsquellen. Vereinfachend kann nach den 2006 IPCC Guidlines allerdings angenommen werden, das der gesamte Kohlenstoffanteil in der Steinkohle früher oder später als CO2 in die Atmosphäre emittiert wird.

>  virtually all of the carbon used for primary steel production is subsequently released into the atmosphere, as CO2, in later energy-related use, or in flaring of the blast furnace gas that forms in the blast furnace or of the basic oxygen furnace gas that forms in the oxygen steel converter.

NIR 2021, S. 327

Die Emissionen verteilen sich auf eine vielzahl verschiedener Emissionskategorien, wie aus der Tabelle 191 und den Emissionsdaten des NIR 2021 entnommen werden kann.

NIR Primärroute | kt CO2 | kt C im CO2 | CO2 Anteil am C | kt CH4 | kt C im CH4 | CH4 Anteil am C | kt C gesamt | % C gesamt
-|-|-|-|-|-|-|-|-
1.A.1.c Kokerein|9.909,56 |	 2.704,40  | 	18,70%	| 6,51 |	 4,87   |	0,03%	| 2.709,27  | 	18,74%	
1.A.2.a Sintering and rolling		|	 2.752,00 |	 751,04 |  	5,19%	| -   |	 -    | 	0,00%	| 751,04 | 5,19%	
1.A.2.a Industry power		|	 21.648,00 |	 5.907,92  | 	40,86%	| 11,71 |	 8,77  | 	0,06%	| 5.916,69  | 	40,92%	
Brennstoff gesamt		|	 34.309,56 	| 9.363,37  | 	64,75%	| 18,21 |	 13,64  | 	0,09%	| 9.377,01  | 	64,85%	
2.C.1 Prozess Emissionen Hochofen		|	 15.811,00 |	 4.314,96  | 	29,84%	| 0,20 |	 0,15   |	0,00%	| 4.315,10   |	29,84%	
2.C.1 Prozess Emissionen Kalkzugabe	|		 2.193,17 	| 598,54 |  	4,14%	| -   |	 -     |	0,00%	| 598,54  | 	4,14%	
Prozessemissionen gesamt		|	 18.004,17 |	 4.913,49  | 	33,98%|	 0,20 |	 0,15 |  	0,00%	| 4.913,64  | 	33,98%	
1.B.1.b Flüchtige Emissionen	|		 614,36 |	 167,66   |	1,16% |	 2,11 |	 1,58   |	0,01%	 169,24 |  	1,17%	
||||||||
gesamt		|	 52.928,09 |	 14.444,52 |	99,89%	| 20,52 |	 15,36 |	0,11%	| 14.459,89 |	100,00%

Der Anteil der Methanemissionen am Kohlenstoffanteil ist äußerst gering.
Somit kann es zwar in den prognostizierten Jahren zu einer verschiebung zwischen den Kategorien kommen, die absolute Menge der CO2e Emissionsn wird allerdings immer durch die verbrannte Kohlemenge bestimmt.
[Diese Zahl wird jährlich vom Verein der Kohleimporteure(VdKI) veröffentlicht.](https://www.kohlenimporteure.de/publikationen/jahresbericht-2021.html)
Es wird angenommen, dass in Steinkohle zu 89% elementarer Kohlenstoff gebunden ist und dieser nach der obigen Verteilung zu CO2 und CH4 reagiert
Bei der Oxidation zu CO2 wird das Gewicht des Kohlenstoffs um das Verhältnis der molaren Masse, also ca. 44/12 anwachsen. (Für CH4 ca. 16/12)
Nach den Daten des VdKI wurden in den deutschen Hochöfen  17,2 mio. t. SKE verbrannt.
Somit ergeben sich 52,390 kt CO2, eine unabhängige Verifikation der Ergebnisse des NIR 2021 der nur um 1,02% von diesem Ergebnis abwicht.

#### Die Methodik der GZ Emissionsbilanz
Aufgrund fehlendem Zugang zu vertraulichen Daten konnte die Methodik des NIR nicht 1 zu 1 nachempfunden werden. Zahlen über die Steinkohlenutzung in der Stahlherstellung [werden zwar vom Verein der Kohleimportuere veröffentlicht,](https://www.kohlenimporteure.de/publikationen/jahresbericht-2021.html) es fehlen aber öffentliche Daten über die Nutzung von nicht-Koks Brennstoffen, differenziert nach Produktionstechnik. Unsere Methodik basiert daher auf den Zahlen aus dem statistischen Jahrbuch der Wirtschaftsvereinigung Stahl. Darin wird der Energiebedarf differenziert sowohl nach Prozessen. 

* Elektrostahlwerken
* Frischdampfkesselhaus
* Hochofen
* Oxygenstahlwerk
* Sinteranlage
* sonst. Betriebe
* Warmwalzbetriebe

Für jeden dieser Prozesse wird nach folgenden Energieträger (im weitesten Sinne) unterschieden.
Nur ein Teil dieser Energieträger führt neuen Kohlenstoff zum Prozess hinzu. 

Kohlenstoffquellen:
* Steinkohle und -briketts
* Koks
* Koksgrus
* Erdgas
* Flüssige Brennstoffe

Sekundäre Energieträger, keine Kohlenstoffquellen:
* Sonstige Brennstoffe
* Hochofengase
* Kokereigase
* Konvertergas
* Sonstige Gase
* Dampf
* Sauerstoff
* Strom

Anders als im NIR wird in unserer Modellierung nicht der Kohlenstoffanteil der Steinkohle als Kohlenstoffquelle berücksichtigt sondern die weiterverarbieten Koks-Produkte.
Die Emissionen in 1.A.1.c werden dann anders als im NIR basiert auf getrennten Aktivitätsdaten berechnet.

Für die Emissionen aus der Hochofenroute wurde der Energiebedarf aus dem Jahresbericht der WV-Stahl für Hochöfen, Sinteranalgen und Oxygenstahlwerke zusammengerechnet.
Die Daten über die produzierte Menge Hochofenstahl können ebenfalls aus dem Bericht der WV-Stahl bezogen werden.
Die Emissionsfaktoren wurden basiert auf der Annahme ermittelt, dass die Brennstoffe früher oder später vollständig oxidiert werden.
Die Emissionsfaktoren für Erdgas und flüssige Brennstoffe wurden aus dem nationalen Inventarbeicht für die Emissionskategorie übernommen.
Der Energiebedarf pro produzierter Tonne Stahl für jeden der Energieträger wurde als konstant angenommen.
Für die Folgejahre kann dann der Bedarf an produziertem Hochofenstahl verändert werden.
So kann in den Folgejahren berechnet werden wie sich der Energiebedarf und die Emissionen für die Hochofenroute verändern wird.

### Elektrostahlroute

Elektrostahlwerke produzieren Stahl nicht aus der verarbeitung von Eisenerzen sondern aus dem Schmelze von Stahlschrott oder Eisenschwemme.
Letzteres wird in den unten erwähnten Direktreduktionsanlagen hergestellt.
In der Elektorstahlproduktion selber wird der überwiegende Anteil der Energie in Form von elektrischem Strom bereit gestellt.
Daten über die Nutzung der übrigen Energieträger, die Kohlenstoff beitragen (Steinkohle, Steinkohlebriketts, Koksgrus, und Erdgas) können aus dem statistischen Jahrbuch der Wirtschaftsvereinigung Stahl bezogen werden.
Auch die Menge an produziertem Elektrostahl aus Stahlschrott kann aus dem Jahrbuch der WV-Stahl bezogen werden. 
Die Emissionsfaktoren für Steinkohle und Koks wurden basiert auf der Annahme ermittelt, dass die Brennstoffe früher oder später vollständig oxidiert werden.
Die Emissionsfaktoren für Erdgas wurden aus dem nationalen Inventarbeicht für die Emissionskategorie übernommen.
Der Energiebedarf pro produzierter Tonne Stahl für jeden der Energieträger wurde als konstant angenommen.
Für die Folgejahre kann dann der Bedarf an produziertem Elektorstahl aus Stahlschrott verändert werden.
Die Menge an verarbeiteter Eisenschwemme ist die Summer der Produktion aus H2 und CH4 Direktreduktion. (s.u.)











