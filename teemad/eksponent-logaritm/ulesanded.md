# Eksponentfunktsioon ja logaritm — ülesanded

## 1. tase ⭐

**1.** Lahenda: $3^x = 81$.

<details><summary>Lahendus</summary>

$$3^x = 3^4 \implies x = 4$$

**Vastus:** $x = 4$.
</details>

---

**2.** Arvuta: $\log_2 32$.

<details><summary>Lahendus</summary>

$$\log_2 32 = \log_2 2^5 = 5$$

**Vastus:** $5$.
</details>

---

**3.** Lihtsusta: $\log_3 9 + \log_3 3$.

<details><summary>Lahendus</summary>

$$\log_3 9 + \log_3 3 = 2 + 1 = 3$$

**Vastus:** $3$.
</details>

---

**4.** Lahenda: $\lg(x + 1) = 2$.

<details><summary>Lahendus</summary>

$$x + 1 = 10^2 = 100 \implies x = 99$$

**Vastus:** $x = 99$.
</details>

---

## 2. tase ⭐⭐

**5.** Lahenda: $2^{2x} - 5 \cdot 2^x + 4 = 0$.

<details><summary>Lahendus</summary>

Asendus $t = 2^x$ (kus $t > 0$):

$$t^2 - 5t + 4 = 0 \implies (t-1)(t-4) = 0$$

$t = 1 \implies 2^x = 1 \implies x = 0$

$t = 4 \implies 2^x = 4 = 2^2 \implies x = 2$

**Vastus:** $x = 0$ või $x = 2$.
</details>

---

**6.** Lahenda: $\log_2(x-3) + \log_2(x+1) = 5$.

<details><summary>Lahendus</summary>

$$\log_2[(x-3)(x+1)] = 5 \implies (x-3)(x+1) = 32$$

$$x^2 - 2x - 3 = 32 \implies x^2 - 2x - 35 = 0$$

$$x = \frac{2 \pm \sqrt{4 + 140}}{2} = \frac{2 \pm 12}{2}$$

$x_1 = 7$, $x_2 = -5$

Kontroll: $x = -5$ → $\log_2(-8)$ — **ei sobi** (negatiivne argument).

$x = 7$: $\log_2 4 + \log_2 8 = 2 + 3 = 5$ ✓

**Vastus:** $x = 7$.
</details>

---

**7.** Eesti Energial on tuulepark. Tuulepargi toodang kasvab igal aastal $8\%$. Algtoodang on 120 GWh. Millal ületab toodang $200$ GWh?

<details><summary>Lahendus</summary>

$$120 \cdot 1{,}08^t > 200$$

$$1{,}08^t > \frac{200}{120} = \frac{5}{3}$$

$$t \cdot \ln 1{,}08 > \ln\frac{5}{3}$$

$$t > \frac{\ln(5/3)}{\ln 1{,}08} = \frac{0{,}5108}{0{,}0770} \approx 6{,}63$$

**Vastus:** $7$ aasta pärast (esimest korda ületab $7$. aastal).
</details>

---

## 3. tase ⭐⭐⭐ — PE-stiilis ülesanded

**8. (8p)** *(PE-tüüpi)* Tartu Ülikooli Teaduspark jälgib uue biokoloonia kasvu katselaboris. Algul on $N_0 = 500$ rakku. Kasvukiirus on kirjeldatud valemiga $N(t) = 500 \cdot 2^{t/4}$, kus $t$ on aeg tundides.

a) (2p) Mitu rakku on 12 tunni pärast?

b) (2p) Millal on rakkude arv $8000$?

c) (2p) Leia kasv 5. ja 6. tunni vahel (ehk $N(6) - N(5)$). Ümarenda lähimale täisarvuni.

d) (2p) Millisel hetkel kasvab rakkude arv kiirusega $100 \cdot \ln 2$ rakku tunnis? (Kasuta tuletist.)

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)**

$$N(12) = 500 \cdot 2^{12/4} = 500 \cdot 2^3 = 500 \cdot 8 = 4000 \text{ rakku}$$

**b)**

$$500 \cdot 2^{t/4} = 8000 \implies 2^{t/4} = 16 = 2^4 \implies \frac{t}{4} = 4 \implies t = 16 \text{ h}$$

**c)**

$$N(5) = 500 \cdot 2^{5/4} = 500 \cdot 2^{1{,}25} \approx 500 \cdot 2{,}378 \approx 1189$$

$$N(6) = 500 \cdot 2^{6/4} = 500 \cdot 2^{1{,}5} = 500 \cdot 2\sqrt{2} \approx 500 \cdot 2{,}828 \approx 1414$$

$$N(6) - N(5) \approx 1414 - 1189 = 225 \text{ rakku}$$

**d)** Kasutame tuletist:

$$N(t) = 500 \cdot 2^{t/4} = 500 \cdot e^{(t/4)\ln 2}$$

$$N'(t) = 500 \cdot e^{(t/4)\ln 2} \cdot \frac{\ln 2}{4} = \frac{500 \ln 2}{4} \cdot 2^{t/4} = 125 \ln 2 \cdot 2^{t/4}$$

Seadistame $N'(t) = 100 \ln 2$:

$$125 \ln 2 \cdot 2^{t/4} = 100 \ln 2 \implies 2^{t/4} = \frac{100}{125} = 0{,}8$$

$$\frac{t}{4} = \log_2 0{,}8 = \frac{\ln 0{,}8}{\ln 2} = \frac{-0{,}2231}{0{,}6931} \approx -0{,}322$$

$$t \approx -1{,}29 \text{ h}$$

*(See on negatiivne — tähendab, et sellest hetkest on kasv alati üle $100 \ln 2$ rakku/h.)*

---

**Hindamisskeem (8p):**

| Samm | Punktid |
|------|---------|
| a) $N(12) = 4000$ | 2 |
| b) Võrrandi lahendus $t = 16$ | 2 |
| c) Mõlemad väärtused arvutatud, vahe $\approx 225$ | 2 |
| d) Tuletis korrektne, võrrand ja lahendamine | 2 |

</details>

---

**9. (6p)** Lahenda võrrandisüsteem:

$$\begin{cases} 2\ln x + \ln y = 5 \\ \ln x - \ln y = 1 \end{cases}$$

a) (2p) Leia $\ln x$ ja $\ln y$ lineaarse süsteemina.

b) (2p) Leia $x$ ja $y$.

c) (2p) Kontrolli tulemust.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)** Tähistame $u = \ln x$, $v = \ln y$:

$$\begin{cases} 2u + v = 5 \\ u - v = 1 \end{cases}$$

Liidame: $3u = 6 \implies u = 2$

Asendame: $v = u - 1 = 1$

**b)**

$$\ln x = 2 \implies x = e^2 \approx 7{,}39$$

$$\ln y = 1 \implies y = e^1 = e \approx 2{,}72$$

**c)** Kontroll:

$2\ln e^2 + \ln e = 4 + 1 = 5$ ✓

$\ln e^2 - \ln e = 2 - 1 = 1$ ✓

---

**Hindamisskeem (6p):**

| Samm | Punktid |
|------|---------|
| a) Asendus ja süsteem $u,v$ kaudu | 1 |
| a) $u = 2$, $v = 1$ | 1 |
| b) $x = e^2$, $y = e$ | 2 |
| c) Kontroll mõlemas võrrandis | 2 |

</details>
