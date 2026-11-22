# Big Data ja dataputket
 
## 1. Pääotsikko
Big Data ja dataputket
 
## 2. Johdanto
 
### 2.1 Aiheen tausta
 
Big Data tai toiselta nimeltään massadata tarkoittaa erittäin suuria ja monimuotoisia tietomääriä. Massadataa syntyy jatkuvasti eri lähteistä. Se voi sisältää esimerkiksi kuvia, tekstiä, videoita jne. Sen käsittely yleensä tarvitsee erityisiä teknologioita ja menetelmiä, jotta sitä pystyttäisiin käsittelemään tehokkaasti. Kaiken datan määrä kasvaa jatkuvasti, koska ihmiset ja laitteet tuottavat tietoa koko ajan.

Internet, Pilvipalvelut ja IoT-laitteet vaikuttavat massadataan erilaisin tavoin. Internet mahdollistaa tiedon tuottamisen ja jakamisen maailmanlaajuisesti. Pilvipalvelut ovat tehneet tiedon keräämisestä ja käsittelystä helpompaa ja edullisempaa. IoT (Internet of Things) laitteet lähettävät jatkuvasti tietoa mikä kasvattaa datan määrää.

Massadataa syntyy paljon ja nopeasti, johon perinteisten järjestelmien yhdellä palvelimella tehty käsittely ei aina riitä. Esimerkiksi tallennustila voi loppua, käsittely hidastua jne. Suurten tietomäärien käsittelyyn on kehitetty uusia teknologioita, kuten Kafka, Spark ja Hadoop. Dataputket taas ovat kehittyneet automatisoiduiksi järjestelmiksi, jotka pystyvät käsittelemään ja siirtämään dataa reaaliajassa.
 
## 2.2 Aiheen merkitys

Big Data on tärkeä osa nykyaikaista ICT-alaa, koska digitaalisten palvelujen käyttö 
tuottaa jatkuvasti suuria määriä dataa. Yritykset keräävät tietoa esimerkiksi 
verkkosivustoilta, mobiilisovelluksista, antureista ja sosiaalisesta mediasta. 
Tämän datan avulla voidaan analysoida käyttäjien toimintaa, tunnistaa trendejä
ja tehdä päätöksiä aiempaa tarkemmin.

Big Datan hyödyntäminen auttaa yrityksiä kehittämään palveluitaan, tehostamaan 
toimintaansa ja vastaamaan asiakkaiden tarpeisiin paremmin. Datan perusteella 
voidaan myös ennustaa tulevia muutoksia ja tunnistaa uusia 
liiketoimintamahdollisuuksia.

Dataputkilla on keskeinen rooli datan keräämisessä, siirtämisessä, käsittelyssä 
ja tallentamisessa. Ne mahdollistavat tiedon kulkemisen eri järjestelmien välillä
sekä varmistavat, että data on saatavilla analysointia ja päätöksentekoa varten. 
Ohjelmistokehittäjien on tärkeää ymmärtää datan kulkua järjestelmissä, jotta 
sovellukset toimivat tehokkaasti ja luotettavasti.

Ilman hyvin suunniteltuja dataputkia data voi olla hajallaan eri järjestelmissä, 
tiedot voivat vanhentua tai analytiikka voi perustua puutteelliseen informaatioon. 
Tämä voi heikentää päätöksenteon laatua ja aiheuttaa ongelmia liiketoiminnalle. 
Tehokkaat dataputket tukevat yritysten toimintaa mahdollistamalla ajantasaisen 
tiedon hyödyntämisen ja prosessien automatisoinnin.

## 3. Keskeiset käsitteet
 
### 3.1 Peruskäsitteet

#### Big Data

Big Data tarkoittaa erittäin suuria ja monimutkaisia tietomääriä, joita 
perinteiset tietojenkäsittelymenetelmät eivät pysty käsittelemään tehokkaasti. 
Big Dataa syntyy jatkuvasti esimerkiksi sosiaalisessa mediassa, IoT-laitteissa, 
verkkopalveluissa ja yritysten liiketoimintajärjestelmissä.

#### Dataputki (Data Pipeline)

