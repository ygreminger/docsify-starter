> # Woche 1

> # Git

## Was ist Git?

Git ist eines der modernsten Versionskontrollsysteme der Welt. Es werden sehr viele Softwareprojekten darauf gespeichert und auch darüber verwaltet. 

Es wird von Privaten sowie auch von Unternehmen genutzt und funktioniert zusammen mit den verschiedensten Plattformen. 

## Wie funktioniert Git? 

Dafür habe ich hier einige wichtige Git-Befehle notiert:

### Nutzername und E-Mail-Adresse hinzufügen

**Command:**

```
git--verion

```

Damit kann man überprüfen welche git-Version isntalliert ist.

**Command:**

```
git config --global user.name "BENUTZERNAME"

```

So kann Ihr Benutzername konfiguriert werden.

**Command:**

```
git config --global user.name

```

Um Ihren Benutzername anzuzeigen. 

**Command:**

```
git config --global user.email "EMAIL"

```

Mit diesem Command kann Ihre Email Adresse konfiguriert werden. 

**Command:**

```
git config --global user.email

```

Um Ihre Email Adresse anzuzeigen. 

### Mit Projekten arbeiten

**Command:**

```
git clone "URL"

```

Mit diesem Command wird das Repository geklont

```
git add DATEINAME
git add DATEINAME2

```

So kann man Änderungen zum Index hinzufügen

**Command:**

```
git commit -m "BESCHREIBUNG"

git commit -a

```

Mit diesem Command werden die gestagten Änderungen commitet. 

```
git push origin master 

```

So werden das lokal gespeicherte Repository auf git gespeichert 

> # Docsify 

 ## Was ist Docsify?

 Docsify generiert einem automatisch eine Dokumentationswebseite im Hintergrund, dazu werden keine statische HTML Seiten generiert. Stattdessen, werden im Hintergrund Markdown Dateien geladen, umgewandelt und als Webseite dargestellt. 
 Alles was man dazu braucht ist das index.html file in welchem man alle grundlegenden Einstellungen anpassen kann. 

  ## Struktur

Meine Struktur in Docsify sieht wie folgt aus: 

- docs
    - dok (Hier werden alle Theoriethemen dokumentiert)
        - week + (Wochenzahl)
    - prax (Hier werden alle praktischen Programmieraufträge dokumentiert)
    - img (Hier werden alle Bilder abgespeichert)

  ## Starten

Um Docsify starten zu können, muss in Visual Studio Code das Terminal geöffnet werden und folgender Befehl ausgeführt werden:

```
docker-compose up 

```
