# Lai matemaatika M12 — Vektorid ruumis

**Aste:** Gümnaasium, lai matemaatika  
**Maht:** 35 tundi (kohustuslik)  
**Koht kursustes:** 12/14  
**Eelteadmised:** M4 (vektorid tasandil), M11 (planimeetria)

---

## Õpitulemused

Kursuse lõpuks õpilane:
- Lahendab ülesandeid 3D koordinaatsüsteemis: koordinaadid, kaugused, nurgad
- Kasutab vektoriarvutusi ruumis: liitmine, lahutamine, skalaarkorrutis
- Määrab ja rakendab vektorite ristkorrutist ja selle geomeetrilist tähendust
- Leab tasandi võrrandi vektoriaalse meetodiga
- Lahendab sirgete ja tasandite lõikepunkte ruumis
- Määrab kaugusi punktist sirgeni, punktist tasandini, sirgete vahel
- Arvutab nurki sirgete ja tasandite vahel
- Kasutab vektormeetodeid ruumiliste ülesannete lahendamisel

## Võtmemõisted

- 3D koordinaadid ja koordinaatsüsteem (3D coordinates)
- Vektor ruumis (vector in space)
- Vektori pikkus ja normaliseeritud vektor (magnitude, unit vector)
- Skalaarkorrutis (dot product)
- Ristkorrutis (cross product)
- Sirge parameetriline võrrand ruumis (parametric line equation)
- Tasandi võrrand (plane equation)
- Vektori projektsioon (vector projection)

## Olulised seosed

Vektori pikkus 3D-s:

$$|\vec{v}| = \sqrt{x^2 + y^2 + z^2}$$

Skalaarkorrutis (dot product):

$$\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z = |\vec{a}| |\vec{b}| \cos \theta$$

Ristkorrutis (cross product):

$$\vec{a} \times \vec{b} = \begin{vmatrix} \vec{i} & \vec{j} & \vec{k} \\ a_x & a_y & a_z \\ b_x & b_y & b_z \end{vmatrix}$$

$$|\vec{a} \times \vec{b}| = |\vec{a}| |\vec{b}| \sin \theta$$

Sirge parameetriline võrrand:

$$\vec{r}(t) = \vec{r}_0 + t \vec{d}, \quad t \in \mathbb{R}$$

Tasandi võrrand:

$$ax + by + cz + d = 0$$

kus $(a, b, c)$ on tasandi normaalvektor.

Tasandi võrrand punkti ja kahe vektori järgi:

$$\vec{r}(s, t) = \vec{r}_0 + s\vec{u} + t\vec{v}$$

Kaugus punktist $(x_0, y_0, z_0)$ tasandini $ax + by + cz + d = 0$:

$$d = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2 + b^2 + c^2}}$$

Nurk kahe vektori vahel:

$$\cos \theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}$$

## Õppesisu

### 3D koordinaatsüsteem ja vektorid ruumis

- Dekartesi koordinaatsüsteem kolmemõõtmelises ruumis
- Koordinaatide tähistus ja geomeetriline tähendus
- Punkti kaugus algusest ja kahe punkti vaheline kaugus
- Vektori koordinaadid ja pikkus ruumis
- Ühikvektori mõiste (unit vector)

### Vektoriarvutused ruumis

- Vektori liitmine ja lahutamine
- Vektori korrutamine skalaariga
- Vektori lineaarne kombinatsioon
- Vektorite kolineaarsus ja sõltumatus

### Skalaarkorrutis (dot product)

- Skalaarkorrutise algebraline ja geomeetriline tähendus
- Skalaarkorrutise omadused: kommutatiivne, assotsiatiivsus skalaariga, distributiivsus
- Ortogonaalsed vektorid: $\vec{a} \perp \vec{b} \Leftrightarrow \vec{a} \cdot \vec{b} = 0$
- Nurga arvutamine vektorite vahel

### Ristkorrutis (cross product)

- Ristkorrutise mõiste ja algebraline definitsioon
- Ristkorrutise geomeetriline tähendus: risti asetsev vektor ja pindala
- Ristkorrutise omadused: antikommutatiivne, distributiivsus
- Determinant ja ristkorrutis
- Ristkorrutise rakendused: tasandi normaalvektori leidmine

### Sirge ruumis

- Sirge parameetriline võrrand: $\vec{r}(t) = \vec{r}_0 + t\vec{d}$
- Sirge kanoonilised võrrandid
- Sirgete paralleelsus ja ristseis
- Sirgete lõikepunkt ja sirgete vaheline nurk
- Vihearvulised sirged (skew lines) ja nende kaugus

### Tasand ruumis

- Tasandi võrrand: $ax + by + cz + d = 0$
- Normaalvektor tasandi võrrandist
- Tasandi võrrand punkti ja normaalvektori järgi
- Tasandi võrrand kolme punkti järgi
- Paralleelsed tasandid: samad normaalvektorid
- Tasandite vaheline nurk

### Sirgete ja tasandite vastastikused asendid

- Sirge ja tasandi ristseis
- Sirge paralleelsus tasandiga
- Sirge ja tasandi lõikepunkt
- Sirge taandamine tasandile (ortogonaalse projektsiooni abil)

### Kaugused ruumis

- Kaugus punktist sirgeni: vektormeetodi abil
- Kaugus punktist tasandini: normaalvektor ja valem
- Kaugus paralleelsete sirgete vahel
- Kaugus paralleelsete tasandite vahel
- Kaugus vihearvuliste sirgete vahel

### Vektormeetod geomeetriliste ülesannete lahendamisel

- Tetraeedri ruumala arvutamine ristkorrutise ja skalaarkortutise abil
- Kolmnurga pindala arvutamine ristkorrutise abil
- Nurga arvutamine tasandite vahel
- Sirge projektsioon tasandile
- Peegeldus tasandi suhtes (reflection)

## Viited

- [Vektorid tasandil](../teemad/analuutiline-geomeetria/)
- [Stereomeetria alused](../teemad/stereomeetria-algus/)
- [Trigonomeetria gümnaasiumis](../teemad/trigonomeetria-gumnaasium/)
