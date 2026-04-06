# Jadad ja piirväärtus — ülesanded

## 1. tase ⭐

**1.** Aritmeetilise jada esimene liige on $a_1 = 4$ ja samm $d = 3$. Leia $a_8$.

<details><summary>Lahendus</summary>

$$a_8 = 4 + 7 \cdot 3 = 4 + 21 = 25$$

**Vastus:** $a_8 = 25$.
</details>

---

**2.** Geomeetrilise jada esimene liige on $a_1 = 6$ ja kvoot $q = 2$. Leia $a_5$.

<details><summary>Lahendus</summary>

$$a_5 = 6 \cdot 2^4 = 6 \cdot 16 = 96$$

**Vastus:** $a_5 = 96$.
</details>

---

**3.** Leia piirväärtus: $\displaystyle\lim_{x \to 4} (x^2 - 3x + 1)$.

<details><summary>Lahendus</summary>

Funktsioon on pidev, seega asendame:

$$\lim_{x \to 4}(x^2 - 3x + 1) = 16 - 12 + 1 = 5$$

**Vastus:** $5$.
</details>

---

**4.** Leia lõpmatu geomeetrilise jada summa: $a_1 = 9$, $q = \dfrac{1}{3}$.

<details><summary>Lahendus</summary>

$$S = \frac{9}{1 - \tfrac{1}{3}} = \frac{9}{\tfrac{2}{3}} = \frac{27}{2} = 13{,}5$$

**Vastus:** $S = 13{,}5$.
</details>

---

## 2. tase ⭐⭐

**5.** Aritmeetilise jada liikmete summa $S_{20} = 390$. Esimene liige on $a_1 = 3$. Leia samm $d$ ja $a_{20}$.

<details><summary>Lahendus</summary>

$$S_{20} = \frac{20(a_1 + a_{20})}{2} = 10(3 + a_{20}) = 390$$

$$3 + a_{20} = 39 \implies a_{20} = 36$$

$$a_{20} = 3 + 19d = 36 \implies 19d = 33 \implies d = \frac{33}{19} \approx 1{,}74$$

**Vastus:** $a_{20} = 36$, $d = \dfrac{33}{19}$.
</details>

---

**6.** Leia piirväärtus: $\displaystyle\lim_{x \to -2} \dfrac{x^2 + 5x + 6}{x + 2}$.

<details><summary>Lahendus</summary>

Kuju $\dfrac{0}{0}$ — tegurdame:

$$x^2 + 5x + 6 = (x+2)(x+3)$$

$$\lim_{x \to -2} \frac{(x+2)(x+3)}{x+2} = \lim_{x \to -2}(x+3) = 1$$

**Vastus:** $1$.
</details>

---

**7.** Tallinna börsil on aktsia hind esimesel päeval $a_1 = 12$ eurot ja kasvab igal päeval $5\%$ võrra. Leia hind 10. päeval ja esimese 5 päeva hindade summa.

<details><summary>Lahendus</summary>

Geomeetriline jada, $q = 1{,}05$.

**10. päev:**

$$a_{10} = 12 \cdot 1{,}05^9 = 12 \cdot 1{,}551 \approx 18{,}61 \text{ €}$$

**Esimese 5 päeva summa:**

$$S_5 = \frac{12(1{,}05^5 - 1)}{1{,}05 - 1} = \frac{12(1{,}276 - 1)}{0{,}05} = \frac{12 \cdot 0{,}276}{0{,}05} = \frac{3{,}312}{0{,}05} = 66{,}24 \text{ €}$$

**Vastus:** 10. päeval $\approx 18{,}61$ €; esimese 5 päeva summa $\approx 66{,}24$ €.
</details>

---

## 3. tase ⭐⭐⭐ — PE-stiilis ülesanded

**8. (8p)** *(PE-tüüpi)* Eesti pensionifond kasutab kahe investeerimisskeemi võrdlemiseks järgmisi mudeleid. **Skeem A:** igal aastal lisatakse fondile $500$ eurot (aritmeetiline kasv). **Skeem B:** fond kasvab igal aastal $6\%$ võrra, algväärtus $5000$ eurot.

