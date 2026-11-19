![[Übungsblatt_5.pdf]]![[Übungsblatt_5.pdf]]
Worum geht es in der Logik

- untersucht Folgerungsbeziehungen in denen von Prämissen auf ein Conclusio
- Kurz: Korrektes Schlussfolgern
---
Fragen:

Was sind sprachliche Ausdrücke?
Wass sind Ausagensätze?
Wie sieht die logische Form von Aussagesätzen aus?
Mit welcher Symbolsprache können wir Aussagesätze wiedergeben?
Wie können Aussagesätze in logische Formelns übersetzt werden?
Wie kommen wir zur Bedeutung von Aussagesätzen?


Wahrheitstafel

$$
\begin{matrix}
& A && B && C && AB &&¬(AB) && ¬(AB) oder C \\
& 1 && 1 && 1 && 1 && 0 && 1 \\
& 1 && 1 && 0 && 1 && 0 && 0 \\
& 1 && 0 && 1 && 0 && 1 && 1 \\
& 1 && 0 && 0 && 0 && 1 && 1 \\

\end{matrix}
$$



<u>Übung:</u>

![[Pasted image 20261103160206.png]]


a) 

$$
\begin{matrix}
A&&B&&C&&¬A&&¬B&&¬Aund¬B \\
1 && 1 && 1 && 0&& 0 && 1\\
1 && 1 && 0 && 0&& 0 && 1\\
1 && 0 && 1 && 0 && 1 && 0\\ 
1 && 0 && 0 && 0 && 1 && 0\\ 
0 && 1 && 1 && 1 && 0 && 0\\ 
0 && 1 && 0 && 1 && 0 && 0\\
0 && 0 && 1 && 1 && 1 && 0\\
0 && 0 && 0 && 1 && 1 && 0\\
\end{matrix}

$$

---
##### Einschub
$$
A\to B \iff \neg A \lor B
$$
---

## Verknüpfungsbasis


Übung NAND

$$
\neg A \iff ? \\
A \land B \iff ? \\
A \lor B \iff ?
$$

1. A NAND A
2. <mark style="background:#d3f8b6">(A NAND B) NAND (A NAND B)</mark> || <mark style="background:#b1ffff">NAND(NAND(A,B),NAND(A,B))</mark>
3. <mark style="background:#d3f8b6">(A NAND A) NAND (B NAND B)</mark> || <mark style="background:#b1ffff">NAND(NAND(A,A),NAND(B,B)</mark>



![[Übungsblatt_5.pdf]]

Aufgabe 3:
$$
A \iff B \to (C \land D) = \neg B \lor(C \land D) \\

\\
\\
\begin{matrix} \\

A && B &&A\land B&& C \\ 
0 && 0 && 0 && 0 \\
1 && 0 && 0 && 0 \\
0 && 1 && 0 && 0 \\
1 && 1 && 1 && 1
\end{matrix}
$$

---

### Disjunktive Normalform und Konjunktive Normalform


<u>Übung</u>

| A   | B   | C   | F   |
| --- | --- | --- | --- |
| 0   | 0   | 0   | 1   |
| 0   | 0   | 1   | 0   |
| 0   | 1   | 0   | 0   |
| 0   | 1   | 1   | 0   |
| 1   | 0   | 0   | 1   |
| 1   | 0   | 1   | 1   |
| 1   | 1   | 0   | 0   |
| 1   | 1   | 1   | 0   |



DNF

$$
(\neg A \land\neg B\land\neg C) \dots\\
——————————————
$$


$$
(A \iff B) \longmapsto \neg C
\\
KNF: \\
$$
![[Pasted image 20261110161427.png]]
![[Übungsblatt_6.pdf]]

Aufgabe 1:

$$
\bullet  \smile     \bullet\\
$$


## Resolution

Resolutionskalkül

...

Übungsblatt 5 | Aufgabe 6



$$
f =  \{\{A,B,\neg C\},\{\neg A\},\{A,B,C\},\{A,\neg B\}\\
\\
Res(1,3) = \{A,B\} \\
Res(5,4) = \{A\} \\
Res(6,2) = \{\}
$$
