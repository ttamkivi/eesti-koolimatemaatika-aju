# Tõenäosus ja statistika — Eksamiülesanded

**Teema:** Kombinatoorika, klassikaline tõenäosus, statistilised karakteristikud, andmete analüüs  
**Tase:** I tase (lihtne), II tase (keskmine), III tase (raske)

---

## I TASE — Algtaseme ülesanded

### Ülesanne 1. Klassikaline tõenäosus

Mündi visatakse üks kord. Mis on tõenäosus, et tuleb pead?

<details>
<summary>Lahendus</summary>

**Samm 1:** Mündi visamisel on kaks võimalikku tulemust: pead või kiri.

**Samm 2:** Pead tuleb täpselt ühel viisil.

**Samm 3:** Klassikaline tõenäosus:
$$P(\text{pead}) = \frac{\text{soodsate tulemuste arv}}{\text{kõigi tulemuste arv}} = \frac{1}{2}$$

**Vastus:** Tõenäosus on $\frac{1}{2}$ ehk 0,5 ehk 50%.

</details>

---

### Ülesanne 2. Kombinatoorika — permutatsioonid

Mitu erinevat 3-kohaline numbri saab moodustada numbritest 1, 2, 3?

<details>
<summary>Lahendus</summary>

**Samm 1:** Kõik kolm numbrit peavad olema erinevad, nii et see on permutatsioon.

**Samm 2:** Permutatsioonide arv:
$$P_3 = 3! = 3 \times 2 \times 1 = 6$$

**Samm 3:** Loetleme: 123, 132, 213, 231, 312, 321

**Vastus:** Võib moodustada 6 erinevat numbritega komplekti.

</details>

---

### Ülesanne 3. Keskväärtus

Andmed: 2, 4, 6, 8. Arvuta keskväärtus.

<details>
<summary>Lahendus</summary>

**Samm 1:** Keskväärtuse valem:
$$\bar{x} = \frac{x_1 + x_2 + ... + x_n}{n}$$

**Samm 2:** Asenda andmed:
$$\bar{x} = \frac{2 + 4 + 6 + 8}{4} = \frac{20}{4} = 5$$

**Vastus:** Keskväärtus on 5.

</details>

---

### Ülesanne 4. Sagedus ja suhteline sagedus

Katsest saadi andmed: vale, õige, õige, vale, õige. Mis on õigete vastuste suhteline sagedus?

<details>
<summary>Lahendus</summary>

**Samm 1:** Loenda õigete vastuste arv: 3

**Samm 2:** Kogu katse arv: 5

**Samm 3:** Suhteline sagedus:
$$f = \frac{\text{vaadeldava sündmuse arv}}{\text{katsete arv}} = \frac{3}{5} = 0,6$$

**Vastus:** Õigete vastuste suhteline sagedus on 0,6 ehk 60%.

</details>

---

### Ülesanne 5. Kahe sõltumatu sündmuse tõenäosus

Kahe mündi visatakse üks kord. Mis on tõenäosus, et mõlemad näitavad pead?

<details>
<summary>Lahendus</summary>

**Samm 1:** Ühe mündi puhul: $P(\text{pead}) = \frac{1}{2}$

**Samm 2:** Sõltumatute sündmuste tõenäosus:
$$P(A \cap B) = P(A) \times P(B)$$

**Samm 3:** Asenda:
$$P(\text{mõlemad pead}) = \frac{1}{2} \times \frac{1}{2} = \frac{1}{4}$$

**Vastus:** Tõenäosus on $\frac{1}{4}$ ehk 0,25 ehk 25%.

</details>

---

## II TASE — Keskmise taseme ülesanded

### Ülesanne 6. Kombinaatorika — kombinatsioonid

Klassist 25 õpilasest tuleb valida 3-liikne komitee. Mitu erinevat komitieed saab moodustada?

<details>
<summary>Lahendus</summary>

**Samm 1:** Komiteen järjekord ei ole oluline, seega see on kombinatsioon.

**Samm 2:** Kombinatsioonide valem:
$$C_n^k = \frac{n!}{k!(n-k)!}$$

**Samm 3:** Arvuta:
$$C_{25}^3 = \frac{25!}{3! \times 22!} = \frac{25 \times 24 \times 23}{3 \times 2 \times 1} = \frac{13800}{6} = 2300$$

**Vastus:** Saab moodustada 2300 erinevat komitieed.

</details>

---

### Ülesanne 7. Hajuvus (dispersioon)

Andmed: 1, 2, 3, 4, 5. Arvuta dispersioon.

<details>
<summary>Lahendus</summary>

**Samm 1:** Leia keskväärtus:
$$\bar{x} = \frac{1 + 2 + 3 + 4 + 5}{5} = 3$$

