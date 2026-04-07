---
title: "Eksam 2024"
weight: 10
---

# Gümnaasiumi lõpueksam 2024

## Ülesanded ja lahendused

---

### Ülesanne 1 (5p)
**Leia funktsiooni $f(x) = 24x - 2x^3 + 9x^2 + 3$ kasvamisvahemik.**

<details>
<summary>Lahendus</summary>

**Samm 1:** Leia tuletis:
$$f'(x) = 24 - 6x^2 + 18x$$

**Samm 2:** Leia kriitilised punktid ($f'(x) = 0$):
$$24 - 6x^2 + 18x = 0$$
$$-6x^2 + 18x + 24 = 0 \quad |:(-6)$$
$$x^2 - 3x - 4 = 0$$
$$(x-4)(x+1) = 0$$
$$x_1 = -1, \quad x_2 = 4$$

**Samm 3:** Uuri tuletise märki:

| Vahemik | $f'(x)$ märk | $f(x)$ käitumine |
|---------|-------------|-----------------|
| $x < -1$ | $-$ | kahanev |
| $-1 < x < 4$ | $+$ | **kasvav** |
| $x > 4$ | $-$ | kahanev |

**Vastus:** $f(x)$ kasvab vahemikus $\boxed{(-1;\ 4)}$.

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Tuletise leidmine | 1p |
| $f'(x) = 0$ lahendamine | 1p |
| Mõlemad kriitilised punktid | 1p |
| Märgiuuring | 1p |
| Õige kasvamisvahemik | 1p |

</details>

---

### Ülesanne 2 (5p)
**Lahenda $\cos 2x - 2\cos x = 2\cos^2 x$ vahemikus $[-\pi;\ 0]$.**

<details>
<summary>Lahendus</summary>

**Samm 1:** Kasuta topeltnurga valemit $\cos 2x = 2\cos^2 x - 1$:
$$2\cos^2 x - 1 - 2\cos x = 2\cos^2 x$$

**Samm 2:** Lihtsusta:
$$-1 - 2\cos x = 0$$
$$2\cos x = -1$$
$$\cos x = -\frac{1}{2}$$

**Samm 3:** Leia lahendid:
$$x = \pm \frac{2\pi}{3} + 2\pi k, \quad k \in \mathbb{Z}$$

**Samm 4:** Filtreeri vahemik $[-\pi;\ 0]$:

- $x = -\frac{2\pi}{3}$ ✓ (kuulub $[-\pi; 0]$)
- $x = \frac{2\pi}{3}$ ✗ (ei kuulu)
- $x = -\frac{2\pi}{3} - 2\pi = -\frac{8\pi}{3}$ ✗ (väljaspool)

**Vastus:** $x = -\dfrac{2\pi}{3}$

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Topeltnurga valemi kasutamine | 1p |
| Lihtsustamine $\cos x = -1/2$ | 1p |
| Üldlahend | 1p |
| Vahemikku kuuluva lahendi leidmine | 1p |
| Õige vastus | 1p |

</details>

---

### Ülesanne 3 (5p)
**Urmasel on 16 patareid, tõenäosus saada juhuslik patarei tühjaks osutub 0,375.**
**a) Mitu tühja patareid on?**
**b) Leia tõenäosus, et 2 juhuslikult võetud patarei osutuvad mõlemad tühjaks.**
**c) Leia tõenäosus, et 4 juhuslikult võetud patarei hulgast on vähemalt 1 tühi.**

<details>
<summary>Lahendus</summary>

**a) Tühjade arv:**
$$n_{t\ddot{u}hi} = 16 \times 0{,}375 = 6$$

Tühje patareisid on **6**, terveid on $16 - 6 = 10$.

---

**b) P(2-st mõlemad tühjad):**

$$P = \frac{\binom{6}{2}}{\binom{16}{2}} = \frac{\frac{6!}{2! \cdot 4!}}{\frac{16!}{2! \cdot 14!}} = \frac{15}{120} = \frac{1}{8} = 0{,}125$$

---

**c) P(4-st vähemalt 1 tühi):**

