# Projektauftrag Nr. 2: Anwendungsübung Altersvorsorge
 
## Orientierung
 
Im Projektauftrag Nr. 1 haben Sie sich mit den Möglichkeiten und Grenzen
von Jupyter Notebooks und den Python Libraries zur Datenvisualisierung
vertraut gemacht. Im Folgenden wenden Sie die gewonnenen Erkenntnisse
auf die Situation der Altersvorsorge in der Schweiz an.
 
Gegenüber dem ersten Auftrag steigen die Anforderungen in drei Punkten:
 
- Sie formulieren Ihre Hypothese selbst und beantragen deren
  Bewilligung.
- Sie planen Ihre Arbeit mit einer Disposition nach den Regeln des
  wissenschaftlichen Arbeitens.
- Sie führen mehrere Datensätze zusammen und diskutieren die Grenzen
  Ihrer Analyse.
## Absicht
 
Ich will, dass sich die Klasse in einer ersten Phase in fünf Gruppen
konstituiert, in einer zweiten Phase in den Gruppen eine
Arbeitshypothese bezüglich der Altersvorsorge formuliert, diese in einer
dritten Phase mit Mitteln der Datenanalyse überprüft und die Ergebnisse
abschliessend der Klasse präsentiert.
 
## Auftrag
 
Überprüfen Sie die bewilligte Arbeitshypothese in einem Jupyter Notebook
mit Mitteln der Datenanalyse, legen Sie Ihr Ergebnis begründet dar und
präsentieren Sie Ihre Erkenntnisse in der Woche vom 14. bis 18. Dezember
2026.
 
## Kommunikation
 
Die Kommunikation erfolgt über die von GitHub zur Verfügung gestellten
Mittel. Für Fragen an mich erstellen Sie ein ISSUE, das Sie mir
zuweisen. Im Notfall stehe ich Ihnen via Teams zur Verfügung.
 
## Besondere Anordnungen
 
- Gruppeneinteilung:
  - **ABLE**: Anass, Thanos, Lav, Artem
  - **BAKER**: Lucija, Sarah, Camilla
  - **CHARLIE**: Fatlind, Kay, Cedric, Hassan
  - **DOG**: Silvan, Ledion, Louis, Yann
  - **EASY**: Livio, Levin, Niaz
- Bewilligte Hypothesen (werden nach der Bewilligung eingetragen):
  - **ABLE**:
  - **BAKER**:
  - **CHARLIE**:
  - **DOG**:
  - **EASY**:
- Repository:
  Jede Gruppe legt für diesen Auftrag ein **neues** Repository an (z. B.
  `prwr-pa2-able`) und fügt alle Gruppenmitglieder sowie die Lehrperson
  als Collaborators hinzu.
- Termine (alle Abgaben jeweils bis **23:59 Uhr**):
  - Do, 29. Oktober 2026: Antrag Hypothese
  - Di, 3. November 2026: Rückmeldung der Lehrperson (bewilligt / zu
    überarbeiten)
  - Do, 5. November 2026: allfällige Überarbeitung des Antrags
  - Do, 12. November 2026: Disposition
  - Do, 10. Dezember 2026: Abgabe der ausgearbeiteten Beurteilung der
    Hypothese
  - 14.–18. Dezember 2026: Präsentation (genauer Termin gemäss
    Stundenplan)
