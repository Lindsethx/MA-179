# MA-179
Matte-2

# Oversikt: Matriser og lineære likningssystemer

Denne filen gir en samlet oversikt over sentrale begreper knyttet til matriser og lineære likningssystemer.

---

## 1. Systemer av linjære likninger

Et **system av linjære likninger** er en samling likninger på formen:

a₁x₁ + a₂x₂ + … + aₙxₙ = b

Eksempel:
2x + y = 5
x − y = 1

### Matriseform (utvidet matrise)
Systemet kan skrives som en **utvidet matrise**:

[ 2 1 | 5 ]
[ 1 -1 | 1 ]


Målet er å forenkle matrisen for å finne løsning(er).

---

## 2. Elementære rad-operasjoner

Disse operasjonene brukes for å løse systemer og bevare løsningene:

1. **Bytte to rader**

    R₁ ↔ R₂

2. **Multiplisere en rad med en ikke-null konstant**

    cR₁ → R₁ (c ≠ 0)

3. **Legge et multiplum av én rad til en annen**

    R₂ + cR₁ → R₂

Disse endrer ikke løsningen til systemet.

---

## 3. Ledende element (Leading entry)

Det **ledende elementet** i en rad er:
- Det **første ikke-null-tallet** fra venstre i raden

Eksempel:

[ 0 0 3 1 ]

↑

ledende element

---

## 4. Trappeform (Row Echelon Form)

En matrise er på **trappeform** hvis:

1. Alle nullrader ligger nederst
2. Det ledende elementet i hver rad er til høyre for det i raden over
3. Alle elementer **under** et ledende element er null

Eksempel:

[ 1 2 0 | 3 ]
[ 0 1 -1 | 4 ]
[ 0 0 1 | 2 ]

---

## 5. Redusert trappeform (Reduced Row Echelon Form – RREF)

En matrise er på **redusert trappeform** hvis:

1. Den er på trappeform
2. Alle ledende elementer er **1**
3. Alle elementer **over og under** hvert ledende element er 0

Eksempel:

Dette gir løsningen direkte.

---

## 6. Pivot

En **pivot** er:
- Et ledende element som brukes som referanse for rad-operasjoner
- Vanligvis gjort om til tallet **1**

Eksempel:

[ 1 3 0 ]

↑

pivot


---

## 7. Pivot-posisjon

En **pivot-posisjon** er:
- Posisjonen i matrisen der en pivot står
- Bestemmes ut fra trappeformen (ikke originalmatrisen)

Eksempel:

[ 1 2 0 ]
[ 0 1 3 ]

Pivot-posisjoner:
- (rad 1, kolonne 1)
- (rad 2, kolonne 2)

---

## 8. Pivot-søyle

En **pivot-søyle** er:
- En kolonne som inneholder en pivot
- Tilsvarer en **ledende variabel** i systemet

Ikke-pivot-søyler:
- Tilsvarer **frie variabler**

Eksempel:

[ 1 0 4 ]
[ 0 1 2 ]


Pivot-søyler: 1 og 2  
Ikke-pivot-søyle: 3

---

## 9. Oppsummering

| Begrep | Kort forklaring |
|------|----------------|
| Linjært system | Flere lineære likninger |
| Elementære rad-operasjoner | Tillatte operasjoner på rader |
| Ledende element | Første ikke-null i en rad |
| Trappeform | Nuller under ledende elementer |
| Redusert trappeform | Nuller både over og under pivoter |
| Pivot | Ledende 1 brukt som referanse |
| Pivot-posisjon | Plasseringen til pivoten |
| Pivot-søyle | Kolonne som inneholder pivot |

----