---
title: "Eksam 2019"
weight: 11
---

# Gümnaasiumi lõpueksam 2019

## Ülesanded ja lahendused

---

### Ülesanne 1 (5p)
**Lihtsusta avaldis** ($a > 0$):
$$\frac{a - \sqrt{4a}}{a} : \left(\frac{a+4}{\sqrt{a}} - 4\right)$$
**Kas saadud avaldis saab võrduda nulliga?**

<details>
<summary>Lahendus</summary>

**Samm 1:** Lihtsusta lugeja:
$$\frac{a - \sqrt{4a}}{a} = \frac{a - 2\sqrt{a}}{a} = 1 - \frac{2}{\sqrt{a}}$$

**Samm 2:** Lihtsusta jagaja:
$$\frac{a+4}{\sqrt{a}} - 4 = \frac{a + 4 - 4\sqrt{a}}{\sqrt{a}} = \frac{(\sqrt{a}-2)^2}{\sqrt{a}}$$

**Samm 3:** Jagamine:
$$\left(1 - \frac{2}{\sqrt{a}}\right) : \frac{(\sqrt{a}-2)^2}{\sqrt{a}} = \frac{\sqrt{a}-2}{\sqrt{a}} \cdot \frac{\sqrt{a}}{(\sqrt{a}-2)^2} = \frac{1}{\sqrt{a}-2}$$

**Kas saab nulliks?**

$\frac{1}{\sqrt{a}-2} = 0$ ei oma lahendeid (murdavaldis saab nulliga võrduda ainult siis, kui lugeja = 0, aga lugeja on 1).

**Vastus:** $\dfrac{1}{\sqrt{a}-2}$, ei saa nulliga võrduda.

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Lugeja lihtsustamine | 1p |
| Jagaja lihtsustamine | 1p |
| Jagamise teisendamine korrutamiseks | 1p |
| Lõppvastus | 1p |
| Null-küsimus selgitusega | 1p |

</details>

---

### Ülesanne 2 (5p)
**Olgu $f(x) = 1{,}5\sin x$ ja $g(x) = \pi x - x^2$.**
**a) Kumb funktsioon on suurem vahemikus $(0;\ \pi)$?**
**b) Arvuta $\displaystyle\int_0^{\pi} 1{,}5\sin x\ dx$.**

<details>
<summary>Lahendus</summary>

**a) Võrdlus vahemikus $(0; \pi)$:**

Kontrollime punktis $x = \frac{\pi}{2}$:
- $f\!\left(\frac{\pi}{2}\right) = 1{,}5 \sin\frac{\pi}{2} = 1{,}5$
- $g\!\left(\frac{\pi}{2}\right) = \pi \cdot \frac{\pi}{2} - \left(\frac{\pi}{2}\right)^2 = \frac{\pi^2}{2} - \frac{\pi^2}{4} = \frac{\pi^2}{4} \approx \frac{9{,}87}{4} \approx 2{,}47$

Seega $g(x) > f(x)$ selles punktis.

Vahemikus $(0; \pi)$ mõlemad funktsioonid on positiivsed. $g(x) = x(\pi - x)$ saavutab maksimumi $\frac{\pi^2}{4} \approx 2{,}47$ punktis $x = \frac{\pi}{2}$, samas $f(x) \leq 1{,}5$.

**Vastus:** $g(x) > f(x)$ kogu vahemikus $(0; \pi)$.

---

**b) Integraal:**
$$\int_0^{\pi} 1{,}5\sin x\ dx = 1{,}5 \left[-\cos x\right]_0^{\pi} = 1{,}5(-\cos\pi + \cos 0)$$
$$= 1{,}5(-(-1) + 1) = 1{,}5 \times 2 = 3$$

**Vastus:** $\displaystyle\int_0^{\pi} 1{,}5\sin x\ dx = 3$

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Konkreetne võrdlus väärtusega | 1p |
| a) | Järeldus koos põhjendusega | 1p |
| b) | Primiitfunktsiooni leidmine $-\cos x$ | 1p |
| b) | Piirväärtuste asendamine | 1p |
| b) | Õige vastus 3 | 1p |

</details>

---

