# Peer_Network# Define the content for the README file
readme_content = """
# Arbeitsregeln für Git-Nutzung

## Arbeitsbeginn

1. **Git Status und Pull:**
   - Zu Beginn jeder Arbeitssitzung führen wir `git status` und `git pull` aus, um den aktuellen Stand des Repositories zu überprüfen und sicherzustellen, dass unsere lokale Arbeitskopie auf dem neuesten Stand ist.

2. **Arbeitsstart Dokumentation:**
   - Vor Arbeitsbeginn erfolgt ein `git add .` gefolgt von einem `git commit` mit der Nachricht im Format:
     ```
     git commit -m 'Arbeitsstart: [Tag] [Datum]' -m 'Arbeitsplan:'
     ```
     - Füge eine kurze Liste von maximal 3 Aufgaben hinzu, die du an diesem Tag bearbeiten wirst. Jede Aufgabe sollte möglichst prägnant beschrieben werden (z. B. ein Satz), es sei denn, der Titel ist selbsterklärend.
     
     Beispiel:
     ```
     git commit -m 'Arbeitsstart: Montag 01.10.2024' -m 'Arbeitsplan:'
     - Aufgabe 1: Datenbank-Schema aktualisieren
     - Aufgabe 2: API-Endpoints für Nutzerverwaltung anpassen
     - Aufgabe 3: Frontend-Bug im Dashboard beheben
     ```

## Wann sollte ein Git Push erfolgen?

- **Nach jeder abgeschlossenen Aufgabe:**
  - Sobald eine der vordefinierten Aufgaben abgeschlossen ist, sollte ein `git push` durchgeführt werden, um die Änderungen in das zentrale Repository zu übernehmen.
  - Der Commit-Message-Titel kann den Status „erledigt“ tragen, und in der Beschreibung sollte so viel Text enthalten sein, dass die C-Ebene (Management) nachvollziehen kann, was passiert ist. Es ist nicht nötig, jede Einzelheit zu erklären, aber der Kontext sollte klar sein.

- **Zwischenstände:**
  - Falls du während des Arbeitstages feststellst, dass keine Aufgabe vollständig abgeschlossen wurde, führe einen „Halbzeit-Push“ durch. Beschreibe dabei das Problem und den Fortschritt. Dies kann nützlich sein, damit andere Teammitglieder, die den Commit sehen, eventuell helfen können.

## Warum diese Vorgehensweise?

- **Versionierung und Stabilität:**
  - Eine kontinuierliche Versionierung des Codes ist entscheidend, damit das Team, insbesondere Jakob, sicherstellen kann, dass wir stets eine stabile und launch-fähige Version des Codes haben.
  - **Umgebungen und Rückfalloptionen:** Es werden sichere Umgebungen benötigt, um bei Problemen auf stabile Versionen zurückgreifen zu können.
  - **Zugänglichkeit für das gesamte Team:** Durch regelmäßiges Pushen in das zentrale Repository bleibt der Code jederzeit zugänglich, was die Zusammenarbeit im Team erleichtert.
"""
