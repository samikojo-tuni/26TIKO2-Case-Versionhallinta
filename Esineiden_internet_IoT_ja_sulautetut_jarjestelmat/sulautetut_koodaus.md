# Laiteläheinen koodaus (C/C++, Arduino, Raspberry Pi)

##

### Laiteläheinen koodaus (eli sulautettu ohjelmointi) tarkoittaa koodin kirjoittamista mikrokontrollereille, suorittimille ja laitteistoille, jotka ohjaavat fyysisiä laitteita

- **Laitteistokontrolli:** Koodi kommunikoi suoraan laitteen rekisterien, antureiden (esim. lämpö- tai sykesensorit) ja toimilaitteiden (esim. moottorit, näytöt) kanssa.

- **Resurssirajoitteet:** Toisin kuin tietokoneohjelmissa, muistia (RAM/Flash) ja laskentatehoa on usein hyvin vähän, joten koodin täytyy olla tehokasta.

- **Tyypilliset kielet:** C- ja C++-kielet ovat alan standardeja, mutta myös Rust ja tietyin rajoituksin Python (esittelyt, MicroPython) ovat yleistyneet.

- **Käyttökohteet:** Älykellot (kuten Oura), autojen ohjausjärjestelmät, kodinkoneet, teollisuusautomaatio ja IoT-laitteet (Internet of Things).

> [Lähde: Punomo.fi](https://punomo.fi/johdanto-laitelaheiseen-ohjelmointiin/)

##

### Ero C:n ja C++:n välillä laiteläheisyydessä

- **C:** Puhdas, pelkistetty ja proseduraalinen kieli. Se on yhä standardivalinta pienille mikrokontrollereille ja ytimille , koska kääntäjän tekemä lopputulos on täysin ennustettavissa eikä kieli "piilota" alleen mitään automaattista taustatoimintaa.

- **C++:** Tarjoaa C:n tehon ja laiteläheisyyden lisäksi tyyppiturvallisuutta, olio-ohjelmointia sekä geneerisiä työkaluja. Nykyaikaisessa C++:ssa voi hyödyntää nollakustannusabstraktioita, jolloin korkeamman tason koodi on yhtä nopeaa kuin C, mutta turvallisempaa.

> [Lähde: Wikipedia](https://fi.wikipedia.org/wiki/C%2B%2B)
