# ioBroker.heliotherm
Iobroker Adapter für Heliotherm Wärmepumpen der modulierenden HP-LM-WEB Serie.

Verbunden ist die Wärmepumpe mit dem Original Heliotherm Moxa Modem das es als Option gibt.
Vielleicht kann ich auch dem ein oder anderen bei der Konfiguration des Moxa Modem's helfen!

Das Protokoll ist mir inzwischen auch bekannt!

Sehr viele Kommandos zur Abfrage der Wärmepumpe kenne ich auch.

Login
Logout
Fehlerspeicher lesen
ALLE MP's (alle Messpunkte) - Durch ein Kommando wird alles aufgelistet
Einige SP's (Setpoints) - Vielleicht gibt es da ja auch ein Kommando um alle abzufragen
Zeitprogramme auslesen
Uhrzeit auslesen

Ich hoffe es gibt auch ein Kommando für Offenbare mir alle SP's

Wenn mir jemand helfen will kann er mich gerne direkt anschreiben!

Das Moxa Modem schickt leider maximal 8 Bytes über das Netzwerk was leider alles zerstückelt was da ankommt.
Bisher kann ich das Frage - Antwort Spiel mit der Wärmepumpe wie Login, Logout, Messpunkte Abfragen, Fehlermeldungen lesen, Uhrzeit auslesen ... (Kommunikation mit dem Modem mit einer Telnet Verbindung auf Port 4001)

Leider habe ich das große Problem bei der Abfrage für Offenbare mir alles..

Mit einer Anfrage an die Wärmepumpe -> Es kommen bei meiner Luftwärmepumpe (HP30LM-WEB) 103 Antworten mir ca. 60-110 Bytes in jeder Antwort! Leider schickt das Moxa aber schon einen Teil der folgenden Antwort mit den ich dann an den Anfang des nächsten Buffers setzen müsste. Leider bin ich Javascript Anfänger ohne Kentniss für Objektorientiertes Asyncrones Programmieren (habe bisher nur C auf Microcontroller programmiert).

Über das Offenbare mir ALLES Kommando möchte ich die Datenpunkte für den ioBroker aufbauen dann ist der Adapter flexibel für alle Wärmepumpentypen von Heliotherm. Darüber lässt sich dann auch alles ändern was man will! :-)

Weitere Infos möchte ich hierüber nicht veröffentlichen!
