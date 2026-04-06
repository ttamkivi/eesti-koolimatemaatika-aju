# Tuletis

## 1. Tuletise mõiste

**Tuletis** kirjeldab funktsiooni muutumise kiirust ehk graafiku tõusu antud punktis.

$$f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}$$

Geomeetriliselt: $f'(x_0)$ on parabooli/kõvera **puutuja tõus** punktis $x_0$.

## 2. Põhifunktsioonide tuletised

| Funktsioon | Tuletis |
|------------|---------|
| $f(x) = c$ (konstant) | $f'(x) = 0$ |
| $f(x) = x^n$ | $f'(x) = n \cdot x^{n-1}$ |
| $f(x) = \sqrt{x}$ | $f'(x) = \dfrac{1}{2\sqrt{x}}$ |
| $f(x) = \dfrac{1}{x}$ | $f'(x) = -\dfrac{1}{x^2}$ |
| $f(x) = e^x$ | $f'(x) = e^x$ |
| $f(x) = \ln x$ | $f'(x) = \dfrac{1}{x}$ |
| $f(x) = \sin x$ | $f'(x) = \cos x$ |
| $f(x) = \cos x$ | $f'(x) = -\sin x$ |

## 3. Diferentseerimise reeglid

**Summa ja vahe:**
$$(f \pm g)' = f' \pm g'$$

**Arv korrutajana:**
$$(cf)' = c \cdot f'$$

**Korrutis:**
$$(fg)' = f'g + fg'$$

**Jagatis:**
$$\left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2}$$

**Liitfunktsioon (ahelureeeel):**
$$(f(g(x)))' = f'(g(x)) \cdot g'(x)$$

## 4. Tuletise rakendused

### 4.1 Funktsiooni monotoonsus
- $f'(x) > 0$ ⟹ $f$ on **kasvav** selles piirkonnas
- $f'(x) < 0$ ⟹ $f$ on **kahanev**
- $f'(x) = 0$ ⟹ võimalik ekstreemum (maksimum või miinimum)

### 4.2 Ekstreemumid
**Teine tuletis:**
- $f''(x_0) > 0$ → **miinimum** punktis $x_0$
- $f''(x_0) < 0$ → **maksimum** punktis $x_0$

**Märgi muutuse meetod:**
Kui $f'$ muutub $+$ → $-$, siis on **maksimum**.
Kui $f'$ muutub $-$ → $+$, siis on **miinimum**.

### 4.3 Puutuja võrrand
Puutuja funktsiooni $f$ graafikul punktis $x_0$:

$$y = f(x_0) + f'(x_0)(x - x_0)$$

## 5. Lahendatud näited

**Näide 1.** Diferentseeri $f(x) = 3x^4 - 2x^2 + 5x - 7$.

$$f'(x) = 12x^3 - 4x + 5$$

**Näide 2.** Leia $f'(2)$, kui $f(x) = x^3 - 3x$.

$$f'(x) = 3x^2 - 3 \implies f'(2) = 3 \cdot 4 - 3 = 9$$

**Näide 3.** Leia funktsiooni $f(x) = x^3 - 6x^2 + 9x + 1$ ekstreemumid.

$$f'(x) = 3x^2 - 12x + 9 = 3(x^2 - 4x + 3) = 3(x-1)(x-3)$$

$f'(x) = 0 \implies x = 1$ või $x = 3$.

- $x = 1$: $f'$ muutub $+$ → $-$ → **lokaalne maksimum**, $f(1) = 1 - 6 + 9 + 1 = 5$
- $x = 3$: $f'$ muutub $-$ → $+$ → **lokaalne miinimum**, $f(3) = 27 - 54 + 27 + 1 = 1$

**Näide 4.** Leia puutuja $y = x^2$ graafikule punktis $x_0 = 2$.

$f(2) = 4$, $f'(x) = 2x$, $f'(2) = 4$.

$$y = 4 + 4(x - 2) = 4x - 4$$

## 6. Tüüpilised vead

- Konstandiga korrutamist unustatakse: $(5x^3)' = 15x^2$, mitte $3x^2$.
- Liitfunktsiooni puhul unustatakse ahela reegel: $(\sin 3x)' = \cos 3x \cdot 3$.
- Ekstreemumitingimus on $f'(x) = 0$, kuid see pole piisav — kontrollida tuleb märgi muutust!

## 7. Seos teiste teemadega

- Integraal on tuletise pöördtehteks.
- Füüsikas: kiirus = asukoha tuletis, kiirendus = kiiruse tuletis.
- Optimeerimisülesannetes otsitakse maksimum/miinimum.
