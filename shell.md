# Shell Commands 
Generalizations
Congratulations! You learned how to use the command line to view and manipulate the filesystem. What can we generalize so far?

Options modify the behavior of commands:
ls -a lists all contents of a directory, including hidden files and directories
ls -l lists all contents in long format
ls -t orders files and directories by the time they were last modified
Multiple options can be used together, like ls -alt
From the command line, you can also copy, move, and remove files and directories:
cp copies files
mv moves and renames files
rm removes files
rm -r removes directories
Wildcards are useful for selecting groups of files and directories


# Cheat Sheet für **Shell Befehle**

#### Wechseln zu anderen Ordnern / Inhalt anzeigen etc.:

- `cd [Ordnername]` change directory
- `..` Weiterleitung in übergeordnete Ordner
- `z neu` = `cd ~/neuefische` z lernt oft benutzte Ordner und bietet so Abkürzung
- `ls` Liste aller Dateien und Unterordner eines Ordners
- `ls -la` Liste mit Details `l` (=long; untereinander auflisten) und durch `a` (=all) werden auch versteckte Dateien angezeigt
- `tree` Verzeichnisbaum anzeigen
- `curl` lädt Objekt über eine URL
- `cat` zeigt den Inhalt einer Datei

#### Neu, verschieben, kopieren, löschen, öffnen:

- `mkdir` Ordner erstellen
- `mkdir [Ordner/Unterordner]` Unterordner erstellen
- `mkdir -p [Ordner/Unterordner/Unterunterordner/...]` Ordnerpfad wird erzeugt
- `touch [Dateiname]` Datei erstellen
- `mv [alter Name] [neuer Name]` Ordner/Datei umbenennen
- `mv [alter Pfad] [neuer Pfad]` Ordner/Datei verschieben
- `mv [Ordner] *` verschieben des Ordners in den aktuellen Ordner
- `cp -R [src-directory] [target-directory]` kopiert alles aus dem Quellverzeichnis in das Zielverzeichnis
- `pbcopy` speichert Eingabe in die Zwischenablage (Bsp.: `cat ~/.ssh/id_rsa.pub | pbcopy`)
- `rm` remove (geht nur bei Dateien)
- `rm -rf` Ordner löschen; `r` = rekursiv (alles in allen Unterordnern); `f` = force (nicht jede Datei einzeln bestätigen); uch **Rimraf** genannt
- `rm -rf *` löschen aller Ordner und Dateien im aktuellen Ordner
- `code .` aktueller Ordner wird bei VS Code aufgerufen
- `open [Datei]` öffnet Datei mit dem Standardprogramm eines Betriebssystems
- `open .` öffnet Ordner im Finder/Explorer
Nachrichteneingabe


Nachricht an #resources
