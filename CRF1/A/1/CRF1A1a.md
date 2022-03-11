# CRF 1.A.1.a Public Electricity and heat production

Die in 1.A.1.a abgebildeten Emissionen umfassen die gesamte Verbrennung von fossilen Energieträgern zur Einspeisung von Strom in das öffentliche Netz.
Nicht aufgeführt sind Industriekraftwerke, die unter 1.A.2, insbesondere 1.A.2.g.viii aufgeführt werden.
Eine Reihe von Vorkettenemissionen werden berücksichtigt, allerdings in anderen Emissionskategorien.
Verbrennungsemissionen, die bei dem Transport in Pipelines z.B. in Kompressorstationen enstehen werden in 1.A.3.e aufgeführt.
Darüber hinaus werden flüchtige Emissionen, die bei der Gewinnung und dem Transport von Energieträgern entstehen unter 1.B.1.a/1.B.2 aufgeführt.
Entfernt verwandt sollen hier auch nich die Raffinerie Emissionen aus 1.A.1.b erwähnt werden.
Die Herstellung von PV/Wind Anlagen kann zu verschiedenen Prozessemissionen in der Grundstoffindustrie führen.
Diese werden, sofern sie in Deutschland anfallen, in der Industrie (z.B. CRF 2.E) aufgeführt.

Darüber hinaus werden KWK und Heizkraftwerke die Wärme erzeugen berücksichtigt, insofern sie Wärmeenergie in ein öffentliches Fernwärmenetz einspeisen.
Wird die Wärme z.B. in einer integrierten Industrieanlage direkt genutzt werden die Emissinen in der relevanten Unterkategorie von 1.A.2 aufgeführt.
Blockheizkraftwerke, die den Wärembedarf in größeren Gebäudekomplexen decken ohne öffentlich einzuspeißen werden in 1.A.4 aufgeführt.

## Modellannahmen

