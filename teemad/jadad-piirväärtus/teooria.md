# Jadad ja piirväärtus

## 1. Arvjada mõiste

**Arvjada** on järjestatud arvude loend $a_1, a_2, a_3, \ldots, a_n, \ldots$

**Üldliige** $a_n$ — valem $n$-nda liikme leidmiseks.

**Näide:** $a_n = 2n - 1$ annab jada $1, 3, 5, 7, \ldots$ (paaritud arvud).

## 2. Aritmeetiline jada

**Definitsioon:** iga järgmine liige on eelmisest suurem/väiksem fikseeritud **sammuvõrra** $d$.

$$a_{n+1} = a_n + d$$

**Üldliige:**
$$a_n = a_1 + (n-1)d$$

**Summa** esimesest $n$ liikmest:
$$S_n = \frac{n(a_1 + a_n)}{2} = \frac{n(2a_1 + (n-1)d)}{2}$$

**Kontrollvalem:** $a_n = \dfrac{a_{n-1} + a_{n+1}}{2}$ (iga liige on naabrite aritmeetiline keskmine).

## 3. Geomeetriline jada

**Definitsioon:** iga järgmine liige saadakse eelmise korrutamisel fikseeritud **kvoodiga** $q \neq 0$.

$$a_{n+1} = a_n \cdot q$$

**Üldliige:**
$$a_n = a_1 \cdot q^{n-1}$$

**Summa** esimesest $n$ liikmest ($q \neq 1$):
$$S_n = \frac{a_1(1 - q^n)}{1 - q} = \frac{a_1(q^n - 1)}{q - 1}$$

**Kontrollvalem:** $a_n^2 = a_{n-1} \cdot a_{n+1}$ (iga liige on naabrite geomeetriline keskmine).

## 4. Lõpmatu geomeetrilise jada summa

Kui $|q| < 1$, siis lõpmatu geomeetrilise jada summa:

$$S = \frac{a_1}{1 - q}$$

See valem kehtib perioodiliste kümnendmurdude muutmisel harilikuks murruks.

## 5. Piirväärtuse intuitiivne mõiste

**Jada piirväärtus:** $\displaystyle\lim_{n \to \infty} a_n = L$ tähendab, et liikmed lähenevad väärtusele $L$.

**Funktsioon piirväärtus:** $\displaystyle\lim_{x \to a} f(x) = L$

**Ühepoolsed piirväärtused:**
$$\lim_{x \to a^-} f(x) \quad (\text{vasak}), \qquad \lim_{x \to a^+} f(x) \quad (\text{parem})$$

## 6. Piirväärtuse arvutamine

**Polünoomi/ratsionaalse funktsiooni piirväärtus:**

$$\lim_{x \to a} f(x) = f(a) \quad (\text{kui } f \text{ on pidev})$$

**Määramata kuju $\dfrac{0}{0}$:** tegurdada ja lühendada.

$$\lim_{x \to 2} \frac{x^2 - 4}{x - 2} = \lim_{x \to 2} \frac{(x-2)(x+2)}{x-2} = \lim_{x \to 2} (x+2) = 4$$

**Piirväärtus lõpmatuses:**

$$\lim_{x \to \infty} \frac{3x^2 + x}{2x^2 - 5} = \frac{3}{2} \quad (\text{kõrgeima astme koefitsientide suhe})$$

## 7. Tuletis kui piirväärtus

Tuletis on defineeritud kui piirväärtus:

$$f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}$$

## 8. Lahendatud näited

**Näide 1.** Aritmeetiline jada: $a_1 = 5$, $d = 3$. Leia $a_{10}$ ja $S_{10}$.

$$a_{10} = 5 + 9 \cdot 3 = 32$$

$$S_{10} = \frac{10(5 + 32)}{2} = 5 \cdot 37 = 185$$

**Näide 2.** Geomeetriline jada: $a_1 = 2$, $q = \dfrac{1}{2}$. Leia lõpmatu summa.

$$S = \frac{2}{1 - \tfrac{1}{2}} = \frac{2}{\tfrac{1}{2}} = 4$$

**Näide 3.** Leia $\displaystyle\lim_{x \to 3} \dfrac{x^2 - 9}{x - 3}$.

$$\lim_{x \to 3} \frac{(x-3)(x+3)}{x-3} = \lim_{x \to 3} (x+3) = 6$$

## 9. Tüüpilised vead

- Aritmeetilises jadassammus $d$ võib olla negatiivne (kahanev jada).
- Geomeetrilise jada kvoot $q$ võib olla negatiivne (liikmed vahelduvad märgiga).
- Lõpmatu summa valem kehtib ainult kui $|q| < 1$.
- Piirväärtus $\dfrac{0}{0}$ ei tähenda vastust $1$ — tuleb lühendada!
