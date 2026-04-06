# Integraal — ülesanded

## 1. tase ⭐

**1.** Leia $\displaystyle\int (4x^3 - 6x + 2)\, dx$.

<details><summary>Lahendus</summary>

$$\int (4x^3 - 6x + 2)\, dx = x^4 - 3x^2 + 2x + C$$

**Vastus:** $x^4 - 3x^2 + 2x + C$.
</details>

---

**2.** Arvuta $\displaystyle\int_0^2 x^2\, dx$.

<details><summary>Lahendus</summary>

$$\int_0^2 x^2\, dx = \left[\frac{x^3}{3}\right]_0^2 = \frac{8}{3} - 0 = \frac{8}{3}$$

**Vastus:** $\dfrac{8}{3} \approx 2{,}67$.
</details>

---

**3.** Leia $\displaystyle\int (e^x + \cos x)\, dx$.

<details><summary>Lahendus</summary>

$$\int (e^x + \cos x)\, dx = e^x + \sin x + C$$

**Vastus:** $e^x + \sin x + C$.
</details>

---

**4.** Arvuta $\displaystyle\int_1^4 \sqrt{x}\, dx$.

<details><summary>Lahendus</summary>

$$\int_1^4 x^{1/2}\, dx = \left[\frac{x^{3/2}}{3/2}\right]_1^4 = \left[\frac{2}{3}x^{3/2}\right]_1^4 = \frac{2}{3}(8) - \frac{2}{3}(1) = \frac{16}{3} - \frac{2}{3} = \frac{14}{3}$$

**Vastus:** $\dfrac{14}{3} \approx 4{,}67$.
</details>

---

## 2. tase ⭐⭐

**5.** Leia pindala, mille moodustavad graafik $y = 4 - x^2$ ja $x$-telg.

<details><summary>Lahendus</summary>

Nullkohad: $4 - x^2 = 0 \implies x = \pm 2$.

$f(x) \geq 0$ lõigul $[-2;\, 2]$, seega:

$$S = \int_{-2}^{2} (4 - x^2)\, dx = \left[4x - \frac{x^3}{3}\right]_{-2}^{2}$$

$$= \left(8 - \frac{8}{3}\right) - \left(-8 + \frac{8}{3}\right) = \frac{16}{3} + \frac{16}{3} = \frac{32}{3}$$

**Vastus:** $\dfrac{32}{3} \approx 10{,}67$ ruutühikut.
</details>

---

**6.** Arvuta $\displaystyle\int_0^{\pi/2} \sin x\, dx$ ja tõlgenda tulemust geomeetriliselt.

<details><summary>Lahendus</summary>

$$\int_0^{\pi/2} \sin x\, dx = [-\cos x]_0^{\pi/2} = -\cos\frac{\pi}{2} - (-\cos 0) = 0 + 1 = 1$$

**Geomeetriline tõlgendus:** pindala siinus-kõvera ja $x$-telje vahel nullist kuni $\dfrac{\pi}{2}$ on $1$ ruutühik.

**Vastus:** $1$.
</details>

---

**7.** Tallinna Ülikooli arhitektuuritudeng arvutab projekti jaoks pindalat. Kahe kõvera $f(x) = x^2$ ja $g(x) = 2x$ vaheline pindala (esimeses veerandis).

<details><summary>Lahendus</summary>

Lõikepunktid: $x^2 = 2x \implies x(x-2) = 0 \implies x = 0$ või $x = 2$.

Lõigul $[0;\, 2]$ on $g(x) = 2x \geq f(x) = x^2$.

$$S = \int_0^2 (2x - x^2)\, dx = \left[x^2 - \frac{x^3}{3}\right]_0^2 = 4 - \frac{8}{3} = \frac{4}{3}$$

**Vastus:** $\dfrac{4}{3} \approx 1{,}33$ ruutühikut.
</details>

---

## 3. tase ⭐⭐⭐ — PE-stiilis ülesanded

**8. (8p)** *(PE-tüüpi)* Emajõe üleujutuse ajal mõõdeti vee voolukiirus. Kiirus $t$ tundi pärast mõõtmise algust oli $v(t) = 3t^2 - 12t + 9$ m/min, kus $0 \leq t \leq 4$.

a) (2p) Leia hetked, millal voolukiirus on $0$.

b) (2p) Millal voolukiirus kasvab ja millal kahaneb? (Kasuta tuletist.)

