---
title: "Harjutusülesanded 1"
weight: 3
---

# Harjutusülesanded 1 — Laia matemaatika riigieksami stiil

> **12 ülesannet** · Ülesanded 1–4: **5 punkti** · Ülesanded 5–12: **10 punkti** · Kokku: **100 punkti**

---

## Ülesanne 1 (5 punkti) — Algebraline lihtsustamine

Lihtsusta avaldis ja leia selle väärtus, kui $a = 4$:

$$A = \frac{a^{3/2} - a^{1/2}}{a - 1} \cdot \sqrt{a}$$

<details>
<summary>📋 Täislahendus</summary>

**Samm 1: Tegurdame lugeja**

$$a^{3/2} - a^{1/2} = a^{1/2}(a - 1)$$

**Samm 2: Lihtsustame murdavaldist**

$$\frac{a^{1/2}(a-1)}{a-1} \cdot \sqrt{a} = a^{1/2} \cdot a^{1/2} = a$$

**Samm 3: Leiame väärtuse $a = 4$ korral**

$$A = 4$$

**Vastus:** $A = 4$

</details>

| Tegevus | Punktid |
|---------|---------|
| Lugeja õige tegurdamine | 2 p |
| Avaldise lihtsustamine $A = a$ | 2 p |
| Väärtuse leidmine | 1 p |

---

## Ülesanne 2 (5 punkti) — Trigonomeetriline võrrand

Lahenda võrrand vahemikus $[0°; 360°)$:

$$2\sin^2 x - \sin x - 1 = 0$$

<details>
<summary>📋 Täislahendus</summary>

**Samm 1: Asendame $t = \sin x$**

$$2t^2 - t - 1 = 0$$

**Samm 2: Lahendame ruutvõrrandi**

Diskriminant: $D = 1 + 8 = 9$

$$t_1 = \frac{1 + 3}{4} = 1, \quad t_2 = \frac{1 - 3}{4} = -\frac{1}{2}$$

**Samm 3: Tagasi trigonomeetriale**

*Juhul $\sin x = 1$:*
$$x = 90°$$

*Juhul $\sin x = -\frac{1}{2}$:*
$$x = 180° + 30° = 210° \quad \text{või} \quad x = 360° - 30° = 330°$$

**Vastus:** $x \in \{90°;\ 210°;\ 330°\}$

</details>

| Tegevus | Punktid |
|---------|---------|
| Asendamine ja ruutvõrrandi kirjutamine | 1 p |
| Mõlemad juurte väärtused | 2 p |
| Kõik kolm lahendit vahemikus | 2 p |

---

## Ülesanne 3 (5 punkti) — Logaritmvõrrand

Lahenda võrrand (kontrolli ODA):

$$\log_2(x + 3) + \log_2(x - 1) = 3$$

<details>
<summary>📋 Täislahendus</summary>

**Samm 1: ODA tingimused**

$$x + 3 > 0 \Rightarrow x > -3$$
$$x - 1 > 0 \Rightarrow x > 1$$

ODA: $x > 1$

**Samm 2: Rakendame logaritmi reegleid**

$$\log_2\bigl[(x+3)(x-1)\bigr] = 3$$

$$(x+3)(x-1) = 2^3 = 8$$

**Samm 3: Lahendame ruutvõrrandi**

$$x^2 + 2x - 3 = 8$$
$$x^2 + 2x - 11 = 0$$

$$x = \frac{-2 \pm \sqrt{4 + 44}}{2} = \frac{-2 \pm 4\sqrt{3}}{2} = -1 \pm 2\sqrt{3}$$

**Samm 4: ODA kontroll**

$x_1 = -1 + 2\sqrt{3} \approx 2{,}46 > 1$ ✓

$x_2 = -1 - 2\sqrt{3} \approx -4{,}46 < 1$ ✗ (ei kuulu ODA-sse)

**Vastus:** $x = -1 + 2\sqrt{3}$

</details>

| Tegevus | Punktid |
|---------|---------|
| ODA kirjutamine | 1 p |
| Logaritmi reeglite rakendamine ja võrrandi kirjutamine | 1 p |
| Ruutvõrrandi lahendamine | 2 p |
| ODA kontroll ja lõppvastus | 1 p |

---

## Ülesanne 4 (5 punkti) — Tõenäosus

Jaanil on sahtlis 12 patareid, millest 4 on tühjad. Ta võtab pimedas juhuslikult 3 patareid.

**(a)** Leia tõenäosus, et kõik 3 patareid on täis.

