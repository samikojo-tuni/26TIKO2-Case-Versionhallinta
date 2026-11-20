# Backend-kehitys, palvelinteknologiat ja tietokannat

## Mikä backend?
Sovelluksen palvelinpuoli, joka hoitaa kulissien takana datan käsittelyn, tietokantaoperaatiot ja autentikaation. Backend ei näy käyttäjälle mutta ilman sitä sovellus on hyödytön.
Kaikissa sovelluksissa ei ole backendia. Esimerkiksi pelkkä esittelysivu tai laskuri voi toimia kokonaan selaimessa. Backend on kuitenkin tarpeen, mikäli sovelluksen pitää muistaa käyttäjien tietoja, kirjata käyttäjä sisään tai käsitellä maksuja.

## Backend-kehittäjä
- Nettisivujen kehittäminen ja ylläpitäminen:
    - Prototyyppien tekeminen nettisivuiksi
    - Käyttää erilaisia työkaluja, viitekehyksiä ja ohjelmointikieliä
- Koodin kirjoittaminen:
    - Koodin laadun tulee olla hyvää ja ymmärrettävää
- Testien luominen koodille:
    - Vähintään yksikkötestien tekeminen omalle koodille
    - Testien tulee mennä läpi, ennen kuin koodia voi viedä tuotantoon
- Sovellusten nopeuden ja toimivuuden tarkkailu:
    - Kehittäjän tulisi olla ajan tasalla sovelluksen toimivuudesta ja sen soveltuvuudesta isompaan käyttäjämäärään
- Vianmäärittely ja selvitys:
    - Vikatilanteiden ratkominen ja niistä kommukoiminen mm. projektijohtajalle
- Opetus ja tuki:
    - Aloittelijoiden opettaminen

### Kehittäjän työkalut
- Backend-kehittäjien käyttämiä, suosittuja ohjelmointikieliä ovat mm:
    - Python, PHP, JavaScript, Ruby, Java, C#
- Viitekehyksiä hyödynnetään tarjoamaan valmiita komponentteja ja rakenteita nopeuttamaan kehitystyötä. Käytetyimpiä ovat:
    - Django, Laravel, Node.js, Spring
- Tietokantoja käytetään sovelluksen tietojen tallentamiseen ja hallitsemiseen. Käytettyjä tietokantoja ovat:
    - MongoDB, MySQL, Oracle, SQLite
- Web-palvelimia käytetään monissa projekteissa. Näitä ovat:
    - Apache, NGINX, Lighttpd, Microsoft IIS

## Palvelinteknologiat
Tarkoittavat ohjelmistoja, laitteistoja ja arkkitehtuureja, joiden avulla verkkosivustot, sovellukset ja pilvipalvelut toimivat ja palvelevat käyttäjiä. Tyypillisesti jaetaan palvelinlaitteistoihin, käyttöjärjestelmiin, verkkopalvelinohjelmistoihin, tietokantoihin ja ohjelmointiympäristöihin.

Saatetaan käyttää myös nimitystä backend-teknologia mutta teknisesti näillä kahdella on pieni sävyero. Backend-teknologia viittaa ensisijaisesti sovelluksen taustalogiikan ohjelmointiin, siinä missä palvelinteknologia kattaa myös itse palvelinympäristön ja infrastruktuurin.

### Palvelinteknologioiden keskeiset osa-alueet
- Ohjelmointikielet
    - Sovelluksen toimintalogiikka ja säännöt (kieliä esim. Python, JavaScript, Java, C#).
- Web-palvelinohjelmistot
    - Vastaanottavat käyttäjien pyyntöjä internetin yli ja reitittävät ne eteenpäin.
- Ohjelmistokehykset (frameworks)
    - Ohjelmoinnin apuväline, jonka tarkoituksena on nopeuttaa uusien ohjelmistotuotteiden valmistusta.
- Rajapinnat (API)
    - Sääntöjen ja määrittelyjen joukko, joka mahdollistaa kahden eri ohjelmiston tai järjestelmän välisen viestinnän ja tiedonvaihdon.
- Tietokannat
- Pilvipalvelut

## Tietokannat
### Relaatiotietokanta (SQL)

| ASIAKAS | TILAUS |
| ------- | -------|
| id = 1  | asiakas_id = 1 |
| nimi = Matti | tuote = läppäri |


- Tiedot tauluissa
- Selkeät suhteet taulujen välillä
- SQL-kyselyt
- Kiinteä rakenne

### Ei-relaatiotietokanta (NoSQL)
```
{
  "id": 1,
  "nimi": "Matti",
  "tilaukset": [
    {
      "tuote": "Läppäri"
    }
  ]
}
```
- Tiedot dokumentteina
- Joustava rakenne
- Ei pakollisia taulusuhteita
- Soveltuu suurille tietomäärille