Dataputki on prosessi, joka siirtää dataa lähteestä kohdejärjestelmään. 
Dataputken tehtävänä on kerätä, käsitellä, muuntaa ja toimittaa data analysointia 
tai tallennusta varten.

#### Datalähde

Datalähde on paikka, josta data kerätään. Datalähteitä voivat olla 
esimerkiksi tietokannat, verkkosovellukset, sensorit, lokitiedostot 
tai sosiaalisen median palvelut.

#### ETL (Extract, Transform, Load)

ETL on prosessi, jossa data ensin kerätään lähteistä (Extract), 
sitten muunnetaan sopivaan muotoon (Transform) ja lopuksi tallennetaan
kohdejärjestelmään (Load). ETL on keskeinen osa monia dataputkia.

#### Data Warehouse

Data Warehouse eli tietovarasto on järjestelmä, johon kerätään ja 
tallennetaan dataa useista eri lähteistä. Tietovarastoa käytetään 
erityisesti raportointiin, analytiikkaan ja liiketoimintatiedon käsittelyyn.

#### Reaaliaikainen data-analytiikka

Reaaliaikainen data-analytiikka tarkoittaa datan analysointia heti 
sen syntymisen jälkeen. Tämän avulla voidaan havaita tapahtumia, 
poikkeamia tai trendejä lähes välittömästi.

#### Hadoop

Hadoop on avoimen lähdekoodin ohjelmistokehys suurten tietomäärien 
hajautettuun tallennukseen ja käsittelyyn. Se mahdollistaa datan 
käsittelyn useilla palvelimilla samanaikaisesti.

#### Apache Spark

Apache Spark on nopea hajautetun datankäsittelyn alusta. Sitä käytetään 
suurten tietomäärien analysointiin, koneoppimiseen sekä reaaliaikaiseen 
datankäsittelyyn.

#### Apache Kafka

Apache Kafka on hajautettu viestinvälitysjärjestelmä, joka mahdollistaa 
suurten tietovirtojen käsittelyn reaaliaikaisesti. Sitä käytetään usein
dataputkissa datan siirtämiseen järjestelmien välillä.
 
### 3.2 Käsitteiden väliset yhteydet

Big Data -järjestelmässä data liikkuu useiden vaiheiden kautta ennen 
kuin sitä voidaan hyödyntää analytiikassa. Prosessi alkaa datalähteistä, 
joista tieto kerätään ja siirretään dataputken kautta käsiteltäväksi. 
Käsittelyn jälkeen data tallennetaan tietovarastoon tai muuhun 
tallennusjärjestelmään, josta analytiikkatyökalut voivat käyttää sitä.

Datalähde, dataputki ja tietovarasto ovat eri osia datan 
käsittelyprosessissa. Datalähde tuottaa dataa, dataputki siirtää 
ja käsittelee sitä, ja tietovarasto säilyttää dataa myöhempää analysointia 
varten. Jokaisella osalla on oma tärkeä tehtävänsä tiedonhallinnassa.

ETL-prosessi liittyy läheisesti dataputkeen. ETL:n aikana data ensin 
kerätään eri lähteistä (Extract), muunnetaan analysointiin sopivaan 
muotoon (Transform) ja lopuksi tallennetaan kohdejärjestelmään (Load). 
Monet dataputket perustuvat juuri tähän toimintamalliin.

Analytiikka hyödyntää dataputken kautta saatua dataa tuottamalla tietoa,
raportteja ja havaintoja päätöksenteon tueksi. Laadukas dataputki varmistaa,
että analysoitava data on ajantasaista, yhtenäistä ja luotettavaa.

#### Datan kulku

