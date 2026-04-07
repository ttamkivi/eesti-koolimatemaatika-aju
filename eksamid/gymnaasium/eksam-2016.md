---
title: "Eksam 2016"
weight: 12
---

# Gümnaasiumi lõpueksam 2016

## Ülesanded ja lahendused

---

### Ülesanne 1 (5p)
**Lihtsusta:**
$$\frac{3x+2}{(6x+4)^2} \cdot (4-9x^2)$$
**ja arvuta väärtus, kui $x = 27^{1/3}$.**

<details>
<summary>Lahendus</summary>

**Samm 1:** Lihtsusta tegureid:
$$\frac{3x+2}{(6x+4)^2} \cdot (4-9x^2)$$

$(6x+4)^2 = [2(3x+2)]^2 = 4(3x+2)^2$

$4 - 9x^2 = (2-3x)(2+3x) = -(3x-2)(3x+2)$

**Samm 2:** Asenda:
$$\frac{3x+2}{4(3x+2)^2} \cdot (-(3x-2)(3x+2))$$

$$= \frac{-(3x-2)(3x+2)^2}{4(3x+2)^2}$$

$$= \frac{-(3x-2)}{4} = \frac{2-3x}{4}$$

**Samm 3:** Arvuta $x = 27^{1/3} = 3$:
$$\frac{2 - 3 \cdot 3}{4} = \frac{2-9}{4} = \frac{-7}{4} = -1{,}75$$

**Vastus:** $\dfrac{2-3x}{4}$; väärtus $x=3$: $-\dfrac{7}{4}$

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| $(6x+4)^2 = 4(3x+2)^2$ | 1p |
| $4-9x^2 = -(3x-2)(3x+2)$ | 1p |
| Taandamine | 1p |
| $x = 27^{1/3} = 3$ | 1p |
| Lõppväärtus | 1p |

</details>

---

### Ülesanne 2 (5p)
**Lahenda võrratus:**
$$1 + \frac{5-x}{x-3} \geq \frac{4x}{x-3}$$

<details>
<summary>Lahendus</summary>

**Samm 1:** $x \neq 3$ (nimetaja ei tohi olla null).

**Samm 2:** Vii ühisele nimetajale:
$$\frac{x-3}{x-3} + \frac{5-x}{x-3} \geq \frac{4x}{x-3}$$

$$\frac{x-3+5-x}{x-3} \geq \frac{4x}{x-3}$$

$$\frac{2}{x-3} \geq \frac{4x}{x-3}$$

**Samm 3:** Lahuta:
$$\frac{2}{x-3} - \frac{4x}{x-3} \geq 0$$

$$\frac{2-4x}{x-3} \geq 0$$

$$\frac{2(1-2x)}{x-3} \geq 0$$

**Samm 4:** Kriitilised punktid: $x = \frac{1}{2}$ ja $x = 3$.

Märgitabel:

| Vahemik | $1-2x$ | $x-3$ | Murdavaldis |
|---------|--------|-------|------------|
| $x < \frac{1}{2}$ | $+$ | $-$ | $-$ |
| $\frac{1}{2} \leq x < 3$ | $\leq 0$ | $-$ | $\geq 0$ ✓ |
| $x > 3$ | $-$ | $+$ | $-$ |

**Vastus:** $x \in \left[\dfrac{1}{2};\ 3\right)$ (NB! $x=3$ on keelatud)

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Ühisele nimetajale viimine | 1p |
| Lihtsustamine | 1p |
| Kriitilised punktid | 1p |
| Märgitabel | 1p |
| Vastus koos $x \neq 3$ | 1p |

</details>

---

### Ülesanne 3 (5p)
**Lahenda:**
$$\log_2(x+3) + \log_2(x-4) = 3\log_2 2$$

<details>
<summary>Lahendus</summary>

**Samm 1:** Määramistingimused:
$$x + 3 > 0 \Rightarrow x > -3$$
$$x - 4 > 0 \Rightarrow x > 4$$
Seega $x > 4$.

**Samm 2:** Lihtsusta parem pool:
$$3\log_2 2 = 3 \cdot 1 = 3 = \log_2 8$$

