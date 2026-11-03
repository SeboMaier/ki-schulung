# KI-Grundlagenschulung – Praxisteil im Browser

Diese Seite stellt das Übungsnotebook der Schulung als JupyterLite-Umgebung bereit.
Python läuft dabei vollständig im Browser der Teilnehmenden – ohne Installation und ohne Benutzerkonto.

**Direkt zum Notebook:** `https://<benutzername>.github.io/<repo-name>/lab/index.html?path=Fahrrad_Sharing_Regression.ipynb`

## Aufbau

- `content/` – alles, was die Teilnehmenden im Dateibrowser sehen (Notebook und Datensatz)
- `requirements.txt` – Werkzeuge zum Bauen der Seite
- `.github/workflows/deploy.yml` – baut und veröffentlicht die Seite automatisch bei jeder Änderung

## Notebook ändern

Neue Fassung von `Fahrrad_Sharing_Regression.ipynb` in den Ordner `content/` hochladen.
Nach ein bis zwei Minuten ist die Seite aktualisiert (Fortschritt unter dem Reiter *Actions*).

Hinweis: Wer das Notebook bereits geöffnet hatte, sieht weiterhin seine eigene, im Browser
gespeicherte Fassung. Für eine geänderte Fassung am besten einen neuen Dateinamen vergeben.

Die Musterlösung gehört nicht in dieses Repository, da es öffentlich ist.
