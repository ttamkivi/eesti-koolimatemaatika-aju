# Ruutvõrrand

**Klass:** 9. klass (põhikool) · Gümnaasium M2 (lai) / K2 (kitsas)
**Eelteadmised:** lineaarvõrrand, ruutjuur, korrutamise abivalemid

---

## Mis on ruutvõrrand?

Ruutvõrrand on võrrand, mille üldkuju on:

$$ax^2 + bx + c = 0, \quad a \neq 0$$

kus $a$, $b$, $c$ on reaalarvud (**kordajad**) ja $x$ on tundmatu.

**Näide:** $2x^2 - 5x + 3 = 0$ (siin $a=2$, $b=-5$, $c=3$)

Kui $a = 0$, siis pole tegu ruutvõrrandiga, vaid lineaarvõrrandiga.

---

## Ruutvõrrandi eriliigid

### 1. Taandatud ruutvõrrand
Kui $a = 1$:
$$x^2 + px + q = 0$$

### 2. Puudulik ruutvõrrand
Kui $b = 0$ või $c = 0$ (või mõlemad):

- $ax^2 + c = 0$ — lahenda ruutjuurega
- $ax^2 + bx = 0$ — too $x$ sulgude ette: $x(ax+b) = 0$

---

## Lahendivalem

Üldise ruutvõrrandi $ax^2 + bx + c = 0$ lahendid leiad valemiga:

$$\boxed{\; x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} \;}$$

Avaldist $b^2 - 4ac$ nimetatakse **diskriminandiks** ja tähistatakse tähega $D$:

$$D = b^2 - 4ac$$

### Diskriminant ütleb, mitu lahendit on:

| Diskriminant | Lahendite arv | Seletus |
|--------------|---------------|---------|
| $D > 0$ | 2 erinevat reaallahendit | Parabool lõikab $x$-telge kahes kohas |
| $D = 0$ | 1 lahend (kahekordne) | Parabool puudutab $x$-telge |
| $D < 0$ | Ei ole reaallahendit | Parabool ei lõika $x$-telge |

---

## Näide 1 — kaks lahendit

Lahenda $x^2 - 5x + 6 = 0$.

**Lahendus.** $a=1$, $b=-5$, $c=6$.

$$D = (-5)^2 - 4 \cdot 1 \cdot 6 = 25 - 24 = 1$$

$D > 0$, seega on kaks lahendit:

$$x_{1,2} = \frac{-(-5) \pm \sqrt{1}}{2 \cdot 1} = \frac{5 \pm 1}{2}$$

$$x_1 = \frac{5+1}{2} = 3, \quad x_2 = \frac{5-1}{2} = 2$$

**Vastus:** $x_1 = 3$, $x_2 = 2$.

---

## Näide 2 — üks lahend ($D = 0$)

Lahenda $x^2 - 6x + 9 = 0$.

**Lahendus.** $a=1$, $b=-6$, $c=9$.

$$D = 36 - 36 = 0$$

$$x = \frac{6}{2} = 3$$

**Vastus:** $x = 3$ (kahekordne lahend).

Märkus: vasakpool on täisruut: $x^2 - 6x + 9 = (x-3)^2$.

---

## Näide 3 — lahendit pole ($D < 0$)

Lahenda $x^2 + 2x + 5 = 0$.

**Lahendus.** $D = 4 - 20 = -16 < 0$.

**Vastus:** reaallahendeid pole.

---

## Näide 4 — puudulik ruutvõrrand

Lahenda $3x^2 - 12 = 0$.

**Lahendus.** Lihtsam on ilma lahendivalemita:

$$3x^2 = 12 \;\Rightarrow\; x^2 = 4 \;\Rightarrow\; x = \pm 2$$

**Vastus:** $x_1 = 2$, $x_2 = -2$.

---

## Viète'i teoreem

Kui ruutvõrrandil $ax^2 + bx + c = 0$ on lahendid $x_1$ ja $x_2$, siis:

$$x_1 + x_2 = -\frac{b}{a}, \qquad x_1 \cdot x_2 = \frac{c}{a}$$

**Taandatud juhul** ($a=1$, ehk $x^2 + px + q = 0$):

$$x_1 + x_2 = -p, \qquad x_1 \cdot x_2 = q$$

**Kasulik näpunäide:** mõnikord saab lahendid lihtsalt ära arvata. Näiteks $x^2 - 7x + 12 = 0$ — otsi kaks arvu, mille summa on $7$ ja korrutis $12$ → need on $3$ ja $4$.

---

## Tegurdamine

Kui ruutvõrrandil $ax^2+bx+c=0$ on lahendid $x_1, x_2$, siis avaldis tegurdub:

$$ax^2 + bx + c = a(x - x_1)(x - x_2)$$

**Näide.** $x^2 - 5x + 6 = (x-2)(x-3)$

---

## Kuidas lahendada — samm-sammult

1. **Vii võrrand kujule** $ax^2 + bx + c = 0$.
2. **Kirjuta välja** $a$, $b$, $c$.
3. **Arvuta diskriminant** $D = b^2 - 4ac$.
4. **Vaata märki:**
   - $D > 0$: kaks lahendit valemiga.
   - $D = 0$: üks lahend $x = -\frac{b}{2a}$.
   - $D < 0$: lahendeid pole.
5. **Kontrolli** (asenda lahendid tagasi võrrandisse).

---

## Tüüpilised vead

- Unustatakse **märk** $b$ ees (nt $b = -5$, mitte $5$).
- Valesti arvutatakse **$b^2$**, kui $b$ on negatiivne — peab olema alati positiivne.
- **Korrutatakse enne** jagamist: kirjuta $\frac{-b \pm \sqrt{D}}{2a}$ alati õigesti, $2a$ mitte $a$.
- Diskriminandi märk jäetakse tähelepanuta.

---

## Harjutus

Vaata [ülesanded.md](ulesanded.md) — seal on 12 ülesannet lahendustega.
