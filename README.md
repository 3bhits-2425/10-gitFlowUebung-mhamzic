# 10-gitFlowUebung-mhamzic

Uebungen von ChatGPT

1. Neues Repository auf GitHub erstellen
    - 10-gitFlowUebungen
    
2. Repository klonen
    - git clone <HTTPS>
  
3. Datei erstellen (gitUebung.txt) und zum Repository hinzufügen
    - nano gitUebung -> dann neue Zeilen erstellen
    - git add, git init und git commit machen
    - mit git push auf Repository hinzufügen

4. Änderungen committen
    - git commit
    
5. Änderungen pushen
    - git push 

6. Datei umbenennen
   - mit git mv gitUebungen.txt aufgaben.txt umbenennen
   - dann commiten
   - dann git pull, pullen
   - dann die neue txt Datei mit git push, pushen
  
7. Dateiunterschiede mit git diff überprüfen
   - In der .txt Datei neue Zeile erstellen und nicht commiten
   - mit git diff kann man den Dateiunterschied sehen

8. In vorherige Version der .txt gehen
      - jetzige Version commiten
      - mit git checkout <HASH-WERT> in alte version wechseln
      - bei mir: git checkout 02d7e8c
      - mit git checkout main -> zurück im main

9. Commit-Nachricht ändern
    - git commit --amend -m "Neue Nachricht eingeben"

10. Commit-Historie in einer Zeile anzeigen
    - mit git commit --oneline
