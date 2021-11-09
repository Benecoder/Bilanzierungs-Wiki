# CRF 1.A.1.a Public Electricity and heat production

Die in 1.A.1.a abgebildeten Emissionen umfassen die gesamte Verbrennung von fossilen Energieträgern zur Einspeisung von Strom in das öffentliche Netz.
Nicht aufgeführt sind Industriekraftwerke, die unter 1.A.2, insbesondere 1.A.2.g.viii aufgeführt werden.
Eine Reihe von Vorkettenemissionen werden berücksichtigt, allerdings in anderen Emissionskategorien.
Verbrennungsemissionen, die bei dem Transport in Pipelines z.B. in Kompressorstationen enstehen werden in 1.A.3.e aufgeführt.
Darüber hinaus werden flüchtige Emissionen, die bei der Gewinnung und dem Transport von Energieträgern entstehen unter 1.B.1.a/1.B.2 aufgeführt.
Entfernt verwand sollen hier auch nich die Raffinerie Emissionen aus 1.A.1.b erwähnt werden.
Die Herstellung von PV/Wind Anlagen kann zu verschiedenen Prozessemissionen in der Grundstoffindustrie führen.
Diese werden, sofern sie in Deutschland anfallen, in der Industrie (z.B. CRF 2.E) aufgeführt.

Darüber hinaus werden KWK und Heizkraftwerke die Wärme erzeugen berücksichtigt, insofern sie Wärmeenergie in ein öffentliches Fernwärmenetz einspeisen.
Wird die Wärme z.B. in einer integrierten Industrieanlage direkt genutzt werden die Emissinen in der relevanten Unterkategorie von 1.A.2 aufgeführt.
Blockheizkraftwerke, die den Wärembedarf in größeren Gebäudekomplexen decken ohne öffentlich einzuspeißen werden in 1.A.4 aufgeführt.

## Modellannahmen

Die Emissionsmodelle für 1.A.1.a die in den nationalen Inventarbericht einfließen, basieren auf einer sehr detaillierten Befragung der Kraftwerksbetreiber, die nicht öffentlich zugänglich ist.
Dennoch weichen die hier beschriebenen Berechnungen im Jahr 2019 nur um 4,2% von den im NIR aufgeführten Emissionen ab.

### Stromerzeugung

Auf Erzeugerseite wurde eine Reihe von werten berechnet um eine differenzierte Modellierung der Stromerzeugung zu ermöglichen.
In der Energiebilanz für das Jahr 2019 der AGEB (AG Energiebilanzen) ist der Umwandlungseinsatz für die Erzeugung von Strom vermekrt.
Dieser wird nach Energieträger und nach öffentlichen und industriellen Kraftwerken differenziert.
Außerdem wird von der AGEB eine Statistik über die Bruttostromerzeugung in Deutschland, differenziert nach Energieträger veröffentlicht.
Aus diesen beiden Statistiken lässt sich ein Primärenergienutzungsgrad für die Stromproduktion, differenziert nach Energieträger berechnen.
Angewendet auf den Umwandlungseinsatz in der Energiebilanz kann außerdem der Umwandlungsausstoß (d.h. die Bruttostromproduktion) differenziert nach ursprünglichem Energieträger für das Jahr 2019 ermittelt werden.

Der Umwandlungsausstoß der öffentlichen Kraftwerke, kombiniert mit der Kraftwerksliste der Bundesnetzagentur erlaubt darüber hinaus die Vollaststunden im Jahr 2019, differenziert nach Energieträger zu berechnen.

Vorgegeben werden kann im Modell dann die Rück-/Zubaurate der Nenntonennleistung der Kraftwerke, ebenfalls differenziert nach Energieträger.
So lässt sich Ausstieg aus der Braunkohle vor dem Ausstieg aus der Steinkohle, vor dem Ausstieg aus dem Erdgas abbilden.

Da - wie oben schon erwähnt - die Vollasstunden vorliegen, kann für die Jahre nach 2019 aus der Leistung die Bruttostromerzeugung berechnet werden.
Unter Zuhilfenahme der Primärenergienutzungsgrade der verschiedenen Energieträger steht außerdem der Primärenergiebedarf der verscheidenen Energieträger fest.
Die spezifischen Emissionswerte bezogen auf den Primärenergiebedarf, die bei der Verbrennung in 1.A.1.a anfallen liegen im CRF Bericht vor.
So können schlussendlich die CO2, CH4 und N2O Emissionen der verschiedenen Energieträger berechnet werden.

### Fernwärme

Die Erzeugung von Fernwärme wird, sofern in ein öffentliches Fernwärmenetz eingespeist wird, in der Energiebilanz der AGEB als Energieumwandlung aufgeführt.
Dabei wird in Heizkraftwerken oder Fernheizwerken zu einem überwiegendem Anteil Energieträger verbrannt.
Die einzige Ausnahme stellen dabei Geothermiekraftwerke dar.
Für alle Energieträger ist in der Energiebilanz der AGEB der Umwandlungseinsatz nach Energieträger aufgeschlüsselt.
Auß der Energiebilanz kann entnommen werden, dass der Umwandlungsausstoß gegenüber dem Umwandlungseinsatz um ca. 2,243% geringer ist.
Dieser Verlust wird für die nächsten Jahre als konstant angenommen.
Die spezifischen Emissionswerte, aufgeschlüsselt nach Energieträger können aus dem CRF des NIR 2021 entnommen werden.

In dem Modell kann die Veränderung der Nutzung verschiedener Energieträger über die Jahre modelliert werden.
