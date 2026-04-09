# Lai matemaatika M9 — Tuletise rakendused

**Aste:** Gümnaasium, lai matemaatika  
**Maht:** 35 tundi (kohustuslik)  
**Koht kursustes:** 9/14  
**Eelteadmised:** M8 (tuletise mõiste, diferentseerimine, põhilised reeglid)

---

## Õpitulemused

Kursuse lõpuks õpilane:
- Määrab funktsiooni kriitilised punktid ja teeb analüüsi tuletise märgi muutumise kohta
- Leiab funktsiooni lokaal- ja globaalseid ekstreemumeid ning selgitab nende geomeetrilist tähendust
- Kasutab funktsiooni käitumise analüüsiks teist tuletist ja määrab käänupunkte
- Joonestab funktsiooni graafiku, kasutades tuletist ja teist tuletist
- Lahendab praktilisi optimeerimisülesandeid funktsiooni maksimumi ja miinimumi leidmise kaudu
- Kasutab lineariseerimist funktsiooni ligikaudseteks arvutusteks
- Rakendab tuletist kiiruse ja kiirenduse leidmisel ning seotud kiiruse ülesannetes

## Võtmemõisted

- Kriitilised punktid (critical points)
- Lokaalsed ja globaalsed ekstreemumid (local and global extrema)
- Monotoonsus ja tuletise märk (monotonicity)
- Teine tuletis (second derivative)
- Käänupunkt (inflection point)
- Kumer ja nõgus funktsioon (concave up and down)
- Optimeerimisülesanded (optimization problems)
- Seotud kiirused (related rates)

## Olulised seosed

Funktsiooni uurimine tuletise abil:

$$f'(x) = 0 \text{ või } f'(x) \text{ ei eksisteeri} \Rightarrow \text{kriitilised punktid}$$

$$f'(x) > 0 \Rightarrow f \text{ kasvab; } f'(x) < 0 \Rightarrow f \text{ kahaneb}$$

Teise tuletise test:

$$f''(x) < 0 \Rightarrow \text{lokaalne maksimum; } f''(x) > 0 \Rightarrow \text{lokaalne miinimum}$$

$$f''(x) = 0 \text{ ja } f'' \text{ muudab märki} \Rightarrow \text{käänupunkt}$$

Lineaarne lähendus:

$$f(x) \approx f(a) + f'(a)(x - a)$$

Seotud kiiruste probleem:

$$\frac{d}{dt}[f(t)] = f'(t) \cdot \frac{dt}{dt}$$

## Õppesisu

### Funktsiooni ekstreemumid

- Kriitiliste punktide määramine: $f'(x) = 0$ ja $f'(x)$ mitteolemise kohad
- Lokaalse ja globaalse maksimumi/miinimumi eristamine
- Esimese tuletise test: tuletise märgi muutumise analüüs
- Teise tuletise test: $f''(a)$ abil ekstreemumi tüübi määramine
- Piirid ja lõpmatus: ekstreemumite otsimine piiril

### Funktsiooni käitumine ja graafiku joonestamine

- Funktsiooni monotoonses intervallidest: kus funktsioon kasvab/kahaneb
- Teise tuletise rakendamine käänupunktide leidmisel
- Kumeruse ja nõgususe analüüs (convexity analysis)
- Asümptoodid ja funktsiooni käitumine lõpmatuses
- Täieliku funktsiooni uurimise algoritm graafi joonestamiseks

### Optimeerimisülesanded

- Käesolevas tekstis mainitud rakendused geomeetrias (suurim pindala, väikseim perimeeter)
- Majanduslikud rakendused (kulud, kasumid, efektiivsus)
- Füüsikalised rakendused (energia, aeg, kaugus)
- Kahemõõtmeline ja kolmemõõtmeline optimeerimise ülesanded
- Piirangutega ülesanded (constrained optimization)

### Lineaarne lähendus ja diferentsiaal

- Funktsiooni ligikaudne väärtus punkti lähedal: $f(a + dx) \approx f(a) + f'(a) \cdot dx$
- Diferentsiaali mõiste: $dy = f'(x) \, dx$
- Suurusuuringute tegemiseks lineaarsel lähendamisel
- Muute levimise analüüs (propagation of error)

### Seotud kiirused

- Kiirusega seotud ülesanded: ratsad, lennukid, varjud
- Geomeetriliste suuruste muutumise kiirus
- Diferentsiaalvõrrandite rakendamine muutuva suurusega seotud ülesannetes
- Ajamuutujast sõltuva funktsiooni tuletise arvutamine

## Viited

- [Tuletis ja diferentseerimine](../teemad/tuletis/)
- [Analüütilised funktsioonid](../teemad/eksponent-logaritm/)
- [Trigonomeetrilised funktsioonid](../teemad/trigonomeetria-gumnaasium/)
