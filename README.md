## 1. Text-Editor der Wahl
Spyder
## 2. Eine Python-Bibliothek
A Chess-playing AI

In diesem Projekt wird es ermöglicht gegen eine komplexe AI Schach zu spielen.
Dies wird auf einem lokal erstellen Server ermöglicht.
## 3. Eine Fehlermeldung und Ihre Lösung
Key Error "title" - Der Key "title" konnten nicht aus den Daten herausgelesen werden.
```
base_url = "https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=pubmed&retmode=json&id="
pmids = ["31452104",
         "31437182",
         "31455877",
         "31535994"]

for pmid in pmids:
    full_url = base_url + pmid
    pmid_json_data = urllib.request.urlopen(full_url).read()
    pmid_data = json.loads(pmid_json_data)
```

Lösung: Durch die Anpassung des Codes und der Ergänzgung von str() vor den IDs können diese nun korrekt zugeordnet werden.
## 4. Was ist JupyterLab?
JupyterLab ist eine Oberfläche, die wesentlich mehr Features als das normale Notebook bietet. Außerdem ist eine bessere Übersichtlichkeits des Menüs vorhanden, advanced tools stehen zur Verfügung und mehrere Tabs gleichzeitig öffnen.

## 5. Aufgabe 2. California
Im ersten Aufgabenteil wird analysiert wie aktiv die Nutzer in der Altersgruppe zwischen 25 und 34 Jahren sind. Dies wird anhand einer Ausleihzahl an Medien von größer als 10 definiert. 
Ergebnis: Insbesondere die Nutzer in Portola sind in dieser Alterklasse besonders aktiv was die Ausleihzalen angeht. In den restlichen Bibliotheken hingegen wurde wesentlich weniger von dieser Nutzergruppe ausgeliehen. 
Im zweiten Teil werden alle Nutzer der Gruppe "Senioren" gesucht, die per Post benachrichtigt werden. Insbesondere in der Hauptbibliothek betrifft das viele Nutzer.   