**(b)** Leia tõenäosus, et täpselt 1 patarei on tühi.

<details>
<summary>📋 Täislahendus</summary>

**Kõigi võimaluste arv:**

$$\binom{12}{3} = \frac{12 \cdot 11 \cdot 10}{6} = 220$$

**Osa (a): Kõik 3 täis (8 täit patareid)**

$$\binom{8}{3} = \frac{8 \cdot 7 \cdot 6}{6} = 56$$

$$P(\text{kõik täis}) = \frac{56}{220} = \frac{14}{55} \approx 0{,}255$$

**Osa (b): Täpselt 1 tühi**

$$\binom{4}{1} \cdot \binom{8}{2} = 4 \cdot 28 = 112$$

$$P(\text{täpselt 1 tühi}) = \frac{112}{220} = \frac{28}{55} \approx 0{,}509$$

</details>

| Tegevus | Punktid |
|---------|---------|
| Kõigi võimaluste arv $\binom{12}{3} = 220$ | 1 p |
| Osa (a): soodsate arv ja tõenäosus | 2 p |
| Osa (b): soodsate arv ja tõenäosus | 2 p |

---

## Ülesanne 5 (10 punkti) — Funktsiooni analüüs

Olgu antud funktsioon $f(x) = x^3 - 6x^2 + 9x + 1$.

**(a)** Leia funktsiooni kasvamis- ja kahanemispiirkonnad.

**(b)** Leia lokaalsed ekstreemumid.

**(c)** Kirjuta punktis $x = 0$ tõmmatud puutuja võrrand.

<details>
<summary>📋 Täislahendus</summary>

**Samm 1: Tuletis**

$$f'(x) = 3x^2 - 12x + 9 = 3(x^2 - 4x + 3) = 3(x-1)(x-3)$$

**Samm 2: Kriitilised punktid**

$f'(x) = 0 \Rightarrow x = 1$ või $x = 3$

**Samm 3: Märgiskeem**

| Vahemik | $(x-1)$ | $(x-3)$ | $f'(x)$ | $f$ |
|---------|---------|---------|---------|-----|
| $x < 1$ | $-$ | $-$ | $+$ | ↗ kasvab |
| $1 < x < 3$ | $+$ | $-$ | $-$ | ↘ kahaneb |
| $x > 3$ | $+$ | $+$ | $+$ | ↗ kasvab |

**Osa (a):** Kasvab: $(-\infty; 1)$ ja $(3; +\infty)$. Kahaneb: $(1; 3)$.

**Osa (b):**
$$f(1) = 1 - 6 + 9 + 1 = 5 \quad \Rightarrow \text{lokaalne maksimum } (1;\, 5)$$
$$f(3) = 27 - 54 + 27 + 1 = 1 \quad \Rightarrow \text{lokaalne miinimum } (3;\, 1)$$

**Osa (c): Puutuja $x = 0$ kohal**

$$f(0) = 1, \quad f'(0) = 9$$

$$y = 9x + 1$$

</details>

| Tegevus | Punktid |
|---------|---------|
| Tuletise leidmine | 2 p |
| Kriitilised punktid | 1 p |
| Kasvamis- ja kahanemispiirkonnad (märgiskeem) | 3 p |
| Mõlemad ekstreemumid koos koordinaatidega | 2 p |
| Puutuja võrrand | 2 p |

---

## Ülesanne 6 (10 punkti) — Optimeerimine

Tartu linna park soovib piirata ristkülikukujulise lillepeenra, mille üheks küljeks on sirge tee (seda ei ole vaja piirdeaiana). Piirdeaia materjali on kokku **36 meetrit**.

**(a)** Väljenda peenra pindala $S$ laiuse $x$ kaudu.

**(b)** Leia $x$ väärtus, mille korral pindala on maksimaalne.

**(c)** Leia maksimaalne pindala.

<details>
<summary>📋 Täislahendus</summary>

**Samm 1: Seos mõõtmete vahel**

Laius on $x$, pikkus on $y$. Kuna üks külg (pikkus) asub tee ääres:

$$2x + y = 36 \Rightarrow y = 36 - 2x$$

Tingimus: $x > 0$ ja $y > 0$, seega $0 < x < 18$.

**Samm 2: Pindala avaldis**

$$S(x) = x \cdot y = x(36 - 2x) = 36x - 2x^2$$

**Samm 3: Maksimum tuletise abil**

$$S'(x) = 36 - 4x = 0 \Rightarrow x = 9$$

