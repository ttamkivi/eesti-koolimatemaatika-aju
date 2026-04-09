# Näidisülesanded ja Lahendused

## Ülesanded erinevate tasemete kaupa

### 1. Koolivoor: Algebra (Põhikool)

**Ülesanne 1: Lineaarvõrrandi süsteem**

Lahenda võrrandi süsteem:
$$\begin{cases}
3x + 2y = 13 \\
x - y = 2
\end{cases}$$

<details>
<summary>Lahendus</summary>

Teisest võrrandist avaldame $x$:
$$x = y + 2$$

Asendame esimesse võrrandisse:
$$3(y + 2) + 2y = 13$$
$$3y + 6 + 2y = 13$$
$$5y = 7$$
$$y = \frac{7}{5} = 1.4$$

Seega $x = 1.4 + 2 = 3.4$

**Vastus:** $x = 3.4$, $y = 1.4$

**Kontrollimine:**
- $3 \cdot 3.4 + 2 \cdot 1.4 = 10.2 + 2.8 = 13$ ✓
- $3.4 - 1.4 = 2$ ✓

</details>

---

### 2. Koolivoor: Kombinatoorika (Põhikool)

**Ülesanne 2: Kolumbusese Printsiip**

Tõesta, et mis tahes 7 erinevast arvust koosnev hulk sisaldab kahte arvu, mille vahe on jagav 6-ga.

<details>
<summary>Lahendus</summary>

Vaatleme jäägiklasse modulo 6. Kui jagame naturaalarvud 6-ga, saame jäägid 0, 1, 2, 3, 4, 5 ehk kokku 6 erinevat jäägilaadi.

Meil on 7 arvu, kuid jäägiklasse on ainult 6. Kolumbusese printsiibist järeldub, et vähemalt kahel arvul on sama jääk modulo 6.

Olgu nendeks arvudeks $a$ ja $b$, kus $a > b$. Siis:
$$a \equiv b \pmod{6}$$

See tähendab, et $a - b$ on jagav 6-ga.

**Järeldus:** Iga 7 arvu hulga seas leidub kaks arvu, mille vahe on jagav 6-ga.

</details>

---

### 3. Piirkondlik Voor: Geomeetria

**Ülesanne 3: Kolmnurga Konstruktsioon**

Antud on kolmnurga $ABC$ külg $AB = c$, kõrgus tipust $C$ poole küljele $AB$ on $h$, ja mediaan tipust $C$ poole küljele $AB$ on $m$.

Konstrueeri kolmnurk $ABC$.

<details>
<summary>Lahendus</summary>

**Konstrueerimise sammud:**

1. Joonista sirgjoone lõik $AB = c$
2. Leia $AB$ keskpunkt $M$
3. Konstrueeri punkt $C$ nii, et:
   - $C$ asub sirgel, mis on paralleelne $AB$-ga ja on $AB$-st kaugusel $h$
   - Kaugus $CM = m$ (mediaan)

**Joonisel:**
- Joonista lõik $AB$ pikkusega $c$
- Märgi punkt $M$ lõigu $AB$ keskpunkt
- Konstrueeri sirge $\ell$ mis on paralleelne $AB$-ga, kaugus $h$
- Ringjoone keskpunkt $M$ ja raadius $m$ lõikab sirget $\ell$ punktides $C_1$ ja $C_2$

**Vastus:** Kolmnurk on konstrueeritud, võimalikud on kaks lahendust ($C_1$ ja $C_2$)

</details>

---

### 4. Piirkondlik Voor: Arvuteooria (Gümnaasium)

**Ülesanne 4: Algarithmide Faktoriseerimine**

Tõesta, et kui $p$ ja $q$ on erinevad algarithmid ja $p > q$, siis $pq + 1$ ei ole kunagi algarithm.

<details>
<summary>Lahendus</summary>

Vaatleme kahte juhtumit:

**Juhtum 1:** $q = 2$

Siis $pq + 1 = 2p + 1$, kus $p$ on paaritu algarithm. Seega $2p$ on paarisarv ja $2p + 1$ on paaritu, nii et see võib potentsiaalselt olla algarithm.

Näide: $p = 3, q = 2 \Rightarrow 2 \cdot 3 + 1 = 7$, mis on algarithm.

**Juhtum 2:** $p, q$ on mõlemad paaritud algarithmid

Siis $pq$ on paaritu (paariitu korda paaritu = paaritu) ja $pq + 1$ on paarisarv. Kuna $pq > 2$, on $pq + 1 > 2$ paarisarv, seega jagub 2-ga ja pole algarithm.

**Järeldus:** Kui mõlemad algarithmid on paaritud, siis $pq + 1$ on alati kordne 2-ga ja suurem kui 2, seega mitte algarithm.

Märkus: Ülesanne nõuab rohkem tingimuseid täpsuseks.

</details>

---

### 5. Piirkondlik Voor: Algebra ja Tõestus

**Ülesanne 5: Ebavõrdsus**

Tõesta, et kõigi positiivsete reaalarvude $x, y, z$ jaoks kehtib:
$$\frac{x}{y+z} + \frac{y}{z+x} + \frac{z}{x+y} \geq \frac{3}{2}$$

