# Funktsioonid ja calculus — Eksamiülesanded

**Teema:** Funktsioonid, tuletis, integraal, optimiseerimine  
**Tase:** I tase (lihtne), II tase (keskmine), III tase (raske)

---

## I TASE — Algtaseme ülesanded

### Ülesanne 1. Funktsiooni määramispiirkond

Leia funktsiooni $f(x) = \frac{1}{x - 2}$ määramispiirkond.

<details>
<summary>Lahendus</summary>

**Samm 1:** Funktsioon on määratud, kui nimetaja ei ole null.

$$x - 2 \neq 0$$
$$x \neq 2$$

**Vastus:** $D(f) = \mathbb{R} \setminus \{2\}$ ehk $x \in (-\infty; 2) \cup (2; \infty)$

</details>

---

### Ülesanne 2. Funktsiooni väärtuse arvutamine

Antud funktsioon $f(x) = 3x^2 - 2x + 1$. Arvuta $f(2)$.

<details>
<summary>Lahendus</summary>

**Samm 1:** Asenda $x = 2$:
$$f(2) = 3(2)^2 - 2(2) + 1$$
$$f(2) = 3 \cdot 4 - 4 + 1$$
$$f(2) = 12 - 4 + 1 = 9$$

**Vastus:** $f(2) = 9$

</details>

---

### Ülesanne 3. Tuletise arvutamine

Leia funktsiooni $f(x) = 3x^2$ tuletis.

<details>
<summary>Lahendus</summary>

**Samm 1:** Kasuta astmefunktsiooni tuletisreeglit: $(x^n)' = n \cdot x^{n-1}$

$$f'(x) = 3 \cdot 2x^{2-1} = 6x$$

**Vastus:** $f'(x) = 6x$

</details>

---

### Ülesanne 4. Lineaarfunktsiooni graafik

Joonista funktsiooni $y = 2x - 3$ graafik ja leia tema nullkohad.

<details>
<summary>Lahendus</summary>

**Samm 1:** Nullkoha leidmiseks pane $y = 0$:
$$2x - 3 = 0$$
$$2x = 3$$
$$x = 1,5$$

**Samm 2:** Graafik on sirge kaldega 2 ja $y$-teljel lõikepunktiga $(0, -3)$.

**Nullkoht:** $(1,5; 0)$
**$y$-teljel lõikepunkt:** $(0, -3)$

**Graafik:** Sirge läbib punkte $(1,5; 0)$ ja $(0; -3)$.

</details>

---

### Ülesanne 5. Tuletise kasutamine — tangensi kaldevector

Leia funktsiooni $f(x) = x^2$ graafiku puutuja kalle punktis $x = 1$.

<details>
<summary>Lahendus</summary>

**Samm 1:** Leia tuletis:
$$f'(x) = 2x$$

**Samm 2:** Arvuta tuletise väärtus punktis $x = 1$:
$$f'(1) = 2 \cdot 1 = 2$$

**Vastus:** Puutuja kalle on 2.

</details>

---

## II TASE — Keskmise taseme ülesanded

### Ülesanne 6. Tuletise arvutamine liitfunktsiooni jaoks

Leia funktsiooni $f(x) = (3x + 1)^2$ tuletis.

<details>
<summary>Lahendus</summary>

**Samm 1:** Kasuta ketiregulit: $(u^n)' = n \cdot u^{n-1} \cdot u'$

Olgu $u = 3x + 1$, siis $u' = 3$.

**Samm 2:** Rakenda reegel:
$$f'(x) = 2(3x + 1)^{2-1} \cdot 3$$
$$f'(x) = 2(3x + 1) \cdot 3$$
$$f'(x) = 6(3x + 1) = 18x + 6$$

**Vastus:** $f'(x) = 18x + 6$

</details>

---

### Ülesanne 7. Funktsiooni uurimine — ekstremumpunktid

Leia funktsiooni $f(x) = x^3 - 3x^2$ lokaalsed ekstremumpunktid.

<details>
<summary>Lahendus</summary>

**Samm 1:** Leia tuletis:
$$f'(x) = 3x^2 - 6x$$

**Samm 2:** Pane tuletis nulliks:
$$3x^2 - 6x = 0$$
$$3x(x - 2) = 0$$
$$x = 0 \text{ või } x = 2$$

**Samm 3:** Determineeri ekstremumi tüüp teise tuletise abil:
$$f''(x) = 6x - 6$$

