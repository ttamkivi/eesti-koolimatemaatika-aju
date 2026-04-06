# Eksponentfunktsioon ja logaritm

## 1. Astme meenutus

Astme omadused (kordamine):

$$a^m \cdot a^n = a^{m+n}, \quad \frac{a^m}{a^n} = a^{m-n}, \quad (a^m)^n = a^{mn}$$

$$a^0 = 1, \quad a^{-n} = \frac{1}{a^n}, \quad a^{1/n} = \sqrt[n]{a}$$

## 2. Eksponentfunktsioon

$$f(x) = a^x, \quad a > 0, \; a \neq 1$$

**Omadused:**
- Definitsioonikogum: $\mathbb{R}$ (kõik reaalarvud)
- Väärtuste kogum: $(0;\, +\infty)$
- Läbib alati punkti $(0;\, 1)$
- Kui $a > 1$: **kasvav**, graafik tõuseb vasakult paremale
- Kui $0 < a < 1$: **kahanev**, graafik langeb

**Erilised alused:**
- $e \approx 2{,}718$ — Euleri arv (looduslik alus)
- $f(x) = e^x$: kõige olulisem eksponentfunktsioon

## 3. Logaritm

**Definitsioon:** $\log_a b = c \iff a^c = b$

*Lugege:* "a-baasiga logaritm b-st on c".

**Erijuhud:**
- $\ln x = \log_e x$ — naturaallogaritm
- $\lg x = \log_{10} x$ — kümnendlogaritm

## 4. Logaritmi omadused

$$\log_a(mn) = \log_a m + \log_a n$$

$$\log_a\!\left(\frac{m}{n}\right) = \log_a m - \log_a n$$

$$\log_a(m^k) = k \cdot \log_a m$$

$$\log_a a = 1, \quad \log_a 1 = 0$$

**Aluse vahetuse valem:**

$$\log_a b = \frac{\log_c b}{\log_c a} = \frac{\ln b}{\ln a}$$

## 5. Eksponentvõrrandid

**Põhimeetod:** viia mõlemad pooled samale alusele.

$$a^{f(x)} = a^{g(x)} \iff f(x) = g(x)$$

**Kui alust muuta ei saa**, võtta logaritm:

$$2^x = 5 \implies x \ln 2 = \ln 5 \implies x = \frac{\ln 5}{\ln 2}$$

## 6. Logaritmvõrrandid

**Põhimeetod:** kasutada logaritmi omadusi, et ühendada termineid.

$$\log_a f(x) = \log_a g(x) \iff f(x) = g(x) \quad (\text{ja } f(x) > 0)$$

$$\log_a f(x) = b \iff f(x) = a^b$$

**NB!** Alati kontrollida, et logaritmide argumendid oleksid positiivsed!

## 7. Eksponentfunktsiooni tuletis ja integraal

$$\frac{d}{dx}(e^x) = e^x, \qquad \int e^x\, dx = e^x + C$$

$$\frac{d}{dx}(a^x) = a^x \ln a$$

$$\frac{d}{dx}(\ln x) = \frac{1}{x}$$

## 8. Kasvumudel

**Eksponentkasv:** $N(t) = N_0 \cdot a^t$

**Kordisega:** $N(t) = N_0 \cdot q^t$ (kus $q$ on kordis)

**Naturaallogaritmiga:** $N(t) = N_0 \cdot e^{kt}$, kus $k$ on kasvukiirus.

**Poolestusaeg** $T_{1/2}$: aeg, mil kogus pooldub. $N(T_{1/2}) = \dfrac{N_0}{2}$

## 9. Lahendatud näited

**Näide 1.** Lahenda $2^{x+1} = 16$.

$$2^{x+1} = 2^4 \implies x + 1 = 4 \implies x = 3$$

**Näide 2.** Lahenda $\log_2(x-1) + \log_2(x+1) = 3$.

$$\log_2[(x-1)(x+1)] = 3 \implies (x-1)(x+1) = 8$$

$$x^2 - 1 = 8 \implies x^2 = 9 \implies x = \pm 3$$

Kontroll: $x = -3$ → argumendid $-4$ ja $-2$ — negatiivsed, **ei sobi!**

$x = 3$: argumendid $2$ ja $4$ — positiivsed, sobib. **Vastus:** $x = 3$.

**Näide 3.** Bakterikoloonias on algul 1000 bakterit, hulk kahekordistub iga 3 tunni järel. Kui palju on baktereid 12 tunni pärast?

$$N(12) = 1000 \cdot 2^{12/3} = 1000 \cdot 2^4 = 16\,000$$

## 10. Tüüpilised vead

- Logaritmi arvutamisel: $\log_a(m + n) \neq \log_a m + \log_a n$!
- Lahenduse kontrollimine logaritmvõrrandites unustatakse.
- $\ln$ ja $\lg$ aja ajatakse segi — märgi alati alus selgelt.