<details>
<summary>Lahendus</summary>

Kasutame Cauchy-Schwartzi ebavõrdsust:

Olgu $a = \frac{x}{y+z}$, $b = \frac{y}{z+x}$, $c = \frac{z}{x+y}$

Märkame, et:
$$a + b + c = \frac{x}{y+z} + \frac{y}{z+x} + \frac{z}{x+y}$$

Kasutame asjaolu, et $x + y + z = (y+z) + (z+x) + (x+y) - (x+y+z) = (y+z) + (z+x) + (x+y) - (x+y+z)$

**Alternatiivne lähenemine - Nesbitti ebavõrdsus:**

$$\frac{x}{y+z} + \frac{y}{z+x} + \frac{z}{x+y} \geq \frac{3}{2}$$

Teisendame:
$$\frac{x}{y+z} + 1 + \frac{y}{z+x} + 1 + \frac{z}{x+y} + 1 \geq \frac{3}{2} + 3 = \frac{9}{2}$$

$$\frac{x+y+z}{y+z} + \frac{x+y+z}{z+x} + \frac{x+y+z}{x+y} \geq \frac{9}{2}$$

$$(x+y+z) \left( \frac{1}{y+z} + \frac{1}{z+x} + \frac{1}{x+y} \right) \geq \frac{9}{2}$$

Cauchy-Schwarzi ebavõrdsuse järgi:
$$\left( \frac{1}{y+z} + \frac{1}{z+x} + \frac{1}{x+y} \right)((y+z) + (z+x) + (x+y)) \geq 9$$

Seega:
$$\left( \frac{1}{y+z} + \frac{1}{z+x} + \frac{1}{x+y} \right) \cdot 2(x+y+z) \geq 9$$

$$(x+y+z) \left( \frac{1}{y+z} + \frac{1}{z+x} + \frac{1}{x+y} \right) \geq \frac{9}{2}$$

Seega tõepoolest kehtib Nesbitti ebavõrdsus.

</details>

---

### 6. Lõppvoor: Kombinatoorika

**Ülesanne 6: Graafi Värvimise Ülesanne**

Kolmnurkse võre kõik tipud on värvitud kolme värvi abil. Määra värvida 3×3 võre (9 tippu) kolme värvi abil selliselt, et ükski kahest külgnevast tipust pole sama värvi.

<details>
<summary>Lahendus</summary>

**Lahenduse meetod - Kronmatiline arv:**

Kolmnurksete võrkude kromatilinen arv on 3 (sest võre sisaldab 3-tsüklit).

**Näidisvärvus 3×3 võrele (värvid A, B, C):**

```
A - B - C
|   |   |
B - C - A
|   |   |
C - A - B
```

**Kontrollimine:** Iga horisontaal- ja vertikaaljärgnev tipp on erinev värvi. Diagonaalsed tipud ei ole külgnevad, seega nõue ei takista.

Üldisem konstruktsioon: Nummerime tipud (i, j) koordinaatidega. Värvime värvi $((i + j) \mod 3)$ järgiselt.

</details>

---

### 7. Lõppvoor: Geomeetria ja Koordinaadid

**Ülesanne 7: Ringjoone Teoreem**

Ringjoon $\omega$ läbib kolmnurga $ABC$ tippe. Kui $M$ on kaare $BC$ (mis ei sisalda $A$) keskpunkt, siis tõesta, et $AM$ poolitab nurga $\angle BAC$.

<details>
<summary>Lahendus</summary>

**Tõestus kasutades kaaride omadusi:**

Kuna $M$ on kaare $BC$ (st $A$-vastane kaar) keskpunkt, on kaarid $BM$ ja $MC$ võrdsed.

Ringjoone teoreemi järgi on sisse kirjutatud nurk poole kaar-nurkast. Seega:
- $\angle BAM$ = poole kaarest $BM$
- $\angle CAM$ = poole kaarest $CM$

Kuna kaarid $BM = CM$ (sest $M$ on kaare keskel), siis:
$$\angle BAM = \angle CAM$$

Selle tulemusena $AM$ poolitab nurga $\angle BAC$.

**Alternatiivsed tõestuse viis - Sümmeetria:**
Kaare $BC$ keskpunkt $M$ määratleb sümmeetriapunkti. Ringjoone tsentrist lähtudes näeme, et $A$ ja $M$ paiknevad seda telje suhtes sümmeetriliselt.

</details>

---

### 8. Lõppvoor: Arvuteooria ja Tõestus

**Ülesanne 8: Diophantilised Võrrandid**

Leida kõik täisarvuline lahendused võrrandile:
$$x^2 - 5y^2 = 1$$

<details>
<summary>Lahendus</summary>

See on Pelli võrrand kujul $x^2 - Dy^2 = 1$, kus $D = 5$.

