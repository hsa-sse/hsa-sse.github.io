---
title: Secure Software Engineering
layout: default
---
*Hochschule Ansbach, Semester: SS 26* ([Archiv](/archive))

# Syllabus
Das Ziel dieser praxisorientierten Veranstaltung für fortgeschrittene Studierende ist es, IT-Sicherheitsherausforderungen in der Softwareentwicklung zu verstehen und zu lösen. Anhand von Codebeispielen lernen Sie, typische Sicherheitsrisiken und Schwachstellen zu identifizieren, zu bewerten und zu beheben. Zudem erwerben Sie theoretisches Wissen über gängige Schutzmaßnahmen entlang des Secure Software Development Lifecycle (SSDL).

Während des Kurses identifizieren Sie Schwachstellen in einer App und entwickeln gezielte Schutzmaßnahmen. Zu Hause bearbeiten Sie kleinere Assignments. Am Ende des Semesters präsentieren Sie einen tiefgehenden theoretischen Einblick in eines der behandelten Themen – der über die in der Veranstaltung vermittelten Inhalte hinausgeht – und demonstrieren anhand Ihrer Implementierung, wie Sie die diesbezüglichen Schwachstellen der App ausgenutzt und erfolgreich behoben haben.

### Lernziele
- Verstehen und Anwenden des Secure Software Development Lifecycle
- Verstehen typischer Schwachstellen und Sicherheitsrisiken bei der Softwareentwicklung
- Analysieren und Beheben konkreter Schwachstellen (z. B. SQL Injection, XSS, SSRF)

### Voraussetzungen
- Kenntnisse in Java und Spaß am Programmieren
- Basiswissen zu Datenbanken und Web-Technologien
- Interesse an IT-Sicherheit und Spaß am Experimentieren

## Inhalte

| **Datum** | **Themen**                     | **Assignment**                                                                   | **Abgabefrist<br>(23:59 Uhr)**         |
|-----------|--------------------------------|----------------------------------------------------------------------------------|----------------------------------------|
| 19. März  | Setup & Technologien           | [Bootiful Spring (A1)](https://moodle.hs-ansbach.de/mod/url/view.php?id=186556)  | -                                      |
| 26. März  | Secure Software Dev. Lifecycle | -                                                                                | <span style="color:red"> **A1**</span> |
| 2. April  | --- Feiertag ---               |                                                                                  |                                        |
| 9. April  | Cryptographic Failures         | [The Argonaut (A2)](https://moodle.hs-ansbach.de/mod/url/view.php?id=186557)     | -                                      |
| 16. April | Broken Access Control          | -                                                                                | <span style="color:red"> **A2**</span> |
| 23. April | SQL Injection                  | [SQL Blind Date (A3)](https://moodle.hs-ansbach.de/mod/url/view.php?id=186558)   | -                                      |
| 30. April | Command Injection              | -                                                                                | -                                      |
| 7. Mai    | XSS                            | [XSStravaganza (A4)](https://moodle.hs-ansbach.de/mod/url/view.php?id=186559)    |                                        |
| 14. Mai   | --- Feiertag ---               |                                                                                  |                                        |
| 21. Mai   | --- Blockwoche ---             |                                                                                  |                                        |
| 28. Mai   | SSRF                           |                                                                                  |                                        |
| 4. Juni   | Path Traversal                 | [DotDotPwn (A5)](https://moodle.hs-ansbach.de/mod/url/view.php?id=186560)        | <span style="color:red"> **A4**</span> |
| 11. Juni  |  --- Feiertag ---              |                                                                                  |                                        |
| 18. Juni  | SCA (Dependency Check)         | [Lord of the Libs (A6)](https://moodle.hs-ansbach.de/mod/url/view.php?id=186561) | -                                      |
| 25. Juni  | Präsentationen                 |                                                                                  |                                        |
| 2. Juli   | Präsentationen                 | -                                                                                | -                                      |



## Bewertung
tbd
{% comment %}
(30 % Assignment)
(30 % Abgabe App)
(40 % Entwicklung einer Spring Boot App mit nicht in VL behandelter Schwachstelle (bspw. Insecure Deserialization) und Präsentation)
Beispiele:
- Insecure Deserialization
- CSRF!
- Session Management & Session Fixation
- Race Conditions
- SSTI
- CORS Misconfiguration?
- Fehlerhaftes Output Encoding?
- JWT Misuse?
- Clickjacking?
- Resource Exhaustion /DOS (Zip Bombe)
- Timing-Side-Channel Attacks (e.g. token validation)
- Timing-based User-Enumeration (e.g. Login-/Reset-Flow)
- XSS trotz CSP
{% endcomment %}

## Impressum
Michael Netter<br>
Hochschule Ansbach<br>
Postfach 1963<br>
91510 Ansbach<br>

Kontakt:<br>
E-Mail: michael.netter@hs-ansbach.de<br>
Tel.: +49 (0) 981 / 4877 227

[Datenschutzerklärung](/datenschutz)