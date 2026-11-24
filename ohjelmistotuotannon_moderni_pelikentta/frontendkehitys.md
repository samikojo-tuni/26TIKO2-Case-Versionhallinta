# Frontend- kehitys

## UI/UX

User Interface / User Experience. 
Käyttöliittymä / käyttökokemus. Suunnitteluun kuuluu myös visuaalinen design, käytettävyys sekä jatkokehitys.

## Mihin? 
Mobiilisovellukset, verkkosivut, muut digitaaliset palvelut.
Fyysiset laitteet: älylaitteet, kodinkoneet, automaatit, autojen näytöt.

##

Käyttöliittymän suunnittelu asiakaslähtöisesti ja käyttäjäystävällisesti 
Lisää yleistä käyttömukavuutta
Helppo navigoida kohteessa, tarvitut toiminnot löytyvät
Suunnittelu asiakaslähtöisesti? Vastataan tarpeisiin, jotta vältyttäisiin turhilta 

Suunnittelulla säästetään aikaa, kun tarvittavat toiminnot  ja visuaalinen ilme suunnitellaan jo valmiiksi ennen varsinaista koodausta
- Testaaminen ennen julkaisua, jotta mahdolliset virheet ja toiminnallisuudet voidaan korjata ennenkuin tuote pääsee asiakkaalle.

## Frontend-kehitys


Ohjelmistot koostuvat monista eri teknologioista, ja ohjelmisto voidaan yleensä jakaa frontend- ja backend-osioihin. Nämä osat yhdessä muodostavat ohjelmiston kokonaisuuden. Full stack -kehityksellä tarkoitetaan sekä frontendin että backendin kehittämistä.

Frontend on ohjelmiston käyttäjälle näkyvä ja käytettävä osa eli käyttöliittymä. Se on usein toteutettu verkkoteknologioilla, kuten HTML:llä, joka määrittelee sivun rakenteen, CSS:llä, jolla määritellään ulkoasu, sekä JavaScriptillä, joka tuo käyttöliittymään toiminnallisuuksia.

### Esimerkki

Esimerkiksi button voidaan luoda HTML + CSS + JavaScript näin:

Html
```
<button id="myButton">Paina tästä</button>
```

CSS
```
#myButton {
    background-color: blue;
    color: white;
    width: 150px;
    height: 50px;
    border: none;
    border-radius: 8px;
    font-size: 16px;
    cursor: pointer;
}

#myButton:hover {
    background-color: darkblue;
}
```

JS
```
const button = document.getElementById("myButton");

button.addEventListener("click", function() {
    alert("Hei! Painoit painiketta!");
});
```


Frontendiin kuuluu esimerkiksi ulkoasu, navigointi, painikkeet, lomakkeet, animaatiot ja erilaiset käyttöliittymäelementit.

Frontend-kehityksessä käytetään erilaisia frameworkeja eli sovelluskehyksiä, kuten Angularia ja Reactia. Ne tarjoavat valmiita työkaluja, rakenteita ja toiminnallisuuksia, joiden avulla kehitystyötä voidaan nopeuttaa. Lisäksi voidaan hyödyntää erilaisia komponenttikirjastoja, joista löytyy valmiita käyttöliittymäelementtejä, kuten painikkeita ja lomakkeita. Ohjelmoija voi mukauttaa niiden ulkoasua ja toiminnallisuuksia omaan projektiinsa sopiviksi.

Käyttöliittymä on usein responsiivinen eli se mukautuu eri laitteiden näyttökokoihin, kuten tietokoneen näytölle, mobiililaitteille ja tableteille. Tämä tarkoittaa sitä, että käyttöliittymän toiminnot säilyvät käytettävissä eri laitteilla, mutta elementtien koot, asettelu ja navigointi voivat muuttua näytön koon mukaan. Pienemmillä näytöillä voidaan myös piilottaa tai muuttaa joidenkin ominaisuuksien esitystapaa.



Lähde
[mectalent](https://www.mectalent.com/fi/ajankohtaista/mita-tarkoittaa-frontend-ja-back-end)