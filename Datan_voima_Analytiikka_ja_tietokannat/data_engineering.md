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
 
- Big Data
- Dataputki (Data Pipeline)
- Datalähde
- ETL (Extract, Transform, Load)
- Data Warehouse
- Reaaliaikainen data-analytiikka
- Hadoop
- Apache Spark
- Apache Kafka
 
### 3.2 Käsitteiden väliset yhteydet
 
- Miten data liikkuu lähteestä analysointiin?
- Mikä ero on datalähteen, dataputken ja tietovaraston välillä?
- Miten ETL liittyy dataputkeen?
- Miten analytiikka hyödyntää dataputken kautta saatua dataa?
- Yksinkertainen kaavio datan kulusta:

Datalähde ↓ Dataputki ↓ Käsittely ↓ Tallennus ↓ Analytiikka


## 4. Aiheen kuvaus

### 4.1 Tarkoitus ja toimintaperiaatteet

- Mitä ongelmia Big Datan avulla ratkaistaan?
- Mikä on dataputken päätarkoitus?
- Miten data kerätään, siirretään, käsitellään ja tallennetaan?
- Mitkä ovat dataputken tärkeimmät vaiheet?
- Mitkä tekijät vaikuttavat dataputken toimivuuteen?

### 4.2 Menetelmät ja käytännöt

- ETL-prosessi
- Batch Processing
- Stream Processing
- Pilvipalveluiden käyttö datankäsittelyssä
- Hadoop-, Spark- ja Kafka-teknologiat
- Menetelmän valinta käyttötarkoituksen mukaan

### 4.3 Käyttökohteet

- Sosiaalinen media
- Verkkokaupat
- Suoratoistopalvelut
- IoT-laitteet
- Finanssiala
- Terveydenhuolto

### 4.4 Hyödyt ja mahdollisuudet

- Tietoon perustuva päätöksenteko
- Parempi liiketoiminta-analytiikka
- Personoidut palvelut
- Prosessien automatisointi
- Reaaliaikainen seuranta
- Tekoälyn hyödyntäminen

### 4.5 Haasteet, riskit ja rajoitukset

- Tietoturva
- Tietosuoja
- Datan laatu
- Kustannukset
- Suurten järjestelmien monimutkaisuus
- Teknologioiden ylläpito

## 5. Esimerkki

### 5.1 Tilanteen kuvaus

Videopalvelu, kuten YouTube tai Netflix:

- Käyttäjät katsovat videoita jatkuvasti.
- Järjestelmä kerää tietoa katselukerroista.
- Dataa syntyy erittäin suuria määriä.
- Tarkoituksena on tarjota käyttäjälle sopivia suosituksia.

### 5.2 Ratkaisu tai toimintatapa

- Käyttäjien toiminta tallennetaan.
- Data siirtyy dataputken kautta käsiteltäväksi.
- Tiedot tallennetaan tietovarastoon.
- Data analysoidaan.
- Tuloksia käytetään sisältösuositusten luomiseen.

### 5.3 Tulokset ja havainnot

- Käyttäjät saavat osuvampia suosituksia.
- Yritys ymmärtää paremmin käyttäjien toimintaa.
- Päätöksenteko perustuu dataan.
- Esimerkki osoittaa dataputkien merkityksen Big Data -ympäristössä.

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