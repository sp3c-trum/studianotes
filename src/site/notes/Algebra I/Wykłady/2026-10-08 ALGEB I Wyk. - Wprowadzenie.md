---
{"dg-publish":true,"permalink":"/algebra-i/wyklady/2026-10-08-algeb-i-wyk-wprowadzenie/","title":"2026-10-08 ALGEB I Wyk. - Wprowadzenie","dg-note-properties":{"title":"2026-10-08 ALGEB I Wyk. - Wprowadzenie","startTime":"08:00","endTime":"10:00","date":"2026-10-08","endDate":null,"completed":null,"timezone":"Europe/Warsaw"}}
---


# Informacje
- Email: bakowska@umk.pl
- 14.01 o godzinie 8:00 - egzamin zerowy
- 05.02 - egzamin pierwszy
- Poprawa w drugiej polowie marca
- Kup zeszyt (opcjonalnie)

# Wektor i skalar
**Skalar:**
- Wielkosc fizyczna
- Zdefiniowany przez wartosc liczbowa 
- Np. Wysokosc, masa

**Wektor:**
- Wielkosc fizyczna
- Zdefinioawny przez wartosc liczbowa, okreslony w przestrzeni, posiada kierunek i zwrot
- Np. Predkosc

Wektor posiada:
- Dlugosc
- Kierunek i zwrot
- Punkt przylozenia/zaczepienia

# Podstawowe operacje na wektorach
${}\alpha \vec{a}{}$ - Mnozenie wektora przez skalar
${}0 * \vec{a} = \vec{0}{}$ - Wektor zerowy
${}\vec{a} + \vec{b}{}$ - Dodawanie wektorow

## Kombinacje liniowe
${}d_{1}\vec{a_{1}} + d_{2}\vec{a_{2}} +... + d_{n}\vec{a_{n}} = \vec{0}{}$

Jezeli rownosc ta jest spelniona jedynie, gdy ${}d_{1} = 0{}$ dla kazdego ${}1 = 1,2,...,n{}$ to wektory ${}\vec{a_{i}}{}$ sa liniowo niezalezne.

Jezeli rownosc ta jest spelniona gdy chociaz jedno ${}d_{i}{}$ jest rozne od zera, to wektory ${}\vec{a_{i}}{}$ sa liniowo zalezne.

Najwieksza liczba wektorow liniowo niezaleznych w danej przestrzeni to wymiar tej przestrzeni.

${}\alpha \vec{a} + \beta \vec{b} = \vec{0}{}$
Jezeli ${}\alpha \neq 0{}$ lub ${}\beta \neq 0{}$, to wektory ${}\vec{a}{}$ i ${}\vec{b}{}$ sa wspoliniowe (kolinearne)

${}\alpha \vec{a} + \beta \vec{b} + \gamma \vec{c}= \vec{0}{}$
Jezeli ${}\alpha\neq 0{}$ lub ${}\beta\neq 0{}$ lub ${}\gamma\neq 0{}$, to wektory ${}\vec{a}, \vec{b}, \vec{c}{}$ sa wspolplaszczyznowe (koplearne).

# Baza, skladowe, wspolrzedne
Jezeli ${}\vec{a}{}$ i ${}\vec{b}{}$ sa liniowo niezalezne to tworza baze na plaszczyznie. Kazdy wektor na tej plaszczyznie daje sie w sposob jednoznaczny przedstawic przez te wektory. 

Wektory ${}\vec{a}{}$ i to skladowe wektora ${}\vec{c}{}$ w tej bazie, a liczby ${}\alpha,\beta{}$ to jego wspolrzedne.
${}\vec{c} = \vec{c_{a}} + \vec{c_{b}} = (\alpha, \beta){}$

Wspolrzedne kartzejanskie:
${}\vec{w} = w_{x}\vec{e_{x}} + w_{y}\vec{e_{y}} + w_{z}\vec{e_{z}} = (w_{x}, w_{y}, w_{z}){}$

${}\vec{u}, \vec{v}{}$ - Wektory bazy
${}\vec{a} = a_{u}\vec{u} + a_{v}\vec{v}{}$
${}\vec{b} = b_{u}\vec{u}+b_{v}\vec{v}{}$

# Mnozenie przez skalar
${}\alpha \vec{a}=\alpha(a_{\vec{u}} +a_{v}\vec{v}) = \alpha a_{u}\vec{u} + \alpha a_{v}\vec{v} = (\alpha a_{u}, \alpha a_{v}){}$
Wynikiem mnozenia przez skalar zawsze jest **wektor**.

# Dodawanie 
${}\vec{a} + \vec{b} = a_{u}\vec{u} + a_{v}\vec{v} + b_{u}\vec{u} + b_{v}\vec{v} = (a_{u} + b_{u})\vec{u} + (a_{v} + b_{v})\vec{v} = (a_{u} + b_{u}, a_{v}+b_{v}){}$

# Zadania
### Przyklad 1:
${}\vec{u}, \vec{v}{}$ - liniowo niezalezne
${}\alpha \vec{u} + \beta \vec{v} = \vec{0}{}$ to ${}\alpha = \beta = 0{}$ jest jedynym rozwiazaniem
${}\vec{a} = 2 \vec{u} - \vec{v}{}$
${}\vec{b} = \vec{u} + 2\vec{v}{}$

Czy ${}{\vec{a}, \vec{b}}{}$ jest zbiorem wektorow liniowo niezaleznych?