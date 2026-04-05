# Statistika ja tõenäosus

## 1. Statistika põhimõisted

**Valim** — kogutud andmete hulk.
**Sagedus** — mitu korda väärtus esineb.
**Suhteline sagedus** — sagedus jagatud valimi mahuga.

## 2. Keskväärtused

**Aritmeetiline keskmine:**
$$\bar{x} = \frac{x_1 + x_2 + \ldots + x_n}{n}$$

**Mediaan** — keskmine väärtus, kui andmed järjestada. Paaritu $n$: keskmine element. Paaris $n$: kahe keskmise keskmine.

**Mood** — kõige sagedamini esinev väärtus.

## 3. Haare ja standardhälve

**Haare (variatsiooniulatus):** $R = x_{\max} - x_{\min}$.

**Dispersioon** (keskmise ruudu hälve):
$$\sigma^2 = \frac{1}{n}\sum_{i=1}^n (x_i - \bar{x})^2$$

**Standardhälve:** $\sigma = \sqrt{\sigma^2}$.

## 4. Tõenäosuse mõiste

**Klassikaline tõenäosus:**
$$P(A) = \frac{\text{soodsate juhtude arv}}{\text{kõikide juhtude arv}}$$

eeldusel, et kõik juhud on **võrdvõimalikud**.

$0 \leq P(A) \leq 1$. $P(\text{võimatu}) = 0$, $P(\text{kindel}) = 1$.

## 5. Sündmuste liigid

- **Vastandsündmus:** $P(\bar{A}) = 1 - P(A)$.
- **Sõltumatud sündmused:** $P(A \cap B) = P(A) \cdot P(B)$.
- **Välistavad sündmused:** $P(A \cup B) = P(A) + P(B)$.

## 6. Kombinatoorika alused

- **Permutatsioonid** (kõik järjestused): $n! = 1 \cdot 2 \cdot \ldots \cdot n$.
- **Variatsioonid** (järjestus oluline): $\dfrac{n!}{(n-k)!}$.
- **Kombinatsioonid** (järjestus pole oluline): $\binom{n}{k} = \dfrac{n!}{k!(n-k)!}$.

## 7. Lahendatud näited

**Näide 1.** Andmed: $4, 7, 3, 5, 6, 4, 8$. Leia keskmine, mediaan, mood.
Keskmine: $\dfrac{4+7+3+5+6+4+8}{7} = \dfrac{37}{7} \approx 5{,}29$.
Järjestus: $3,4,4,5,6,7,8$. Mediaan $5$. Mood $4$.

**Näide 2.** Täringu viskamine. Tõenäosus saada paaritu arv?
$$P = \frac{3}{6} = \frac{1}{2}$$

**Näide 3.** Kaks täringut. Tõenäosus, et summa on $7$?
Summa $7$ võimalused: $(1,6),(2,5),(3,4),(4,3),(5,2),(6,1)$ — $6$ võimalust. Kõikide juhtude arv $36$. $P = \dfrac{6}{36} = \dfrac{1}{6}$.

**Näide 4.** 5 punast ja 3 valget palli. Tõmbame ühe juhuslikult. Tõenäosus, et on punane?
$$P = \frac{5}{8}$$

## 8. Tüüpilised vead

- Mediaani leidmiseks unustatakse andmed järjestada.
- Tõenäosuse põhivalem: juhud peavad olema võrdvõimalikud.
- Sõltumatute sündmuste korrutamine segi saadakse välistavate sündmustega.

## 9. Seos teiste teemadega

- Protsent (suhteline sagedus).
- Murrud (tõenäosused).
- Funktsioonid ja graafikud (jaotused).
