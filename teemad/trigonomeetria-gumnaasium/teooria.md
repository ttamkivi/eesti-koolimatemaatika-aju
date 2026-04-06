# Trigonomeetria (gümnaasium)

## 1. Trigonomeetrilised funktsioonid

Üldistame trigonomeetriat kõikidele nurkadele ja reaalarvudele.

### Ühikrinkel

Punktile $(\cos\alpha,\; \sin\alpha)$ ühikringel vastavus nurgaga $\alpha$.

$$\sin^2\alpha + \cos^2\alpha = 1 \quad \text{(Pythagorase teoorem)}$$

$$\tan\alpha = \frac{\sin\alpha}{\cos\alpha}, \quad \cot\alpha = \frac{\cos\alpha}{\sin\alpha}$$

## 2. Põhiväärtused

| $\alpha$ | $0°$ | $30°$ | $45°$ | $60°$ | $90°$ | $180°$ | $270°$ | $360°$ |
|----------|-------|--------|--------|--------|--------|---------|---------|---------|
| $\sin\alpha$ | $0$ | $\frac{1}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ | $1$ | $0$ | $-1$ | $0$ |
| $\cos\alpha$ | $1$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$ | $0$ | $-1$ | $0$ | $1$ |
| $\tan\alpha$ | $0$ | $\frac{1}{\sqrt{3}}$ | $1$ | $\sqrt{3}$ | — | $0$ | — | $0$ |

## 3. Taandamisvalemid

**Teisendamine $90°$ ja $180°$ kaudu:**

$$\sin(90° - \alpha) = \cos\alpha, \quad \cos(90° - \alpha) = \sin\alpha$$

$$\sin(180° - \alpha) = \sin\alpha, \quad \cos(180° - \alpha) = -\cos\alpha$$

$$\sin(-\alpha) = -\sin\alpha, \quad \cos(-\alpha) = \cos\alpha$$

## 4. Liitmisvalemid

$$\sin(\alpha \pm \beta) = \sin\alpha\cos\beta \pm \cos\alpha\sin\beta$$

$$\cos(\alpha \pm \beta) = \cos\alpha\cos\beta \mp \sin\alpha\sin\beta$$

$$\tan(\alpha \pm \beta) = \frac{\tan\alpha \pm \tan\beta}{1 \mp \tan\alpha\tan\beta}$$

## 5. Kaksiknurga valemid

$$\sin 2\alpha = 2\sin\alpha\cos\alpha$$

$$\cos 2\alpha = \cos^2\alpha - \sin^2\alpha = 1 - 2\sin^2\alpha = 2\cos^2\alpha - 1$$

## 6. Trigonomeetrilised võrrandid

### $\sin x = a$
$$x = \arcsin a + 2\pi n \quad \text{või} \quad x = \pi - \arcsin a + 2\pi n, \quad n \in \mathbb{Z}$$

### $\cos x = a$
$$x = \pm\arccos a + 2\pi n, \quad n \in \mathbb{Z}$$

### $\tan x = a$
$$x = \arctan a + \pi n, \quad n \in \mathbb{Z}$$

**Kraadides** (kui ülesandes nõutakse):
- $\sin x = \frac{1}{2}$: $x = 30° + 360°n$ või $x = 150° + 360°n$

## 7. Sinuslause ja koosinuslause

**Sinuslause:**
$$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R$$

kus $R$ on ümberringjoone raadius.

**Koosinuslause:**
$$a^2 = b^2 + c^2 - 2bc\cos A$$

$$\cos A = \frac{b^2 + c^2 - a^2}{2bc}$$

## 8. Kolmnurga pindala

$$S = \frac{1}{2}ab\sin C$$

## 9. Trigonomeetriliste funktsioonide graafikud

**$y = \sin x$:** periood $2\pi$, amplituud $1$, nullkohad $0, \pi, 2\pi, \ldots$

**$y = A\sin(Bx + C) + D$:**
- Amplituud: $|A|$
- Periood: $\dfrac{2\pi}{|B|}$
- Nihkub horisontaalselt: $-C/B$
- Nihkub vertikaalselt: $D$

## 10. Lahendatud näited

**Näide 1.** Lahenda $\sin x = \dfrac{\sqrt{3}}{2}$, $x \in [0°;\; 360°]$.

$$x = 60° \quad \text{või} \quad x = 180° - 60° = 120°$$

**Näide 2.** Kolmnurgas on $a = 5$, $b = 7$, $C = 60°$. Leia $c$.

$$c^2 = 25 + 49 - 2 \cdot 5 \cdot 7 \cdot \cos 60° = 74 - 35 = 39$$
$$c = \sqrt{39} \approx 6{,}24$$

**Näide 3.** Leia kolmnurga pindala, kui kaks külge on $a = 6$ ja $b = 8$ ning nendevaheline nurk $\gamma = 30°$.

$$S = \frac{1}{2} \cdot 6 \cdot 8 \cdot \sin 30° = \frac{1}{2} \cdot 48 \cdot \frac{1}{2} = 12$$

## 11. Tüüpilised vead

- Kraadide ja radiaanide segamine — kontrolli, mida ülesanne nõuab.
- $\sin x = a$ korral on **kaks** lahendit perioodis, mitte üks.
- $\cos^2 + \sin^2 = 1$ — mitte $\cos + \sin = 1$.
- Sinuslause puhul: $\dfrac{a}{\sin A}$, mitte $\dfrac{\sin A}{a}$.
