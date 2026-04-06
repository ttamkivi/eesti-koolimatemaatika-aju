# Tuletis — ülesanded

## 1. tase ⭐

**1.** Diferentseeri $f(x) = 4x^3 - 2x^2 + 7$.

<details><summary>Lahendus</summary>

$$f'(x) = 12x^2 - 4x$$

**Vastus:** $f'(x) = 12x^2 - 4x$.
</details>

---

**2.** Leia $f'(3)$, kui $f(x) = x^2 - 5x + 1$.

<details><summary>Lahendus</summary>

$$f'(x) = 2x - 5 \implies f'(3) = 6 - 5 = 1$$

**Vastus:** $f'(3) = 1$.
</details>

---

**3.** Diferentseeri $f(x) = \sqrt{x} + \dfrac{1}{x}$.

<details><summary>Lahendus</summary>

$$f(x) = x^{1/2} + x^{-1}$$

$$f'(x) = \frac{1}{2\sqrt{x}} - \frac{1}{x^2}$$

**Vastus:** $f'(x) = \dfrac{1}{2\sqrt{x}} - \dfrac{1}{x^2}$.
</details>

---

**4.** Leia tuletis: $f(x) = \sin x + \cos x$.

<details><summary>Lahendus</summary>

$$f'(x) = \cos x - \sin x$$

**Vastus:** $f'(x) = \cos x - \sin x$.
</details>

---

## 2. tase ⭐⭐

**5.** Leia funktsiooni $f(x) = 2x^3 - 9x^2 + 12x - 4$ ekstreemumid ja määra nende tüüp.

<details><summary>Lahendus</summary>

$$f'(x) = 6x^2 - 18x + 12 = 6(x^2 - 3x + 2) = 6(x-1)(x-2)$$

$f'(x) = 0 \implies x = 1$ või $x = 2$.

**Märgianalüüs:**
- $x < 1$: $f' > 0$ (kasvab)
- $1 < x < 2$: $f' < 0$ (kahaneb)
- $x > 2$: $f' > 0$ (kasvab)

$x = 1$: maksimum, $f(1) = 2 - 9 + 12 - 4 = 1$

$x = 2$: miinimum, $f(2) = 16 - 36 + 24 - 4 = 0$

**Vastus:** lokaalne maksimum $1$ kui $x = 1$; lokaalne miinimum $0$ kui $x = 2$.
</details>

---

**6.** Leia puutuja võrrand funktsioonile $f(x) = x^3 - 2x$ punktis $x_0 = 1$.

<details><summary>Lahendus</summary>

$f(1) = 1 - 2 = -1$

$f'(x) = 3x^2 - 2 \implies f'(1) = 3 - 2 = 1$

Puutuja: $y = -1 + 1 \cdot (x - 1) = x - 2$

**Vastus:** $y = x - 2$.
</details>

---

**7.** Tallinna taksojuht käib tööl kaugusel $s(t) = t^3 - 6t^2 + 9t$ km, kus $t$ on aeg tundides. Leia, millal auto seisab (kiirus = 0) ja millised on kiirenduse väärtused neil hetkedel.

<details><summary>Lahendus</summary>

Kiirus: $v(t) = s'(t) = 3t^2 - 12t + 9 = 3(t^2 - 4t + 3) = 3(t-1)(t-3)$

$v(t) = 0 \implies t = 1$ või $t = 3$

Kiirendus: $a(t) = v'(t) = 6t - 12$

$a(1) = 6 - 12 = -6$ km/h² (pidurdab)

$a(3) = 18 - 12 = 6$ km/h² (kiirendab)

**Vastus:** auto seisab hetkedel $t = 1$ ja $t = 3$; esimesel hetkel kiirendus $-6$ km/h², teisel $+6$ km/h².
</details>

---

## 3. tase ⭐⭐⭐ — PE-stiilis ülesanded

**8. (8p)** *(PE-tüüpi)* Tallinna Botaanikaaia lillepeenar on ristkülikukujuline. Peenar piiratakse aiaga, mille kogupikkus on $60$ m. Ühe külje moodustab looduslik hekk (aiata). Tähistame hekiga paralleelse külje pikkuse $x$-ga (meetrites).

a) (2p) Väljenda teise külje pikkus $x$ kaudu.

b) (2p) Koosta peenarala $S(x)$ valem ja leia $S'(x)$.