**Samm 3:** Vasak pool:
$$\log_2[(x+3)(x-4)] = \log_2 8$$

$$(x+3)(x-4) = 8$$
$$x^2 - x - 12 = 8$$
$$x^2 - x - 20 = 0$$
$$(x-5)(x+4) = 0$$
$$x_1 = 5, \quad x_2 = -4$$

**Samm 4:** Kontroll: $x > 4$, seega $x = 5$ ✓, $x = -4$ ✗.

**Kontroll:** $\log_2 8 + \log_2 1 = 3 + 0 = 3$ ✓

**Vastus:** $x = 5$

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Määramistingimused | 0,5p |
| $3\log_2 2 = 3$ | 0,5p |
| Logaritmide ühendamine | 1p |
| Ruutvõrrand | 1p |
| Sobimatu lahendi välistamine | 1p |
| Kontroll | 1p |

</details>

---

### Ülesanne 4 (5p)
**Olgu $f(x) = 2\sin x$.**
**a) Joonesta $f(x)$ vahemikus $[0;\ 2\pi]$.**
**b) Lahenda $2\sin(\pi - x) = \sin\!\left(\dfrac{\pi}{2}\right)$, $x \in [0;\ 2\pi]$.**

<details>
<summary>Lahendus</summary>

**a) Joonestamine:**

| $x$ | $0$ | $\frac{\pi}{6}$ | $\frac{\pi}{2}$ | $\pi$ | $\frac{3\pi}{2}$ | $2\pi$ |
|-----|-----|-----------------|-----------------|-------|------------------|--------|
| $f(x)$ | $0$ | $1$ | $2$ | $0$ | $-2$ | $0$ |

Amplituud: 2, periood: $2\pi$.

---

**b) Lahendamine:**

$$2\sin(\pi - x) = \sin\frac{\pi}{2}$$

Kasutame valemit $\sin(\pi - x) = \sin x$:
$$2\sin x = 1$$
$$\sin x = \frac{1}{2}$$

Vahemikus $[0;\ 2\pi]$:
$$x_1 = \frac{\pi}{6}, \quad x_2 = \pi - \frac{\pi}{6} = \frac{5\pi}{6}$$

**Vastus:** $x = \dfrac{\pi}{6}$ või $x = \dfrac{5\pi}{6}$

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Korrektne graafik, amplituud = 2 | 2p |
| b) | $\sin(\pi-x) = \sin x$ | 1p |
| b) | $\sin x = 1/2$ | 1p |
| b) | Mõlemad lahendid | 1p |

</details>

---

### Ülesanne 5 (10p)
**Olgu $f(x) = -x^3 + 3x^2 + 2$.**
**a) Leia kasvamisvahemik.**
**b) Leia miinimumpunkt.**
**c) Leia puutuja võrrand punktis $x_0 = -1$.**

<details>
<summary>Lahendus</summary>

**Tuletis:**
$$f'(x) = -3x^2 + 6x = -3x(x-2)$$

**a) Kasvamisvahemik** ($f'(x) > 0$):

$-3x(x-2) > 0 \Rightarrow x(x-2) < 0 \Rightarrow 0 < x < 2$

**Kasvab vahemikus $(0;\ 2)$.**

---

**b) Miinimumpunkt:**

Kriitilised punktid: $x = 0$ ja $x = 2$.

$f''(x) = -6x + 6$

- $f''(0) = 6 > 0$ → **lokaalne miinimum** punktis $x = 0$... 

Wait — kuna $f'$ läheb negatiivsest positiivseks $x=0$ juures? Kontrollime:
- $x < 0$: $f'(-1) = -3(-1)(-3) = -9 < 0$ → kahanev
- $0 < x < 2$: $f'(1) = -3(1)(-1) = 3 > 0$ → kasvav
- $x > 2$: $f'(3) = -3(3)(1) = -9 < 0$ → kahanev

Seega:
- $x = 0$: lokaalne **miinimum**, $f(0) = 2$ → miinimumpunkt $(0;\ 2)$
- $x = 2$: lokaalne **maksimum**, $f(2) = -8+12+2 = 6$

**Miinimumpunkt on $(0;\ 2)$.**

---

