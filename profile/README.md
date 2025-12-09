# Projekt Adler

### Links

| Beschreibung | Link |
| --- | --- |
| Projektwebseite | https://projekt-adler.eu |
| Autorentool Download | https://github.com/ProjektAdLer/Autorentool/releases/latest |
| AdLer-Webserver-Edition - Offizielle Testumgebung | https://hello.projekt-adler.eu |
| AdLer Icons Downloadpage | https://icons.projekt-adler.eu |
| AdLer 3D-Models Downloadpage | https://models.projekt-adler.eu |
| AdLer Lernzielunterstützung | https://lernziele.projekt-adler.eu |
| AdLer Dokumentation | https://docs.projekt-adler.eu |

### AdLer selbst betreiben

**Den vollständigen AdLer aufsetzen**
- [AdLerStack releases](https://github.com/ProjektAdLer/AdLerStack/releases): beinhaltet die `docker-compose.yml` auf der sämtliche unserer Deployments aufbauen und eine Beispiel `.env` Datei.
- [AdLerStack deploy guide](https://github.com/ProjektAdLer/AdLerStack/blob/main/docs/deploying_adler.md): Eine kurze Anleitung zum aufsetzen des AdLers.
- [deployment-adler-prod](https://github.com/ProjektAdLer/deployment-adler-prod): Die vollständige deployment Konfiguration wie wir sie auf unserer Produktivumgebung einsetzen. Geeignet als referenz. Zu beachten ist insbesondere der `deploy` branch. Hinweis: die Secrets sind nicht in der .env aufgeführt und wurden extern verwaltet.
- [Admin Dokumentation: AdLer installieren](https://projektadler.github.io/Documentation/adler-installieren-vp.html): Eine etwas umfangreichere Dokumentation zu unserem konkreten Setup.

**Die Webserver Edition aufsetzen**
- [Installationsanleitung AdLer-Webserver-Edition](https://hello.projekt-adler.eu/Documentation/adler-webserver-edition-installationsanleitung.html): Hierbei handelt es sich um eine reduzierte Version des AdLers, welche die Verknüpfung zum LMS (Moodle) entfernt und nur im Browser des jeweiligen Nutzers läuft. Es findet keine Persitierung oder Synchronisation des Lernfortschritts außerhalb des Webbrowsers statt.