$$S''(x) = -4 < 0 \Rightarrow \text{tegemist on maksimumiga}$$

**Samm 4: Maksimaalne pindala**

$$S(9) = 36 \cdot 9 - 2 \cdot 81 = 324 - 162 = 162 \text{ m}^2$$

**Vastus:** Maksimaalne pindala $162\ \text{m}^2$ saavutatakse, kui $x = 9\ \text{m}$ ja $y = 18\ \text{m}$.

</details>

| Tegevus | Punktid |
|---------|---------|
| Piirangu kirjutamine | 2 p |
| Pindala avaldamine ühe muutuja kaudu | 2 p |
| Tuletise leidmine ja võrdsustamine nulliga | 3 p |
| Maksimumi kontrollimine | 1 p |
| Maksimaalne pindala | 2 p |

---

## Ülesanne 7 (10 punkti) — Kolmnurga trigonomeetria

Kolmnurgas $ABC$ on teada: $AB = 7\ \text{cm}$, $BC = 5\ \text{cm}$ ja $\angle ABC = 60°$.

**(a)** Leia kolmnurga pindala.

**(b)** Leia külg $AC$ (koosinuslause).

**(c)** Leia nurk $\angle BAC$ (siinuslause).

<details>
<summary>📋 Täislahendus</summary>

**Osa (a): Pindala**

$$S = \frac{1}{2} \cdot AB \cdot BC \cdot \sin(\angle ABC) = \frac{1}{2} \cdot 7 \cdot 5 \cdot \sin 60° = \frac{35\sqrt{3}}{4} \approx 15{,}16\ \text{cm}^2$$

**Osa (b): Koosinuslause**

$$AC^2 = AB^2 + BC^2 - 2 \cdot AB \cdot BC \cdot \cos(\angle ABC)$$
$$AC^2 = 49 + 25 - 2 \cdot 7 \cdot 5 \cdot \frac{1}{2} = 74 - 35 = 39$$
$$AC = \sqrt{39} \approx 6{,}24\ \text{cm}$$

**Osa (c): Siinuslause**

$$\frac{\sin(\angle BAC)}{BC} = \frac{\sin(\angle ABC)}{AC}$$

$$\sin(\angle BAC) = \frac{5 \cdot \sin 60°}{\sqrt{39}} = \frac{5 \cdot \frac{\sqrt{3}}{2}}{\sqrt{39}} = \frac{5\sqrt{3}}{2\sqrt{39}}$$

$$\sin(\angle BAC) \approx \frac{4{,}330}{6{,}245} \approx 0{,}693$$

$$\angle BAC \approx 43{,}8°$$

</details>

| Tegevus | Punktid |
|---------|---------|
| Pindala valem ja arvutus | 2 p |
| Koosinuslause rakendamine | 3 p |
| $AC$ väärtus | 2 p |
| Siinuslause rakendamine ja nurk | 3 p |

---

## Ülesanne 8 (10 punkti) — Koordinaatgeomeetria

Koordinaattasandil on antud punktid $A(1;\ 4)$, $B(5;\ 2)$ ja $C(3;\ -2)$.

**(a)** Leia sirge $AB$ võrrand.

**(b)** Leia sirge $AB$ suhtes risti olev sirge, mis läbib punkti $C$.

**(c)** Leia ring, mille läbimõõt on lõik $AB$. Kirjuta ringi võrrand.

<details>
<summary>📋 Täislahendus</summary>

**Osa (a): Sirge AB võrrand**

Tõus: $k = \frac{2-4}{5-1} = \frac{-2}{4} = -\frac{1}{2}$

$$y - 4 = -\frac{1}{2}(x - 1) \Rightarrow y = -\frac{1}{2}x + \frac{9}{2}$$

ehk $x + 2y - 9 = 0$

**Osa (b): Ristsirgete tõusude suhe $k_1 \cdot k_2 = -1$**

$$k_\perp = 2$$

Sirge läbi $C(3;\ -2)$: $y + 2 = 2(x - 3) \Rightarrow y = 2x - 8$

**Osa (c): Ring läbimõõduga AB**

Keskpunkt on $AB$ keskpunkt:

$$M = \left(\frac{1+5}{2};\ \frac{4+2}{2}\right) = (3;\ 3)$$

Raadius:

$$r = \frac{|AB|}{2} = \frac{\sqrt{(5-1)^2 + (2-4)^2}}{2} = \frac{\sqrt{16+4}}{2} = \frac{\sqrt{20}}{2} = \sqrt{5}$$

