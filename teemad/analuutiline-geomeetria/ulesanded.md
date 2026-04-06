# Analüütiline geomeetria — ülesanded

## 1. tase ⭐

**1.** Punktid $A(2;\, 1)$ ja $B(5;\, 5)$. Leia vektor $\overrightarrow{AB}$ ja selle pikkus.

<details><summary>Lahendus</summary>

$$\overrightarrow{AB} = (5-2;\; 5-1) = (3;\; 4)$$

$$|\overrightarrow{AB}| = \sqrt{9 + 16} = 5$$

**Vastus:** $\overrightarrow{AB} = (3;\; 4)$, pikkus $5$.
</details>

---

**2.** Kas vektorid $\vec{a} = (2;\, -3)$ ja $\vec{b} = (-4;\, 6)$ on paralleelsed?

<details><summary>Lahendus</summary>

Kontrollime: $\vec{b} = k\vec{a}$?

$$-4 = 2k \implies k = -2, \quad 6 = -3k = -3(-2) = 6 \checkmark$$

Jah, $\vec{b} = -2\vec{a}$ — vektorid on **paralleelsed** (vastassuunalised).

**Vastus:** jah, paralleelsed.
</details>

---

**3.** Leia ringjoon $(x-3)^2 + (y+1)^2 = 25$ keskpunkt ja raadius.

<details><summary>Lahendus</summary>

Standardkujuga võrreldes: $m = 3$, $n = -1$, $r^2 = 25 \implies r = 5$.

**Vastus:** keskpunkt $(3;\; -1)$, raadius $5$.
</details>

---

## 2. tase ⭐⭐

**4.** Leia nurk vektorite $\vec{a} = (1;\, \sqrt{3})$ ja $\vec{b} = (2;\, 0)$ vahel.

<details><summary>Lahendus</summary>

$$\vec{a} \cdot \vec{b} = 1 \cdot 2 + \sqrt{3} \cdot 0 = 2$$

$$|\vec{a}| = \sqrt{1 + 3} = 2, \quad |\vec{b}| = 2$$

$$\cos\varphi = \frac{2}{2 \cdot 2} = \frac{1}{2} \implies \varphi = 60°$$

**Vastus:** nurk on $60°$.
</details>

---

**5.** Leia kaugus punktist $P(3;\, 4)$ sirgeni $4x - 3y + 1 = 0$.

<details><summary>Lahendus</summary>

$$d = \frac{|4 \cdot 3 - 3 \cdot 4 + 1|}{\sqrt{16 + 9}} = \frac{|12 - 12 + 1|}{5} = \frac{1}{5} = 0{,}2$$

**Vastus:** kaugus $0{,}2$ ühikut.
</details>

---

**6.** Tallinna Vanalinn paikneb koordinaatteljestikus nii, et Raekoja plats on $O(0;\, 0)$ ja Oleviste kirik on punktis $A(3;\, 4)$. Suurtüki torn on punktis $B(-1;\, 2)$. Leia nurk, mille moodustavad vektorid $\overrightarrow{OA}$ ja $\overrightarrow{OB}$.

<details><summary>Lahendus</summary>

$$\overrightarrow{OA} = (3;\, 4), \quad \overrightarrow{OB} = (-1;\, 2)$$

$$\overrightarrow{OA} \cdot \overrightarrow{OB} = -3 + 8 = 5$$

$$|\overrightarrow{OA}| = 5, \quad |\overrightarrow{OB}| = \sqrt{1 + 4} = \sqrt{5}$$

$$\cos\varphi = \frac{5}{5\sqrt{5}} = \frac{1}{\sqrt{5}} \approx 0{,}447$$

$$\varphi = \arccos\frac{1}{\sqrt{5}} \approx 63{,}4°$$

**Vastus:** nurk $\approx 63{,}4°$.
</details>

---

## 3. tase ⭐⭐⭐ — PE-stiilis ülesanded

**7. (8p)** *(PE-tüüpi)* Koordinaattasandil on antud kolmnurk $ABC$, kus $A(0;\, 0)$, $B(6;\, 0)$ ja $C(2;\, 4)$.

a) (2p) Leia kolmnurga küljepikkused $AB$, $BC$ ja $CA$.

b) (2p) Leia kolmnurga pindala kasutades vektorite skalaarkorrutist.

c) (2p) Kirjuta sirgete $AB$, $BC$ ja $CA$ võrrandid üldkujul.

d) (2p) Leia kõrguse $h_C$ (küljele $AB$) pikkus ja kõrgusjala koordinaadid.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)**

