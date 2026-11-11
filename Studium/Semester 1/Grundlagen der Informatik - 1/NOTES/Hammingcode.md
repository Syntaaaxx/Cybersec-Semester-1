
## Strategie 1
Fehlerkorrekturcodes (Vorwärtsfehlerkorrektur, Forward Error Connection)

## Strategie 2
Fehlererkennungscodes


## Hammingabstand

Hamming distance is a measure of dissimilarity between two data objects of equal length. It is defined as the number of positions at which the corresponding elements in the two objects are different. If they have the same length, the objects being compared can be binary strings, character strings or vectors of categorical values.


Der Hammingabstand eines Binär-Codes entspricht dem Minumum

## Hamminggewicht

XOR mit 0
1 zählen

### Parity Check

Übung

1011 0101 -> 1
1000 0101 -> 1
1001 0011 -> 0 


### Coderate

$$
R = n/m
$$

### Wie viele k Checkbits sind notwendig?

Hat ein Code den Hammingabstand d+1, so können alle Fehler erkannt werden, die höchstens d Bits betreffen.

Hat ein Code den Hammingabstand 2d + 1, so können alle Fehler behoeben werden, die höchstens d bits betreffen.


<u>Übung</u>

Die gültigen Codewörter sind: 000, 011, 101, 110

-> 101 wurde zu 111 geändert

Kann der Fehler erkannt und bereinigt werden?


Hamming Abstand = 2 (weil Codewörter)

> [!success] Ergebnis
> Fehler kann erkannt aber nicht bereinigt werden


---

Übungsblatt 2 | Aufgabe 6


![[Pasted image 20261027142622.png]]

0111 -> 2 
1101 -> 4
1000 -> 2 

### Fehlercodes wichtige Fragen

- Wie viele k Checkbits sind notwendig, um Fehler erkennen oder beheben zu können?
- Wo sollen die Checkbits im Codewort positioniert sein?
- Aus welchen Datenbits sollen die Checkbits berechnet werden?


<u>Hamming codes (7,4)</u>

1001011 -> 8
1001100 -> 9 



Übung

Zu überprüfende Nahcricht

0111110

| 7   | 6   | 5   | 4                              | 3   | 2                              | 1                              | Dezimal |
| --- | --- | --- | ------------------------------ | --- | ------------------------------ | ------------------------------ | ------- |
| 0   | 1   | 1   | <font color="#f79646">1</font> | 1   | <font color="#f79646">1</font> | <font color="#f79646">0</font> | 7       |




![[Übungsblatt_3.pdf]]



### Aufgabe 1

![[Drawing 2026-10-27 16.00.58.excalidraw]]