- Kui $x = 0$: $f''(0) = -6 < 0$ → lokaalne maksimum
- Kui $x = 2$: $f''(2) = 6 > 0$ → lokaalne miinimum

**Samm 4:** Arvuta funktsioonide väärtused:
- $f(0) = 0^3 - 3(0)^2 = 0$
- $f(2) = 2^3 - 3(2)^2 = 8 - 12 = -4$

**Vastus:** Lokaalne maksimum $(0; 0)$, lokaalne miinimum $(2; -4)$.

</details>

---

### Ülesanne 8. Integraali arvutamine

Arvuta määramata integraal: $\int (4x^3 - 2x) dx$

<details>
<summary>Lahendus</summary>

**Samm 1:** Kasuta astmefunktsiooni integraalireeglit: $\int x^n dx = \frac{x^{n+1}}{n+1} + C$

$$\int (4x^3 - 2x) dx = \int 4x^3 dx - \int 2x dx$$

**Samm 2:** Integreeri iga liige:
$$= 4 \cdot \frac{x^4}{4} - 2 \cdot \frac{x^2}{2} + C$$
$$= x^4 - x^2 + C$$

**Vastus:** $\int (4x^3 - 2x) dx = x^4 - x^2 + C$

</details>

---

### Ülesanne 9. Määratud integraal

Arvuta määratud integraal: $\int_0^2 (x^2 + 1) dx$

<details>
<summary>Lahendus</summary>

**Samm 1:** Leia antiderivatiiv:
$$\int (x^2 + 1) dx = \frac{x^3}{3} + x + C$$

**Samm 2:** Kasuta Newton-Leibnizi valemit:
$$\int_0^2 (x^2 + 1) dx = \left[\frac{x^3}{3} + x\right]_0^2$$

**Samm 3:** Arvuta:
$$= \left(\frac{2^3}{3} + 2\right) - \left(\frac{0^3}{3} + 0\right)$$
$$= \left(\frac{8}{3} + 2\right) - 0$$
$$= \frac{8}{3} + \frac{6}{3} = \frac{14}{3}$$

**Vastus:** $\int_0^2 (x^2 + 1) dx = \frac{14}{3} \approx 4,67$

</details>

---

## III TASE — Kõrgema taseme ülesanded

### Ülesanne 10. Optimiseerimine — maksimaalse pindala ristkülik

Ristkülikul on perimeetr 20 cm. Leia selle küljed, et pindala oleks maksimaalsel.

<details>
<summary>Lahendus</summary>

**Samm 1:** Defineeri muutujad. Olgu küljed $x$ ja $y$.

**Samm 2:** Perimeetri tingimus:
$$2x + 2y = 20$$
$$x + y = 10$$
$$y = 10 - x$$

**Samm 3:** Pindala funktsioon:
$$A(x) = x \cdot y = x(10 - x) = 10x - x^2$$

**Samm 4:** Leia maksimum:
$$A'(x) = 10 - 2x = 0$$
$$x = 5$$

**Samm 5:** Kontrol teise tuletisega:
$$A''(x) = -2 < 0$$ → maksimum

**Samm 6:** Leia $y$:
$$y = 10 - 5 = 5$$

**Vastus:** Ristkülik on ruut külgedega 5 cm. Maksimaalne pindala on $25 \text{ cm}^2$.

</details>

---

### Ülesanne 11. Pindala arvutamine integraaliga

Leia funktsioonide $y = x^2$ ja $y = 2x$ vaheline pindala lõigul $[0; 2]$.

<details>
<summary>Lahendus</summary>

**Samm 1:** Määra, kumb funktsioon on ülal. Kontrolli punktis $x = 1$:
- $y = x^2$: $y = 1$
- $y = 2x$: $y = 2$

Seega $y = 2x$ on ülal.

**Samm 2:** Pindala:
$$A = \int_0^2 (2x - x^2) dx$$

**Samm 3:** Arvuta:
$$= \left[x^2 - \frac{x^3}{3}\right]_0^2$$
$$= \left(4 - \frac{8}{3}\right) - (0 - 0)$$
$$= \frac{12}{3} - \frac{8}{3} = \frac{4}{3}$$

**Vastus:** Pindala on $\frac{4}{3}$ ruutühikut.

</details>

---

Ülesanded on soovituslik lahendamisjärjekord:
1. Alusta I tasemega (harjutamiseks)
2. Jätka II tasemega (eksamiks valmistumiseks)
3. Lahenda III tase (optimaalseks soorituseks)