**c) Puutuja $x_0 = -1$:**

$$f(-1) = -(-1)^3 + 3(-1)^2 + 2 = 1 + 3 + 2 = 6$$

$$f'(-1) = -3(-1)(-1-2) = -3(-1)(-3) = -9$$

Puutuja võrrand:
$$y - 6 = -9(x-(-1))$$
$$y = -9x - 9 + 6$$
$$y = -9x - 3$$

**Hindamisskeem:**

| Osa | Samm | Punktid |
|-----|------|---------|
| — | Tuletis | 1p |
| a) | Kriitilised punktid | 1p |
| a) | Kasvamisvahemik $(0;2)$ | 2p |
| b) | Märgiuuring | 1p |
| b) | Miinimumpunkt $(0;2)$ | 1p |
| c) | $f(-1) = 6$ | 1p |
| c) | $f'(-1) = -9$ | 1p |
| c) | Puutuja võrrand | 2p |

</details>

---

### Ülesanne 6 (10p)
**Postipakk: pikkuse ja laiuse suhe on $2:1$.**
**Pikkus + laius + kõrgus = 60 cm.**
**Leia kõrgus, mille korral ruumala on maksimaalne.**

<details>
<summary>Lahendus</summary>

Olgu laius $a$, siis pikkus $= 2a$ ja kõrgus $= h$.

**Piirang:**
$$2a + a + h = 60 \Rightarrow h = 60 - 3a$$

**Ruumala:**
$$V = 2a \cdot a \cdot h = 2a^2(60-3a) = 120a^2 - 6a^3$$

**Maksimum:**
$$V'(a) = 240a - 18a^2 = 6a(40-3a) = 0$$

$$a = 0 \quad (\text{ei sobi}) \quad \text{või} \quad a = \frac{40}{3}$$

**Samm:** Kontroll, et tegu on maksimumiga:
$$V''(a) = 240 - 36a$$
$$V''\!\left(\frac{40}{3}\right) = 240 - 480 = -240 < 0 \quad ✓ \text{ maksimum}$$

**Kõrgus maksimaalse ruumala korral:**
$$h = 60 - 3 \cdot \frac{40}{3} = 60 - 40 = 20\ \text{cm}$$

**Maksimaalne ruumala:**
$$V = 120 \cdot \left(\frac{40}{3}\right)^2 - 6 \cdot \left(\frac{40}{3}\right)^3 = 120 \cdot \frac{1600}{9} - 6 \cdot \frac{64000}{27}$$
$$= \frac{192000}{9} - \frac{384000}{27} = \frac{576000 - 384000}{27} = \frac{192000}{27} \approx 7111\ \text{cm}^3$$

**Vastus:** Maksimaalne ruumala saavutatakse kõrguse $h = 20\ \text{cm}$ korral.

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Muutujate seadistamine ($a$, $2a$, $h$) | 1p |
| Piirangu väljendamine | 1p |
| Ruumala funktsioon | 2p |
| Tuletis ja kriitilised punktid | 3p |
| Maksimumi tõestamine | 1p |
| Kõrguse leidmine | 2p |

</details>

---

### Ülesanne 7 (10p)
**Kolmnurgas ABC: $AB = 237\ \text{m}$, $AC = 470\ \text{m}$, nurk $A = 112°$.**
**a) Leia $BC$ ja pindala (hektarites).**
**b) Leia mediaani pikkus tipust A BC keskpunkti poole.**

<details>
<summary>Lahendus</summary>

**a) BC (cosinus-teoreem):**
$$BC^2 = AB^2 + AC^2 - 2 \cdot AB \cdot AC \cdot \cos A$$
$$= 237^2 + 470^2 - 2 \cdot 237 \cdot 470 \cdot \cos 112°$$

$\cos 112° \approx -0{,}3746$

$$= 56169 + 220900 - 222780 \cdot (-0{,}3746)$$
$$= 277069 + 83470{,}9 \approx 360540$$
$$BC \approx 600{,}4\ \text{m}$$

**Pindala:**
$$S = \frac{1}{2} \cdot AB \cdot AC \cdot \sin A = \frac{1}{2} \cdot 237 \cdot 470 \cdot \sin 112°$$