### Ülesanne 3 (5p)
**Bussifirma müüb pileteid nii, et iga 5 pileti järel tõuseb hind 1€ võrra.**
**25 piletit müüdi kokku tulu 155€.**
**Kui palju maksab odavaim pilet?**

<details>
<summary>Lahendus</summary>

Olgu odavaim pilet $a$ eurot.

Pileti hinnad:
- 1.–5. pilet: $a$ €
- 6.–10. pilet: $a+1$ €
- 11.–15. pilet: $a+2$ €
- 16.–20. pilet: $a+3$ €
- 21.–25. pilet: $a+4$ €

Kogu tulu:
$$5a + 5(a+1) + 5(a+2) + 5(a+3) + 5(a+4) = 155$$
$$5a + 5a+5 + 5a+10 + 5a+15 + 5a+20 = 155$$
$$25a + 50 = 155$$
$$25a = 105$$
$$a = 4{,}2\ €$$

**Vastus:** Odavaim pilet maksab **4,20 €**.

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Hinnaste kirjutamine (aritmeetiline jada) | 1p |
| Tulusumma koostamine | 1p |
| Võrrandi lahendamine | 2p |
| Õige vastus | 1p |

</details>

---

### Ülesanne 4 (5p)
**6 kaardil on numbrid: $1,\ -2,\ 3^{-4},\ \sqrt{5},\ 6^7,\ -\tfrac{1}{8}$.**
**Võetakse juhuslikult 2 kaarti.**
**a) Leia tõenäosus, et mõlemad arvud on täisarvud.**
**b) Leia tõenäosus, et vähemalt üks arv on negatiivne.**

<details>
<summary>Lahendus</summary>

**Arvude klassifitseerimine:**

| Arv | Täisarv? | Negatiivne? |
|-----|---------|------------|
| $1$ | ✓ | ✗ |
| $-2$ | ✓ | ✓ |
| $3^{-4} = \frac{1}{81}$ | ✗ | ✗ |
| $\sqrt{5} \approx 2{,}24$ | ✗ | ✗ |
| $6^7 = 279936$ | ✓ | ✗ |
| $-\frac{1}{8}$ | ✗ | ✓ |

Täisarvud: $\{1, -2, 6^7\}$ — 3 tk.
Negatiivsed: $\{-2, -\frac{1}{8}\}$ — 2 tk.

Kõik võimalused: $\binom{6}{2} = 15$

---

**a) P(mõlemad täisarvud):**
$$P = \frac{\binom{3}{2}}{\binom{6}{2}} = \frac{3}{15} = \frac{1}{5} = 0{,}2$$

---

**b) P(vähemalt 1 negatiivne):**
$$P = 1 - P(\text{ei ühtegi negatiivset}) = 1 - \frac{\binom{4}{2}}{\binom{6}{2}} = 1 - \frac{6}{15} = 1 - \frac{2}{5} = \frac{3}{5} = 0{,}6$$

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| — | Arvude klassifitseerimine | 1p |
| a) | Kombinatsioonid + arvutus | 2p |
| b) | Täiendtõenäosuse kasutamine | 1p |
| b) | Õige vastus | 1p |

</details>

---

### Ülesanne 5 (10p)
**Lahenda süsteem:**
$$\begin{cases}(3x-4)(x-2) \leq x+2 \\ \dfrac{3x-4}{x-2} < x+2\end{cases}$$

<details>
<summary>Lahendus</summary>

**Võrratus 1:** $(3x-4)(x-2) \leq x+2$

$$3x^2 - 6x - 4x + 8 \leq x + 2$$
$$3x^2 - 10x + 8 \leq x + 2$$
$$3x^2 - 11x + 6 \leq 0$$
$$(3x-2)(x-3) \leq 0$$

Lahendus: $\dfrac{2}{3} \leq x \leq 3$

---

**Võrratus 2:** $\dfrac{3x-4}{x-2} < x+2$ (NB! $x \neq 2$)

