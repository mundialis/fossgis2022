actinia talk: https://pretalx.com/fossgis2022/talk/review/RARQYQUFVYQCLRA3EAKQD97PQK3KYLCV
actinia ws:   https://pretalx.com/fossgis2022/talk/review/JL3HHK7F3HDVCSTYNCMBXPBZ8NG8D8UC
stac talk:    https://pretalx.com/fossgis2022/talk/review/P3VZNV3XSVD9MNCEW8ELWFAZEJRJDUFM



STAC und openEO in der Praxis: Integration in actinia

Mit Hilfe von STAC können Geodaten leichter indiziert und aufgefunden werden. Mit Hilfe der openEO API gibt es einen HTTP API Standard für die Prozessierung von Erdbeobachtungsdaten. Dabei sind die openEO Endpunkte für die Entdeckung der Daten (EO Data Discovery) kompatibel zu STAC, so dass bei einer Implementierung beide Konzepte wunderbar zusammenspielen können.
Dieser Vortrag zeigt am Beispiel von actinia und dem openeo-grassgis-driver, wie so eine Implementierung aussehen kann.

Mit Hilfe von [STAC](https://stacspec.org/) können Geodaten leichter indiziert und aufgefunden werden. Mit Hilfe der [openEO API](https://openeo.org/) gibt es einen HTTP API Standard für die Prozessierung von Erdbeobachtungsdaten, so dass verschiedene Client- und Serverimplementierungen untereinander austauschbar sind. Dabei sind die openEO Endpunkte für die Entdeckung der Daten (EO Data Discovery) kompatibel zu STAC, so dass bei einer Implementierung beide Konzepte wunderbar zusammenspielen können.
Dieser Vortrag zeigt am Beispiel von [actinia](https://github.com/mundialis/actinia_core) und dem [openeo-grassgis-driver](https://github.com/Open-EO/openeo-grassgis-driver), wie so eine Implementierung aussehen kann. Actinia bietet über ein Plugin die Möglichkeit, bestehende STAC Collections zu registrieren, so dass diese als Input für Prozessierungen gefiltert und verwendet werden können. Das Ergebnis einer Prozessierung kann wiederum als spatio temporal asset registriert werden.
Die Anbindung an den openeo-grassgis-driver ermöglicht eine standardisierte Verwendung all dessen von allen Clients, die kompatibel zur openEO API sind.



Neues von actinia

"Hallo, mein Name ist actinia. Ich wurde entwickelt, um GRASS GIS Funktionalität über eine HTTPS REST API nutzbar zu machen und um Algorithmen zu Cloud-Geodaten zu bringen. Falls Sie mich schon kennen - wissen Sie, was in den letzten 2 Jahren alles passiert ist? Eine ganze Menge! Verwendung von Zwischenergebnissen, Helm Chart, verbesserter Exporter, STAC Integration und mehr. Ich möchte Ihnen auch etwas über meinen Einsatz in verschiedenen Projekten erzählen. Also kommen Sie vorbei!"

"Hallo, mein Name ist [actinia](https://github.com/mundialis/actinia_core). Einige von Ihnen kennen mich vielleicht schon. Ich wurde 2019 ein OSGeo Community Projekt und mein erster Auftritt auf einer FOSSGIS Konferenz war 2020, wo ich in einem Vortrag vorgestellt wurde. Für diejenigen, die mich noch nicht kennen - ich wurde entwickelt, um GRASS GIS Funktionalität über eine HTTPS REST API nutzbar zu machen, mit der GRASS GIS Locations, Mapsets und raum-zeitliche Daten als Ressourcen zur Verfügung stehen, um ihre Verwaltung und Visualisierung zu ermöglichen. Dadurch kann man mit mir alle Arten von Prozessierungen machen, die auch mit GRASS GIS möglich sind, wie Klassifikationen, Analysen von Zeitreihen, Erdbeobachtungsdaten, Punktwolken und viele mehr. Ich wurde entwickelt, um Algorithmen zu Cloud-Geodaten zu bringen, die täglich wachsenden großen Geodatenpools im Blick. Ich kann in einer Cloud-Umgebung installiert werden und dabei helfen, eine große Menge an Geoinformationen aufzubereiten, zu analysieren und bereitzustellen. Aber auch für diejenigen, die mich schon kennen - wissen Sie, was in den letzten 2 Jahren alles passiert ist? Eine ganze Menge! Stichworte sind: Verwendung von Zwischenergebnissen, Helm Chart, verbesserter Exporter, Überwachung der Mapset-Größe, STAC Integration und eine Aufteilung meiner Plugins inklusive Modul-Selbstbeschreibung von mehr als 500 Modulen, um nur einige zu nennen. Mit der Weiterentwicklung des openeo-grassgis-driver können Sie mit mir entweder in meiner Muttersprache oder über die openEO API kommunizieren. Ich möchte Ihnen auch ein paar interessante Fakten über meinen Einsatz in verschiedenen Projekten erzählen. Also kommen Sie vorbei!"



Eine kleine Einführung in Actinia: Geoverarbeitung in der Cloud

[Actinia](https://github.com/mundialis/actinia_core) (https://actinia.mundialis.de/) ist eine open source REST API für die skalierbare, verteilte, hochleistungsfähige Verarbeitung geographischer Daten, die hauptsächlich GRASS GIS für Berechnungsaufgaben nutzt. Die Kernfunktionalität umfasst die Verarbeitung von Satellitenbildern (sowohl Einzelszenen als auch Zeitreihen), sowie die Verarbeitung von Raster- und Vektordaten, auch aus externen Quellen. Die bestehenden großen offenen Datenpools der Erdbeobachtung (Landsat, Sentinel, etc.) wachsen von Tag zu Tag zusammen mit einer Fülle anderer Quellen. Actinia folgt dem Paradigma, Algorithmen zu den Daten zu bringen und erspart den Nutzern das lokale Herunterladen und Verarbeiten riesiger Datenmengen. Actinia ist seit 2019 ein OSGeo Community Projekt. Es kann mit docker-swarm auf einer Workstation, aber auch in OpenShift und kubernetes installiert werden.

In diesem Workshop werden wir eine kurze Einführung in REST API Konzepte und einige Hintergründe zur Cloud Verarbeitung geben. Es folgt eine Einführung in [actinia](https://github.com/mundialis/actinia_core) mit praktischen Übungen, um sich mit dem Thema vertraut zu machen. Dieser Workshop richtet sich an Personen mit Grunderfahrungen in der Geodatenanalyse. Und wir freuen uns darauf, die Actinia-Community zu erweitern!
