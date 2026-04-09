# Lai matemaatika M10 — Integraal ja selle rakendused

**Aste:** Gümnaasium, lai matemaatika  
**Maht:** 35 tundi (kohustuslik)  
**Koht kursustes:** 10/14  
**Eelteadmised:** M8 (tuletis), M9 (tuletise rakendused)

---

## Õpitulemused

Kursuse lõpuks õpilane:
- Määrab funktsioonide antiderivatiive ja lahendab määramata integraale
- Selgitab Newtoni-Leibnizi seadust ja rakendab seda määratud integraalide arvutamisel
- Arvutab kõverjooneliste figuuri pindalasid integraalide abil
- Kasutab integraali füüsikaliste suuruste (nihkumine, töö) arvutamisel
- Rakendab ositi integreerimise ja asenduse meetodeid keerukamate integraalide lahendamisel
- Arvutab keha ruumala pöörlemiskehadel
- Lahendab praktilisi probleeme, kasutades integraali rakendusi

## Võtmemõisted

- Antiderivatiiv ja määramata integraal (antiderivative, indefinite integral)
- Määratud integraal (definite integral)
- Integreerimise reeglid (integration rules)
- Newtoni-Leibnizi seadus (Fundamental Theorem of Calculus)
- Pindala ja integraal (area and integral)
- Ositi integreerimine (integration by parts)
- Asenduse meetod (substitution method)
- Pöörlemiskeha ruumala (volume of revolution)

## Olulised seosed

Antiderivatiivide põhivalem:

$$\int f(x) \, dx = F(x) + C, \quad \text{kus } F'(x) = f(x)$$

Newtoni-Leibnizi seadus:

$$\int_a^b f(x) \, dx = F(b) - F(a), \quad \text{kus } F'(x) = f(x)$$

Määramata integraali põhireeglid:

$$\int [af(x) + bg(x)] \, dx = a\int f(x) \, dx + b\int g(x) \, dx$$

$$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C, \quad n \neq -1$$

$$\int e^x \, dx = e^x + C; \quad \int a^x \, dx = \frac{a^x}{\ln a} + C$$

$$\int \sin x \, dx = -\cos x + C; \quad \int \cos x \, dx = \sin x + C$$

Pindala kõvera ja x-telje vahel:

$$A = \int_a^b |f(x)| \, dx$$

Ositi integreerimine:

$$\int u \, dv = uv - \int v \, du$$

Asendus:

$$\int f(g(x)) \cdot g'(x) \, dx = \int f(u) \, du, \quad u = g(x)$$

Pöörlemiskeha ruumala (x-telje ümber):

$$V = \pi \int_a^b [f(x)]^2 \, dx$$

## Õppesisu

### Antiderivatiiv ja määramata integraal

- Antiderivatiivi mõiste: funktsioon $F$ on funktsioon $f$ antiderivatiiv, kui $F'(x) = f(x)$
- Antiderivatiivide mitteühesus: antiderivatiiv on määratud kuni konstantse lisandini
- Määramata integraali tähistus ja tähendus: $\int f(x) \, dx$
- Grundefunktsiooniode integreerimine: polünoomid, eksponentfunktsioon, trigonomeetrilised funktsioonid

### Integreerimise reeglid

- Lineaarsus: summa ja vahe integreerimine
- Korrutamisega konstandi integreerimine
- Astme funktsioon, eksponentfunktsioon, logaritmiline funktsioon
- Trigonomeetriliste funktsioonide integreerimine
- Ratsionaalsed funktsioonid (partial fractions)

### Määratud integraal

- Integraali geomeetriline tähendus: pindala all kõvera
- Määratud integraali omadused: aditiivsus intervallidel, lineaarsus
- Newtoni-Leibnizi seadus ja praktilised arvutused
- Pöördvõrded: määratud integraali arvutamine asenduse ja ositi integreerimisega

### Newtoni-Leibnizi seadus

- Seaduse sõnastus ja tõestus
- Integraali arvutamine antiderivatiivide abil
- Rakendused pidevate funktsioonide integreerimisel

### Kõverjoonelise figuuri pindala

- Pindala kõvera ja x-telje vahel
- Pindala kahe kõvera vahel
- Polaarkoordinaatides antud funktsioonide pindala

### Ositi integreerimine ja asenduse meetod

- Ositi integreerimise valem ja rakendused
- LIATE/ILATE reegel valiku arvutamisel
- Asenduse meetod: lin ageelarvutamine ja edasiviimine
- Trigonomeetrilised asendused

### Füüsilised rakendused

- Nihkumine: kiiruse integreerimine
- Töö: jõu integreerimine piki rada
- Massikeskme leidmine: geomeetriliste figuuride karakteristikud
- Tõenäosusjaotused: integraal normaliseerimise tingimuses

### Pöörlemiskeha ruumala

- Pöörlemiskeha ruumala x-telje ümber
- Pöörlemiskeha ruumala y-telje ümber
- Üldraalvõte: varjestikku integreerimise meetod
- Koonuse, silindri ja kera ruumala arvutamine

## Viited

- [Integraal ja määramata integraal](../teemad/integraal/)
- [Tuletis ja diferentseerimine](../teemad/tuletis/)
- [Eksponent- ja logaritmfunktsioonid](../teemad/eksponent-logaritm/)
- [Trigonomeetrilised funktsioonid](../teemad/trigonomeetria-gumnaasium/)
