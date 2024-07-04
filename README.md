# sq7a_project

SQ7A - Docker-Compose Projekt
Zeit - 180 Minuten
20 Minuten Einführung
150 Minuten + 180 Bearbeitung des Auftrags (in diesem + den beiden folgenden Blöcken)
10 Minuten Besprechung
Lernart bzw. Sozialform
Partnerarbeit (2 Personen, im Ermessen der LP)
HANOKs
M169
1.4. Kennt die Vorgehensweise, wie Services im Backend bereitgestellt und wie die Services im Frontend
von Clients genutzt werden.
1.5. Kennt die einer Containerumgebung zugrundeliegende Architektur (Daemon, Client/Server, Images,
Container, Registry).
1.6. Kennt die Abhängigkeiten von Services und deren Bereitstellung in einer lokalen Infrastruktur
(Beispiele: persistente Datenspeicherung, Vernetzung und andere).
3.3. Kennt die Vorgehensweise, wie Systeme und Services codebasiert (Infrastructure as Code - IaC)
aufgebaut werden.
M347
2.1. Kennt Architekturformen (z.B. Aufteilung der Dienste auf Container) und deren Aufbau, Konzept und
Unterschiede für den Einsatz von Containerlösungen.
2.4. Kennt die Anwendungsmöglichkeiten von Containern, deren Kompositionen und deren Services.
4.3. Kennt die Entwicklungsschritte zur Virtualisierung einer Applikation oder Dienstes mit Containern.

Einführung LP in das Basiswissen
Motivation für IPA-nahes Projekt mit Arbeitsplanung und Dokumentation
Motivation für Pair Programming: zwei Lernende arbeiten gemeinsam an einem Laptop
Projekt wird mit weiteren Inputs (SQ8a, SQ9a) bis Block 10 durchgeführt
Bewertungsraster für das Projekt besprechen
Weitere Literatur zum Thema
Docker für Einsteiger [Hans M. Hopp, BMU Verlag] Kapitel 12
Ausgangslage
aufgabe nhp.md 2024-06-27
2 / 3
Du hast gerade gelernt, wie man Applikationsstacks für Microservices mit docker-compose Files elegant
konfigurieren und erstellen kann. Nun stellst du dein Wissen in einem praktischen Projekt zur Verfügung.

Ziele / erwartete Lernergebnisse
Du erstellst Microservices mit docker-compose
Du erstellst Testpläne.
Du testest das System und protokollierst die Ergebnisse

Auftrag
Für ein Informatik-KMU sollst du einige Dienste einrichten. Folgende Anforderungen wurden vom
Auftraggeber formuliert:
1. Das KMU möchte einen Jupyter-Server mit persistenter Datenspeicherung. (Jupyter ist ein
Webservice für interaktives Python-Scripting, ohne dass man selbst Python installiert haben muss)
2. Das Unternehmen möchte die Firmenwebseite mit Drupal erstellen. Als DB-Backend soll PostGres
eingesetzt werden.
3. Das Unternehmen möchte den Quellcode firmenintern auf einer gogs Instanz mit PostGres-Backend
verwalten.
4. Alle Daten der Dienste müssen persistent gespeichert werden.
5. Die Dienste sollen mit Portainer überwacht werden.
6. Die notwendigen Dateien sowie die Systemdokumentation sollen auf deinem privaten GithubRepository versioniert werden.