Ringi võrrand:

$$(x - 3)^2 + (y - 3)^2 = 5$$

</details>

| Tegevus | Punktid |
|---------|---------|
| Sirge $AB$ tõus | 1 p |
| Sirge $AB$ võrrand | 2 p |
| Ristsirgete tingimus ja sirge $C$ kaudu | 3 p |
| Ringi keskpunkt | 2 p |
| Ringi võrrand | 2 p |

---

## Ülesanne 9 (10 punkti) — Integraal ja pindala

Olgu antud funktsioonid $f(x) = x^2 - 2x$ ja $g(x) = x$.

**(a)** Leia funktsioonide graafikute lõikepunktid.

**(b)** Leia graafikute vaheline pindala lõikepunktide vahel.

<details>
<summary>📋 Täislahendus</summary>

**Osa (a): Lõikepunktid**

$$x^2 - 2x = x$$
$$x^2 - 3x = 0$$
$$x(x - 3) = 0$$
$$x = 0 \quad \text{või} \quad x = 3$$

Lõikepunktid: $(0;\ 0)$ ja $(3;\ 3)$

**Osa (b): Pindala**

Vahemikus $[0;\ 3]$ kontrollime, kumb on suurem:

$g(1) = 1$, $f(1) = 1 - 2 = -1$, seega $g(x) > f(x)$ vahemikus $[0;\ 3]$.

$$S = \int_0^3 \bigl[g(x) - f(x)\bigr]\, dx = \int_0^3 \bigl[x - (x^2 - 2x)\bigr]\, dx = \int_0^3 (3x - x^2)\, dx$$

$$= \left[\frac{3x^2}{2} - \frac{x^3}{3}\right]_0^3 = \frac{27}{2} - \frac{27}{3} = \frac{27}{2} - 9 = \frac{9}{2} = 4{,}5$$

**Vastus:** Pindala on $\dfrac{9}{2}$ ruutühikut.

</details>

| Tegevus | Punktid |
|---------|---------|
| Lõikepunktide x-koordinaadid | 2 p |
| Lõikepunktide koordinaadid | 1 p |
| Integraali avaldis (vahe) | 3 p |
| Integraali arvutamine | 3 p |
| Lõppvastus | 1 p |

---

## Ülesanne 10 (10 punkti) — Aritmeetiline jada

Tallinna bussifirma Naviigo piletite hind tõuseb järgmiselt: esimene pilet maksab $a_1$ eurot, iga järgmine pilet maksab **0,50 eurot** rohkem kui eelmine. Ühel päeval müüdi **20 piletit** ja kogutulu oli **165 eurot**.

**(a)** Koosta võrrand ja leia odavaima pileti hind $a_1$.

**(b)** Kui palju maksis 15. pilet?

**(c)** Alates mitmendast piletist ületab hind **9 eurot**?

<details>
<summary>📋 Täislahendus</summary>

**Aritmeetilise jada üldliige:** $a_n = a_1 + (n-1) \cdot 0{,}50$

**Osa (a): Summa 20 liikme kohta**

$$S_{20} = \frac{20}{2}(2a_1 + 19 \cdot 0{,}50) = 10(2a_1 + 9{,}50) = 165$$

$$2a_1 + 9{,}50 = 16{,}50$$
$$2a_1 = 7{,}00 \Rightarrow a_1 = 3{,}50 \text{ €}$$

**Osa (b): 15. pileti hind**

$$a_{15} = 3{,}50 + 14 \cdot 0{,}50 = 3{,}50 + 7{,}00 = 10{,}50 \text{ €}$$

**Osa (c): $a_n > 9$**

$$3{,}50 + (n-1) \cdot 0{,}50 > 9$$
$$(n-1) \cdot 0{,}50 > 5{,}50$$
$$n - 1 > 11 \Rightarrow n > 12$$

**Vastus:** Alates **13. piletist** ületab hind 9 eurot.

</details>

| Tegevus | Punktid |
|---------|---------|
| Summa valemi kirjutamine | 2 p |
| $a_1$ leidmine | 2 p |
| 15. pileti hind | 2 p |
| Võrratus ja lahendamine | 3 p |
| Lõppvastus (alates 13.) | 1 p |

---

## Ülesanne 11 (10 punkti) — Geomeetriline jada ja liitintress

Mari pani **2000 eurot** Tartu Panga hoiusele aastaintressiga **4%** aastas (liitintress).

