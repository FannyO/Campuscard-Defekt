_**Ngo onla fanny, Eric Martial Tindo, Arnold Marius N. Nkouamou, Guerin Fossi , Dieffi T.Arold kevin**_

-Prozesszweck: _Bearbeitung eine defektcard._

-Kunden und Erwartung:_Die Studenten erwarten seine neue Campuscard._

-Outcome:_Benachrichtigen der Studierende über der Abholungstermin._

-Auslöser:_Studierende Secretariat._

-Erster Prozesschritt:_Abholung der Karte._

-Schnittstellen Ausgangseitig: _controlling._

-Schnittstellen Eingangseitig:_Transation festgeschalten._

**Bei einer Transaktion in der Hochschule Mensa stellt der Studierende fest, dass seine Campuscard nicht funktioniert, dann geht er damit zum Studentensekretariat, Einmal dort wird von der Sachbearbeiterin nach augenscheinlichen Defekten (geknickt, gelocht, eingerissen) geschaut. Falls augenscheinlicher Defekt (unsachgemäßer Umgang) wird in der Regel am selben/nächsten Tag eine Ersatzkarte ausgestellt, darüber hinaus überprüft das Studentensekretariat, ob es Geldguthaben in der alten defekten Campuscard gibt. Dies wird beim Studentenwerk Potsdam per E-Mail angefragt und ihnen nach Rückmeldung (2-3 Tage) Falls kein augenscheinlicher Defekt wird der Studierende zum Rechenzentrum geschickt mit der Bitte um Überprüfung der Campuscard, das Rechenzentrum überprüft noch mal die Campuscard mit einem bestimmten Gerät und bestätigt einen Chip oder Antennendefekt durch "Nichtmehrauslesbarkeit der Karte", teilt dem Studentensekretariat diese Meldung mit, dann geht der Studierende wieder zum Studentensekretariat, gibt die defekte Campuscard ab und lässt sich eine neue Campuscard ausstellen. Das Studentensekretariat übertragt das Geldguthaben je nach der Antwort des Studentenwerks Potsdam nach Erhalt ihrer Rückmeldung auf die neue Campuscard. Der Studierende wird über einen Abholungstermin benachrichtigt und kann seine neue Campuscard im Studentensekretariat abholen, anschließend endet der Prozess mit der Abholung der neuen Campuscard.**


<img src="https://github.com/FannyO/Campuscart-Defekt/blob/master/modellf.PNG?raw=true" alt="modellf.PNG">
## Analyse

**Prozessqualität**
1.	Die erste Schwachstelle (XOR- Gateways) entscheidet, ob das Chip Defekt ist oder nicht.
Hier überprüft das Rechenzentrum die Studierendenkarte. Falls die Karte ein Chip oder ein Antenne Problem hat, wird der Prozess fortgesetzt. Im Fall die Karte ein anderes Problem (Wie zum Beispiel: Karte ist abgelaufen oder gesperrt, Die Karte hat ein Software Problem) hat, dann wird der Prozess beendet.

**Prozesszeit**

2.	Die zweite Schwachstelle entscheidet, ob die defekte Karte gutgeschrieben ist oder nicht.  Vor diese Schwachstelle wird die Studierendensekretariat innerhalb von zwei bis drei Tage über die Karte Guthaben benachrichtigt. Falls Guthaben vorhanden waren, wird diese Guthaben von Sekretariat übertragen und Studierende über einen Abholungstermin benachrichtigt. Im Fall kein Guthaben vorhanden wird Studierende über einen Abholungstermin benachrichtigt.

**.Unser Prozess ist teilweise digital**

**.Auf der Aktivität (Eventbasiertes Gateway) verwenden**

## Verbesserungen
3. 
Die Guthaben Prüfung durch Studentenwerk Potsdam könnte vermieden werden, so kann eine Datenbank einrichten, in der das Studierendensekretariat Zugang zu den Informationen über das Guthaben der Studenten hat.


**.Prozesszeit**

2)3) Lösung: Die Aktivität wird durch einen Service Task ersetzt 

3) Automatisieren von noch mehr prozessschritten 




