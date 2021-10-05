Rollup pakendustööriista peale ehitatud projekt
===============================

Ametliku veebisaidi kohaselt on "Rollup JavaScripti moodulipakett,
mis koondab väikesed kooditükid millekski suuremaks ja keerukamaks,
näiteks teegiks või rakenduseks."
Rollup on koodi jagamise ehk  “code splitting” kuningas.
Lisaks toetab Rollup “tree-shaking”-ut. Rollup lubab ES-moodulite kasutamist 
ja analüüsib staatiliselt imporditavat koodi ja jätab välja kõik,
mida tegelikult ei kasutata.

## Projekti taust

Seoses KILP 2021 tehniliste töödega on vaja ressursside halduse
front-end arenduse stacki uuendada ja üle minna vanadelt
tehnoloogiatelt uutele.

Lisaks Reacti uuendamisele on vaja üle minna ka kaasaegsele
ehitus- ja pakendustööriistale.


- [Nõuded ehitus- ja pakendustööriistale](#nõuded-ehitus--ja-pakendustööriistale)
- [Kuidas kasutada](#kuidas-kasutada)


## Nõuded ehitus- ja pakendustööriistale

### 1. Kuidas mõjutab arenduse kiirust?
Ehitamise protsessi kiirus, Hot Module Replacement.

### 2. Peab toetama:

- React
- JSX
- TypeScript
- SCSS (ka CSS mooduleid)

### 3. Peab olema võimalikult lihtsalt konfigureeritav.

### 4. Lisavõimalused (tuleviku arendusi silmas pidades):

- Tree shaking
- Code splitting
- Automaatne formattimine (eslint, Prettier)


## Kuidas kasutada

Ehitamiseks 
```
npm run build
```

Ehitamiseks ja jooksutamiseks

```
npm run start
```

Juurdepääs ```http://localhost:3000```
