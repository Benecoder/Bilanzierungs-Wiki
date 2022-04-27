# CRF 3.B Manure management / Güllemanagement

In 3.B werden die THG-Emissionen aus dem Güllemanagement bilanziert. Diese sind größtenteils CH4-Emissionen, ein signifikanter Anteil entfällt auch auf N2O. NMVOC fallen ebenfalls an, diese werden in diesem Modell jedoch nicht bilanziert.

Die Einteilung in Unterkategorien erfolgt analog zu [3.A, Tierische Verdauung](CRF3A.md):
* Rinder, welche wiederum in Milchkühe und Nicht-Milchkühe eingeteilt sind. 
* Schweine
* Anderes Vieh (Hühner, eine geringe Anzahl Pferde) 

Im Unterschied zu [3.A, Tierische Verdauung](CRF3A.md) kommt hier jedoch eine weitere Unterkategorie hinzu:
* Indirekte N2O-Emissionen

Im Gegensatz zu den CRF-Tabellen werden die Emissionen von Ziegen aufgrund des geringen Anteils (<1 Promille) der Emissionen vernachlässigt.

# Modellannahmen
Die CH4-Emissionen werden nach folgender Formel berechnet:

Anzahl Tiere x Emissionsfaktor (t CH4 pro Tier und Jahr)

Sowohl die Anzahl der Tiere als auch der Emissionsfaktor sind für die Prognosen veränderlich.

Die N2O-Emissionen werden nach dieser Formel berechnet:

Anzahl Tiere x Emissionsfaktor (t N2O pro Tier und Jahr)

Sowohl die Anzahl der Tiere als auch der Emissionsfaktor sind für die Prognosen veränderlich.

Die einzige Unterkategorie, die davon abweicht ist 3.B.5, indirekte N2O-Emissionen.
Hier werden die Emissionen wie folgt berechnet:

N (Stickstoff) verflüchtigt als NH3 und Nox [t/Jahr] x atmosphärische Ablagerung [kg N2O-N/kg N]