**Samm 2:** Arvuta ruutu tõstetud erinevused:
- $(1 - 3)^2 = 4$
- $(2 - 3)^2 = 1$
- $(3 - 3)^2 = 0$
- $(4 - 3)^2 = 1$
- $(5 - 3)^2 = 4$

**Samm 3:** Dispersioon:
$$\sigma^2 = \frac{4 + 1 + 0 + 1 + 4}{5} = \frac{10}{5} = 2$$

**Vastus:** Dispersioon on 2.

</details>

---

### Ülesanne 8. Tingimuslik tõenäosus

Kaardipakist (52 kaardi) võetakse üks kaart. Mis on tõenäosus, et see on patu jäägid, arvestades, et see on must kaart?

<details>
<summary>Lahendus</summary>

**Samm 1:** Must kaarte on 26 (patud ja treffid).

**Samm 2:** Patu jäägieid on 13.

**Samm 3:** Tingimuslik tõenäosus:
$$P(\text{patu jäägid | must kaart}) = \frac{13}{26} = \frac{1}{2}$$

**Vastus:** Tõenäosus on $\frac{1}{2}$ ehk 0,5 ehk 50%.

</details>

---

### Ülesanne 9. Bernoulli test

Õpilane teeb katses 4 küsimust, millest igaühe õige vastuse tõenäosus on 0,5 (juhuslik valimine). Mis on tõenäosus, et ta vastab õigesti täpselt 3 küsimusele?

<details>
<summary>Lahendus</summary>

**Samm 1:** Bernoulli valemi kasutamine:
$$P(X = k) = C_n^k \cdot p^k \cdot (1-p)^{n-k}$$

**Samm 2:** Andmed: $n = 4$, $k = 3$, $p = 0,5$

**Samm 3:** Kombinatsioon:
$$C_4^3 = \frac{4!}{3! \times 1!} = 4$$

**Samm 4:** Arvuta:
$$P(X = 3) = 4 \times 0,5^3 \times 0,5^1 = 4 \times 0,125 \times 0,5 = 0,25$$

**Vastus:** Tõenäosus on 0,25 ehk 25%.

</details>

---

## III TASE — Kõrgema taseme ülesanded

### Ülesanne 10. Normaaljaotus

Õpilaste testide skoorid on normaaljaotusega keskväärtusega 70 ja standardhälbega 10. Arvuta tõenäosus, et juhuslikult valitud õpilase skoor on 80-100.

<details>
<summary>Lahendus</summary>

**Samm 1:** Normaliseerida väärtused (z-skoor):
$$z = \frac{x - \mu}{\sigma}$$

**Samm 2:** Alumine piir ($x = 80$):
$$z_1 = \frac{80 - 70}{10} = 1$$

**Samm 3:** Ülemine piir ($x = 100$):
$$z_2 = \frac{100 - 70}{10} = 3$$

**Samm 4:** Normaaljaotuse tabelitest või funktsioonidest:
- $P(Z \leq 1) \approx 0,8413$
- $P(Z \leq 3) \approx 0,9987$

**Samm 5:** Tõenäosus:
$$P(80 \leq X \leq 100) = P(Z \leq 3) - P(Z \leq 1) = 0,9987 - 0,8413 = 0,1574$$

**Vastus:** Tõenäosus on ligikaudu 0,1574 ehk 15,74%.

</details>

---

### Ülesanne 11. Andmete analüüs ja järeldused

Klassis toimub testimine. Hasil: 60, 70, 75, 80, 85, 90. Analüüsi andmeid ja tee järeldused.

<details>
<summary>Lahendus</summary>

**Samm 1:** Keskväärtus:
$$\bar{x} = \frac{60 + 70 + 75 + 80 + 85 + 90}{6} = \frac{460}{6} \approx 76,67$$

**Samm 2:** Mediaan (6 andmepunkti puhul):
$$\text{Mediaan} = \frac{75 + 80}{2} = 77,5$$

**Samm 3:** Mood: puudub (kõik väärtused esinevad ühe korra)

**Samm 4:** Ulatus:
$$\text{Ulatus} = 90 - 60 = 30$$

**Samm 5:** Standardhälve (ligikaudne):
$$\sigma \approx 10,5$$

**Järeldused:**
- Keskmiselt saavutavad õpilased punkti ligikaudu 76-77
- Andmed on üsna lahti, standardhälve näitab märgatavat varieerumist
- Parim sooritaja sai 90, halvim 60
- Tulemused jagunevad üsna ühtlaselt

**Vastus:** Klass näitab mitmekesiseid tulemusi, keskväärtusega ligikaudu 76,67 punkti.

</details>

---

Ülesanded on soovituslik lahendamisjärjekord:
1. Alusta I tasemega (harjutamiseks)
2. Jätka II tasemega (eksamiks valmistumiseks)
3. Lahenda III tase (optimaalseks soorituseks)