a) (2p) Skeem A: fondi suurus 20 aasta pärast, kui algul on $1000$ eurot ja igal aastal lisatakse $500$ eurot. (Kasuta aritmeetilise jada summat.)

b) (2p) Skeem B: fondi suurus 20 aasta pärast.

c) (2p) Kummal skeemil on 20 aasta pärast suurem fond? Mitu eurot vahet on?

d) (2p) Mitme aasta pärast ületab skeem B summa $15\,000$ eurot? (Kasuta logaritmi.)

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)** Skeem A on aritmeetiline jada: $a_1 = 1000 + 500 = 1500$ (esimese aasta lõpus), $d = 500$.

Fondi suurus 20 aasta pärast = $a_{20} = 1000 + 20 \cdot 500 = 11\,000$ eurot.

*(Kui vaadata lisamaksete kogusummat: $S_{20} = \frac{20 \cdot 500 \cdot 21}{2}$... Lihtsam: algus $1000 + 20 \times 500 = 11\,000$.)*

**b)** Skeem B, geomeetriline kasv:

$$A_{20} = 5000 \cdot 1{,}06^{20} = 5000 \cdot 3{,}207 \approx 16\,035 \text{ €}$$

**c)** $16\,035 - 11\,000 = 5\,035$ eurot — skeem B on $5035$ eurot suurem.

**d)** $5000 \cdot 1{,}06^t > 15\,000$

$$1{,}06^t > 3 \implies t \cdot \ln 1{,}06 > \ln 3$$

$$t > \frac{\ln 3}{\ln 1{,}06} = \frac{1{,}099}{0{,}0583} \approx 18{,}85$$

**Vastus:** $19$ aasta pärast ületab skeem B summa $15\,000$ eurot.

---

**Hindamisskeem (8p):**

| Samm | Punktid |
|------|---------|
| a) Skeem A, $11\,000$ € | 2 |
| b) Skeem B, $1{,}06^{20}$ arvutus, $\approx 16\,035$ € | 2 |
| c) Vahe ja järeldus | 2 |
| d) Logaritmvõrrand ja tulemus $t = 19$ | 2 |

</details>

---

**9. (6p)** Perioodilise murru $0{,}\overline{54} = 0{,}545454\ldots$ teisendamine harilikuks murruks lõpmatu geomeetrilise jada kaudu.

a) (2p) Kirjuta $0{,}\overline{54}$ lõpmatu geomeetrilise jadana ($a_1$ ja $q$ leidmine).

b) (2p) Leia lõpmatu summa valemiga.

c) (2p) Kontrolli tulemust (murru korrutamine).

<details><summary>Täislahendus ja hindamisskeem</summary>

**a)**

$$0{,}545454\ldots = 0{,}54 + 0{,}0054 + 0{,}000054 + \ldots$$

Esimene liige: $a_1 = 0{,}54 = \dfrac{54}{100}$

Kvoot: $q = \dfrac{0{,}0054}{0{,}54} = 0{,}01 = \dfrac{1}{100}$

Kuna $|q| = 0{,}01 < 1$, summa koondub.

**b)**

$$S = \frac{a_1}{1 - q} = \frac{\tfrac{54}{100}}{1 - \tfrac{1}{100}} = \frac{\tfrac{54}{100}}{\tfrac{99}{100}} = \frac{54}{99} = \frac{6}{11}$$

**c)** Kontroll: $\dfrac{6}{11} = 0{,}5454\ldots$ ✓

(Jagades: $6 \div 11 = 0{,}545454\ldots$)

---

**Hindamisskeem (6p):**

| Samm | Punktid |
|------|---------|
| a) $a_1 = 54/100$ ja $q = 1/100$ | 2 |
| b) Summavalemi rakendamine, $6/11$ | 2 |
| c) Kontroll | 2 |

</details>