Kasutame täiendtõenäosust:
$$P(\text{vähemalt 1 tühi}) = 1 - P(\text{kõik 4 terved})$$

$$P(\text{kõik terved}) = \frac{\binom{10}{4}}{\binom{16}{4}} = \frac{210}{1820} = \frac{3}{26}$$

$$P(\text{vähemalt 1 tühi}) = 1 - \frac{3}{26} = \frac{23}{26} \approx 0{,}885$$

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Tühjade arv = 6 | 1p |
| b) | Kombinatsioonide kasutamine | 1p |
| b) | Õige vastus 1/8 | 1p |
| c) | Täiendtõenäosuse idee | 1p |
| c) | Õige lõppvastus | 1p |

</details>

---

### Ülesanne 4 (5p)
**Lahenda $\sqrt{x+6} = 2 + \sqrt{2x-5}$.**

<details>
<summary>Lahendus</summary>

**Samm 1:** Määramise tingimused:
$$x + 6 \geq 0 \Rightarrow x \geq -6$$
$$2x - 5 \geq 0 \Rightarrow x \geq 2{,}5$$

Seega $x \geq 2{,}5$ ja parem pool $\geq 2 > 0$, mistõttu ka vasak pool on positiivne. ✓

**Samm 2:** Ruudu võtmine:
$$(\sqrt{x+6})^2 = (2 + \sqrt{2x-5})^2$$
$$x + 6 = 4 + 4\sqrt{2x-5} + (2x-5)$$
$$x + 6 = 2x - 1 + 4\sqrt{2x-5}$$
$$7 - x = 4\sqrt{2x-5}$$

**Samm 3:** Tingimus $7 - x \geq 0 \Rightarrow x \leq 7$.

**Samm 4:** Ruudu võtmine uuesti:
$$(7-x)^2 = 16(2x-5)$$
$$49 - 14x + x^2 = 32x - 80$$
$$x^2 - 46x + 129 = 0$$

**Samm 5:** Diskriminant:
$$D = 46^2 - 4 \times 129 = 2116 - 516 = 1600$$
$$\sqrt{D} = 40$$
$$x = \frac{46 \pm 40}{2}$$
$$x_1 = 43, \quad x_2 = 3$$

**Samm 6:** Kontroll tingimuste vastu ($2{,}5 \leq x \leq 7$):
- $x = 43$: ei kuulu ✗
- $x = 3$: kuulub ✓

**Kontroll:** $\sqrt{3+6} = 3$ ja $2 + \sqrt{6-5} = 2 + 1 = 3$ ✓

**Vastus:** $x = 3$

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Määramise tingimused | 0,5p |
| Ruudu võtmine, lihtsustamine | 1p |
| Ruutvõrrand $x^2 - 46x + 129 = 0$ | 1p |
| Mõlemad lahendid | 1p |
| Kontrollimine ja vale lahendi välistamine | 1,5p |

</details>

---

### Ülesanne 5 (10p)
**Kolmnurgas ABC: $AB = 8\ \text{cm}$, $AC = 6\ \text{cm}$, $BC = 4\ \text{cm}$.**
**Punkt D asub lõigul AB nii, et $CD = 5\ \text{cm}$.**
**a) Leia $AD$ ja $BD$.**
**b) Leia punkt B kaugus sirgelt AC.**

<details>
<summary>Lahendus</summary>

**a) AD ja BD leidmine:**

Olgu $AD = x$, siis $BD = 8 - x$.

Kolmnurgast ACD (cosinus-teoreem):
$$CD^2 = AC^2 + AD^2 - 2 \cdot AC \cdot AD \cdot \cos A$$

Esmalt leiame $\cos A$ kolmnurgast ABC:
$$BC^2 = AB^2 + AC^2 - 2 \cdot AB \cdot AC \cdot \cos A$$
$$16 = 64 + 36 - 2 \cdot 8 \cdot 6 \cdot \cos A$$
$$16 = 100 - 96\cos A$$
$$\cos A = \frac{84}{96} = \frac{7}{8}$$

