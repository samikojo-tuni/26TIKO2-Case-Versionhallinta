## 1. Pääotsikko

Artikkelin otsikko, joka kertoo selkeästi, mitä aihetta artikkelissa käsitellään.

## 2. Johdanto

### 2.1. Aiheen tausta

SQL tulee englannin sanoista *Structured Query Language* eli rakenteinen kyselykieli. Se on ohjelmointikieli, jota on käytetty laajasti relaatiotietokantojen hallintaan 1970-luvulta lähtien. Näitä tietokantoja hallitaan relaatiotietokannan hallintajärjestelmällä (RDBMS). Aluksi tietojen tallentaminen oli kallista, joten SQL-tietokantojen suunnittelussa pyrittiin erityisesti vähentämään saman tiedon tallentamista moneen kertaan.

SQL on ollut käytössä jo vuosikymmeniä, ja useimmat tietokantojen kanssa työskentelevät asiantuntijat tuntevat sen. Ajan myötä tiedon määrä ja muodot ovat kuitenkin muuttuneet. Myös tallennustila, tietokoneiden teho ja tiedon analysoinnin tarpeet ovat kehittyneet. Siksi on syntynyt uusia tietokantatekniikoita, jotka sopivat paremmin uudenlaisiin käyttötarkoituksiin. Näitä tietokantoja kutsutaan yleensä NoSQL-tietokannoiksi.

NoSQL-tietokannat alkoivat yleistyä 2000-luvun lopulla, kun tietojen tallentaminen tuli paljon halvemmaksi.

Kun tallentaminen halpeni nopeasti, sovellusten piti tallentaa ja käsitellä yhä suurempia tietomääriä. Tiedot olivat monenlaisia: rakenteisia, puolirakenteisia ja rakenteettomia. Siksi niiden rakennetta oli yhä vaikeampi määritellä etukäteen. NoSQL-tietokannat antavat kehittäjille mahdollisuuden tallentaa erittäin suuria määriä rakenteetonta tietoa ja muuttaa tietojen rakennetta joustavasti.

Vuonna 2009 kiinnostus NoSQL-tietokantoja kohtaan kasvoi selvästi. Tähän vaikuttivat myös kaksi tärkeää dokumenttitietokantaa: MongoDB ja CouchDB. 2010-luvulle tultaessa oli syntynyt erilaisia NoSQL-tietokantatyyppejä. Niiden käyttö alkoi levitä, kun yritykset alkoivat hyödyntää tietoa yhä enemmän.


### 2.2. Aiheen merkitys
Tietokannan valinta tai sopivan tietokannan suositteleminen on tärkeä tehtävä monille tietokanta-alan asiantuntijoille. SQL:n ja NoSQL:n vertailu auttaa tekemään perusteltuja valintoja. Valinnassa pitää ottaa huomioon tärkeimmät tietoja koskevat vaatimukset. Lisäksi on mietittävä, mistä ominaisuuksista voidaan tarvittaessa joustaa, jotta järjestelmä toimii riittävän nopeasti ja pysyy käytettävissä.

## 3. Keskeiset käsitteet

### 3.1. Peruskäsitteet

#### 3.1.1. SQL

SQL:ää käytetään edelleen paljon relaatiotietokantojen kyselyissä. Relaatiotietokannoissa tiedot tallennetaan taulukoiden riveille, ja taulukot voivat liittyä toisiinsa eri tavoin. Yksi tietue voi liittyä yhteen tai useaan muuhun tietueeseen. Myös yhden taulukon monet tietueet voivat liittyä toisen taulukon moniin tietueisiin. Relaatiotietokannat voivat tallentaa ja hakea tietoja nopeasti sekä käsitellä suuria tietomääriä ja monimutkaisia SQL-kyselyitä.

#### 3.1.2. NoSQL

NoSQL tarkoittaa ei-relationaalisia tietokantoja. Niissä tietoja voidaan tallentaa myös muilla tavoilla kuin SQL-tietokantojen riveistä ja sarakkeista koostuviin taulukoihin. Siksi tietojen rakenteeksi voidaan valita juuri niille sopiva muoto.

