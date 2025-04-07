* {}            /* univerzalni */
* h1 {}           /* tag */
* #id {}          /* ID */
* .class {}       /* klasa */
* div p {}        /* potomci */

## Box Model
content → padding → border → margin

## Layout
display: flex;

display: grid;

position: static | relative | absolute | fixed | sticky

## Stilovi
Boje: color, background-color

Fontovi: font-family, font-size, line-height

📊 Ključne razlike: Flexbox vs Grid
Stavka	Flexbox	Grid
Dimenzija	Jednodimenzionalan (red/kolona)	Dvodimenzionalan (red i kolona)
Kontrola	Redosled elemenata	Precizna pozicija (grid areas)
Kompleksnost	Jednostavan	Moćan za kompleksne layoute
Responzivnost	Fleksibilan, ali ograničen	Idealno za responsivne mreže
Primer upotrebe	Navbar, dugmići u redu	Galerije, kartični layout
Dimenzije: width, height, %, px, em, rem

##Responsivnost
@media screen and (max-width: 768px) {
  /* mobilna verzija */
}