Nüüd kolmnurgas ACD:
$$25 = 36 + x^2 - 2 \cdot 6 \cdot x \cdot \frac{7}{8}$$
$$25 = 36 + x^2 - \frac{21x}{2}$$
$$x^2 - \frac{21x}{2} + 11 = 0 \quad |\times 2$$
$$2x^2 - 21x + 22 = 0$$

$$D = 441 - 176 = 265, \quad \sqrt{D} \approx 16{,}28$$
$$x = \frac{21 \pm 16{,}28}{4}$$
$$x_1 \approx 9{,}32 \quad (\text{ei sobi, kuna } x \leq 8)$$
$$x_2 \approx 1{,}18\ \text{cm}$$

Seega $AD \approx 1{,}18\ \text{cm}$ ja $BD = 8 - 1{,}18 \approx 6{,}82\ \text{cm}$.

---

**b) Kaugus B-st sirgele AC:**

Kolmnurga ABC pindala Heroni valemiga:
$$s = \frac{8+6+4}{2} = 9$$
$$S = \sqrt{9 \cdot (9-8) \cdot (9-6) \cdot (9-4)} = \sqrt{9 \cdot 1 \cdot 3 \cdot 5} = \sqrt{135} = 3\sqrt{15}$$

Pindala valemist $S = \frac{1}{2} \cdot AC \cdot h_B$:
$$3\sqrt{15} = \frac{1}{2} \cdot 6 \cdot h_B$$
$$h_B = \sqrt{15} \approx 3{,}87\ \text{cm}$$

**Vastus:** $B$ kaugus sirgelt $AC$ on $h_B = \sqrt{15} \approx 3{,}87\ \text{cm}$.

**Hindamisskeem:**

| Osa | Samm | Punktid |
|-----|------|---------|
| a) | $\cos A$ leidmine | 2p |
| a) | Ruutvõrrandi koostamine | 2p |
| a) | $AD$ ja $BD$ | 2p |
| b) | Pindala arvutus | 2p |
| b) | Kauguse leidmine | 2p |

</details>

---

### Ülesanne 6 (10p)
**Lihtsusta:**
$$\frac{1 - m^{-1/2}}{1 + m^{1/2}} \cdot \frac{m^{1/2} + m^{-1/2}}{m - 1}$$
**ja arvuta väärtus, kui $m = \log_6 180 - \log_6(3a) - \frac{1}{2}\log_6\!\left(\frac{25}{9a^2}\right)$.**

<details>
<summary>Lahendus</summary>

**Osa 1: Lihtsustamine**

Kirjutame astmed murdjõuna:
$$\frac{1 - \frac{1}{\sqrt{m}}}{1 + \sqrt{m}} \cdot \frac{\sqrt{m} + \frac{1}{\sqrt{m}}}{m - 1}$$

Esimene murd — korrutame $\sqrt{m}$-ga:
$$\frac{\sqrt{m} - 1}{\sqrt{m}(1 + \sqrt{m})}$$

Teine murd — korrutame $\sqrt{m}$-ga:
$$\frac{m + 1}{\sqrt{m}(m-1)} = \frac{m+1}{\sqrt{m}(\sqrt{m}-1)(\sqrt{m}+1)}$$

Korrutis:
$$\frac{\sqrt{m}-1}{\sqrt{m}(\sqrt{m}+1)} \cdot \frac{m+1}{\sqrt{m}(\sqrt{m}-1)(\sqrt{m}+1)}$$

$$= \frac{m+1}{m(\sqrt{m}+1)^2}$$

---

**Osa 2: m väärtuse leidmine**

$$m = \log_6 180 - \log_6(3a) - \frac{1}{2}\log_6\!\left(\frac{25}{9a^2}\right)$$

$$= \log_6 \frac{180}{3a} - \log_6 \sqrt{\frac{25}{9a^2}}$$

$$= \log_6 \frac{60}{a} - \log_6 \frac{5}{3a}$$

$$= \log_6 \left(\frac{60}{a} \cdot \frac{3a}{5}\right)$$

$$= \log_6 36 = \log_6 6^2 = 2$$

Seega $m = 2$. Asendame:

