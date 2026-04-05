# Panustamine — Eesti Koolimatemaatika Aju

Aitäh, et tahad kaasa aidata! Siin on lühike juhend, kuidas lisada või parandada sisu.

## Kes võib panustada?

- Matemaatikaõpetajad (põhikool, gümnaasium)
- Eraõpetajad ja tuutorid
- Üliõpilased (matemaatika, füüsika, informaatika)
- Õpilased, kes märkasid vea

## Kuidas muudatust teha — ilma Git'i tundmata

1. Ava fail, mida tahad muuta (nt `teemad/ruutvorrand/teooria.md`).
2. Kliki paremal üleval pliiatsiikoonil ✏️ ("Edit this file").
3. Tee oma muudatus otse brauseris.
4. Kerige alla ja kliki **"Propose changes"**.
5. GitHub loob pull request'i. Administraator vaatab üle ja lisab.

Kui oled uus GitHubis, loo endale tasuta konto aadressil [github.com](https://github.com). See võtab 2 minutit.

## Mida me ootame?

**Jah, palun:**
- Uusi teooriaselgitusi, mis on **õpilasesõbralikud**
- Uusi ülesandeid koos lahendustega
- Eksamiülesandeid (viita aastale ja allikale)
- Vigade parandusi (kirjavead, valemivead, loogikavead)
- Pildifaile (SVG eelistatud, `/static/images/` kausta)

**Ei, mitte päris:**
- Otsene kopeerimine õpikutest (autoriõigused!)
- Sisu, mis ei vasta Eesti riiklikule õppekavale
- Ülesanded ilma lahenduseta

## Sisu formaat

Teoreetilised failid on **Markdown** (.md) formaadis. Matemaatika kirjutame LaTeX-süntaksiga:

- Reasisene valem: `$a^2 + b^2 = c^2$` → $a^2 + b^2 = c^2$
- Eraldi plokk:
  ```
  $$
  x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
  $$
  ```

## Teema struktuur

Iga teemakaust `/teemad/<teemanimi>/` sisaldab:
- `teooria.md` — lühike selgitus + näited
- `ulesanded.md` — harjutusülesanded koos lahenduste ja vastustega

## Küsimused?

Ava [Issue](https://github.com/ttamkivi/eesti-koolimatemaatika-aju/issues) või võta ühendust projekti omanikuga.

---

*Aitäh, et aitad Eesti koolimatemaatika heaks!*
