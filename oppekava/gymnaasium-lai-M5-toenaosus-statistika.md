# Lai matemaatika M5 — Tõenäosus ja statistika

**Aste:** Gümnaasium, lai matemaatika  
**Maht:** 35 tundi (kohustuslik)  
**Koht kursustes:** 5/14  
**Eelteadmised:** M1 (Kompleksarvud ja funktsioonid)

---

## Õpitulemused

Kursuse lõpuks õpilane:
- tunneb kombinatoorikat (permutatsioonid, kombinatsioonid, variatsioonid)
- saab arvutada tõenäosusi juhuslikes sündmustes erinevatel meetoditel
- teab tingimuslikku tõenäosust ja tõenäosuste korrutamist
- tunneb diskreetseid tõenäosusjaotusi (binoomjaotus, Poissoni jaotus)
- teab normaaljaotuse omadusi ja saab seda rakendada
- saab teostada statistilist andmeanalüüsi (keskmised, dispersioon, standardhälve)
- tunneb korrelatsiooni ja regressiooni
- saab teha järeldusi statistiliste andmete põhjal

## Võtmemõisted

- Permutatsioon, kombinatsioon, variatsioon
- Sündmus, elementaarsündmus
- Tõenäosus (klassikaline, statistiline, geomeetriline)
- Tingimuslik tõenäosus
- Sõltumatud sündmused
- Juhuslik suurus
- Tõenäosusjaotus
- Matemaatiline ootus ja dispersioon
- Normaaljaotus
- Standardhälve

## Olulised seosed

**Faktoriaal:**
$$n! = 1 \cdot 2 \cdot 3 \cdot \ldots \cdot n$$

**Permutatsioonid:**
$$P_n = n!$$

**Kombinatsioonid:**
$$C_n^k = \binom{n}{k} = \frac{n!}{k!(n-k)!}$$

**Variatsioonid:**
$$A_n^k = \frac{n!}{(n-k)!}$$

**Klassiline tõenäosus:**
$$P(A) = \frac{m}{n}$$
kus $m$ on soodsate tulemuste arv ja $n$ on kõigi võimalike tulemuste arv.

**Tingimuslik tõenäosus:**
$$P(A|B) = \frac{P(A \cap B)}{P(B)}$$

**Sõltumatute sündmuste korrutamise reegel:**
$$P(A \cap B) = P(A) \cdot P(B)$$

**Matemaatiline ootus:**
$$E(X) = \mu = \sum_{i} x_i p_i$$

**Dispersioon:**
$$D(X) = \sigma^2 = E(X^2) - [E(X)]^2$$

**Standardhälve:**
$$\sigma = \sqrt{D(X)}$$

**Binoomjaotus:**
$$P(X = k) = \binom{n}{k} p^k (1-p)^{n-k}$$

**Normaaljaotuse tihedusfunktsioon:**
$$f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}$$

## Õppesisu

### Kombinatoorika
Permutatsioonid. Kombinatsioonid ja nende omadused. Variatsioonid. Binoomkoefitsiendid. Kombinatoorika rakendused.

### Juhuslikkus ja tõenäosus
Sündmused ja nende klassifikatsioon. Tõenäosuse klassikaline definitsioon. Geomeetriline tõenäosus. Statistiline tõenäosus. Suhtelised sagedused.

### Tõenäosuste arvutamine
Liitmise reegel. Vastutuletamise reegel. Korrutamise reegel. Tingimuslik tõenäosus. Bayesi valem.

### Juhuslikud suurused ja nende jaotused
Diskreeetsed juhuslikud suurused. Binoomjaotus ja selle omadused. Poissoni jaotus. Matemaatiline ootus ja dispersioon. Keskväärtuse ja dispersiooni omadused.

### Normaaljaotus
Normaaljaotuse tihedusfunktsioon. Standardiseeritud normaaljaotus. Normaaljaotuse kasutamine. Keskliimiitteoreem. Normaaljaotuse rakendused.

### Statistika
Valim ja üldkogum. Andmete kogumine ja korrastamine. Arvuline karakteristika: aritmeetiline keskmine, mediaan, moodus, kvartiilid. Hajuvuskarakteristikad: dispersioon, standardhälve, kvartiilivahe.

### Korrelatsioon ja regressioon
Hajuvusdiagramm. Korrelatsioonikoefitsient. Lineaarne regressioon ja regressioonijoone määramine. Prognoosimist.

## Viited

- [Kombinatoorika](../teemad/kombinatoorika/)
- [Tõenäosuse alused](../teemad/toenaosuse-alused/)
- [Tingimuslik tõenäosus](../teemad/tingimuslik-toenaosus/)
- [Juhuslikud suurused](../teemad/juhuslikud-suurused/)
- [Binoomjaotus](../teemad/binoomjaotus/)
- [Normaaljaotus](../teemad/normaaljaotus/)
- [Statistiline andmeanalüüs](../teemad/statistiline-andmeanalyys/)
- [Korrelatsioon ja regressioon](../teemad/korrelatsioon-regressioon/)