$$AB = |B - A| = \sqrt{36 + 0} = 6$$

$$BC = |C - B| = \sqrt{(2-6)^2 + (4-0)^2} = \sqrt{16 + 16} = 4\sqrt{2} \approx 5{,}66$$

$$CA = |A - C| = \sqrt{4 + 16} = \sqrt{20} = 2\sqrt{5} \approx 4{,}47$$

**b)** Kasutame valemit $S = \dfrac{1}{2}|\vec{AB} \times \vec{AC}|$ (ristkorrutis).

$\overrightarrow{AB} = (6;\, 0)$, $\overrightarrow{AC} = (2;\, 4)$

Tasandil: $|\vec{AB} \times \vec{AC}| = |6 \cdot 4 - 0 \cdot 2| = 24$

$$S = \frac{24}{2} = 12$$

**c)**

$AB$: $y = 0$ (x-telg)

$BC$: läbi $B(6;\, 0)$ ja $C(2;\, 4)$. Tõus $k = \dfrac{4-0}{2-6} = -1$.

$y = -(x-6) = -x + 6 \implies x + y - 6 = 0$

$CA$: läbi $C(2;\, 4)$ ja $A(0;\, 0)$. Tõus $k = 2$.

$y = 2x \implies 2x - y = 0$

**d)** Kõrgus $h_C$ on risti küljega $AB$ (mis on x-telg), seega kõrguse pikkus on $C$ y-koordinaat:

$$h_C = 4$$

Kõrgusjala koordinaadid: $H(2;\, 0)$ (punkt $AB$-l, mille x-koordinaat on sama mis $C$-l).

---

**Hindamisskeem (8p):**

| Samm | Punktid |
|------|---------|
| a) Kõik kolm külge arvutatud | 2 |
| b) Ristkorrutise meetod, pindala $12$ | 2 |
| c) Kolme sirge võrrandid | 2 |
| d) Kõrguse pikkus $4$ ja kõrgusjala koordinaadid $(2;\, 0)$ | 2 |

</details>

---

**8. (6p)** *(PE-tüüpi)* Tallinna trammliin nr 4 sõidab mööda sirgjoont. Trammipeatused on koordinaatteljestikus: Balti jaam $A(0;\, 2)$, Kesklinn $B(4;\, 5)$, Kadriorg $C(10;\, 9)$.

a) (2p) Kontrolli, kas punkt $C$ asub sirgel $AB$ (kas $A$, $B$, $C$ on kollineaarsed).

b) (2p) Leia sirgele $AB$ risti sirge, mis läbib punkti $D(2;\, 6)$.

c) (2p) Leia kaugus peatusest $D(2;\, 6)$ trammilinini $AB$.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)** Sirge $AB$ suundvektor: $\overrightarrow{AB} = (4;\, 3)$.

$\overrightarrow{AC} = (10;\, 7)$.

Kui kollineaarsed, siis $\dfrac{10}{4} = \dfrac{7}{3}$?

$2{,}5 \neq 2{,}33$ — **ei ole kollineaarsed**, $C$ ei asu sirgel $AB$.

*(Märkus: tramm peab kurvi tegema!)*

**b)** Sirge $AB$ tõus: $k_{AB} = \dfrac{3}{4}$.

Risti sirge tõus: $k_\perp = -\dfrac{4}{3}$ (tõuside korrutis $= -1$).

Sirge läbi $D(2;\, 6)$:

$$y - 6 = -\frac{4}{3}(x - 2) \implies 3y - 18 = -4x + 8 \implies 4x + 3y - 26 = 0$$

**c)** Sirge $AB$ üldkuju: suundvektor $(4;\, 3)$, normaalvektor $(3;\, -4)$.

Sirge: $3(x - 0) - 4(y - 2) = 0 \implies 3x - 4y + 8 = 0$

Kaugus $D(2;\, 6)$:

$$d = \frac{|3 \cdot 2 - 4 \cdot 6 + 8|}{\sqrt{9 + 16}} = \frac{|6 - 24 + 8|}{5} = \frac{|-10|}{5} = 2$$

**Vastus:** kaugus $2$ ühikut.

---

**Hindamisskeem (6p):**

| Samm | Punktid |
|------|---------|
| a) Kontroll koordinaadikujul, järeldus | 2 |
| b) Risti sirge võrrand $4x + 3y - 26 = 0$ | 2 |
| c) Kaugusvalem, tulemus $2$ | 2 |

</details>
