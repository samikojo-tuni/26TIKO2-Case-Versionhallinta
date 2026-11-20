# Laiteläheinen koodaus (C/C++, Arduino, Raspberry Pi)

##

## Laiteläheinen koodaus (eli sulautettu ohjelmointi) tarkoittaa koodin kirjoittamista mikrokontrollereille, suorittimille ja laitteistoille, jotka ohjaavat fyysisiä laitteita

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

##

## Laiteläheinen koodaus Arduinolla

- **Käytännössä** ohjelmointia, joka on suoraan yhteydessä fyysiseen laitteistoon, kuten antureihin, moottoreihin ja mikrokontrollerin rekistereihin. Tämä tehdään pääasiassa C/C++-kielellä, ja se mahdollistaa reaaliaikaisen reagoinnin fyysisen maailman tapahtumiin.

    **Pääpiirteet**

- Suora laitteiston ohjaus
- Laitteistotason väylät
- Resurssien hallinta
- Keskeyykset ja ajastimet

##

## Laiteläheinen koodaus Raspberry Pi -alustalla

- **Käytännössä** ohjelmistojen kirjoittamista, jotka keskustelevat suoraan fyysisen elektroniikan, kuten antureiden, moottoreiden ja LED-valojen kanssa. Tämä onnistuu Linux-pohjaisen tietokoneen (esim. Raspberry Pi 4 tai 5) tai erillisen mikrokontrollerin (Raspberry Pi Pico) avulla.

    **Alustat ja ohjelmointikielet**

- **Yhden piirilevyn tietokoneet (Raspberry Pi 3, 4, 5, Zero)** -  Nämä pyörittävät täyttä Linux-käyttöjärjestelmää, kuten Raspberry Pi OS -järjestelmää. Ne sopivat projekteihin, joissa tarvitaan verkkoyhteyttä, kameraa tai raskasta laskentaa.

- **Mikrokontrollerit (Raspberry Pi Pico)** - Pico ei pyöritä käyttöjärjestelmää, vaan se suorittaa yhtä ohjelmaa suoraan raudalla. Se soveltuu erinomaisesti tarkkaa reaaliaikaista ajoitusta vaativaan ohjaukseen ja paristokäyttöisiin laitteisiin.

- **Python ja GPIO Zero** - Aloittelijoille helpoin tapa ohjata nastoja Linux-ympäristössä on Python ja GPIO Zero -kirjasto.

- **C ja C++** - Kun tarvitaan maksimaalista suorituskykyä, pientä viivettä ja suoraa muistinhallintaa, käytetään C- tai C++-kieltä. Picolle on tarjolla oma virallinen C/C++ SDK.

> [Lähde: Linux.fi](https://www.linux.fi/wiki/Raspberry_Pi) , [mehackit.org](https://mehackit.org/kurssit/robotiikka_tulevaisuudessa/02-internet_of_things/04-raspberry_pin_testaaminen/)
