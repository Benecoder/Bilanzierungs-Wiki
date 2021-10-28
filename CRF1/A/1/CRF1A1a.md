# CRF 1.A.1.a Public Electricity and heat production

Die in 1.A.1.a umfassten Emissionen umfassen die gesamte Verbrennung von fossilen Energieträgern zur Einspeisung von Strom in das öffentliche Netz.
Darüber hinaus werden KWK und Heizkraftwerke die Wärme erzeugen berücksichtigt.
Nicht aufgeführt sind Industriekraftwerke, die unter 1.A.2, insbesondere 1.A.2.g.viii aufgeführt werden.
Verbrennungsemissionen, die bei dem Transport in Pipelines z.B. in Kompressorstationen enstehen werden in 1.A.3.e aufgeführt.
Darüber hinaus werden flüchtige Emissionen, die bei der Gewinnung und dem Transport von Energieträgern entstehen unter 1.B.1.a/1.B.2 aufgeführt. 

## Modellannahmen

### Stromerzeugung

#### Öffentliches Netz

Auf Erzeugerseite wurde eine Reihe von werten berechnet um eine differenzierte Modellierung der Stromerzeugung zu ermöglichen.
In der Energiebilanz für das Jahr 2019 der AGEB (AG Energiebilanzen) ist der Umwandlungseinsatz für die Erzeugung von Strom vermekrt.
Dieser wird nach Energieträger und nach öffentlichen und industriellen Kraftwerken differenziert.
Außerdem wird von der AGEB eine Statistik über die Bruttostromerzeugung in Deutschland, differenziert nach Energieträger veröffentlicht.
Aus diesen beiden Statistiken lässt sich ein Primärenergienutzungsgrad für die Stromproduktion, differenziert nach Energieträger berechnen.
Angewendet auf den Umwandlungseinsatz in der Energiebilanz kann außerdem der Umwandlungsausstoß (d.h. die Bruttostromproduktion) differenziert nach ursprünglichem Energieträger für das Jahr 2019 ermittelt werden.

Der Umwandlungsausstoß der öffentlichen Kraftwerke, kombiniert mit der Kraftwerksliste der Bundesnetzagentur erlaubt darüber hinaus die Vollaststunden im Jahr 2019, differenziert nach Energieträger zu berechnen.

Vorgegeben werden kann im Modell dann die Rück-/Zubaurate der Nenntonennleistung der Kraftwerke, ebenfalls differenziert nach Energieträger.
So lässt sich Ausstieg aus der Braunkohle vor dem Ausstieg aus der Steinkohle, vor dem Ausstioeg aus dem Erdgas abbilden.

Da - wie oben schon erwähnt - die Vollasstunden vorliegen, kann daraus wieder die Bruttostromerzeugung berechnet werden.
Unter Zuhilfenahme der Primärenergienutzungsgrade der verschiedenen Energieträger wird daraufhin eine Prognose über den Primärenergiebedarf der verscheidenen Energieträger getroffen.
Die spezifischen Emissionswerte, die bei der Verbrennung in 1.A.1.a anfallen liegen im CRF Bericht vor.
So können schlussendlich die CO2, CH4 und N2O Emissionen der verschiedenen Energieträger berechnet werden.
