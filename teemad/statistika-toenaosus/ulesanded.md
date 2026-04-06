# Statistika ja tõenäosus — ülesanded

## 1. tase ⭐

**1.** Matemaatika kontrolltöö tulemused: $4, 5, 3, 5, 4, 5, 2, 4$. Leia aritmeetiline keskmine, mediaan ja mood.

<details><summary>Lahendus</summary>

**Aritmeetiline keskmine:**

$$\bar{x} = \frac{4+5+3+5+4+5+2+4}{8} = \frac{32}{8} = 4$$

**Mediaan** (järjestame kasvavalt): $2, 3, 4, 4, 4, 5, 5, 5$

Kaheksa elemendi keskmine kaks: $\dfrac{4+4}{2} = 4$

**Mood:** $4$ ja $5$ (mõlemad esinevad 3 korda)

</details>

---

**2.** Visatakse regulaarne täring. Tõenäosus saada:
a) arv $6$; b) paarisarv; c) arv, mis on väiksem kui $3$.

<details><summary>Lahendus</summary>

Kõik võrdselt tõenäolised tulemused: $\{1, 2, 3, 4, 5, 6\}$, kokku $6$.

a) $P(6) = \dfrac{1}{6}$

b) Paarisarvud: $\{2, 4, 6\}$. $P = \dfrac{3}{6} = \dfrac{1}{2}$

c) Väiksemad kui $3$: $\{1, 2\}$. $P = \dfrac{2}{6} = \dfrac{1}{3}$

</details>

---

**3.** Kotis on $5$ punast ja $3$ sinist palli. Võetakse juhuslikult üks. Tõenäosus saada sinine?

<details><summary>Lahendus</summary>

Kokku $5 + 3 = 8$ palli.

$$P(\text{sinine}) = \frac{3}{8}$$

</details>

---

## 2. tase ⭐⭐

**4.** Andmed hüppepikkustest (cm): $480, 502, 495, 510, 488, 502, 476, 510, 502, 495$.

a) Leia aritmeetiline keskmine, mediaan ja mood.
b) Leia andmete haare.

<details><summary>Lahendus</summary>

**a)** Sorteeritud: $476, 480, 488, 495, 495, 502, 502, 502, 510, 510$

Aritmeetiline keskmine:

$$\bar{x} = \frac{476+480+488+495+495+502+502+502+510+510}{10} = \frac{4960}{10} = 496 \text{ cm}$$

Mediaan (10 elementi, keskmised 5. ja 6.):

$$\text{mediaan} = \frac{495+502}{2} = 498{,}5 \text{ cm}$$

Mood: $502$ (esineb 3 korda)

**b)** Haare: $510 - 476 = 34$ cm

</details>

---

**5.** Kaks mündiviskamist järjest. Koosta kõigi võimalike tulemuste tabel ja leia:

a) Tõenäosus, et mõlemad on kulled.
b) Tõenäosus, et täpselt üks on kull.
c) Tõenäosus, et vähemalt üks on kull.

<details><summary>Lahendus</summary>

Kõik tulemused: $KK, KK_s, K_sK, K_sK_s$ — kokku $4$ võrdset võimalust.

a) $P(KK) = \dfrac{1}{4}$

b) $P(\text{täpselt 1}) = \dfrac{2}{4} = \dfrac{1}{2}$

c) Vastandsündmus — kumbagi kullu: $P = \dfrac{1}{4}$

$$P(\text{vähemalt 1}) = 1 - \frac{1}{4} = \frac{3}{4}$$

</details>

---

**6.** Kahe täringu viskamisel — tõenäosus, et summa on täpselt $7$?

<details><summary>Lahendus</summary>

Kõik tulemused: $6 \times 6 = 36$.

Soodsad paarid (summa $= 7$):

$(1,6), (2,5), (3,4), (4,3), (5,2), (6,1)$ — kokku $6$.

$$P = \frac{6}{36} = \frac{1}{6}$$

</details>

---

## 3. tase ⭐⭐⭐ — PE-stiilis ülesanded

**7. (8p)** *(PE-tüüpi)* Eesti põhikooliõpetajate kohta on koostatud tabel.

| Vanuserühm | Mehed (%) | Naised (%) |
|-----------|----------|-----------|
| Alla 30 | 15 | 10 |
| 30–50 | 44 | 44 |
| 51–60 | 24 | 30 |
| Üle 60 | 17 | 16 |

Kokku on $14\,905$ õpetajat: $2121$ meest ja $12\,784$ naist.

a) (2p) Kui suur osa kõigist õpetajatest on naised? (%-des, ühe kümnendiku täpsusega)

b) (3p) Mitu õpetajat on vanuses $51$ aastat ja vanem? (lähim täisarv)

c) (3p) Alla $30$-aastaseid on meeste seas proportsionaalselt rohkem. Mitu korda rohkem? Arvuta mõlemad absoluutarvud.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a) Naiste osakaal:**

