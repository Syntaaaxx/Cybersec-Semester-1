[[Erste Vorlesung]]

---
#### Übung![[GL-Übungsblatt_1.pdf]]
## Aufgabe 2
5! = 120
7! = 5040

## Aufgabe 3
01101001 = 105
00010101 = 21

01111110 = 126


## Aufgabe 4
2344 Dezimal in Hexadezimal

2344 / 16 = 146 Rest 8
146 / 16 =  9 Rest 2
9 / 16 = 0 Rest 9
-> 928

567 Dezimal in Hexadezimal 

567 / 16 = 35 Rest 7
35 / 16 = 2 Rest 3
2 / 16 = 0 Rest 2
-> 237

## Aufgabe 5

423 / 2 = 211 Rest 1
211 / 2 = 105 Rest 1
105/2 = 52 Rest 1
52/2 = 26 Rest 0
26 / 2 = 13 Rest 0
13/2 = 6 Rest 1
6/2 = 3 Rest 1
3 / 2 = 1 Rest 1
1 / 2 = 0 Rest 1

-> 110100111

111 / 2 = 55 Rest 1
...

-> 1101111

---
## <font color="#92d050">Wie stellt man negative Zahlen dar?</font>****

###### 1. Verschobener Wert (biased value)
###### 2. Vorzeichenbit
###### 3. Einerkomplementdarstellung
###### 4. Zweierkomplementdarstellung

-> Binärzahl invertieren
-> 1 dazuaddieren

0011 = 3

1100
-> 1101

0111
1001


## Übung Zweierkomplement
![[Übungsblatt 2.pdf]]

105 / 2 = 52 Rest 1
52 / 2 = 26 Rest 0
26 / 2 = 13 Rest 0
13 / 2 = 6 Rest 1
6 / 2 = 3 Rest 0
3 / 2 = 1 Rest 1
1 / 2 = 0 Rest 1


105 = 1101010

21 / 2 = 10 Rest 1
10 /2 = 5 Rest 0
5 / 2 = 2 Rest 1
2 / 2 = 1 Rest 0
1 / 2 = 0 Rest 1

21 = 10101



### Aufgabe 2

Einerkomplement zu 10101

-> 01010

---
AFFE 

$$
10*15³+15*16²+15*16¹+14*16⁰
$$

= 45054

1010111111111110
0101000000000001

---

57 - 122

111001 - 1111010

Invertieren und addieren
-> 10111110

Wieder invertieren

01000001

## Umwandlung echt gebrochene Zahlen in Binär

Rezept:

Zahl mal 2 
	Wenn Überlauf 1 anschreiben
Wiederholen


##### <u>Übung</u>
Dezimal____
0.078125
Binär____
0.000101

Dezimal____
0.01953125
Binär_____
0.00000101


---
Bei unecht gebr. Zahlen, zuerst den Teil vorm Komma /2 ...
Dann Teil hinter dem Komma x2 ...


15.3125

15/2 = 7 Rest 1
7/2 = 3 Rest 1
3/2 = 1 Rest 1
1/2 = 0 Rest 1

1111 | Erster Teil


0.3125 x 2 = 0.625  -> 0
0.625 x 2 = 1.25    -> 1
0.25 x 2 = 0.5      -> 0
0.5 x2 = 1          -> 1


=> Zahl ist ***1111.0101***

