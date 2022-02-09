# Osnove Haskela

## O haskelu

Haskel je funkcionalni programski jezik. Hakel je dizajniran početkom devedetih kodina prošlog veka, po uzoru na funkcionalne jezike kao što su [Miranda](https://en.wikipedia.org/wiki/Miranda_(programming_language)) i [ML](https://en.wikipedia.org/wiki/ML_(programming_language))

Haskel je danas sinonim za funkcionalnu paradigmu, jer mnoge karakteristike Haskel jezika vezujemo za funkcionalnu paradigimu:

+ **Funkije kao građani prvog reda.** Haskel dozvoljava programeru baratanje sa funkcijama kao što je to slučaj sa promenljivama.
+ **Funkcije su čiste.** Za razliku od imperativnih i objektno orijentisanih porogramskih jezika, u funkcije u Haskelu su čiste, što znači funkcije ne zavise od globalnog stanja, niti mogu da menjaju to stanje. Na taj način pojam *funkcije* u Haskelu više odgovara *matematičkom* pojmu funkcije nego što je to slučaj sa ostalim jezicima.
+ **Lenjo izračunavanje.** Zbog toga što su funkcije u Haskelu čiste, Haskel može da odlaže izračunavanje neke funkcije, dokle god je to moguće. Između ostalog, to omogućuje programeru da radi sa beskonačnim strukturama podataka u Haskelu.
+ **Jak sistem tipova.** Veliki deo Haskel jezika (i programiranja u Haskelu) se odnosi na sistem tipova. Haskel je statički tipiziran jezik sa . Takođe, sistem tipova je dovoljno moćan da kompajler može sam zaključiti tip izraza (ovo je omogućuno [Hindley–Milner](https://en.wikipedia.org/wiki/Hindley%E2%80%93Milner_type_system) sistemom tipova)

Haskel je dobio ime po američkom logičaru [Haskell Curry-ju](https://en.wikipedia.org/wiki/Haskell_Curry).

## Instalacija Haskel okruženja

Iako je tokom istorije Haskela razvijeno nekoliko kompajlera, danas se koristi samo *Glasgow Haskell Compiler* (GHC). Osim kompajlera, za bilo kakvi ozbiljniji rad potreban je i jedan od paketa menadžera: *Stack* ili *Cabal*. Takođe je korisno imati instaliran i *Haskell Language Server* (HSL).

Instalacija navedenih programa razlikuje se u zavisnosti od sistema do sistema. Trenutuno se preporučuje [GHCup](https://www.haskell.org/ghcup/) kao alat za automatsku instalaciju svih potrebnih programa.

## Aritmetički i logički izrazi

U terminalu pokrenimo `ghci`. Pojaviće se tekst poput sledećeg

```plaintext
GHCi, version 8.10.7: https://www.haskell.org/ghc/  :? for help
Prelude> 
```

Linija `Prelude>` označava prompt, odnoso prostor za unos naredbi i Haskel koda. *Prelude* je ime standardne Haskell biblioteke.

Propmt se može promeniti, u npr. `>`, pomoću naredbe `:set prompt ">"`. U nastavku teksta ćemo koristiti `>` za prompt.




## Funkcije

## Liste i niske

## n-torke