$$\frac{2+1}{2(\sqrt{2}+1)^2} = \frac{3}{2(3+2\sqrt{2})} = \frac{3}{6+4\sqrt{2}}$$

Ratsionaliseerimine:
$$= \frac{3(6-4\sqrt{2})}{(6+4\sqrt{2})(6-4\sqrt{2})} = \frac{18-12\sqrt{2}}{36-32} = \frac{18-12\sqrt{2}}{4} = \frac{9-6\sqrt{2}}{2}$$

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Murruavaldiste korrastamine | 2p |
| Lihtsustamine | 2p |
| Logaritmide omaduste kasutamine | 2p |
| $m = 2$ leidmine | 2p |
| Lõppväärtus | 2p |

</details>

---

### Ülesanne 7 (10p)
**Kolmnurgas ABC: $AC = 4\ \text{cm}$, $CB = 10\ \text{cm}$.**
**Mediaan $AM$ (M on BC keskpunkt) moodustab AC-ga $45°$ nurga.**
**Leia kolmnurga ümbermõõt ja pindala.**

<details>
<summary>Lahendus</summary>

**Mediaan AM:** M on BC keskpunkt, $CM = \frac{10}{2} = 5\ \text{cm}$.

**Samm 1:** Kolmnurgas ACM (nurk C, nurk MAC = 45°):

Sinuse teoreem kolmnurgas ACM:
$$\frac{CM}{\sin \angle CAM} = \frac{AC}{\sin \angle AMC}$$

Nurk $\angle AMC = 180° - \angle AMB$. Olgu $\angle ACM = \gamma$.

Kasutame kolmnurka ACM:
$$\angle CAM = 45°, \quad AC = 4, \quad CM = 5$$

Sinuse teoreem:
$$\frac{CM}{\sin 45°} = \frac{AC}{\sin \angle AMC}$$

$$\frac{5}{\frac{\sqrt{2}}{2}} = \frac{4}{\sin \angle AMC}$$

$$\sin \angle AMC = \frac{4 \cdot \frac{\sqrt{2}}{2}}{5} = \frac{2\sqrt{2}}{5}$$

**Samm 2:** Nurk $\angle ACM$:
$$\angle ACM = 180° - 45° - \angle AMC$$

$$\cos \angle AMC = \sqrt{1 - \frac{8}{25}} = \sqrt{\frac{17}{25}} = \frac{\sqrt{17}}{5}$$

**Samm 3:** Mediaan $AM$ pikkus:
$$AM^2 = AC^2 + CM^2 - 2 \cdot AC \cdot CM \cdot \cos \angle ACM$$

Leiame $\angle ACM$ cosinus-teoreemiga:
$$AM^2 = 4^2 + 5^2 - 2 \cdot 4 \cdot 5 \cdot \cos\angle ACM$$

Teise vaatenurgaga: kolmnurgas ACM sinusega:
$$\frac{AM}{\sin \gamma} = \frac{5}{\sin 45°} = 5\sqrt{2}$$

$$AM = 5\sqrt{2} \sin\gamma$$

Ning $\angle A + \angle AMC + \gamma = 180°$, seega $\gamma = 180° - 45° - \angle AMC$.

Leiame $AM$ otse:
$$AM^2 = AC^2 + CM^2 - 2 \cdot AC \cdot CM \cdot \cos\gamma$$

Mediaani valemist:
$$AM^2 = \frac{2AB^2 + 2AC^2 - BC^2}{4}$$

Olgu $AB = c$. Siis:
$$AM^2 = \frac{2c^2 + 2 \cdot 16 - 100}{4} = \frac{2c^2 - 68}{4}$$

Cosinus-teoreemist kolmnurgas ACM:
$$AM^2 = AC^2 + CM^2 - 2 \cdot AC \cdot CM \cdot \cos C = 16 + 25 - 40\cos C$$

Samuti kolmnurgast ABC: $\cos C = \frac{AC^2 + BC^2 - AB^2}{2 \cdot AC \cdot BC} = \frac{16+100-c^2}{80}$