**(a)** Kirjuta valem summa $S_n$ jaoks pärast $n$ aastat.

**(b)** Kui suur on summa pärast 10 aastat? (Vasta sentide täpsusega.)

**(c)** Mitme aasta pärast ületab summa esimest korda **3000 eurot**?

<details>
<summary>📋 Täislahendus</summary>

**Osa (a): Valem**

$$S_n = 2000 \cdot 1{,}04^n$$

**Osa (b): Pärast 10 aastat**

$$S_{10} = 2000 \cdot 1{,}04^{10} = 2000 \cdot 1{,}48024\ldots \approx 2960{,}49 \text{ €}$$

**Osa (c): Millal $S_n > 3000$?**

$$2000 \cdot 1{,}04^n > 3000$$
$$1{,}04^n > 1{,}5$$

Võtame mõlemalt poolt logaritmi:

$$n \ln(1{,}04) > \ln(1{,}5)$$
$$n > \frac{\ln 1{,}5}{\ln 1{,}04} = \frac{0{,}4055}{0{,}03922} \approx 10{,}34$$

**Vastus:** Summa ületab 3000 eurot pärast **11 aastat**.

*Kontroll:* $S_{11} = 2000 \cdot 1{,}04^{11} \approx 3074{,}11\ \text{€} > 3000$ ✓

</details>

| Tegevus | Punktid |
|---------|---------|
| Õige valem $S_n = 2000 \cdot 1{,}04^n$ | 2 p |
| $S_{10}$ arvutamine | 2 p |
| Võrratus logaritmiga | 3 p |
| $n$ leidmine logaritmide abil | 2 p |
| Lõppvastus (11 aastat) | 1 p |

---

## Ülesanne 12 (10 punkti) — Stereomeetria

Korrapärase nelinurkse püramiidi aluse külg on $a = 6\ \text{cm}$ ja kõrgus on $h = 8\ \text{cm}$.

**(a)** Leia püramiidi külgtahk (kolmnurga kujuline) koos kõrgusega.

**(b)** Leia nurk, mille moodustab külgserv alusega.

**(c)** Leia püramiidi täispindala.

<details>
<summary>📋 Täislahendus</summary>

**Samm 1: Aluse diagonaal ja poolväärtused**

Aluse pool-diagonaal: $d = \frac{a\sqrt{2}}{2} = \frac{6\sqrt{2}}{2} = 3\sqrt{2}\ \text{cm}$

Aluse poole külje kaugus tipust: $m = \frac{a}{2} = 3\ \text{cm}$

**Osa (a): Külgtahu kõrgus (apoteem)**

Apoteem $l$ (kõrgus, mis läheb tipust aluse külgede keskpunkti):

$$l = \sqrt{h^2 + m^2} = \sqrt{64 + 9} = \sqrt{73}\ \text{cm} \approx 8{,}54\ \text{cm}$$

**Osa (b): Nurk külgservaga**

Külgserva pikkus $s$ (tipust aluse nurka):

$$s = \sqrt{h^2 + d^2} = \sqrt{64 + 18} = \sqrt{82}\ \text{cm}$$

Nurk $\alpha$ külgserva ja aluse vahel:

$$\cos\alpha = \frac{d}{s} = \frac{3\sqrt{2}}{\sqrt{82}}$$

$$\alpha = \arccos\!\left(\frac{3\sqrt{2}}{\sqrt{82}}\right) \approx \arccos(0{,}469) \approx 62{,}1°$$

**Osa (c): Täispindala**

Alus: $S_{\text{alus}} = a^2 = 36\ \text{cm}^2$

Üks külgtahu pindala: $S_{\text{külg}} = \frac{1}{2} \cdot a \cdot l = \frac{1}{2} \cdot 6 \cdot \sqrt{73} = 3\sqrt{73}\ \text{cm}^2$

Täispindala:

$$S = 36 + 4 \cdot 3\sqrt{73} = 36 + 12\sqrt{73} \approx 36 + 102{,}5 \approx 138{,}5\ \text{cm}^2$$

</details>

| Tegevus | Punktid |
|---------|---------|
| Apoteemi (külgtahu kõrguse) leidmine | 3 p |
| Külgserva pikkuse leidmine | 2 p |
| Nurga arvutamine | 2 p |
| Aluspindala | 1 p |
| Täispindala | 2 p |

---

*Harjutusülesanded koostatud Eesti gümnaasiumi laia matemaatika riigieksami (2016–2024) põhjal.*