$$\frac{3x-4}{x-2} - (x+2) < 0$$
$$\frac{3x-4 - (x+2)(x-2)}{x-2} < 0$$
$$\frac{3x-4 - (x^2-4)}{x-2} < 0$$
$$\frac{3x - 4 - x^2 + 4}{x-2} < 0$$
$$\frac{-x^2 + 3x}{x-2} < 0$$
$$\frac{x(-x+3)}{x-2} < 0$$
$$\frac{x(3-x)}{x-2} < 0$$

Märgitabel:

| Vahemik | $x$ | $3-x$ | $x-2$ | Murdavaldis |
|---------|-----|-------|-------|------------|
| $x < 0$ | $-$ | $+$ | $-$ | $+$ |
| $0 < x < 2$ | $+$ | $+$ | $-$ | $-$ ✓ |
| $2 < x < 3$ | $+$ | $+$ | $+$ | $+$ |
| $x > 3$ | $+$ | $-$ | $+$ | $-$ ✓ |

Lahendus: $0 < x < 2$ või $x > 3$

---

**Süsteemi lahendus** (ühisosa):

$\left[\frac{2}{3};\ 3\right] \cap \left[(0;2) \cup (3;+\infty)\right]$

$= \left[\frac{2}{3};\ 2\right)$ (sest $x=2$ on keelatud ja $x=3$ ei kuulu teise võrratusse)

**Vastus:** $x \in \left[\dfrac{2}{3};\ 2\right)$

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| 1. võrratuse lahendamine | 3p |
| 2. võrratuse teisendamine | 3p |
| Märgitabel | 2p |
| Ühisosa leidmine | 2p |

</details>

---

### Ülesanne 6 (10p)
**Olgu $f(x) = 2^x - 4$ ja $g(x) = 2^{x-1}$.**
**a) Lahenda $f(x) = g(x)$.**
**b) Joonesta mõlemad funktsioonid ning märgi lõikepunkt A.**
**c) Leia $m$, nii et $h(x) = 2^{mx}$ läbib punkti A.**

<details>
<summary>Lahendus</summary>

**a) $f(x) = g(x)$:**

$$2^x - 4 = 2^{x-1}$$
$$2^x - 4 = \frac{2^x}{2}$$

Olgu $t = 2^x$:
$$t - 4 = \frac{t}{2}$$
$$2t - 8 = t$$
$$t = 8$$
$$2^x = 8 = 2^3$$
$$x = 3$$

Lõikepunkt: $A = (3,\ f(3)) = (3,\ 2^3 - 4) = (3,\ 4)$

---

**b) Joonestamine:**

| $x$ | $f(x) = 2^x - 4$ | $g(x) = 2^{x-1}$ |
|-----|-----------------|-----------------|
| $-1$ | $-3{,}5$ | $0{,}25$ |
| $0$ | $-3$ | $0{,}5$ |
| $1$ | $-2$ | $1$ |
| $2$ | $0$ | $2$ |
| $3$ | $4$ | $4$ ← A |
| $4$ | $12$ | $8$ |

$f(x)$ on $2^x$ nihutatuna 4 võrra allapoole.
$g(x)$ on $2^x$ nihutatuna 1 võrra paremale.
Lõikepunkt: $A = (3,\ 4)$.

---

**c) $h(x) = 2^{mx}$ läbi punkti $A = (3,\ 4)$:**

$$2^{m \cdot 3} = 4 = 2^2$$
$$3m = 2$$
$$m = \frac{2}{3}$$

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Asendus $t = 2^x$ | 1p |
| a) | $x = 3$, punkt A | 2p |
| b) | Mõlemad jooned korrektselt | 3p |
| b) | Lõikepunkti märkimine | 1p |
| c) | $m$ leidmine | 3p |

</details>

---

### Ülesanne 7 (10p)
**Ristküliku ühe külje pikkus on $\sqrt{x+1}\ \text{cm}$, diagonaali pikkus on $\sqrt{x+50}\ \text{cm}$ ning ümbermõõt on $x\ \text{cm}$. Leia ristküliku pindala.**

<details>
<summary>Lahendus</summary>

Olgu külgede pikkused $a = \sqrt{x+1}$ ja $b$.

**Samm 1:** Ümbermõõdust: $2(a+b) = x$, seega $a + b = \frac{x}{2}$, ehk $b = \frac{x}{2} - \sqrt{x+1}$.