- Abgaben im Detail:
  - **Antrag Hypothese**: als Issue mit dem Titel
    `Antrag Hypothese <GRUPPE>`, der Lehrperson zugewiesen. Inhalt:
    - die Hypothese in einem Satz, überprüfbar formuliert,
    - eine kurze Begründung (weshalb ist die Hypothese relevant?),
    - die vorgesehenen Datenquellen mit Links,
    - eine Skizze des Vorgehens.
    Die Hypothese wird bewilligt, wenn sie
    - durch Daten bestätigt oder widerlegt werden kann,
    - einen klaren Bezug zur Altersvorsorge in der Schweiz hat,
    - mit verfügbaren Daten überprüfbar ist und
    - im vorgegebenen Zeitrahmen bearbeitet werden kann.
    Die Lehrperson antwortet im Issue. Nach der Bewilligung schliesst
    sie das Issue und trägt die Hypothese oben ein. Wird auch der
    überarbeitete Antrag nicht bewilligt, gibt die Lehrperson eine
    Hypothese vor.
  - **Disposition**: als Datei `disposition.md` im Repository auf dem
    `dev`-Branch. Der abgabefertige Stand wird mit dem Tag `disposition`
    markiert (siehe Git-Ergänzung unten). Massgebend ist der Stand des
    Tags.
  - **Schlussabgabe**: als Pull Request von `dev` nach `main` (nur den
    Pull Request erstellen, nicht mergen). Der abgabefertige Stand wird
    zusätzlich mit dem Tag `abgabe` markiert. Massgebend ist der Stand
    des Tags.
- Inhalt der Disposition (in Anlehnung an Sachs, Sybille, und Andrea
  Hauser. *Das ABC der betriebswirtschaftlichen Forschung: Anleitung zum
  wissenschaftlichen Arbeiten.* Versus, 2002):
  - Ausgangslage und Problemstellung
  - Zielsetzung und Fragestellung
  - Hypothese (in der bewilligten Fassung)
  - Abgrenzung (was wird bewusst nicht untersucht?)
  - Vorgehen und Methode: welche Daten, welche Aufbereitungsschritte,
    welche Visualisierungen
  - Provisorische Gliederung des Notebooks
  - Zeitplan mit Verantwortlichkeiten der Gruppenmitglieder
  - Quellenverzeichnis
- Tech Stack:
  - Python mit Pandas, NumPy und Matplotlib (und weiterer erforderlicher
    Libraries)
  - Jupyter Notebooks
  - git und GitHub
- Inhaltliche Auflagen:
  - Grundlage ist die bewilligte, überprüfbare Hypothese.
  - Die Daten stammen in erster Linie aus amtlichen Quellen (z. B.
    Bundesamt für Statistik, Bundesamt für Sozialversicherungen). Andere
    Quellen sind nur zulässig, wenn sie im Antrag begründet und
    bewilligt wurden.
  - Die Quellen sind vollständig offenzulegen (Herausgeber, Titel, URL,
    Abrufdatum).
  - Mindestens zwei Datensätze werden im Notebook zusammengeführt.
  - Die Aufbereitung der Daten erfolgt innerhalb des Jupyter Notebooks
    und ist nachvollziehbar kommentiert.
  - Die Daten sind zur Unterstützung der Argumentation zu visualisieren
    (mit Titel, Achsenbeschriftung inkl. Einheiten und Quellenangabe).
  - Das Fazit hält begründet fest, ob die Hypothese bestätigt, widerlegt
    oder mit den vorliegenden Daten nicht entscheidbar ist.
  - Die Grenzen der Analyse werden diskutiert (z. B. Datenqualität,
    Datenlücken, Korrelation vs. Kausalität).
