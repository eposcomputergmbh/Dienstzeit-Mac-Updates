# Dienstzeit Mac-Updates

Dieses öffentliche Repository verteilt die signierten Mac-App-Pakete und Release-Metadaten von Dienstzeit. Der Quellcode wird separat verwaltet.

## Download und Erstinstallation

Freigegebene Pakete erscheinen unter [aktuellem Release](https://github.com/eposcomputergmbh/Dienstzeit-Mac-Updates/releases/latest). Für die erste Installation das ZIP entpacken und `DienstzeitMac.app` nach `~/Applications` kopieren. Die App muss dem ausführenden Benutzer gehören, damit spätere Updates ohne macOS-Administratorfreigabe möglich sind.

## Updates

Die Mac-App prüft alle 24 Stunden auf eine neue Version. Der Hinweis mit dem Button **Update** ist sowohl im Kartenterminal als auch in der Verwaltung sichtbar. Die Installation benötigt keine Dienstzeit-Anmeldung. Nach Klick auf **Update** werden Download und Signatur geprüft; anschließend startet die App neu. Laufende Stempelungen und Speichervorgänge verhindern den Neustart.

Der Updatefeed wird mit einem vollständig geprüften stabilen Release veröffentlicht: [appcast.xml](https://github.com/eposcomputergmbh/Dienstzeit-Mac-Updates/releases/latest/download/appcast.xml).

Die signierte und von Apple notarisierte App ist für macOS 15 oder neuer verfügbar. Das Paket enthält Apple-Silicon- und Intel-Versionen.