**Samm 2:** Pythagorase teoreem (diagonaal):
$$a^2 + b^2 = d^2$$
$$(x+1) + b^2 = x + 50$$
$$b^2 = 49$$
$$b = 7\ \text{cm}$$

**Samm 3:** Leia $x$ ümbermõõdust:
$$2(a + 7) = x$$
$$a = \frac{x}{2} - 7 = \sqrt{x+1}$$

$$\left(\frac{x}{2} - 7\right)^2 = x + 1$$
$$\frac{x^2}{4} - 7x + 49 = x + 1$$
$$\frac{x^2}{4} - 8x + 48 = 0 \quad |\times 4$$
$$x^2 - 32x + 192 = 0$$

$$D = 1024 - 768 = 256, \quad \sqrt{D} = 16$$
$$x = \frac{32 \pm 16}{2}$$
$$x_1 = 24, \quad x_2 = 8$$

**Samm 4:** Kontroll ($a > 0$):
- $x = 24$: $a = 12 - 7 = 5\ \text{cm}$ ✓, $b = 7\ \text{cm}$ ✓
- $x = 8$: $a = 4 - 7 = -3$ ✗

**Samm 5:** Pindala:
$$S = a \times b = 5 \times 7 = 35\ \text{cm}^2$$

**Vastus:** Ristküliku pindala on $S = 35\ \text{cm}^2$.

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| $b^2 = 49 \Rightarrow b = 7$ | 2p |
| Ruutvõrrandi koostamine | 3p |
| Mõlemad lahendid | 2p |
| Negatiivse välistamine | 1p |
| Pindala | 2p |

</details>

---

### Ülesanne 8 (10p)
**Olgu $f(x) = 0{,}5x^3 - 3x^2 + 6$.**
**a) Leia sirge $s$ võrrand, mis läbib $f(x)$ ekstreemumpunkte.**
**b) Leia sirge $s$ ja $f(x)$ kolmas lõikepunkt P.**

<details>
<summary>Lahendus</summary>

**a) Ekstreemumid:**

$$f'(x) = 1{,}5x^2 - 6x = 1{,}5x(x-4)$$

$f'(x) = 0$: $x_1 = 0$, $x_2 = 4$

Ekstreemumipunktid:
- $f(0) = 6$ → punkt $(0;\ 6)$
- $f(4) = 0{,}5 \cdot 64 - 3 \cdot 16 + 6 = 32 - 48 + 6 = -10$ → punkt $(4;\ -10)$

Sirge $s$ läbi $(0;\ 6)$ ja $(4;\ -10)$:
$$k = \frac{-10 - 6}{4 - 0} = \frac{-16}{4} = -4$$
$$s: y = -4x + 6$$

---

**b) Kolmas lõikepunkt:**

$f(x) = s(x)$:
$$0{,}5x^3 - 3x^2 + 6 = -4x + 6$$
$$0{,}5x^3 - 3x^2 + 4x = 0$$
$$x(0{,}5x^2 - 3x + 4) = 0$$

Teame, et $x = 0$ ja $x = 4$ on lahendid. Kolmas lahend:
$$0{,}5x^2 - 3x + 4 = 0 \quad |\times 2$$
$$x^2 - 6x + 8 = 0$$
$$(x-2)(x-4) = 0$$
$$x = 2 \quad \text{või} \quad x = 4$$

Seega $x = 2$ on kolmas lõikepunkt.
$$y = -4 \cdot 2 + 6 = -2$$

**Punkt P = (2; −2).**

**Kontroll:** $f(2) = 0{,}5 \cdot 8 - 3 \cdot 4 + 6 = 4 - 12 + 6 = -2$ ✓

**Hindamisskeem:**

| Samm | Punktid |
|------|---------|
| Tuletis, ekstreemumid | 2p |
| Ekstreemumpunktide koordinaadid | 2p |
| Sirge võrrand | 2p |
| Võrrandi koostamine lõikepunkti jaoks | 2p |
| Kolmas lõikepunkt P = (2; −2) | 2p |

</details>

---

*Eksam 2019 — gümnaasiumi lõpueksam matemaatikas*