- Formelle Auflagen:
  - Die Arbeit ist mit git zu versionieren.
  - Gearbeitet wird im `dev`-Branch. Teilaufgaben werden in eigenen
    Unterbranches bearbeitet (z. B. `dev-datenimport`).
  - Unterbranches werden per Pull Request in `dev` übernommen. Jeder
    dieser Pull Requests wird vor dem Merge von einem anderen
    Gruppenmitglied geprüft (Review).
  - Die Schlussabgabe erfolgt als Pull Request von `dev` nach `main`
    (nur den Pull Request erstellen, nicht mergen).
  - Halten Sie sich bezüglich der Versionierung an die [best
    practices](https://gist.github.com/Aditi3/a7a1ddd1ecef73dab548f7955210cfff)
    für git.
- Präsentation:
  - 10 Minuten Präsentation, anschliessend 5 Minuten Fragen
  - Alle Gruppenmitglieder präsentieren einen Teil.
  - Grundlage ist das Notebook oder daraus abgeleitete Folien.
- Beurteilung:
  - Nicht eingehaltene Termine (Antrag, Disposition, Schlussabgabe)
    führen automatisch zu einer ungenügenden Beurteilung.
  - **Persönliches Engagement (ein Drittel der Note)**: gemessen an der
    Einhaltung der formellen Auflagen im git log über die gesamte
    Projektdauer, einschliesslich der Reviews. Im Fall von pair
    programming ist der Name des Partners im Text der jeweiligen Commits
    festzuhalten (`Co-authored-by:`).
  - **Teamleistung (zwei Drittel der Note)**, bestehend aus:
    - Disposition: 25 % (Vollständigkeit gemäss obiger Liste,
      Schlüssigkeit des Vorgehens, Realisierbarkeit des Zeitplans)
    - Ausgearbeitete Beurteilung der Hypothese: 50 % (Erfüllung der
      inhaltlichen Auflagen, Schlüssigkeit der Argumentation,
      Angemessenheit der Visualisierungen, Qualität der Diskussion der
      Grenzen)
    - Präsentation: 25 % (Verständlichkeit, Einhaltung der Zeit, Umgang
      mit Fragen)
### Git-Ergänzung für Projektauftrag Nr. 2
 
Grundlage bleibt das Tutorial zu Projektauftrag Nr. 1. Neu kommen zwei
Dinge hinzu.
 
**Abgabestand mit einem Tag markieren** (für Disposition und
Schlussabgabe):
 
```bash
git checkout dev
git pull
git tag disposition            # bzw. git tag abgabe
git push origin disposition    # bzw. git push origin abgabe
```
 
Auf GitHub ist der Tag danach unter *Code → Tags* sichtbar. Prüfen Sie
das. Verschieben Sie einen gesetzten Tag nach dem Termin nicht mehr.
 
**Unterbranch mit Review in `dev` übernehmen**:
 
```bash
git checkout dev
git pull
git checkout -b dev-datenimport
# arbeiten, committen ...
git push -u origin dev-datenimport
```
 
Auf GitHub dann: **Pull requests** → **New pull request** → **base:**
`dev` ← **compare:** `dev-datenimport`. Unter **Reviewers** ein anderes
Gruppenmitglied eintragen. Dieses prüft die Änderungen, kommentiert bei
Bedarf und genehmigt sie (**Approve**). Erst danach wird gemergt. Im
Unterschied zur Schlussabgabe **wird dieser Pull Request gemergt**.

# Projektauftrag Nr. 1: Einstiegsübung Datenvisualisierung

## Orientierung

Im Unterricht im Fach PrWR geht es ganz grundsätzlich um eine Einführung
in Data Science an Beispielen aus dem Wirtschaftsunterricht. Der erste
Projektauftrag dient dabei in erster Linie dazu, sich mit dem Tech-Stack
für Data Science-Arbeiten vertraut zu machen.

## Absicht

Ich will, dass Sie in Gruppen im Rahmen des von Ihnen gewählten Themas
eine Hypothese formulieren und diese gestützt auf amtlich zur Verfügung
gestellte Daten prüfen. Die Prüfung der Hypothese soll zur besseren
Verständlichkeit Ihrer Argumentation durch eine Visualisierung der von
Ihnen gewählten Daten unterstützt werden.

## Auftrag

Überprüfen Sie die von Ihnen formulierte Hypothese anhand der gefundenen
Daten und visualisieren Sie diese zur Unterstützung Ihrer Argumentation. 

## Kommunikation

Die Kommunikation erfolgt über die von GitHub zur Verfügung gestellten
Mittel. Für Fragen an mich erstellen Sie ein ISSUE, das Sie mir
zuweisen. Im Notfall stehe ich Ihnen via Teams zur Verfügung.

## Besondere Anordnungen

- Gruppeneinteilung:
  - **UNO**: Anass, Levin, Yann, Cédric
  - **DUE**: Camilla, Sarah, Lucija
  - **TRE**: Fatlind, Kay, Hassan, Niaz
  - **QUATRO**: Louis, Ledion, Silvan
  - **CINQUE**: Livio, Artem, Lav, Thanos
- Themenzuteilung:
  - **UNO**: Geographische Verteilung der Maturandenquote in der Schweiz
  - **DUE**: Geographische Verteilung der privaten PV-Anlagen
  - **TRE**: Zusammenhang zwischen Immobilienpreisen und Anbindung an
    den öffentlichen Verkehr
  - **QUATRO**: Geographische Verteilung der Maturandenquote in der Schweiz
  - **CINQUE**: Autodichte im Kanton Zürich
- Termine:
  - 10\. September 26: Abgabe Zeitplan und Analyse des Auftrags
  - 25\. September 26: Abgabe der Arbeit
- Tech Stack:
  - Python mit Pandas, NumPy und Matplotlib (und weiterer erforderlicher
    Libraries)
  - Jupyter Notebooks
  - git und GitHub
- Inhaltliche Auflagen:
  - Es ist eine überprüfbare Hypothese zu formulieren.
  - Die Quelle der verwendeten Daten ist offenzulegen.
  - Die Aufbereitung der Daten hat innerhalb des Jupyter Notebooks zu erfolgen.
  - Die Daten sind zur Unterstützung der Argumentation zu visualisieren.
- Formelle Auflagen:
  - Die Arbeit ist mit git zu versionieren.
  - Gearbeitet wird im `dev`-Branch (weitere Unterbranches sind zulässig).
  - Abgaben erfolgen als Pull Request von `dev` nach `main` (nur den
    Pull Request erstellen, nicht mergen).
  - Halten Sie sich bezüglich der Versionierung an die [best
    practices](https://gist.github.com/Aditi3/a7a1ddd1ecef73dab548f7955210cfff)
    für git.
- Beurteilung:
  Die Beurteilung erfolgt entlang der Inhaltlichen und Formellen
  Auflagen. Nicht eingehaltene Termine führen automatisch zu einer
  ungenügenden Beurteilung. Das persönliche Engagement, gemessen an der
  Einhaltung der formellen Auflagen (Versionierung) im git log, wird zu
  einem Drittel gewichtet (im Fall von pair programming ist 
  dieses im Text der jeweiligen Commits mit dem Namen des Partners
  festzuhalten). Die Teamleistung beträgt zwei Drittel der Note und
  setzt sich aus dem Rest der Kriterien zusammen. 

## Kommunikation

Die Kommunikation erfolgt über die von GitHub zur Verfügung gestellten
Mittel. Für Fragen an mich erstellen Sie ein ISSUE, das Sie mir
zuweisen. Im Notfall stehe ich Ihnen via Teams zur Verfügung.

## Git & GitHub – Tutorial für Projektauftrag Nr. 1

Dieses Tutorial ist auf genau den Workflow zugeschnitten, den der Auftrag
verlangt: Arbeiten im `dev`-Branch, Abgabe als Pull Request von `dev` nach
`main`, Fragen über Issues.

### 0. Voraussetzungen

- Git installiert (`git --version` prüft das)
- GitHub-Account
- Einmalig Namen und E-Mail setzen (erscheinen im `git log` und zählen für die Beurteilung):

```bash
git config --global user.name "Vorname Nachname"
git config --global user.email "eure@email.ch"
```

### 1. Repository aufsetzen

Eine Person der Gruppe legt auf GitHub ein neues Repository an (z. B. `prwr-projekt-uno`), dann:

```bash
git clone https://github.com/USERNAME/prwr-projekt-uno.git
cd prwr-projekt-uno
```

Danach die übrigen Gruppenmitglieder als **Collaborators** hinzufügen: auf
GitHub unter *Settings → Collaborators*. Alle anderen klonen dann dasselbe Repo.

### 2. Der `dev`-Branch

Der Auftrag verlangt: gearbeitet wird im `dev`-Branch, `main` bleibt
unangetastet bis zum Pull Request.

```bash
git checkout -b dev        # dev-Branch erstellen und hineinwechseln
git push -u origin dev     # dev auf GitHub veröffentlichen
```

Alle arbeiten ab jetzt auf `dev` (oder Unterbranches, siehe Abschnitt 6).
Prüfen, wo ihr gerade seid:

```bash
git branch                 # der aktuelle Branch ist mit * markiert
```

### 3. Der tägliche Arbeitszyklus

Das ist die Schleife, die ihr immer wieder durchlauft:

```bash
git pull                   # 1. neuste Änderungen der anderen holen
# ... jetzt am Notebook arbeiten ...
git add notebook.ipynb     # 2. Änderungen zum Commit vormerken
git commit -m "..."        # 3. Änderung mit Nachricht festhalten
git push                   # 4. auf GitHub hochladen
```

Mit `git status` seht ihr jederzeit, was geändert, aber noch nicht committet ist.

### 4. Gute Commits (das zählt für ein Drittel der Note!)

Die Beurteilung misst euer persönliches Engagement am `git log`. Deshalb:

- **Oft committen**, in kleinen, thematisch abgegrenzten Schritten – nicht einmal am Schluss alles.
- **Aussagekräftige Nachrichten** im Imperativ: `Add Datenimport aus BFS-CSV`, nicht `stuff` oder `update`.
- Bei **Pair Programming** den Namen der Partnerin/des Partners in die Commit-Nachricht schreiben:

```bash
git commit -m "Bereinige fehlende Werte in PV-Datensatz

Co-authored-by: Sarah <sarah@email.ch>"
```

### 5. Konflikte (kein Grund zur Panik)

Wenn zwei Personen dieselbe Datei ändern, meldet Git beim `pull` oder `merge`
einen Konflikt. Git markiert die betroffene Stelle in der Datei so:

```
<<<<<<< HEAD
eure Version
=======
Version der anderen Person
>>>>>>> ...
```

Ihr entscheidet, was stehen bleibt, löscht die Markierungszeilen, dann:

```bash
git add datei
git commit
```

**Tipp gegen Konflikte bei Notebooks:** `.ipynb`-Dateien konflikten schnell,
weil sie Ausgaben mitspeichern. Teilt die Arbeit möglichst so auf, dass nicht
zwei gleichzeitig dasselbe Notebook bearbeiten – oder nutzt getrennte
Notebooks und führt sie später zusammen.

### 6. Optional: Unterbranches

Erlaubt und sauber ist es, pro Teilaufgabe einen eigenen Branch von `dev` zu machen:

```bash
git checkout dev
git checkout -b dev-visualisierung
# arbeiten, committen ...
git checkout dev
git merge dev-visualisierung
```

## 7. Die Abgabe: Pull Request von `dev` nach `main`

Zum Abgabetermin (25. September):

1. Sicherstellen, dass alles auf `dev` committet und gepusht ist (`git status` sauber, `git push`).
2. Auf GitHub das Repo öffnen → Reiter **Pull requests** → **New pull request**.
3. **base:** `main` ← **compare:** `dev` wählen.
4. Titel und Beschreibung ausfüllen, **Create pull request** klicken.
5. **Nicht mergen!** Der Auftrag verlangt ausdrücklich nur das Erstellen des Pull Requests.

### 8. Kommunikation: Fragen als Issue

Fragen an die Lehrperson laufen über **Issues**:

1. Repo → Reiter **Issues** → **New issue**.
2. Frage als Titel und Text formulieren.
3. Rechts unter **Assignees** die Lehrperson zuweisen.

---

### Spickzettel

| Zweck | Befehl |
|---|---|
| Status ansehen | `git status` |
| Änderungen holen | `git pull` |
| Vormerken | `git add <datei>` |
| Festhalten | `git commit -m "Nachricht"` |
| Hochladen | `git push` |
| Branch wechseln | `git checkout <branch>` |
| Verlauf ansehen | `git log --oneline` |