$\sin 112° \approx 0{,}9272$

$$S = \frac{1}{2} \cdot 237 \cdot 470 \cdot 0{,}9272 \approx \frac{1}{2} \cdot 103\ 310 \approx 51\ 655\ \text{m}^2$$

Teisendame hektariteks ($1\ \text{ha} = 10\ 000\ \text{m}^2$):
$$S \approx \frac{51\ 655}{10\ 000} \approx 5{,}17\ \text{ha}$$

---

**b) Mediaani pikkus tipust A:**

Mediaani valem:
$$m_a^2 = \frac{2b^2 + 2c^2 - a^2}{4}$$

kus $a = BC \approx 600{,}4$, $b = AC = 470$, $c = AB = 237$:

$$m_a^2 = \frac{2 \cdot 470^2 + 2 \cdot 237^2 - 600{,}4^2}{4}$$
$$= \frac{2 \cdot 220900 + 2 \cdot 56169 - 360480}{4}$$
$$= \frac{441800 + 112338 - 360480}{4}$$
$$= \frac{193658}{4} \approx 48414{,}5$$
$$m_a \approx 220{,}0\ \text{m}$$

**Hindamisskeem:**

| Osa | Samm | Punktid |
|-----|------|---------|
| a) | Cosinus-teoreem | 2p |
| a) | $BC \approx 600\ \text{m}$ | 2p |
| a) | Pindala arvutus | 2p |
| a) | Teisendus hektariteks | 1p |
| b) | Mediaani valem | 2p |
| b) | Mediaani pikkus | 1p |

</details>

---

### Ülesanne 8 (10p)
**Lauluvõistlusele esitati 216 laulu, millest 12,5% pääseb edasi.**
**Edasi pääsevatest lauludest on $\frac{5}{9}$ ingliskeelsed, ülejäänud eestikeelsed.**
**a) Leia tõenäosus, et võitja on eestikeelne.**
**b) Leia tõenäosus, et top 3 on kõik ingliskeelsed.**
**c) Leia tõenäosus, et top 3-s on vähemalt 2 eestikeelset laulu.**

<details>
<summary>Lahendus</summary>

**Andmed:**
- Edasi pääsenud: $216 \times 0{,}125 = 27$ laulu
- Ingliskeelseid: $27 \times \frac{5}{9} = 15$
- Eestikeelseid: $27 - 15 = 12$

---

**a) P(võitja on eestikeelne):**

Eeldame, et kõigil on võrdne šanss:
$$P(\text{eesti võidab}) = \frac{12}{27} = \frac{4}{9} \approx 0{,}444$$

---

**b) P(top 3 kõik ingliskeelsed):**

$$P = \frac{\binom{15}{3}}{\binom{27}{3}} = \frac{\frac{15 \cdot 14 \cdot 13}{6}}{\frac{27 \cdot 26 \cdot 25}{6}} = \frac{455}{2925} = \frac{91}{585} = \frac{7}{45} \approx 0{,}156$$

---

**c) P(top 3-s vähemalt 2 eestikeelset):**

$$P(\text{täpselt 2 eesti}) = \frac{\binom{12}{2}\binom{15}{1}}{\binom{27}{3}} = \frac{66 \times 15}{2925} = \frac{990}{2925} = \frac{22}{65}$$

$$P(\text{täpselt 3 eesti}) = \frac{\binom{12}{3}}{\binom{27}{3}} = \frac{220}{2925} = \frac{44}{585}$$

$$P(\text{vähemalt 2 eesti}) = \frac{990 + 220}{2925} = \frac{1210}{2925} = \frac{242}{585} \approx 0{,}414$$

**Hindamisskeem:**

| Osa | Samm | Punktid |
|-----|------|---------|
| — | Ingliskeelsete ja eestikeelsete arv | 1p |
| a) | $P = 12/27$ | 2p |
| b) | Kombinatsioonide kasutamine | 2p |
| b) | Õige tõenäosus | 1p |
| c) | Kahe osa eraldi arvutamine | 2p |
| c) | Summa = lõppvastus | 2p |

</details>

---

*Eksam 2016 — gümnaasiumi lõpueksam matemaatikas*
