# Lai matemaatika M14 — Matemaatilised rakendused. Protsesside modelleerimine

**Aste:** Gümnaasium, lai matemaatika  
**Maht:** 35 tundi (kohustuslik)  
**Koht kursustes:** 14/14 (lõppkursus)  
**Eelteadmised:** M1–M13 (kõik eelmised kursused)

---

## Õpitulemused

Kursuse lõpuks õpilane:
- Modelleerib reaalse maailma protsesse matemaatiliste funktsiooniede ja võrranditega
- Kasutab diferentsiaalvõrrandeid füüsikaliste ja bioloogiliste protsesside kirjeldamisel
- Lahendab optimeerimisülesandeid praktilistes kontekstides
- Rakendab tõenäosus- ja statistikat reaalsetes andmestikes
- Kasutab ligikaudmeetodeid ja numbrilisi võtteid
- Analüüsib matemaatiliste mudelite adekvaatsust ja piiranguid
- Lahendab finantsmatemaatika ülesandeid: intressid, annuiteedid, investeeringud
- Kommunikeerib matemaatiliste tulemuste abil reaalsest maailmast

## Võtmemõisted

- Matemaatiline mudel (mathematical model)
- Diferentsiaalvõrrand (differential equation)
- Logistiline kasv (logistic growth)
- Eksponentsialne kasv ja kahanemine (exponential growth/decay)
- Optimeerimisülesanne (optimization problem)
- Lineaarne regressioon (linear regression)
- Finantsmatemaatika (financial mathematics)
- Numbriline analüüs (numerical analysis)

## Olulised seosed

Eksponentsiaalse kasvu/kahanemise mudel:

$$\frac{dy}{dt} = ky, \quad y(t) = y_0 e^{kt}$$

Logistilise kasvu mudel (Verhulsti võrrand):

$$\frac{dy}{dt} = r y \left(1 - \frac{y}{K}\right)$$

Liitintresside valem:

$$A = P\left(1 + \frac{r}{n}\right)^{nt}$$

Pidevas intressiga kapitaliseerimine:

$$A = Pe^{rt}$$

Annuiteedi nüüdisväärtus:

$$PV = PMT \times \frac{1 - (1 + i)^{-n}}{i}$$

Newtonile-Raphsoni meetod juurte leidmiseks:

$$x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}$$

Trapetsi reegel integreerimiseks:

$$\int_a^b f(x) \, dx \approx \frac{b-a}{2n} \left[f(a) + 2f(x_1) + 2f(x_2) + \cdots + 2f(x_{n-1}) + f(b)\right]$$

Lineaarne regressioon:

$$\hat{y} = a + bx, \quad b = \frac{\sum(x_i - \bar{x})(y_i - \bar{y})}{\sum(x_i - \bar{x})^2}$$

## Õppesisu

### Matemaatiliste mudelite koostamine

- Mudeli etapid: probleemsituatsiooni tuvastamine, matemaatilise struktuuri seadmine, lahendamine, tulemuste interpreteerimine
- Diskreetsed ja pidevad mudelid
- Lineaarsed ja mittelineaarsed mudelid
- Mudelite adekvaatsuse ja piirangute analüüs
- Andmete kogumine ja puhastamine

### Eksponentsiaalse kasvu ja kahanemise mudelid

- Radioaktiivsus ja poolestusperiood
- Populatsioonije kasv ja kahanemine
- Külmutatud objekti soojenemine (Newtoni jahutamise seadus)
- Intressid ja investeeringud
- Bakterite paljunemine

### Logistiline mudel

- Logistilise kasvu võrrand ja lahendus
- Kandevõimsus (carrying capacity)
- Populatsioonimodellid peredo ja saakloomade süsteemides
- Epideemiamudelid (SIR-mudel)

### Differentsiaalvõrrandid praktilistes rakendustes

- Esimese järgu lineaarsed diferentsiaalvõrrandid
- Eralduvate muutujatega võrrandid
- Newtoni teine seadus: $F = ma$ ja liikumisvõrrandid
- Viskoosse hõõrdumisega pallide kukkumine
- Harmoonilised võnked

### Optimeerimisülesanded praktilistes kontekstides

- Kulude minimeerimine ja kasumi maksimeerimine
- Transpordi- ja marsruudistamisülesanded
- Materjalikulude minimeerimine (embalaaž, konstruktsioon)
- Energeetika ja ressursside kasutamine
- Lineaarne programmeerimine

### Finantsmatemaatika

- Intressimäärad: nominaalne, efektiivne, perioodiline
- Liitintressid ja pidev kapitaliseerimne
- Laenuotingud ja hipoteegilaenud
- Annuiteedid: nüüdisväärtus ja tulevikuväärtus
- Investeeringute analüüs: NPV, IRR
- Pensiooniplaanid
- Obligatsioonianalüüs

### Statistika ja tõenäosuse rakendused

- Tõenäosusjaotused: normaalne, binomne, Poisson
- Hüpoteeside kontrollimine
- Konfidentsusintervallid
- Regressioon ja korrelatsioon
- Aegridade analüüs ja prognoosimine
- Bayes'i teoreemi rakendused

### Numbrilised meetodid

- Juurte leidmine: bisektsiooni meetod, Newtoni-Raphsoni meetod
- Funktsiooni ligikaudne integreerimine: trapetsi reegel, Simpsoni reegel
- Diferentsiaalvõrrandite numbriline lahendamine: Euleri meetod
- Tulemuste täpsuse hindamine

### Lineaarne regressioon ja andmeanalüüs

- Kahe muutuja seos: skatterdiagramm
- Regressioonijoone määramine: vähimruutude meetod
- Korrelatsioonikordaja arvutamine
- Prognoosimise käyttö
- Mitme muutujaga regressioon

### Päriselulised modelleerimisjuhud

- Kliimamuutused ja karbondioksiidi konsentratsioon
- Epidemioloogilised mudelid: COVID-19 levimise prognoosimine
- Ökoloogilised mudelid: liikide kooseksistents
- Majandusteaduslikud mudelid: tarbimine ja säästmine
- Ainevahetus ja farmakokinetiika

### Mudelite kriitilise hindamise ja valideerimise

- Mudelite piirangud ja eeldused
- Tundlikkuse analüüs (sensitivity analysis)
- Mudelite võrdlemine ja valik
- Kommunikatsiooni matemaatiliste tulemustega
- Eetilised küsimused matemaatilises modelleerimises

## Viited

- [Eksponent- ja logaritmfunktsioonid](../teemad/eksponent-logaritm/)
- [Jadad ja piirväärtus](../teemad/jadad-piirväärtus/)
- [Statistika ja tõenäosus](../teemad/statistika-toenaosus/)
- [Tuletis ja selle rakendused](../teemad/tuletis/)
- [Integraal ja selle rakendused](../teemad/integraal/)
