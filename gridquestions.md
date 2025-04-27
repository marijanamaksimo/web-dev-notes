# 📖 Web Development Pitanja i Odgovori

## 📝 Pitanja

1. Napiši korake u komunikaciji između klijenta i servera.
2. Napiši time and space complexity poznatih sorting algoritama (prosečan slučaj za vreme).
3. Šta je SPA (Single Page Application)?
4. Razlika između `<span>` i `<div>`.
5. Objasni closure koncept u JavaScriptu.
6. Objasni box model u CSS-u.
7. Razlika između id-a i class-e u CSS-u.
8. Šta je CSS specificity?
9. Navedi karakteristike objektno-orijentisanog programiranja (OOP).
10. Razlika između `let`, `const` i `var`.
11. Šta je singleton pattern?
12. Razlika između `==` i `===` u JavaScriptu.
13. Šta je hoisting u JavaScriptu?
14. Razlika između block, inline i inline-block elemenata u CSS-u.
15. Objasni event loop u JavaScriptu.
16. Šta su microtasks i macrotasks u JavaScriptu?
17. Šta je scope u JavaScriptu?
18. Šta su meta tagovi u HTML-u?
19. Šta je callback hell?
20. Za šta su skraćenice IIFE i DRY?
21. Razlika između Jave i JavaScripta.
22. Šta su klase u JavaScriptu?
23. Kako radi `this` u JavaScriptu?
24. Razlika između `null` i `undefined`.
25. Kako implementirati responsive dizajn?
26. Šta su pseudo-klase i pseudo-elementi u CSS-u?
27. Kako funkcioniše CSS specificity (dodatno objašnjenje)?
28. Osnove GIT-a: Kako napraviti branch?
29. Kako rešiti merge conflict u GIT-u?

## 📝 Pitanja i Odgovori

1. **Napiši korake u komunikaciji između klijenta i servera.**
   - Klijent šalje HTTP zahtev serveru → Server prima zahtev → Server obrađuje zahtev → Server šalje HTTP odgovor → Klijent prikazuje rezultat korisniku.

2. **Napiši time and space complexity poznatih sorting algoritama (prosečan slučaj za vreme).**
   - Bubble Sort: Time O(n²), Space O(1)
   - Insertion Sort: Time O(n²), Space O(1)
   - Selection Sort: Time O(n²), Space O(1)
   - Merge Sort: Time O(n log n), Space O(n)
   - Quick Sort: Time O(n log n), Space O(log n)
   - Heap Sort: Time O(n log n), Space O(1)

3. **Šta je SPA (Single Page Application)?**
   - Aplikacija koja učitava jednu HTML stranicu i dinamički menja sadržaj bez ponovnog učitavanja stranice sa servera.

4. **Razlika između `<span>` i `<div>`.**
   - `<span>` je inline element (ne pravi novi red), a `<div>` je block element (zauzima ceo red).

5. **Objasni closure koncept u JavaScriptu.**
   - Closure je funkcija koja "pamti" promenljive iz svog spoljnog okruženja čak i nakon što je to okruženje završilo sa izvršavanjem.

6. **Objasni box model u CSS-u.**
   - Box model se sastoji od: Content → Padding → Border → Margin.

7. **Razlika između id-a i class-e u CSS-u.**
   - `id` je jedinstven za ceo dokument (koristi se jednom), dok `class` može biti primenjen na više elemenata.

8. **Šta je CSS specificity?**
   - Pravilo koje određuje koji CSS selektor ima prednost kada više selektora cilja isti element.

9. **Navedi karakteristike objektno-orijentisanog programiranja (OOP).**
   - Nasleđivanje (Inheritance), Polimorfizam (Polymorphism), Enkapsulacija (Encapsulation), Apstrakcija (Abstraction).