**Väikseim lahendus:**
Proovime väikseid väärtusi:
- $x = 1: 1 - 5y^2 = 1 \Rightarrow y = 0$ ✓
- $x = 2: 4 - 5y^2 = 1 \Rightarrow 5y^2 = 3$ (pole lahendust)
- $x = 3: 9 - 5y^2 = 1 \Rightarrow 5y^2 = 8$ (pole lahendust)
- $x = 4: 16 - 5y^2 = 1 \Rightarrow 5y^2 = 15 \Rightarrow y^2 = 3$ (pole lahendust)
- $x = 9: 81 - 5y^2 = 1 \Rightarrow 5y^2 = 80 \Rightarrow y^2 = 16 \Rightarrow y = 4$ ✓

Seega väikseim mittriviaalne lahendus on $(x, y) = (9, 4)$.

**Kõik lahendused:**
Pelli võrrandi jaoks on kõik lahendused saadavad fundamentaalse lahenduse potentseerimisel:

Kui $(x_1, y_1) = (9, 4)$ on fundamentaalne lahendus, siis kõik lahendused on:
$$(x_n, y_n) = (9 + 4\sqrt{5})^n + (9 - 4\sqrt{5})^n \text{ jne}$$

**Vastus:** Kõik lahendused saadakse rekursiooniga:
- $(x_0, y_0) = (1, 0)$ (triviaalne)
- $(x_{n+1}, y_{n+1}) = (9x_n + 20y_n, 4x_n + 9y_n)$

Esimesed lahendused: $(1, 0)$, $(9, 4)$, $(161, 72)$, ...

</details>

---

### 9. Lõppvoor: Kombinatoorika ja Tõestus

**Ülesanne 9: Schubfachirinzip ja Ramsey Teooria**

Tõesta, et üheski 6-inimesese grupis leidub kas kolm parimust sõpra või kolm parimust vaenlist.

<details>
<summary>Lahendus</summary>

**Tõestus Ramsey Teooria abil:**

Vaatleme 6 inimest ja ühendame iga paari punase ribaga (sõbrad) või sinise ribaga (vaenlased).

Valime ühe inimese, näiteks $A$. Tal on 5 teist inimest.

Riibeide otsa: $A$-st lähtub 5 ribat. Neist 5 ribast on vähemalt 3 sama värvi (punased või sinised).

**Juhtum 1:** Kolm punast ribat
Olgu need ribad $AB$, $AC$, $AD$ (kus $B$, $C$, $D$ on sõbrad $A$-ga).
- Kui $B$ ja $C$ on sõbrad, siis $(B, C, A)$ on kolm parimust sõpra
- Kui $B$ ja $C$ on vaenlased, siis vaatame $D$:
  - Kui $B$ ja $D$ on sõbrad ja $C$ ja $D$ on sõbrad, siis on kolm parimust sõpra
  - Kui vähemalt üksi neist paaritest on vaenlased, saame kolm parimust vaenlist

**Juhtum 2:** Kolm sinist ribat
Analoogiliselt.

**Järeldus:** Igas 6-inimesese grupis leidub kas kolm parimust sõpra või kolm parimust vaenlist.

Teoreem: $R(3,3) = 6$ (Ramsey arv)

</details>

---

### 10. Lõppvoor: Algebra ja Geomeetria

**Ülesanne 10: Analüütiline Geomeetria**

Leida kõik täisarvulised lahendused võrrandi:
$$x^2 + y^2 = z^2$$

kus $\gcd(x, y, z) = 1$ (primitiivne Pythagorase kolmik).

<details>
<summary>Lahendus</summary>

**Eukleidese Parameetrisatsioon:**

Iga primitiivne Pythagorase kolmik on kujul:
$$x = m^2 - n^2, \quad y = 2mn, \quad z = m^2 + n^2$$

kus:
- $m > n > 0$
- $\gcd(m, n) = 1$
- $m$ ja $n$ ei ole mõlemad paaritud

**Tõestus:**
1. Jagage võrrand $z^2$ poolt: $(x/z)^2 + (y/z)^2 = 1$
2. See parametriseerib ühikringjoont ratsionaalsete punktide abil
3. Stereograafiline projektsioon annab parameetrisatsiooni

**Näited primitiivsetest Pythagorase kolmikutest:**
- $m = 2, n = 1$: $(3, 4, 5)$
- $m = 3, n = 2$: $(5, 12, 13)$
- $m = 4, n = 1$: $(15, 8, 17)$
- $m = 4, n = 3$: $(7, 24, 25)$

**Vastus:** Iga primitiivne Pythagorase kolmik saadakse Eukleidese parameetrisatsiooniga.

</details>

---

## Lahendamisnõuanded

1. **Enne lahendamist:** Loe ülesannet hoolikalt, märgi olulised tingimsed
2. **Joonis:** Joonista diagramm (eriti geomeetria ülesannete puhul)
3. **Sammud:** Kirjuta lahendus samm-sammult, iga samm põhjendatult
4. **Kontroll:** Kontrolli vastust, asenda tagasi ülesandesse
5. **Kirjutus:** Kasuta selget matemaatilist tähistust ja keelt

---

*Viimati uuendatud: 2026. aprill*
*Eesti Matemaatika Olümpiaadi juhatus*