c) (2p) Arvuta jõe läbitud veetaseme muutus lõigul $[0;\, 4]$, st arvuta $\displaystyle\int_0^4 v(t)\, dt$.

d) (2p) Leia voolukiiruse minimaalne väärtus ajavahemikul $[0;\, 4]$.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)** $v(t) = 3t^2 - 12t + 9 = 3(t^2 - 4t + 3) = 3(t-1)(t-3)$

$v(t) = 0 \implies t = 1$ või $t = 3$.

**b)** $v'(t) = 6t - 12 = 6(t - 2)$

- $v'(t) < 0$ kui $t < 2$ → kiirus **kahaneb** $[0;\, 2]$
- $v'(t) > 0$ kui $t > 2$ → kiirus **kasvab** $[2;\, 4]$

**c)**

$$\int_0^4 (3t^2 - 12t + 9)\, dt = [t^3 - 6t^2 + 9t]_0^4$$

$$= (64 - 96 + 36) - 0 = 4 \text{ m/min} \cdot \text{min} = 4 \text{ m}$$

**d)** Miinimum on $t = 2$ (kus $v' = 0$ ja $v'' = 6 > 0$):

$$v(2) = 3(4) - 12(2) + 9 = 12 - 24 + 9 = -3 \text{ m/min}$$

(Negatiivne tähendab hetkelist tagasivoolu.)

**Vastus:** minimaalne voolukiirus $-3$ m/min hetkel $t = 2$.

---

**Hindamisskeem (8p):**

| Samm | Punktid |
|------|---------|
| a) Mõlemad nullid $t = 1$ ja $t = 3$ | 2 |
| b) Tuletis $v'(t) = 6t - 12$ ja õiged piirkonnad | 2 |
| c) Algfunktsioon $t^3 - 6t^2 + 9t$ | 1 |
| c) Arvutus tulemusega $4$ | 1 |
| d) Minimaalne väärtus $-3$ (koos põhjendusega) | 2 |

</details>

---

**9. (6p)** *(PE-tüüpi)* Leia pindala, mille piiravad kõverad $y = x^3 - x$ ja $y = x^2 - 1$.

a) (2p) Leia kõverate lõikepunktid.

b) (2p) Määra, kumb kõver on kõrgemal lõikepunktide vahel.

c) (2p) Arvuta pindala.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)** Lõikepunktid: $x^3 - x = x^2 - 1$

$$x^3 - x^2 - x + 1 = 0$$

$$x^2(x - 1) - (x - 1) = 0$$

$$(x-1)(x^2 - 1) = 0 \implies (x-1)(x-1)(x+1) = 0$$

$x = 1$ (kaksikmuur) või $x = -1$.

Lõikepunktid: $x = -1$ ja $x = 1$.

**b)** Kontrolli $x = 0$:

$f(0) = 0 - 0 = 0$

$g(0) = 0 - 1 = -1$

Seega $f(x) = x^3 - x \geq g(x) = x^2 - 1$ lõigul $[-1;\, 1]$.

**c)**

$$S = \int_{-1}^{1} [(x^3 - x) - (x^2 - 1)]\, dx = \int_{-1}^{1} (x^3 - x^2 - x + 1)\, dx$$

$$= \left[\frac{x^4}{4} - \frac{x^3}{3} - \frac{x^2}{2} + x\right]_{-1}^{1}$$

$x = 1$: $\dfrac{1}{4} - \dfrac{1}{3} - \dfrac{1}{2} + 1 = \dfrac{3 - 4 - 6 + 12}{12} = \dfrac{5}{12}$

$x = -1$: $\dfrac{1}{4} + \dfrac{1}{3} - \dfrac{1}{2} - 1 = \dfrac{3 + 4 - 6 - 12}{12} = -\dfrac{11}{12}$

$$S = \frac{5}{12} - \left(-\frac{11}{12}\right) = \frac{16}{12} = \frac{4}{3}$$

**Vastus:** pindala $\dfrac{4}{3}$ ruutühikut.

---

**Hindamisskeem (6p):**

| Samm | Punktid |
|------|---------|
| a) Lõikepunktid $x = -1$ ja $x = 1$ | 2 |
| b) Korrektne võrdlus, $f \geq g$ lõigul $[-1;\, 1]$ | 1 |
| c) Integraali avaldis | 1 |
| c) Arvutus ja lõpptulemus $\dfrac{4}{3}$ | 2 |

</details>