```text
Datalähde
    ↓
Dataputki
    ↓
Käsittely
    ↓
Tallennus
    ↓
Analytiikka


## 4. Aiheen kuvaus

### 4.1 Tarkoitus ja toimintaperiaatteet

Big Dataa käytetään ratkaisemaan ongelmia, jotka liittyvät suurten 
tietomäärien keräämiseen, käsittelyyn ja analysointiin. Organisaatiot
voivat hyödyntää Big Dataa esimerkiksi asiakaskäyttäytymisen 
ymmärtämisessä, liiketoiminnan kehittämisessä ja päätöksenteon 
tukemisessa.

Dataputken päätarkoituksena on siirtää data tehokkaasti lähteestä 
kohdejärjestelmään. Samalla dataputki huolehtii datan käsittelystä
ja muuntamisesta sellaiseen muotoon, että sitä voidaan hyödyntää 
analytiikassa.

Data kerätään erilaisista lähteistä, kuten tietokannoista,
verkkopalveluista, sensoreista ja sovelluksista. Tämän jälkeen data
siirretään dataputken kautta käsiteltäväksi, tallennetaan sopivaan 
järjestelmään ja lopulta analysoidaan.

Dataputken tärkeimpiä vaiheita ovat datan kerääminen, siirtäminen, 
käsittely, tallennus ja analysointi. Jokainen vaihe vaikuttaa koko 
järjestelmän tehokkuuteen.

Dataputken toimivuuteen vaikuttavat muun muassa datan määrä,
tiedonsiirron nopeus, järjestelmien luotettavuus, tietoturva sekä 
käytettävät teknologiat.

### 4.2 Menetelmät ja käytännöt

Big Datan käsittelyssä käytetään erilaisia prosesseja ja 
teknologioita, jotta dataa voidaan käsitellä tehokkaasti. 
Yksi yleisimmistä prosesseista on ETL (Extract, Transform, Load), 
jossa dataa kerätään lähteestä, muokataan ja tallennetaan 
tietovarastoon. Dataa voidaan käsitellä joko Batch Processing- 
tai Stream Processing -menetelmällä. Batch Processing -menetelmällä
tietoa käsitellään suurissa erissä tietyin aikavälein. 
Stream Processing -menetelmällä tietoa käsitellään reaaliaikaisesti
sen syntyessä.

Datankäsittelyssä hyödynnetään usein pilvipalveluita, jotka
tarjoavat joustavan tallennus- ja laskentakapasiteetin. 
Pilvipalveluiden etuna on myös niiden hyvä skaalautuvuus 
kasvaville datamäärille. Big Datan käsittelyssä käytetään 
teknologioita, kuten Hadoop, Apache Spark ja Apache Kafka.
Hadoop mahdollistaa datan hajautetun käsittelyn, Apache Spark
nopeuttaa datan analysointia ja Apache Kafka tukee reaaliaikaista
datansiirtoa. Käsittelymenetelmän valinta riippuu 
käyttötarkoituksesta, datan määrästä sekä siitä, käsitelläänkö 
dataa reaaliaikaisesti vai tietyin aikavälein.

### 4.3 Käyttökohteet

Big Dataa käytetään laajasti eri toimialoilla. Sosiaalisen median 
palvelut hyödyntävät sitä käyttäjien toiminnan analysointiin ja 
sisällön suositteluun.

Verkkokaupat käyttävät dataa asiakkaiden ostokäyttäytymisen 
analysointiin, kun taas suoratoistopalvelut hyödyntävät sitä 
personoitujen sisältösuositusten tarjoamiseen.

IoT-laitteet tuottavat jatkuvasti suuria määriä dataa, jota voidaan 
analysoida reaaliajassa. Finanssialalla Big Dataa käytetään
esimerkiksi petosten tunnistamiseen ja riskienhallintaan.

Terveydenhuollossa dataa voidaan hyödyntää potilastietojen 
analysointiin, sairauksien ennustamiseen sekä hoitoprosessien 
kehittämiseen.

### 4.4 Big Datan edut ja mahdollisuudet

Big Data auttaa organisaatioita tekemään tietoon perustuvia
päätöksiä. Analysoimalla suuria tietomääriä voidaan tunnistaa 
trendejä, ennakoida muutoksia ja parantaa liiketoiminnan 
tehokkuutta.

Datan hyödyntäminen mahdollistaa tarkemman liiketoiminta-analytiikan 
sekä personoidut palvelut, jotka vastaavat paremmin asiakkaiden 
tarpeisiin.

Dataputket tukevat prosessien automatisointia ja reaaliaikaista
seurantaa. Lisäksi Big Data tarjoaa perustan tekoälyn ja 
koneoppimisen hyödyntämiselle.

### 4.5 Haasteet, riskit ja rajoitukset

Big Datan käytössä on myös haasteita. Tietoturva ja tietosuoja 
ovat keskeisiä kysymyksiä, koska järjestelmät käsittelevät usein 
suuria määriä arkaluonteista tietoa.

Datan laatu vaikuttaa suoraan analyysien luotettavuuteen. 
Virheellinen tai puutteellinen data voi johtaa epäluotettaviin 
tuloksiin.

Suurten järjestelmien rakentaminen ja ylläpito voivat aiheuttaa 
merkittäviä kustannuksia. Lisäksi Hadoopin, Sparkin ja Kafkan 
kaltaiset teknologiat voivat lisätä järjestelmän monimutkaisuutta 
ja ylläpitotarvetta.

## 5. Esimerkki

### 5.1 Tilanteen kuvaus

Hyvä esimerkki Big Datan hyödyntämisestä on videopalvelu, 
kuten YouTube tai Netflix. Miljoonat käyttäjät katsovat videoita 
päivittäin eri laitteilla ja eri puolilla maailmaa.

Jokainen katselukerta, hakutoiminto, arviointi ja sisällön 
valinta tuottaa uutta dataa. Tämän seurauksena järjestelmä
kerää jatkuvasti erittäin suuria tietomääriä.

Palvelun tavoitteena on hyödyntää tätä dataa käyttäjien
mieltymysten ymmärtämiseen ja tarjota mahdollisimman osuvia
sisältösuosituksia.

### 5.2 Ratkaisu tai toimintatapa

Käyttäjien toiminta tallennetaan järjestelmään datana. 
Tiedot voivat sisältää esimerkiksi katsottuja videoita, 
katseluaikaa, hakuhistoriaa ja käyttäjän antamia arvioita.

Kerätty data siirtyy dataputken kautta käsiteltäväksi. 
Käsittelyn aikana data puhdistetaan, järjestellään ja
muunnetaan analysointiin sopivaan muotoon.

Tämän jälkeen tiedot tallennetaan tietovarastoon, jossa
niitä voidaan säilyttää ja hyödyntää myöhemmin. Tallennettua
dataa analysoidaan erilaisilla työkaluilla ja menetelmillä.

Analyysin tuloksia käytetään sisältösuositusten luomiseen. 
Näin palvelu voi ehdottaa käyttäjälle videoita ja ohjelmia, 
jotka vastaavat hänen kiinnostuksen kohteitaan.

### 5.3 Tulokset ja havainnot

Big Datan ja dataputkien hyödyntämisen ansiosta käyttäjät 
saavat tarkempia ja henkilökohtaisempia suosituksia. 
Tämä parantaa käyttökokemusta ja auttaa käyttäjiä löytämään 
heitä kiinnostavaa sisältöä.

Yritys saa samalla paremman käsityksen käyttäjien 
käyttäytymisestä, mieltymyksistä ja palvelun käytöstä. 
Näiden tietojen avulla voidaan kehittää palvelua sekä 
tehdä liiketoimintaa koskevia päätöksiä.

Esimerkki osoittaa, kuinka tärkeä rooli dataputkilla on 
Big Data -ympäristössä. Ilman tehokasta datan keräämistä, 
käsittelyä ja analysointia suurten tietomäärien hyödyntäminen
olisi huomattavasti vaikeampaa.

## 6. Yhteenveto ja lähteet

### 6.1 Yhteenveto

- Mitä Big Data tarkoittaa?
- Mikä on dataputki?
- Miten data liikkuu järjestelmissä?
- Mitkä ovat tärkeimmät menetelmät ja teknologiat?
- Mitä hyötyjä ja haasteita Big Dataan liittyy?
- Miksi aihe on tärkeä ICT-alan ammattilaisille?

### 6.2 Lähteet

- IBM: Big Data
- Microsoft Learn
- AWS Documentation
- Apache Hadoop Documentation
- Apache Kafka Documentation
- Apache Spark Documentation
- 