# Ölverbrauch
Bestimmt den Ölverbrauch und Kosten nach dem FIFO Prinzip

Dies ist eine ganz einfache Anwendung, die uns hoffentlich (viel) Zeit erspart.

Aus dem Anfangsbestand in Litern und dem Preis dieses Anfangsbestandes zusammen mit Zukauf in Litern, den Gesamtkosten des Zukaufs und dem Verbrauch in Litern, der durch Ablesung einmal jährlich ermittelt wird, berechnen wir den jährlichen Verbrauch, die Verbauchskosten und den Rest sowie die Restkosten. In der nächsten Heizperiode ist der Restbestand der Anfangsbestand und alles geht von vorne los.

Heizperiode ist normalerweise vom 1.7. eines Jahres bis zum 30.6 des nächsten Jahres. Die Heizung wird sicherlich nicht so lange laufen. Dann verbrät sie aber auch kein Öl!

Eingabe:

- Anfangsbestand (l - Liter)
- Kosten des Anfangsbestandes (Euro)
- Zukauf während der Heizperiode (l)
- Kosten des Zukaufs (Euro)
- Verbrauch (durch jährliche Ablesung) ermittelt (l)

Ausgabe:

- Verbrauch während der Heizperiode (l)
- Gesamtkosten des Verbrauchs (Euro) und Kosten pro Liter (Euro / l)
- Restbestand (l), Gesamtkosten des Restbestandes (Euro), Kosten pro Liter des Restbestandes (Euro / Liter)


Restbestand der vorherigen Heizperiode entspricht dem Anfangsbestandes der nächsten Heisperiode.

Das FIFO Prinzip besagt, dass ein Restbestand und dessen Kosten zuerst verbraucht werden bevor der Zukauf verbraucht wird. Die Verbrauchskosten sind daher nicht ein Durchschnittswert, sondern werden genau aus den Werten und Kosten der verschiedenen Bestaende ermittelt. Im Gruden ist es einfach und nicht der Rede wert. Wenn man dies jedoch nur einmal im Jahr macht, muss man sich immer wieder alles von vorne durch den Kopft gehen lassen. Daher einemal richtig implementiert und Zeit gespart.

Ich hoffe es hilf, wenns dann fertig ist, :).


