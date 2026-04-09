# Lai matemaatika M8 — Jadad. Piirväärtus. Tuletis

**Aste:** Gümnaasium, lai matemaatika  
**Maht:** 35 tundi (kohustuslik)  
**Koht kursustes:** 8/14  
**Eelteadmised:** M6 (Funktsioonid I: astme-, eksponent- ja logaritmfunktsioon)

---

## Õpitulemused

Kursuse lõpuks õpilane:
- teab arvjadade tüüpidest ja nende omadusi
- saab arvutada aritmeetilise ja geomeetrilise jada summasid
- tunneb aritheetilise jada ja geomeetrilise jada lõpmatu summat
- saab määrata jada piirväärtust
- tunneb funktsiooni piirväärtuse mõistet
- teab tuletise definitsioonist
- saab arvutada põhiliste funktsioonide tuletisi
- saab rakendada tuletist funktsiooni uurimisel ja praktilistes ülesannetes
- tunneb tuletise geomeetrilist ja füüsikalist tähendust

## Võtmemõisted

- Jada
- Aritmeetiline jada
- Geomeetriline jada
- Jada piirväärtus
- Koonduminemine ja lahknemine
- Funktsiooni piirväärtus
- Tuletis
- Tuletise geomeetriline tähendus (puutuja, kalle)
- Kiirus ja kiirendus
- Kutsutav ja mittekulutav jada

## Olulised seosed

**Aritmeetilise jada üldliige:**
$$a_n = a_1 + (n-1)d$$

**Aritmeetilise jada summa:**
$$S_n = \frac{n(a_1 + a_n)}{2} = \frac{n[2a_1 + (n-1)d]}{2}$$

**Geomeetrilise jada üldliige:**
$$a_n = a_1 \cdot q^{n-1}$$

**Geomeetrilise jada summa:**
$$S_n = a_1 \cdot \frac{1 - q^n}{1 - q}, \quad q \neq 1$$

**Lõpmatu geomeetrilise jada summa (kui $|q| < 1$):**
$$S = \frac{a_1}{1 - q}$$

**Jada piirväärtus:**
$$\lim_{n \to \infty} a_n = L$$

**Funktsiooni piirväärtus:**
$$\lim_{x \to x_0} f(x) = L$$

**Tuletise definitsioon:**
$$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$

**Lihtsamate funktsioonide tuletised:**
$$(c)' = 0, \quad (x)' = 1, \quad (x^n)' = nx^{n-1}$$
$$(e^x)' = e^x, \quad (\ln x)' = \frac{1}{x}$$
$$(\sin x)' = \cos x, \quad (\cos x)' = -\sin x$$
$$(\tan x)' = \frac{1}{\cos^2 x}$$

**Tuletise arvutamise reeglid:**
$$(f + g)' = f' + g'$$
$$(cf)' = c \cdot f'$$
$$(f \cdot g)' = f' \cdot g + f \cdot g'$$
$$\left(\frac{f}{g}\right)' = \frac{f' \cdot g - f \cdot g'}{g^2}$$

**Koosfunktsiooni tuletis (ahelreegel):**
$$(f(g(x)))' = f'(g(x)) \cdot g'(x)$$

**Puutuja võrrand punktis $(x_0, y_0)$:**
$$y - y_0 = f'(x_0)(x - x_0)$$

## Õppesisu

### Arvjadad
Jada definitsioon ja tähisus. Jada limiidi mõiste. Aritmeetiline jada: defineerimine, üldliige, summa. Geomeetriline jada: defineerimine, üldliige, summa. Lõpmatu geomeetrilise jada summa.

### Jada konvergents
Jada konvergentsi mõiste. Jada piirväärtus ja selle omadused. Konvergentsed ja lahknevad jadad. Erinevat tüüpi jadade käitumine piiramatu suurenemisel.

### Funktsiooni piirväärtus
Funktsiooni piirva väärtuse mõiste. Ühepoolsed piirväärtused. Piirväärtuse arvutamine graafiliselt ja algebraaliselt. Piirväärtuse omadused.

### Tuletise mõiste
Tuletise definitsioon ja geomeetriline tähendus. Tuletis kui hetkelise kiiruse mõõt. Funktsioonide diferentseeritavus. Tuletise olemasolu ja pidevuse seos.

### Tuletise arvutamine
Tuletise arvutamise reeglid (summa, korrutis, jagatis). Koosfunktsiooni tuletis (ahelreegel). Elementaarsete funktsioonide tuletised.

### Tuletise rakendused
Funktsiooni monotoonsus ja tuletis. Funktsiooni ekstremaalsed väärtused. Funktsiooni uurimine tuletise abil. Joone puutuja ja kalle. Optimeerimisülesanded.

### Füüsikalised rakendused
Kiirus ja kiirendus liikumisülesannetes. Muutumise kiirus erinevates kontekstides. Elastsus ja sõltuvused füüsikas ja majanduses.

## Viited

- [Aritmeetiline jada](../teemad/aritmeetiline-jada/)
- [Geomeetriline jada](../teemad/geomeetriline-jada/)
- [Jada piirväärtus ja konvergents](../teemad/jada-piirvaartus/)
- [Funktsiooni piirväärtus](../teemad/funktsiooni-piirvaartus/)
- [Tuletise definitsioon](../teemad/tuletise-definitsioon/)
- [Tuletise arvutamise reeglid](../teemad/tuletise-arvutamise-reeglid/)
- [Elementaarsete funktsioonide tuletised](../teemad/elementaarsete-funktsioonide-tuletised/)
- [Tuletis ja funktsiooni uurimine](../teemad/tuletis-funktsiooni-uurimine/)
- [Optimeerimisülesanded](../teemad/optimeerimisülesanded/)