c) (2p) Millise $x$ väärtuse korral on pindala maksimaalne? Leia maksimaalne pindala.

d) (2p) Leia puutuja peenara pindalafunktsiooni graafikule punktis $x = 10$.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)** Kolme külje kogupikkus on 60 m (üks pikk külg on hekk):

$$x + 2y = 60 \implies y = \frac{60 - x}{2} = 30 - \frac{x}{2}$$

**b)** Pindala:

$$S(x) = x \cdot y = x\left(30 - \frac{x}{2}\right) = 30x - \frac{x^2}{2}$$

$$S'(x) = 30 - x$$

**c)** Maksimum: $S'(x) = 0 \implies x = 30$

$S''(x) = -1 < 0$ → tõepoolest maksimum.

$$S(30) = 30 \cdot 30 - \frac{900}{2} = 900 - 450 = 450 \text{ m}^2$$

Teine külg: $y = 30 - 15 = 15$ m.

**Vastus:** maksimaalne pindala $450$ m², mõõtmed $30 \times 15$ m.

**d)** Puutuja $x_0 = 10$:

$S(10) = 30 \cdot 10 - \frac{100}{2} = 300 - 50 = 250$

$S'(10) = 30 - 10 = 20$

$$y = 250 + 20(x - 10) = 20x + 50$$

---

**Hindamisskeem (8p):**

| Samm | Punktid |
|------|---------|
| a) Teine külg $y = 30 - x/2$ | 2 |
| b) Pindalavalem $S(x) = 30x - x^2/2$ | 1 |
| b) Tuletis $S'(x) = 30 - x$ | 1 |
| c) $S'(x) = 0 \implies x = 30$ | 1 |
| c) Maksimaalne pindala $450$ m² | 1 |
| d) Puutuja võrrand $y = 20x + 50$ | 2 |

</details>

---

**9. (6p)** *(PE-tüüpi)* Antud on $f(x) = x^3 - 3x^2 - 9x + 2$.

a) (2p) Leia kõik kohaliku ekstreemumi punktid ja määra nende tüüp.

b) (2p) Millisel lõigul $[-2;\, 5]$ on funktsiooni suurim ja väikseim väärtus?

c) (2p) Kas graafik on punktis $(-1;\, 7)$ tõusev või langev? Põhjenda tuletisega.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)**

$$f'(x) = 3x^2 - 6x - 9 = 3(x^2 - 2x - 3) = 3(x-3)(x+1)$$

$f'(x) = 0 \implies x = 3$ või $x = -1$.

$x = -1$: $f'$ muutub $+$ → $-$ → **lokaalne maksimum**

$f(-1) = -1 - 3 + 9 + 2 = 7$

$x = 3$: $f'$ muutub $-$ → $+$ → **lokaalne miinimum**

$f(3) = 27 - 27 - 27 + 2 = -25$

**b)** Lõigul $[-2;\, 5]$ arvutame väärtused kriitilistes punktides ja otspunktides:

$f(-2) = -8 - 12 + 18 + 2 = 0$

$f(-1) = 7$ (max)

$f(3) = -25$ (min)

$f(5) = 125 - 75 - 45 + 2 = 7$

**Suurim väärtus:** $7$ (saavutatakse $x = -1$ ja $x = 5$ korral).

**Väikseim väärtus:** $-25$ (saavutatakse $x = 3$ korral).

**c)** $f'(-1) = 3((-1)-3)((-1)+1) = 3 \cdot (-4) \cdot 0 = 0$

Punktis $x = -1$ on $f'(-1) = 0$ — see on ekstreemumpunkt, mitte tõusev ega langev. Kontrollime: $x = -1$ on lokaalne maksimum — graafik muutub tõusvast langevaks.

**Vastus:** Punktis $x = -1$ on $f'(-1) = 0$, graafik on hetkeliselt horisontaalne (ekstreemum).

---

**Hindamisskeem (6p):**

| Samm | Punktid |
|------|---------|
| a) Tuletis $f'(x) = 3(x-3)(x+1)$ | 1 |
| a) Mõlemad ekstreemumid tüübiga | 1 |
| b) Väärtused kõigis kriitilistes punktides ja otspunktides | 1 |
| b) Suurim ja väikseim väärtus õige | 1 |
| c) $f'(-1) = 0$ arvutus | 1 |
| c) Korrektne järeldus | 1 |

</details>
