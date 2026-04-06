# Integraal

## 1. Määramata integraal (algfunktsioon)

Funktsioon $F(x)$ on $f(x)$ **algfunktsioon**, kui $F'(x) = f(x)$.

$$\int f(x)\, dx = F(x) + C$$

kus $C$ on integratsioonikonstand.

## 2. Põhiintegraali valemid

| Funktsioon | Integraal |
|------------|-----------|
| $\int x^n\, dx$ | $\dfrac{x^{n+1}}{n+1} + C$ (kui $n \neq -1$) |
| $\int \dfrac{1}{x}\, dx$ | $\ln|x| + C$ |
| $\int e^x\, dx$ | $e^x + C$ |
| $\int \sin x\, dx$ | $-\cos x + C$ |
| $\int \cos x\, dx$ | $\sin x + C$ |
| $\int k\, dx$ | $kx + C$ |

## 3. Integreerimise omadused

$$\int (f(x) \pm g(x))\, dx = \int f(x)\, dx \pm \int g(x)\, dx$$

$$\int c \cdot f(x)\, dx = c \int f(x)\, dx$$

## 4. Määratud integraal — Newtoni–Leibnizi valem

$$\int_a^b f(x)\, dx = F(b) - F(a)$$

kus $F$ on $f$ algfunktsioon.

**Märge:** Tulemust nimetatakse sageli $[F(x)]_a^b = F(b) - F(a)$.

## 5. Pindala arvutamine

### 5.1 Pindala x-telje ja graafiku vahel

Kui $f(x) \geq 0$ lõigul $[a;\, b]$:

$$S = \int_a^b f(x)\, dx$$

Kui $f(x) \leq 0$, võtame absoluutväärtuse:

$$S = \left|\int_a^b f(x)\, dx\right|$$

Kui funktsioon muutab märki, jagame lõigu osadeks.

### 5.2 Pindala kahe kõvera vahel

$$S = \int_a^b [f(x) - g(x)]\, dx$$

kus $f(x) \geq g(x)$ kogu lõigul $[a;\, b]$.

## 6. Lahendatud näited

**Näide 1.** Leia $\displaystyle\int (3x^2 - 4x + 1)\, dx$.

$$\int (3x^2 - 4x + 1)\, dx = x^3 - 2x^2 + x + C$$

**Näide 2.** Arvuta $\displaystyle\int_1^3 (2x + 1)\, dx$.

$$\int_1^3 (2x + 1)\, dx = [x^2 + x]_1^3 = (9 + 3) - (1 + 1) = 12 - 2 = 10$$

**Näide 3.** Leia pindala, mille $f(x) = x^2$ ja $g(x) = x$ piiravad (1. veerandis).

Lõikepunktid: $x^2 = x \implies x = 0$ või $x = 1$.

Lõigul $[0;\, 1]$ on $g(x) \geq f(x)$ (sirge on kõrgemal).

$$S = \int_0^1 (x - x^2)\, dx = \left[\frac{x^2}{2} - \frac{x^3}{3}\right]_0^1 = \frac{1}{2} - \frac{1}{3} = \frac{1}{6}$$

## 7. Tüüpilised vead

- Konstand $+C$ ununeb määramata integraalis.
- Potentsi valemis $n+1$ koef: $\int x^3 dx = \dfrac{x^4}{4} + C$, mitte $\dfrac{x^4}{4+1}$.
- Pindala arvutamisel $f(x) - g(x)$ järjekord: suurem miinus väiksem.
- Negatiivse piirkonna pindala: võtta absoluutväärtus, mitte jätta negatiivne.

## 8. Seos teiste teemadega

- Tuletis ja integraal on pöördtehteks.
- Füüsikas: töö = jõu integraal tee järgi, läbitud tee = kiiruse integraal.
- Tõenäosusjaotuste tihedusfunktsioonide integreerimine.
