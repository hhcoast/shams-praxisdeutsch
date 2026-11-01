# SHAMS Praxisdeutsch Haus Hetzendorf

Ein statischer, mobilfreundlicher Lernprototyp für GitHub Pages.

## Veröffentlichung

1. Neues GitHub Repository anlegen, z. B. `shams-praxisdeutsch`.
2. `index.html` in das Stammverzeichnis hochladen.
3. Unter **Settings → Pages** die Option **Deploy from a branch** wählen, Branch `main`, Folder `/ (root)` und speichern.
4. Nach Bereitstellung ist die Seite unter `https://BENUTZERNAME.github.io/shams-praxisdeutsch/` erreichbar.

## Enthalten

- 9 Tätigkeits- und Lernthemen mit deutschen Beispielsätzen und redaktionell verfassten levantinisch-arabischen Alltagstranslationen
- Deutsch vorlesen per Browserstimme, Arabisch vorlesen soweit eine arabische Systemstimme verfügbar ist
- Wörter antippen, nachschlagen und merken
- A2-Übungen mit Texteingabe, optionaler browserbasierter Spracheingabe und eigener Audioaufnahme zum Anhören
- A2 Praxischeck mit 5 Aufgaben, Musterantworten und manueller Bewertung
- Ein eigener Themenbereich für typische Anweisungen der Hausleitung (redaktionelle Übungsbeispiele, keine offiziellen Anweisungen)
- Speicherung von Antworten und Wörterliste lokal im Browser (localStorage)

## Einschränkungen

- Es gibt **keine** freie Echtzeitübersetzung beliebiger Sätze, keine automatische Korrektur und **keine** zuverlässige Aussprachebewertung. Dafür braucht es zusätzliche Dienste mit Datenschutzkonzept und Backend.
- Nicht alle Browser unterstützen SpeechRecognition. Auch kann Audio zur Spracherkennung an externe Dienste übermittelt werden.
- Arabische synthetische Stimme setzt die Verfügbarkeit einer passenden Stimme auf dem Gerät voraus.
- Die Audioaufnahme wird nicht dauerhaft gespeichert, sondern kann während der offenen Sitzung direkt abgespielt werden.
- Kein offizielles Angebot oder Arbeitsablaufhandbuch der Johanniter. Hausinterne Details müssen Bernie bzw. die Leitung freigeben.
- **Keine Bewohnerdaten oder vertrauliche Dienstinformationen eingeben.** GitHub Pages ist öffentlich erreichbar und kein geeignetes System für personenbezogene Fallnotizen.

## Quellen

https://www.johanniter.at/wien/hilfe-angebote/unterstuetzung-in-krisenzeiten/wohnungslosenhilfe/wie-die-johanniter-helfen
https://www.johanniter.at/hilfe-angebote/unterstuetzung-in-krisenzeiten/wohnungslosenhilfe
https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API

## Nächste Schritte

Für echtes freies Übersetzen, arabischsprachige Worterklärungen auf Nachfrage, gezielte Rückmeldung zu Sprechleistungen und ein redaktionelles Portal für Bernie wäre ein separates Backend mit abgesicherter API, Rollenrechten und einem geprüften Datenschutzprozess sinnvoll.

## Version 0.3

- Schalter „Alle Übersetzungen anzeigen“ und „Nur Deutsch“ oberhalb der Lerntexte
- `.nojekyll` für einfache statische GitHub-Pages-Auslieferung
- Keine externen API-Schlüssel, kein Backend und keine Übertragung von eingegebenen Lernantworten durch eigenen Code

## Qualitäts- und Datenschutzprüfung vor dem öffentlichen Einsatz

- Arabische Übersetzungen von einer arabischsprachigen Vertrauensperson prüfen lassen. Dialekte unterscheiden sich.
- Betriebsspezifische Anweisungen nur nach fachlicher Freigabe der Einrichtungsleitung übernehmen.
- Keine Bewohnerdaten, Namen, Fallbeispiele aus realen Einsätzen oder internen Dokumente eingeben.
- Browserspracherkennung kann, je nach Browser, über externe Dienste laufen. Dies vor dem Einsatz kommunizieren.
- Keine automatische Aussprachebewertung, kein freies KI-Übersetzen und kein geschütztes Redaktionsportal vorhanden.
