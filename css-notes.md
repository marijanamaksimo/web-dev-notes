* {}            /* univerzalni */
* h1 {}           /* tag */
* #id {}          /* ID */
* .class {}       /* klasa */
* div p {}        /* potomci */

## Box Model
content → padding → border → margin

## Layout
display: flex;

### Svojstva za kontejner

| Svojstvo          | Vrednosti                                       | Opis                            |
|-------------------|-------------------------------------------------|---------------------------------|
| flex-direction    | row, row-reverse, column, column-reverse        | Glavna osa                      |
| justify-content   | flex-start, center, space-between, space-around | Poravnanje po glavnoj osi       |
| align-items       | stretch, center, flex-start, flex-end           | Poravnanje po poprečnoj osi     |
| gap               | 1rem, 10px                                      | Razmak između stavki            |

### Svojstva za stavke (deca)

| Svojstvo        | Vrednosti       | Opis                                            |
|-----------------|-----------------|-------------------------------------------------|
| flex-grow       | 0, 1            | Da li stavka raste da popuni prostor            |
| flex-shrink     | 0, 1            | Da li stavka može da se smanji                  |
| flex-basis      | auto, 100px     | Početna veličina stavke                         |
| order           | 0, 1, -1        | Redosled stavki                                 |
| align-self      | auto, center    | Pojedinačno poravnanje stavke u poprečnoj osi   |

---

display: grid;

### Svojstva za kontejner

| Svojstvo               | Vrednosti                               | Opis                                          |
|------------------------|-----------------------------------------|-----------------------------------------------|
| grid-template-columns  | repeat(3, 1fr), 200px 1fr 1fr           | Broj i širina kolona                          |
| grid-template-rows     | 100px auto                              | Visina redova                                 |
| gap                    | 10px, 1rem                              | Razmak između redova i kolona                 |
| justify-items          | start, center, end, stretch             | Horizontalno poravnanje unutar ćelija         |
| align-items            | start, center, end, stretch             | Vertikalno poravnanje unutar ćelija           |
| place-items            | center, start                           | Kombinacija justify i align                   |

### Svojstva za stavke (deca)

| Svojstvo        | Vrednosti       | Opis                                            |
|-----------------|-----------------|-------------------------------------------------|
| grid-column     | 1 / 3           | Kolone koje stavka zauzima                      |
| grid-row        | 2 / 4           | Redove koje stavka zauzima                      |
| grid-area       | "header"        | Imenovanje oblasti sa `grid-template-areas`     |

---

## Poređenje: Flexbox vs Grid

| Stavka             | Flexbox               | Grid                                      |
|--------------------|-----------------------|-------------------------------------------|
| Dimenzionalnost    | Jednodimenzionalan     | Dvodimenzionalan                         |
| Poravnanje         | Po jednoj osi          | Po obe ose                                |
| Preciznost         | Redosled stavki        | Precizno pozicioniranje                   |
| Idealno za         | Navigacije, liste     | Galerije, dashboard-i, layout sekcije     |
| Responzivnost      | Fleksibilan, ali manje precizan | Moćan za kompleksne rasporede            |

---

## Napomena
- Flexbox i Grid se **mogu kombinovati** – npr. Grid za glavni raspored, Flexbox za poravnanje unutar pojedinačnih elemenata.
- Oba sistema su podržana u svim modernim browserima.

---

position: static | relative | absolute | fixed | sticky

## Stilovi
Boje: color, background-color

Fontovi: font-family, font-size, line-height

##Responsivnost
@media screen and (max-width: 768px) {
  /* mobilna verzija */
}



+-------------------------------+ | Margin |
| +-------------------------+ | | | Border | | | | +-------------------+ | | | | | Padding | | | | | | +-------------+ | | | | | | | Content | | | | | | | +-------------+ | | | | | +-------------------+ | | | +-------------------------+ | +-------------------------------+