Kun puhutaan NoSQL-tietokannasta, tarkoitetaan yleensä mitä tahansa ei-relationaalista tietokantaa. NoSQL voidaan selittää sanoilla *non-SQL* (ei SQL) tai *not only SQL* (ei pelkästään SQL). Molemmat nimet viittaavat siihen, että tietoja voidaan tallentaa joustavasti ja niiden luonteeseen sopivalla tavalla. NoSQL tarkoittaa erilaisten tietokantojen lähestymistapaa, kun taas SQL on kyselykieli. Myös NoSQL-järjestelmillä on omia kyselykieliään.

**NoSQL-tietokantojen päätyypit**

NoSQL-tietokannoista on kehittynyt neljä päätyyppiä: dokumenttitietokannat, avain–arvo-tietokannat, laajasarakkeiset tietokannat ja graafitietokannat. Lisäksi monimalliset tietokannat ovat nykyään yhä suositumpia.

**Dokumenttitietokanta (Document database)** tallentaa tiedot dokumentteihin, jotka muistuttavat JSON-objekteja (*JavaScript Object Notation*). Jokaisessa dokumentissa on kenttiä ja niihin liittyviä arvoja. Arvot voivat olla esimerkiksi tekstiä, numeroita, totuusarvoja, listoja tai toisia objekteja. Dokumenttitietokannan tietomalli on joustava, ja se sopii hyvin puolirakenteiselle sekä usein myös rakenteettomalle tiedolle. Dokumentin sisällä voi olla myös sisäkkäisiä rakenteita. Niiden avulla voidaan kuvata monimutkaisia suhteita ja hierarkioita.

**Avain–arvo-tietokanta (Key-value database)** on yksinkertaisempi tietokantatyyppi. Jokaisella tallennetulla tiedolla on avain ja siihen liittyvä arvo. Jokainen avain on yksilöllinen. Tällaisia tietokantoja käytetään esimerkiksi välimuistissa ja käyttäjäistuntojen hallinnassa. Tietojen lukeminen ja kirjoittaminen on usein nopeaa, koska tietoja voidaan säilyttää keskusmuistissa.

**Laajasarakkeinen tietokanta (Wide-column database)** järjestää tiedot taulukoihin, riveihin ja muuttuviin sarakkeisiin. Toisin kuin perinteisissä SQL-tietokannoissa, eri riveillä voi olla eri sarakkeita. Tällainen tietokanta voi myös pakata sarakkeiden tietoja, jotta tallennustilaa kuluu vähemmän ja toiminta nopeutuu. Malli sopii harvalle tiedolle eli tilanteisiin, joissa monista kohdista puuttuu arvo.

**Graafitietokanta (Graph database)** tallentaa tiedot solmuina ja niiden välisinä yhteyksinä. Solmut voivat kuvata esimerkiksi ihmisiä, paikkoja tai esineitä. Yhteydet kertovat, miten solmut liittyvät toisiinsa. Graafitietokanta sopii hyvin tietoihin, joissa on paljon erilaisia yhteyksiä ja joissa yhteydet eivät aina ole heti selviä.

**Monimallinen tietokanta (Multi-model database)** tukee useampaa kuin yhtä NoSQL-tietomallia. Siksi kehittäjät voivat käyttää eri rakenteita sovelluksen tarpeiden mukaan. Samalla tietokannan hallintajärjestelmällä voidaan käsitellä useita tietomalleja yhdessä tietokannassa.


### 3.2. Käsitteiden väliset yhteydet



## 4. Aiheen kuvaus

### 4.1. Tarkoitus ja toimintaperiaatteet



### 4.2. Menetelmät ja käytännöt


### 4.3. Käyttökohteet



### 4.4. Hyödyt ja mahdollisuudet


### 4.5. Haasteet, riskit ja rajoitukset



## 5. Esimerkki

### 5.1. Tilanteen kuvaus



### 5.2. Ratkaisu tai toimintatapa


### 5.3. Tulokset ja havainnot



## 6. Yhteenveto ja lähteet

### 6.1. Yhteenveto



### 6.2. Lähteet


