# Tarifberater
Wir brauchen eine Anwendung für eine Webseite, auf der Nutzer den anonymisierten Anruf-Verlauf aus ihrer Telefonanlage hochladen können. Anhand der Daten empfiehlt die Anwendung den besten Tarif.

## Anruf-Verlauf
Der Anruf-Verlauf hat das folgende Format:
```javascript
[
'in 2019-09-14 12:20 12:45 mobil',
'out 2019-09-14 13:30 15:01 festnetz'
]
```
in und out signalisierten, ob es ein eingehender oder ausgehender Anruf war.
Die erste Uhrzeit ist der Beginn des Gesprächs und die zweite das Ende

## Tarife
Erstellt eine Liste von Tarifen, die von der Anwendung abgefragt werden kann. z.B.:

**Tarif 1**
1 Cent pro Minute in's Festnetz
9 Cent pro Minute für Mobilfunk

**Tarif 2**
Bis zu 100 Minuten pro Monat in's Festnetz und 50 Minuten in's Mobilfunknetz inklusive.
Danach
19 Cent pro Minute in's Mobilfunknetz
3 Cent pro Minute in's Festnetz
## ToDo
Erstellt ein Objekt, das ein Array mit den Tarifen enthält und eine Methode, die als Parameter die Anrufliste annimmt und den günstigsten Tarif zurückgibt.
