

Nachdem sich ein Nutzer authentifiziert hat, erfolgen die Zugriffskontrolle und Autorisierung

-> Dies ist Aufgabe der Rechteverwaltung und Prüfung


Auswahl einer Sicherheitsstrategie

DAC (Discretionary Access Control)
MAC (Mandatory Access Control)
RBAC (Rollenbasierte Zugrifsskontrolle)
ABAC (Attributbasierte Zugriffskontrolle)


Bell Lapadula Modell

---
Monitoring
...

---
## Übung

a)
$$
\begin{matrix}
& NT & ST & TT & DT& CC & FO & SO & TO & HO & EE \\
CC & rwx & rwx & rwx & rwx &  & rwx & rwx & rwx & rwx & rwx \\
FO & rwx & rwx& rwx & rwx&  &  & rwx & rwx& rwx & rwx \\
SO &  & rwx &  & &  & &  & &  &  \\
TO  &  &  r& rwx & & & & & & rwx\\
HO & rwx & r& & & & & & & & ‎\\
EE & & & & &rwx & rwx & rwx & rwx & rwx & \\

\end{matrix}

$$

b) CC hat Zugriff auf NT und darf HO Befehle erteilen, aber HO hat selbst vollen Zugriff auf NT.

c)
