# CRF 1.A.2.g Other

1.A.2.g umfasst ein breites Spektrum an Emissionen, die im Rahmen des nationalen Inventarberichts nicht weiter spezifiziert werden.
Es umfasst es die gesamte industrielle Verbrennung von Brennstoffen zur Erzeugung von Prozesswärme und Strom oft in kombinierten Anlagen.

## Modellannahmen
Die genauere Modellierung der Kategorie erfordert umfassende Daten, die dem Umweltbundesamt vorliegen, die aus vertraulichkeitsgründen nicht öffentlich zugänglich sind.
Erschwerend kommt hinzu das in der öffentlichen Version des CRF Berichtes die Aktivitätsdaten für die Kategorie 1.A.2.g nicht nach Energieträger aufgeschlüsselt werden.
Auf Nachfrage beim UBA werden die Daten zum der Brennstoffeinsatz allerdings herausgegeben.
Im GermaZero Sharepoint liegen sie unter Bilanzierung -> Industrie.
Generell wurde die angenommen, dass die Emissionen in 1.A.2.g durch drei verschiedene Prozesse reduziert werden.

1. Eine weiter verbreitet Kreislaufwirtschaft trägt veringernd zum Energiebedarf insgesamt bei, weil industrielle Aktivität abnimmt. Darauf ist insbesondere in der energieintensiven Grundstoffindustrie zu hoffen.
2. In der Stromerzeugung gehen industrielle Verbraucher dazu über Strom nicht aus eigenen fossilen Anlagen, sondern aus erneuerbaren Anmlagen zu beziehen. Auch wenn dieser Strom über einen Direktvertrag vermarktet wird und sogar nie im öffentlichen Netz transportiert wird, wird der zubau von EE-Anlagen zu diesem Zweck im Rahmen der Modellierung von 1.A.1.a betrachtet. An dieser Stelle muss nicht der gesamte fossile Energiebedarf durch strom ersetzt werden, da fossile Wärmekraftwerke über einen sehr geringen Wirkungsgrad verfügen. 1 TJ aus den Aktivitätsdaten zu 1.A.2.g müssen also nur mit ca. 0,5 TJ erneuerbarem Strom ersetzt werden.
3. Die übrige Prozesswärme muss durch direkt oder indirekt mit Hilfe von Wärmepumpen unter der Verwendung von elktrischem Strom gedeckt werden. In diesem Fall können keine Effizienzgewinne erwartet werden, 1 TJ aus den Aktivitätsdaten zu 1.A.2.g müssen also mit 1 TJ erneuerbarer Energie ersetzt werden.

Um die verschiedenen Prozesse getrennt zu modellieren muss der Brennstoffeinsatz für die Strom und Prozesswärmeerzeugung getrennt werden was mit Hilfe der Daten den Aktivitästdaten des UBA nicht möglich ist. Es wurde daher auf die Daten aus der Energiebilanz der AGEB zurückgegriffen.

### Stromerzeugung
Die Stromerzeugung in industriellen Anlagen kann nicht so genau erfolgen wie das bei der Stromerzeugung für das öffentliche Netz in 1.A.1.a passiert ist.
Insbesondere fehlt ein Datensatz über die installierte Leistung der Kraftwerke, differenziert nach Energieträger oder ein Datensatz über die Vollasstunden der Kraftwerke, ebenfalls differenziert nach Energieträger.
Anders als bei der Stromerzeugung der öffentliche Kraftwerke (siehe 1.A.1.a) werden daher keine Zeitreihen über die Netto Nennleistung der Kraftwerke prognostiziert.
Die Modelierung beschränkt sich somit auf die Entwicklung des Primärenergiebedarfs und des Bruttostromausstoses.

Mithilfe der Statistik über die gesamte Stromerzeugung (Strommix) der Arbeitsgruppe Energiebilanzen (AGEB) und der Daten aus der Energiebilanz der AGEB lassen sich Primärenergienutzungsgrade bei der Stromerzeugung, differenziert nach Energieträger berechnen.
Dabei wird über die industriellen und öffentlichen Kraftwerke gemittelt.
Der Primärenergiebedarf der industriellen Wärmekraftwerke der Stromerzeugung, aufgeschlüsselt nach Energieträger, kann der Zeile 19 der Energiebilanz der Arbeitsgruppe Energiebilanzen (AGEB) entnommen werden.
Zusammen mit den eben erwähnten Wirkungsgraden lässt sich so die Bruttostromerzeugung der industriellen Kraftwerke berechnen.
Die Treibhausgasemissionen können dann basiert auf der Primäerenergienutzung berechnet werden.
Dabei werden die spezifischen Emissionsfaktoren aus der Kategorie 1.A.1.a genutzt, da die spezifischen Emissionswerte für 1.A.2.g im CRF Bericht fehlen.
Diese werden als konstant angenommen.
Die Bruttostromerzeugung der Industriekraftwerke, aufgeschlüsselt nach Energieträger, kann dann über die nächsten 15 Jahre modelliert werden.
Hierbei kann die Veränderung der Nutzung bestimmter Energieträger in Industriekraftwerken eingestellt werden.
Für diesen Zeitraum wird dann mit Hilfe der Wirkungsgrade ein Primärenergieverbrauch berechnet.
Schlussendlich kann somit wieder auf die Treibhausgasemissionen geschlossen werden.
Insgesammt kann so die Reduktion der Nutzung fossiler Krafsstoffe in Industriekraftwerken berechnet werden.
Die Veränderung des Anlagenparks selber und Veränderungen im Auslastungsgrad bleiben allerdings unbeachtet.

### Prozesswärme
Die Brennstoffnutzung in der Industrie, die nicht zur Stromerzeugung genutzt wird, wird in der AGEB Energiebilanz in Zeile 46 bis 60 differenziert nach Energieträger aufgeführt.
Weil die Sektorenabgrenzung der AGEB sich von der Abgrenzung innerhalb der Unterkategorien von 1.A.2 stark unterscheidet kann kein direkter Vergleich gezogen werden.
Für das Jahr 2019 werden die Aktivitätsdaten für die Erzeugung von Prozesswärme berechnet, indem der Endenergieverbrauch der Verarbeitenden Industrie in Zeile 60 der AGEB Energiebilanz un die Kraftstoffklassen des NIR übertragen werden.
Davon werden die Aktivitätsdaten für die NIR Kategorein 1.A.2.a bis 1.A.2.f abgezogen.
Im Modell kann dann die Veränderung der Nutzung der fossilen Energieträger, der Biomasse und des gesamten Energiebedarfs für die Folgejahre eingestellt werden.
Die Lücke zwischen dem gesamten Energiebdarf und den anderen Energieträgern wird dann mithilfe von direkter Elektrifizierung geschlossen.
Die Emissinosfaktoren für die Kateogrie werden aus dem NIR von der Kategorei 1.A.2 übernommen, da die Werte für 1.A.2.g nicht vorliegen.
Es wird angenommen, dass die Emissionsfaktoren für die Folgejahre konstant bleiben.
Insgesamt kann so eine Veränderung in der Nutzung der Energieträger in den Folgejahren abgebildet werden.
