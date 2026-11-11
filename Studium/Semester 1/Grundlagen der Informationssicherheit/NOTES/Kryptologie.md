<mark style="background:#affad1">Table of Content</mark>
1. Grundbegriffe
2. Symmetrischer Kryptografie
3. Asymmetrische Kryptografie
4. Anwendung klassischer Kryptoverfahren

---
---


## 1. Grundbegriffe

- Kryptographie
	>Daten so verändern, dass sie nur für autoriesierte Personen verständlich sind

- Kryptoanalyse
	>Kryptoanalyse ist die Wissenschaft, die sich mit der Entschlüsselung von verschlüsselten Informationen ohne Zugriff auf den Schlüssel beschäftigt

- Kryptologie(cryptology)
	>Kryptologie ist die Wissenschaft, die sich mit der Verschlüsselung und Entschlüsselung von Informationen beschäftigt

- Steganographie <-> Steganalyse

---

Gängige Begriffe

Klartext, Chifir dir Scfretext, Chiffrierung, Verschlüsselung, Dechiffrierung, Entschlüsselung, <mark style="background:#ff4d4f"><mark style="background:#ff4d4f">Schlüsselraum(Menge aller möglichen Schlüssel bei einem Verschlüsselungsve</mark>rfahren)</mark>

---
#### Angriffszenarien (nach Stärke sortiert)

- Ciphertext Only
- Probable Plaintext
- Known Plaintext
- Chosen Plaintext
- Chosen Ciphertext
- Adaptively Chosen Ciphertext
- Chosen Text
- Adaptive Chosen Text

---

Zentrale Anforderung an Kryptosysteme

-> Prinzip der starken Kryptologie (Kerckhoffs-Prinzip)

> Das Kerckhoffs’sche Prinzip besagt, dass die Sicherheit eines kryptografischen Verfahrens nicht von der Geheimhaltung des Verfahrens selbst abhängen sollte, sondern ausschließlich von der Geheimhaltung des Schlüssels


---
## 2. Symmetrische Kryptographie


Alice und Bob

<font color="#9bbb59">symmetrische Schlüssel</font>
- beide Parteien teilen sich einen geheimen Schlüssel
- Problem des sicheren Schlüsselaustauschs
- i.d.R. schnell

<font color="#f79646">asymmetrische Schlüssel</font>
- jede Partei besitzt privaten und einen öffentlichen Schlüssel
- spontane vertrauliche Kommunikation möglich
- geeignet für digitale Signaturen
- i.d.R langsam

---

##### Grundprinzipien

| Transposition                                                     | Substitution                                               |
| ----------------------------------------------------------------- | ---------------------------------------------------------- |
| Zeichen innerhalb einer Nachricht werden vertauscht (Permutation) | Jedes Element des Klartexts wird durch ein anderes ersetzt |
| Schlüssel: Größe des Blocks                                       |                                                            |


## Einfachste Verschlüsselungsverfahren

Cäsar, Vigenere


### Weitere Verfahren

One-time-pad




### Übung


Aufgabe 1:

![[Pasted image 20261105112532.png]]



a) Verschlüsselter Text
DuTsianhoesiokztcrluehuuvhangoirdarcmbl<mark style="background:#b1ffff">x</mark>heis<mark style="background:#b1ffff">x</mark>nrnw<mark style="background:#b1ffff">x</mark>


![[Drawing 2026-11-05 11.27.35.excalidraw]]


b)
![[Drawing 2026-11-05 11.47.51.excalidraw]]

c)
$$
\begin{matrix}
K&& o&& y&&c&&o&&p \\ 
r&&a&&s&&h&&ß&&a  \\
y&&n&&e&&t&&e&&ß \\
p&&a&&m&&g&&n&& x \\
t&&l&&a&&r&&S&&x
\end{matrix}
$$


Aufgabe 2:

a) Ein Schlüsselraum ist die Menge aller möglichen Schlüssel für eine Verschlüsselungsmethode

