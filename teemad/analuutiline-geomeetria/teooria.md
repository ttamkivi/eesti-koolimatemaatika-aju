# Analüütiline geomeetria

## 1. Vektorid

**Vektor** $\vec{a}$ on suunatud lõik. Iseloomustavad: suund ja pikkus (moodul).

**Koordinaatkujul:** $\vec{a} = (a_x;\; a_y)$ (tasandil) või $\vec{a} = (a_x;\; a_y;\; a_z)$ (ruumis).

**Moodul (pikkus):**

$$|\vec{a}| = \sqrt{a_x^2 + a_y^2} \quad (\text{tasandil})$$

$$|\vec{a}| = \sqrt{a_x^2 + a_y^2 + a_z^2} \quad (\text{ruumis})$$

## 2. Vektori operatsioonid

**Liitmine:** $\vec{a} + \vec{b} = (a_x + b_x;\; a_y + b_y)$

**Lahutamine:** $\vec{a} - \vec{b} = (a_x - b_x;\; a_y - b_y)$

**Skalaariga korrutamine:** $k\vec{a} = (ka_x;\; ka_y)$

**Skalaarkorrutis:**

$$\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z = |\vec{a}||\vec{b}|\cos\varphi$$

kus $\varphi$ on vektorite vaheline nurk.

**Risti tingimus:** $\vec{a} \perp \vec{b} \iff \vec{a} \cdot \vec{b} = 0$

**Paralleelsuse tingimus:** $\vec{a} \parallel \vec{b} \iff \vec{a} = k\vec{b}$ (ehk koordinaadid on proportsionaalsed).

## 3. Nurk vektorite vahel

$$\cos\varphi = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|}$$

## 4. Sirge võrrand tasandil

**Üldkuju:** $ax + by + c = 0$

**Tõusuga kuju:** $y = kx + b$, kus $k$ on tõus.

**Kaks punkti läbiv sirge:** läbi $A(x_1;\, y_1)$ ja $B(x_2;\, y_2)$:

$$\frac{x - x_1}{x_2 - x_1} = \frac{y - y_1}{y_2 - y_1}$$

**Normaalvektor ja sirge:** Sirge $ax + by + c = 0$ normaalvektor on $\vec{n} = (a;\; b)$.

## 5. Kaugus punktist sirgeni

Punkt $P(x_0;\, y_0)$, sirge $ax + by + c = 0$:

$$d = \frac{|ax_0 + by_0 + c|}{\sqrt{a^2 + b^2}}$$

## 6. Ringjoon

Ringjoon keskpunktiga $(m;\, n)$ ja raadiusega $r$:

$$(x - m)^2 + (y - n)^2 = r^2$$

**Üldkuju:** $x^2 + y^2 + Dx + Ey + F = 0$ (vajalik viia standardkujule täisruudu eraldamisega).

## 7. Tasand ruumis

Tasandi võrrand: $ax + by + cz + d = 0$

Normaalvektor: $\vec{n} = (a;\; b;\; c)$

**Kaugus punktist tasandini:**

$$d = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2 + b^2 + c^2}}$$

## 8. Vektori projektsioon

Vektori $\vec{a}$ projektsioon suunas $\vec{b}$:

$$\text{proj}_{\vec{b}}\vec{a} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2}\vec{b}$$

Skalaarne projektsioon: $\dfrac{\vec{a} \cdot \vec{b}}{|\vec{b}|}$

## 9. Lahendatud näited

**Näide 1.** Punktid $A(1;\, 2)$ ja $B(4;\, 6)$. Leia $\overrightarrow{AB}$, selle pikkus ja sirge $AB$ võrrand.

$$\overrightarrow{AB} = (4-1;\; 6-2) = (3;\; 4)$$

$$|\overrightarrow{AB}| = \sqrt{9 + 16} = 5$$

Tõus: $k = \dfrac{4}{3}$. Sirge: $y - 2 = \dfrac{4}{3}(x - 1) \implies 4x - 3y + 2 = 0$

**Näide 2.** Leia nurk vektorite $\vec{a} = (1;\, 2)$ ja $\vec{b} = (3;\, -1)$ vahel.

$$\vec{a} \cdot \vec{b} = 3 - 2 = 1, \quad |\vec{a}| = \sqrt{5}, \quad |\vec{b}| = \sqrt{10}$$

$$\cos\varphi = \frac{1}{\sqrt{5} \cdot \sqrt{10}} = \frac{1}{\sqrt{50}} = \frac{1}{5\sqrt{2}} \approx 0{,}141 \implies \varphi \approx 81{,}9°$$

**Näide 3.** Kaugus punktist $P(1;\, 1)$ sirgeni $3x + 4y - 5 = 0$.

$$d = \frac{|3 + 4 - 5|}{\sqrt{9 + 16}} = \frac{|2|}{5} = \frac{2}{5} = 0{,}4$$

## 10. Tüüpilised vead

- Skalaarkorrutis annab **arvu**, mitte vektori.
- Ringjoon: $r^2$ on valemis parem pool — $r$ on selle ruutjuur!
- Kauguse valemis: mõlemad koordinaadid asendada ning absoluutväärtus võtta.
- Vektori suund ja moodul — mitte segi ajada.
