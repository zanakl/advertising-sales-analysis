# Uvod u analizu podataka – Prva zadaća

Analiza skupa podataka **Advertising Dataset** u sklopu kolegija *Uvod u analizu podataka*.

## O projektu

Cilj zadaće je analizirati odnos između ulaganja u oglašavanje i prodaje proizvoda. Analiza je provedena nad skupom podataka koji sadrži informacije o iznosima potrošenim na oglašavanje putem televizije, radija i novina te o ostvarenoj prodaji.

Poseban naglasak stavljen je na ispitivanje povezanosti između ulaganja u TV oglašavanje i prodaje proizvoda.

## Skup podataka

Korišten je **Advertising Dataset**, koji sadrži 200 uzoraka i četiri varijable:

* `TV` – iznos potrošen na TV oglašavanje
* `Radio` – iznos potrošen na radio oglašavanje
* `Newspaper` – iznos potrošen na oglašavanje u novinama
* `Sales` – ostvarena prodaja

Podaci su numeričkog tipa.

Izvor podataka: [GeeksforGeeks – Dataset for Linear Regression](https://www.geeksforgeeks.org/dataset-for-linear-regression/)

## Provedena analiza

U zadaći su provedene sljedeće analize:

1. učitavanje i provjera podataka
2. provjera nedostajućih vrijednosti i duplikata
3. deskriptivna statistička analiza
4. statističko testiranje hipoteza
5. analiza varijance
6. analiza kovarijance
7. izračun koeficijenta korelacije
8. grafička analiza odnosa TV oglašavanja i prodaje
9. primjena linearne regresije
10. interpretacija dobivenih rezultata

## Linearna regresija

U završnom dijelu analize primijenjen je model linearne regresije kojim se ispituje odnos između:

* ulazne varijable: `TV`
* ciljne varijable: `Sales`

Dobiveni rezultati pokazuju snažnu pozitivnu povezanost između ulaganja u TV oglašavanje i prodaje. Pearsonov koeficijent korelacije iznosi približno **0.9012**.

Regresijski model pokazuje da se na temelju ulaganja u TV oglašavanje može napraviti procjena očekivane prodaje, uz napomenu da na prodaju utječu i drugi čimbenici koji nisu uključeni u ovaj jednostavni model.

## Korištene tehnologije

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Datoteke

* `ZKlasic_dz1.ipynb` – Jupyter Notebook s kompletnom analizom
* `advertising_table.xlsx` – korišteni skup podataka