Nurga $\angle CAM = 45°$: sinuse teoreem kolmnurgas ACM:
$$\frac{\sin 45°}{CM} = \frac{\sin C}{AM}$$

$$\sin C = \frac{AM \cdot \sin 45°}{5} = \frac{AM\sqrt{2}}{10}$$

Kombineerides:
$$AM^2 = 41 - 40 \cdot \frac{16+100-c^2}{80} = 41 - \frac{116 - c^2}{2} = \frac{82 - 116 + c^2}{2} = \frac{c^2 - 34}{2}$$

Koos $AM^2 = \frac{2c^2-68}{4} = \frac{c^2-34}{2}$ ✓ (konsistentne).

Ning $AM^2 \sin^2 C = AM^2 \cdot \frac{AM^2 \cdot 2}{100}$... Kasutame numbrilist lähenemist:

$\angle CAM = 45°$, kolmnurgas ACM:

$$\tan 45° = \frac{h}{AD}$$, kus $h$ on kõrgus C-st AM-le... 

**Lihtsam meetod** — pindala kaudu:
$$S_{ACM} = \frac{1}{2} \cdot AC \cdot AM \cdot \sin 45° = \frac{1}{2} \cdot 4 \cdot AM \cdot \frac{\sqrt{2}}{2} = AM\sqrt{2}$$

Samuti: $S_{ACM} = \frac{1}{2} \cdot AC \cdot CM \cdot \sin C = \frac{1}{2} \cdot 4 \cdot 5 \cdot \sin C = 10\sin C$

Seega $AM\sqrt{2} = 10\sin C$ → $AM = \frac{10\sin C}{\sqrt{2}} = 5\sqrt{2}\sin C$.

Cosinus-teoreemist: $AM^2 = 16 + 25 - 40\cos C = 41 - 40\cos C$

$AM = 5\sqrt{2}\sin C$ → $AM^2 = 50\sin^2 C = 50(1-\cos^2 C)$

$$50(1-\cos^2 C) = 41 - 40\cos C$$
$$50 - 50\cos^2 C = 41 - 40\cos C$$
$$50\cos^2 C - 40\cos C - 9 = 0$$

$$\cos C = \frac{40 \pm \sqrt{1600 + 1800}}{100} = \frac{40 \pm \sqrt{3400}}{100} = \frac{40 \pm 10\sqrt{34}}{100} = \frac{4 \pm \sqrt{34}}{10}$$

$\sqrt{34} \approx 5{,}83$:
- $\cos C = \frac{4 + 5{,}83}{10} \approx 0{,}983$ → $C \approx 10{,}6°$
- $\cos C = \frac{4 - 5{,}83}{10} \approx -0{,}183$ → $C \approx 100{,}5°$

$AB^2 = AC^2 + BC^2 - 2 \cdot AC \cdot BC \cdot \cos C = 16 + 100 - 80\cos C$

- Variant 1: $AB^2 = 116 - 80 \times 0{,}983 \approx 37{,}4$ → $AB \approx 6{,}12\ \text{cm}$
- Variant 2: $AB^2 = 116 - 80 \times (-0{,}183) \approx 130{,}6$ → $AB \approx 11{,}43\ \text{cm}$

**Pindala:**
- Variant 1: $S = \frac{1}{2} \cdot 4 \cdot 10 \cdot \sin 10{,}6° \approx 3{,}68\ \text{cm}^2$
- Variant 2: $S = \frac{1}{2} \cdot 4 \cdot 10 \cdot \sin 100{,}5° \approx 19{,}7\ \text{cm}^2$

**Ümbermõõt:**
- Variant 1: $P \approx 4 + 10 + 6{,}12 = 20{,}12\ \text{cm}$
- Variant 2: $P \approx 4 + 10 + 11{,}43 = 25{,}43\ \text{cm}$

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Mediaani ja nurga seose kasutamine | 2p |
| Cosinus-võrrandi koostamine | 3p |
| Mõlema variandi käsitlemine | 2p |
| Pindala | 2p |
| Ümbermõõt | 1p |

</details>

---

*Eksam 2024 — gümnaasiumi lõpueksam matemaatikas*