$$\frac{12\,784}{14\,905} \approx 0{,}8577 \approx \boxed{85{,}8\%}$$

**b) Üle 51-aastased:**

Mehed $(51+)$: $(24\% + 17\%) \cdot 2121 = 0{,}41 \cdot 2121 \approx 870$

Naised $(51+)$: $(30\% + 16\%) \cdot 12\,784 = 0{,}46 \cdot 12\,784 \approx 5881$

$$\boxed{870 + 5881 = 6751 \text{ õpetajat}}$$

**c) Alla 30-aastased:**

Mehed alla $30$: $15\% \cdot 2121 \approx 318$

Naised alla $30$: $10\% \cdot 12\,784 \approx 1278$

Proportsionaalselt: meeste seas $15\%$, naiste seas $10\%$ → meeste seas on **$1{,}5$ korda** rohkem (protsentuaalselt).

Absoluutarvult on naisi rohkem: $1278 > 318$.

---

**Hindamisskeem (8p):**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Jagamine ja protsendiks teisendamine | 1 |
| a) | Vastus $85{,}8\%$ | 1 |
| b) | Meeste summa õige | 1 |
| b) | Naiste summa õige | 1 |
| b) | Koguarv $\approx 6751$ | 1 |
| c) | Mõlemad absoluutarvud | 1 |
| c) | Proportsionaalne võrdlus (1,5 korda) | 1 |
| c) | Selgitus absoluutarvu vs proportsionaalsuse erinevuse kohta | 1 |

</details>

---

**8. (6p)** Klassis on $20$ õpilast. Nende ujumistulemused (m) on:

$$38, 42, 45, 47, 50, 50, 52, 55, 55, 55, 57, 60, 60, 62, 65, 68, 70, 72, 75, 80$$

a) (1p) Leia mediaan.

b) (2p) Leia alumine ja ülemine kvartiil ($Q_1$ ja $Q_3$).

c) (1p) Leia kvartiilhaare $IQR = Q_3 - Q_1$.

d) (2p) Kas tulemus $80$ m on erand (outlier)? Kasuta reegleid $> Q_3 + 1{,}5 \cdot IQR$ ja $< Q_1 - 1{,}5 \cdot IQR$.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a) Mediaan** (20 elementi, 10. ja 11. keskväärtus):

$$\text{mediaan} = \frac{55 + 57}{2} = 56 \text{ m}$$

**b) Kvartiilid:**

Alumine pool ($1$–$10$): $38, 42, 45, 47, 50, 50, 52, 55, 55, 55$

$$Q_1 = \frac{50+50}{2} = 50 \text{ m}$$

Ülemine pool ($11$–$20$): $57, 60, 60, 62, 65, 68, 70, 72, 75, 80$

$$Q_3 = \frac{65+68}{2} = 66{,}5 \text{ m}$$

**c)** $IQR = 66{,}5 - 50 = 16{,}5$ m

**d)** Ülemine piir: $Q_3 + 1{,}5 \cdot IQR = 66{,}5 + 24{,}75 = 91{,}25$ m

Alumine piir: $Q_1 - 1{,}5 \cdot IQR = 50 - 24{,}75 = 25{,}25$ m

Kuna $80 < 91{,}25$, **ei ole** $80$ m erand.

---

**Hindamisskeem (6p):**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Mediaan $56$ m | 1 |
| b) | $Q_1 = 50$ m | 1 |
| b) | $Q_3 = 66{,}5$ m | 1 |
| c) | $IQR = 16{,}5$ m | 1 |
| d) | Ülemine piir arvutus | 1 |
| d) | Järeldus $80$ m kohta | 1 |

</details>

---

**9. (6p)** Korvpallitreening: $10$ vabaviskest tabas Jaanus $7$. Mitu korda peab ta viskama, et tema tabavuse keskmine tõuseks $75\%$-ni?

*(Eeldame, et kõik järgmised viskeid tabab.)*

a) (2p) Koosta võrrand.

b) (2p) Lahenda võrrand.

c) (2p) Kontrolli vastust.

<details><summary>Täislahendus ja hindamisskeem</summary>

**a) Võrrand:**

Olgu täiendavaid viskeid $n$ (kõik tabavad). Kokku visked: $10 + n$, tabamused: $7 + n$.

$$\frac{7+n}{10+n} = 0{,}75$$

**b) Lahendus:**

$$7 + n = 0{,}75(10 + n)$$
$$7 + n = 7{,}5 + 0{,}75n$$
$$0{,}25n = 0{,}5$$
$$n = 2$$

**c) Kontroll:**

$$\frac{7+2}{10+2} = \frac{9}{12} = 0{,}75 = 75\% \checkmark$$

**Vastus:** Jaanus peab lisaks viskama $2$ vabaviset.

---

**Hindamisskeem (6p):**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Murdvõrrand $\frac{7+n}{10+n} = 0{,}75$ | 2 |
| b) | Lahendus $n = 2$ | 2 |
| c) | Kontrollarvutus | 2 |

</details>
