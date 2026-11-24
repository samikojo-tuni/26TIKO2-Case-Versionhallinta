<!-- Author Jari Järvenpää -->
# Tulevaisuuden kyberuhat

## AI
Kyberturvallisuus alana on tällä hetkellä ison murroksen alla. Generatiivinen tekoäly on mullistanut mahdollisuuden löytää haavoittuvuuksia nopeassa ajassa. Generatiivinen tekoäly agenttien avulla voi käydä läpi ensin miljoonia rivejä koodia, esim käyttöjärjestelmän kerneli (ydin). Tämän jälkeen agentit merkkaavat kohdat joissa todennäkösesti löytyy haavoittuvuuksia. Tämän jälkeen agentit, jotka ovat erikoistuneet haavoittuvuuksien testaamiseen käyvät nämä rivit koodia läpi ja testaavat nopeasti voiko haavoittuvuutta hyödyntää. Jos voi, he raportoivat miten he pääsivät läpi ja mahdollisesti miten se voidaan korjata.
Lähde: https://openai.com/index/a-thousand-fewer-paths-to-root/

Tämä aiheuttaa sen, että laajoja haavoittuvuuksia on löytynyt viime kuukausien aikana, jotka ovat olleet vuosia jo löytämättä. Näistä hyviä esimerkkejä on PHP2Shell, Java4Shell.
Lähteet: https://www.wiz.io/blog/php2shell-php-rce, https://calif.io/java4shell

Hyvä puoli tässä on se, että kyberturvallisuus ammattilaiset voivat hyödyntää näitä samoja työkaluja ja korjata tai edes raportoida ongelmia nopeassa ajassa. Huono puoli on, että samat työkalut ovat myös hakkereilla käytössä ja generatiivisen tekoälyn käyttö madaltaa kynnystä hyödyntää näitä haavoittuvuuksia. Enään ei tarvitse olla edes ammattilainen löytääkseen ja hyödyntääkseen näitä haavoittuvuuksia.

Useimmat näistä lähiaikoina löydetyistä vakavista haavoittuvuuksista liittyvät vialliseen muistinhallintaan. Se on erittäin kriittistä kyberturvallisuuen kannalta ja AI agentit osaavat pääosassa välttää näitä virheitä koodissa. Voi siis olla, että lähitulevaisuudessa tämän tyyppiset haavoittuvuudet vähenevät.

## Kvanttitietokoneet

Julkisuudessa ei vielä ainakaan ole kerrottu kovin kyvykkäistä kvanttitietokoneista. Joidenkin arvioiden mukaan jo 2030 luvulla meillä voi olla niin laskentatehokas kvanttitietokone, joka murtaa hetkessä klassiset epäsymmetriset salausmenetelmät. Tästä päivästä puhutaan käsitteellä Q-päivä (Q-day). Tästä syystä jo nyt on kehitetty kvanttiturvallisia salausmetodeita, kuten openSSH on tehnyt. Lähde: https://www.openssh.org/pq.html

Ongelmanahan tässä on se, että ne ovat vielä teoreettisia, vielä ei voida tietää mitä käytännössä tapahtuu. Vielä suuremman kyberturvallisuus uhan tästä muodostaa hyökkääjien mahdollisuus kerätä salattua tietoa sekä säilyttää sitä tätä pahamaineista Q-day:ta miettien. Tätä kutsutaan strategiaksi: "harvest now, decrypt later". Aiheesta lisää: https://www.kyberturvallisuuskeskus.fi/files/media/file/Kybers%C3%A4%C3%A4%20syyskuu%202026.pdf

<!-- AUTHOR: Henri Hurme -->
# Tietoturvan merkitys koodarille

Tietoturva on tärkeää koodarille, jotta koodarin projektit ei päädy vääriin käsiin hänen työskennellessään yritykselle, jonka koodit ovat liikesalaisuus tai luottamuksellista tietoa. Kyber-rikolliset saattavat manipuloida koodia, vakoilla tai itse hyödyntää saamiaan tietoja sekä koodia. Koodarin tulee ymmärtää tietoturvan merkitys työskennellessään sekä pysyä tietoturvaan liittyvissä asioissa ajan tasalla, jottei edellämainittuja pääse tapahtumaan.

Luottamuksellista sisältöä käsitelläessä on hyvä varmistaa, ettei ulkopuoliset henkilöt pääse näkemään koodia, käyttää ja pitää ajantasalla firewallia, anti-malware ohjelmia, sekä käyttöjärjestelmää. Turvallisuusasetuksia esimerkiksi asettamalla käyttöoikeuksia, käyttämällä hyviä, vahvoja salasanoja, sekä kahden vaiheen tunnistautumisia on tärkeää hyödyntää pitämään tiedot turvassa.
Lokitietojen kerääminen sekä käyttö
tietomurtojen havaitseminen ja tutkinta
Kyberturvallisuuskeskus traficom on hyvä lähde