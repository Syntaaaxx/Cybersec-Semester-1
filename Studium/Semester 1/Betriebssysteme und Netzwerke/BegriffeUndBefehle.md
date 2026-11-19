## Begriffe und Befehle für Betriebssysteme

In dieser Datei sammeln wir alles, was besprochen wurde und entweder nicht oder nicht so "knackig" im Skript steht.



#### Begriffe und Namen

* Hardware, BIOS, Software; Systemsoftware, Anwendungssoftware; Programme, Daten
* Bedeutung von Schnittstellen
* Kommando, Argument, Option
* relative und absolute Pfade
* Standard-Ordnerstruktur in Linux, also Verzeichnisse in /
  * /etc Konfigurationsdateien
  * /home Homebereiche für die Benutzer, also persönliche Verzeichnisse
  * /usr  vorinstalliertes für Benutzer verfügbares Betriebssystem
    * /usr/bin   (und auch /bin):   vorinstallierte ausführbare Programme
  * /tmp  temporäre Dateien, wird beim nächsten Boot gelöscht
* nicht verwechseln: die Verzeichnisse Root (/)  und Home (~  also z.B. /home/hans) und "Slash-Home" (/home)


#### Befehle

| Linux                                 | Optionen                 | Beschreibung                                                                                                                                                                                          | Windows              |
| ------------------------------------- | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| ls                                    |                          | liste den Inhalt des aktuellen Ordners auf<br />mit *Pfad* als Argument: listet den Inhalt von *Pfad* auf. **noch nicht besprochen, kommt erst**                                                      | dir, ls              |
|                                       | -a                       | alle Dateien **noch nicht besprochen, kommt erst**                                                                                                                                                    |                      |
|                                       | -l                       | lange, detailreiche Liste **noch nicht besprochen, kommt erst**                                                                                                                                       |                      |
|                                       | -r                       | rekursiv **noch nicht besprochen, kommt erst**                                                                                                                                                        | /S                   |
| cd  *Pfad*                            |                          | "change dir", also wechsle ins Verzeichnis *Pfad*<br />Bemerkung: braucht normalerweise ein Argument: *wohin* soll ich wechseln<br />Ohne Argument: Default (Standard): ~   also das Home-Verzeichnis | cd                   |
| pwd                                   |                          | "print working directory", also in welchem Verzeichnis stehe ich aktuell                                                                                                                              |                      |
| touch *Name*                          |                          | "touch" legt eine leere Datei mit dem Namen *Name* an, falls sie nicht existiert und<br />setzt den Zeitpunkt der letzten Änderung auf "jetzt" **noch nicht besprochen, kommt erst**                  | echo *Text* > *Name* |
| mkdir *Name*                          |                          | "Make Directory" Erstellt im Aktuellen Verzeichnis einen Ordner mit eigens eingegebenem Namen.                                                                                                        | mkdir/md             |
|                                       | -p                       | "Parent" legt eine ganze verzeichniskette an z.B. durch Eingabe von  "mkdir -p Bla/Blub/blaeh".                                                                                                       |                      |
| rmdir *Name*                          |                          | "Remove Directory" Entfernt ein Leeres Verzeichnis.                                                                                                                                                   | rmdir/rd             |
| rm *Datei* oder *Ordner*              |                          | "Remove", Entfernt Dateien oder Verzeichnisse.                                                                                                                                                        | del/erase            |
|                                       | -r                       | "Rekursiv" entferne diesen Ordner und allen Inhalt (Dateien und Verzeichnisse).                                                                                                                       | /S                   |
|                                       | -f                       | "Force" Erzwingt das löschen von Dateien ohne nach Bestätigung zu Fragen und Ignoriert nicht vorhandene Dateien.                                                                                      |                      |
| cat *Datei*                           |                          | Lest eine Textdatei aus.                                                                                                                                                                              |                      |
|                                       | ">" *Datei*              | Gibt die 1. Datei in die 2. aus. (Kopiert also quasi den Inhalt der 1. in die 2.)                                                                                                                     |                      |
| less *Datei*                          |                          | less lest auch eine Datei aber als "offene Datei". Man kann mit den Pfeil tasten hoch und herunter fahren und nach Keywords suchen. ("Q" Drücken zum Verlassen).                                      |                      |
| mv    *Dateiname*   *Ziel*            |                          | "Move" , Bewege Datei xy von hier zum Ziel. Kann auch als Rename benutzt werden wenn das Argument des Ziels Leergelassen wird.                                                                        | move                 |
| cp     *Dateiname*   *Ziel*           |                          | "Copy",  Kopiere Datei xy von hier zum Ziel.                                                                                                                                                          | copy                 |
|                                       | -p                       | Kopiert alle Eigenschaften der Datei mit (Zeitstempel, Rechte).                                                                                                                                       |                      |
|                                       | -i                       | Kopiert Links mit.                                                                                                                                                                                    |                      |
|                                       | -r                       | "Rekursiv" Verzeichnisbäume werden Kopiert.                                                                                                                                                           |                      |
| ln           *Original*        *Ziel* |                          | "Link" Erstellt einen Hard-Link zur Original-Datei.                                                                                                                                                   | /H                   |
|                                       | -s                       | Erstellt einen Soft-Link zur Original-Datei.                                                                                                                                                          | mklink               |
| **nicht gelernt**                     |                          | "Rename" Ändert den Namen einer Datei.                                                                                                                                                                | ren                  |
| echo *Eingabe*                        |                          | "Echo"  gibt die Eingabe wieder aus.                                                                                                                                                                  | echo                 |
|                                       | ">" *Datei*              | Überschreibt die Datei mit der Eingabe.                                                                                                                                                               |                      |
|                                       | ">>" *Datei*             | Schreibt die Eingabe in die Datei.                                                                                                                                                                    |                      |
| head *Datei*                          |                          | Gibt die ersten (standardmäßig) 10 Zeilen einer Datei aus.                                                                                                                                            |                      |
|                                       | -n *Zahl*                | Gibt so viele Zeilen wie in der "Zahl" stehen aus. Bei negativer Zahl werden so viele Zeilen am Ende weggelassen.                                                                                     |                      |
|                                       | *<u>ohne Datei</u>*      | Gibt die Standard Eingabe (Tastatur) aus.                                                                                                                                                             |                      |
|                                       | ">" *Datei*              | Gibt die ersten (standartmäßig) 10 Zeilen der 1. Datei in die 2. aus.                                                                                                                                 |                      |
| ~~*Datei*~~                           | "<" *Datei*              | Gibt den Inhalt der Datei als Standard Eingabe an das Kommando.                                                                                                                                       |                      |
| tail *Datei*                          |                          | Gibt die letzten (standardmäßig) 10 Zeilen einer Datei aus.                                                                                                                                           |                      |
|                                       | -n *Zahl*                | Gibt so viele Zeilen wie in der "Zahl" stehen von hinten aus.                                                                                                                                         |                      |
| grep        *"Eingabe"*    *Datei*    |                          | Sucht in der Datei nach der Eingabe.                                                                                                                                                                  |                      |
| cut                                   |                          |                                                                                                                                                                                                       |                      |
|                                       | -c         *Zahl(-Zahl)* | Gib die Zeichen jeder Zeile aus, welche zwischen den Zahlen liegen.                                                                                                                                   |                      |
|                                       | -f       *Zahl(-Zahl)*   | Gibt die Datei in Spalten aus, bei Tabellarischen Dateien. Normale Zeilen werden vollständig ausgegeben.                                                                                              |                      |
|                                       | -d *'Zeichen'*           | Benutzt das "Zeichen" als Trenner von Spalten.                                                                                                                                                        |                      |
| ssh *user*@*Ziel*                     |                          | In Zielserver einloggen                                                                                                                                                                               | ssh *user*@*Ziel*    |
| ip l                                  |                          | Zeigt Internet Anschlüsse an.                                                                                                                                                                         |                      |
| man                                   | -S 7 signal              | man manual for signals to processes                                                                                                                                                                   |                      |