10. **Razlika između `let`, `const` i `var`.**
    - `var` ima function scope, može biti redeklarisan.  
    - `let` ima block scope, ne može biti redeklarisan.  
    - `const` ima block scope i vrednost se ne može menjati.

11. **Šta je singleton pattern?**
    - Dizajn šablon koji omogućava kreiranje samo jedne instance klase.

12. **Razlika između `==` i `===` u JavaScriptu.**
    - `==` upoređuje vrednosti uz konverziju tipova, dok `===` upoređuje i vrednost i tip bez konverzije.

13. **Šta je hoisting u JavaScriptu?**
    - Mehanizam gde deklaracije promenljivih i funkcija bivaju "podignute" na vrh svoje scope pre izvršavanja koda.

14. **Razlika između block, inline i inline-block elemenata u CSS-u.**
    - Block: zauzima ceo red (npr. `<div>`)
    - Inline: ne pravi novi red (npr. `<span>`)
    - Inline-block: ponaša se kao inline ali može imati dimenzije (width, height).

15. **Objasni event loop u JavaScriptu.**
    - Mehanizam koji omogućava JavaScriptu da izvršava asinhroni kod tako što obrađuje stack i queue događaja.

16. **Šta su microtasks i macrotasks u JavaScriptu?**
    - Microtasks (npr. Promise callbacks) imaju viši prioritet od macrotasks (npr. setTimeout, setInterval).

17. **Šta je scope u JavaScriptu?**
    - Scope definiše vidljivost i dostupnost promenljivih i funkcija u određenim delovima koda.

18. **Šta su meta tagovi u HTML-u?**
    - Tagovi koji sadrže metapodatke o HTML dokumentu (npr. charset, viewport, description).

19. **Šta je callback hell?**
    - Situacija kada se višestruki callback-ovi ugnjezde jedni u druge, što otežava čitanje i održavanje koda.

20. **Za šta su skraćenice IIFE i DRY?**
    - IIFE: Immediately Invoked Function Expression (funkcija koja se odmah izvršava).  
    - DRY: Don't Repeat Yourself (princip izbegavanja ponavljanja koda).

21. **Razlika između Jave i JavaScripta.**
    - Java: kompajlirani, objektno-orijentisani jezik.  
    - JavaScript: interpretirani, skriptni jezik za web aplikacije.

22. **Šta su klase u JavaScriptu?**
    - Sintaksni šećer preko prototype-based nasleđivanja za pravljenje objekata i upravljanje njihovim ponašanjem.

23. **Kako radi `this` u JavaScriptu?**
    - `this` se odnosi na objekat koji poziva funkciju; zavisi od konteksta (globalni, objekat, eksplicitno definisano).

24. **Razlika između `null` i `undefined`.**
    - `null` predstavlja namerno odsustvo vrednosti.  
    - `undefined` znači da promenljivoj nije dodeljena vrednost.

25. **Kako implementirati responsive dizajn?**
    - Korišćenjem media query-a, fleksibilnih layout-a (flexbox, grid), relativnih jedinica (%, rem, em).

26. **Šta su pseudo-klase i pseudo-elementi u CSS-u?**
    - Pseudo-klase (`:hover`, `:focus`) ciljaju specifična stanja elemenata.  
    - Pseudo-elementi (`::before`, `::after`) kreiraju virtualne elemente.

27. **Kako funkcioniše CSS specificity (dodatno objašnjenje)?**
    - Specificity zavisi od broja ID-a, klasa i tagova u selektoru. Računa se kao numerička vrednost:  
      ID (100) > Class/Pseudo-klasa (10) > Tag/Pseudo-element (1).

28. **Osnove GIT-a: Kako napraviti branch?**
    - Komanda: `git checkout -b naziv-brancha`

29. **Kako rešiti merge conflict u GIT-u?**
    - Otvoriti fajlove sa konfliktima → ručno izabrati ispravan kod → sačuvati → dodati izmene (`git add`) → napraviti commit (`git commit`).