Die Emissionsmodelle für 1.A.1.a die in den nationalen Inventarbericht einfließen, basieren auf einer sehr detaillierten Befragung der Kraftwerksbetreiber, die nicht öffentlich zugänglich ist.
Die Aktivitätsdaten wurden so genau wie möglich aus anderen Statisitken nachvollzogen.
Hierbei wurde insbesondere 
[Energiebilanz und die Auswertungstabelle der AG Energiebilanzen](https://ag-energiebilanzen.de/daten-und-fakten/) 
sowie die 
[Kraftwerksliste der Bundesnetzagentur](https://www.bundesnetzagentur.de/DE/Fachthemen/ElektrizitaetundGas/Versorgungssicherheit/Erzeugungskapazitaeten/Kraftwerksliste/start.html)
genutzt.


### Stromerzeugung

In der Energiebilanz für das Jahr 2019 der AGEB (AG Energiebilanzen) ist der Umwandlungseinsatz für die Erzeugung von Strom vermerkt.
Das stellt für die Emissionsberechnung die relevaten Aktivitätsdaten dar, weil die der Primärenergieverbauch im Gegensatz zur Bruttostromerzeugung unabhängig vom Primärenergienutzungsgrad der Kraftwerke ist.
Der Primärenergiebedarf wird nach Energieträger und nach öffentlichen und industriellen Kraftwerken differenziert.
Außerdem wird von der AGEB eine Statistik über die Bruttostromerzeugung in Deutschland, differenziert nach Energieträger veröffentlicht.
Aus diesen beiden Statistiken lässt sich ein Primärenergienutzungsgrad für die Stromproduktion, differenziert nach Energieträger berechnen.
Angewendet auf den Umwandlungseinsatz in der Energiebilanz kann außerdem der Umwandlungsausstoß (d.h. die Bruttostromproduktion) differenziert nach ursprünglichem Energieträger für das Jahr 2019 ermittelt werden.

Der Umwandlungsausstoß der öffentlichen Kraftwerke, kombiniert mit der Kraftwerksliste der Bundesnetzagentur erlaubt darüber hinaus die effektiven Vollaststunden im Jahr 2019, differenziert nach Energieträger zu berechnen.
Für die Jahre nach 2019 werden diese berechneten Vollasstunden angenommen, auch wenn sie teilweise deutlich unter den Vollaststunden aus anderen Datenquellen wie z.B. [dem Fraunehofer ISE](https://energy-charts.info/downloads.html?l=de&c=DE) liegen. 
Besonders beim Energieträger Gas ist diese Diskrepanz enorm.
Die berechnet Werte werden dennoch als verlässlicher erachtet, weil die effektiven Vollasstunden nur die Stunden umfassen, in denen das Kraftwerk ins Netz einspeist.
Bei Industriekraftwerken kann davon ausgegangen werden, dass sie einen Anteil ihrer Zeit nicht für die Einspeisung ins Netz fahren und diese Stunden dennoch zu den Vollaststunden dazu gezählt werden.
Die Präfalenz von Gaskraftwerken bei der Eigenversorgung von Industrieunternehmen erklärt auch warum diese bei den Vollaststunden so deutlich abweichen.

Vorgegeben werden kann im Modell dann die Rück-/Zubaurate der Nenntonennleistung der Kraftwerke in den Folgejahren, ebenfalls differenziert nach Energieträger.
Ebenfalls kann die Vollaststundenzahl der foosilen Kraftwerke modifiziert werden.
So lässt sich Ausstieg aus der Braunkohle vor dem Ausstieg aus der Steinkohle, vor dem Ausstieg aus dem Erdgas abbilden.
Außerdem lässt sich der Anteil der synthetischen Gase am Primärenergiebedarf von Gaskraftwerken eingestellt werden.

Da - wie oben schon erwähnt - die Vollasstunden vorliegen, kann für die Jahre nach 2019 aus der Leistung die Bruttostromerzeugung berechnet werden.
Für die Berechnung des in Deutschland zur Verfügung stehenden Strommenge werden Leitungsverluste die 4,51% des Bruttostromverbrauchs ausmachen abgezogen.
Darüber hinaus wird die Strommenge die zur Erzeugung synthetischen Gase benötigt wird abgezogen, sofern die Gase rückverstomt werden.
Unter Zuhilfenahme der Primärenergienutzungsgrade der verschiedenen Energieträger kann auf den Primärenergiebedarf der verscheidenen Energieträger rückgeschlossen werden.
Die spezifischen Emissionswerte bezogen auf den Primärenergiebedarf, die bei der Verbrennung in 1.A.1.a anfallen liegen im CRF Bericht vor.
So können schlussendlich die CO2, CH4 und N2O Emissionen der verschiedenen Energieträger berechnet werden.

### Fernwärme (unfertig)

Die Erzeugung von Fernwärme wird, sofern in ein öffentliches Fernwärmenetz eingespeist wird, in der Energiebilanz der AGEB als Energieumwandlung aufgeführt.
Dabei wird in Heizkraftwerken oder Fernheizwerken zu einem überwiegendem Anteil Energieträger verbrannt.
Die einzige Ausnahme stellen dabei Geothermiekraftwerke dar.
Für alle Energieträger ist in der Energiebilanz der AGEB der Umwandlungseinsatz nach Energieträger aufgeschlüsselt.
Auß der Energiebilanz kann entnommen werden, dass der Umwandlungsausstoß gegenüber dem Umwandlungseinsatz um ca. 2,243% geringer ist.
Dieser Verlust wird für die nächsten Jahre als konstant angenommen.
Die spezifischen Emissionswerte, aufgeschlüsselt nach Energieträger können aus dem CRF des NIR 2021 entnommen werden.

In dem Modell kann die Veränderung der Nutzung verschiedener Energieträger über die Jahre modelliert werden.

## Entwicklung

_Work in Progress_

