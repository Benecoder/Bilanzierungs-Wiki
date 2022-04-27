# CRF 3.A Enteric Fermentation / Tierische Verdauung

In 3.A werden die THG-Emissionen der tierischen Verdauung bilanziert, welche ausschließlich Methan-Emissionen sind. Die Kategorie ist eingeteilt in:
* Rinder, welche wiederum in Milchkühe und Nicht-Milchkühe eingeteilt sind. 
* Schweine
* Anderes Vieh (Hühner, eine geringe Anzahl Pferde) 

Im Gegensatz zu den CRF-Tabellen werden die Emissionen von Ziegen aufgrund des geringen Anteils (<1 Promille) der Emissionen vernachlässigt.

# Modellannahmen
Die Emissionen werden mit Hilfe folgender Formel berechnet:

Anzahl Tiere x Durchschnittliche Energieaufnahme pro Tier [MJ/Tier und Tag] x Durchschnittliche CH4 Konversionsrate

Im Falle der Schafe und des anderen Viehs sind die durchschnlittliche Energieaufnahme und die durchschnittliche CH4 Konversionsrate zu einem Emissionsfaktor zusammengefasst, da die beiden erstgenannten Werte in den CRF-Tabellen für Schafe und anderes Vieh nicht verfügbar sind.

Für die Prognosen der Emissionen gibt es drei Hebel: Die Anzahl der Tiere, die durchschnittliche Energieaufnahme pro Tier und die durchschnittliche CH4 Konversionsrate. Für Schafe und anderes Vieh sind die beiden letztgenannten entsprechend zu einem Hebel, dem Emissionsfaktor pro Tier, zusammengefasst.

Der Emissionsfaktor ist über folgende Beziehung mit der durchschnittlichen Energieaufnahme pro Tier und der durchschnittlichen CH4 Konversionsrate verknüpft:

Durchschnittliche Energieaufnahme pro Tier x 365 x Durchschnittliche CH4 Konversionsrate x 10^-3 / Energiegehalt CH4 [MJ/kg]

Wobei der Energiegehalt von CH4 ist 55,65 MJ/kg.
