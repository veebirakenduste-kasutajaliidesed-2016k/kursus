# Veebirakenduste kasutajaliidesed 2016k

* **Kursuseprogramm:** [IFI6093](http://www.cs.tlu.ee/instituut/oppe_tegevus/kp/kp_k_2016/)
* **Õpetaja:** Romil Rõbtšenkov, [romilr@tlu.ee](mailto:romilr@tlu.ee)
* **Testserver:** lin2.tlu.ee, greeny.cs.tlu.ee ([tunneli loomise juhend](http://minitorn.tlu.ee/~jaagup/kool/java/kursused/09/veebipr/naited/greenytunnel/greenytunnel.pdf))
* **Tunni näited:** [~romil/vk16k](http://minitorn.cs.tlu.ee/~romil/vk16k)
* **Rühmad:** [I rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k?utf8=%E2%9C%93&query=-I-ruhm), [II rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k?utf8=%E2%9C%93&query=-II-ruhm),

## Kodused tööd ja projektid

* 1. kodutöö ([I rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k/1.kodutoo-I-ruhm), [II rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k/1.kodutoo-II-ruhm))
* 2. kodutöö ([I rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k/2.vk-kodutoo-I-ruhm), [II rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k/2.vk-kodutoo-II-ruhm))
* 3. kodutöö ([I rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k/3.vk-kodutoo-I-ruhm), [II rühm](https://github.com/veebirakenduste-kasutajaliidesed-2016k/3.vk-kodutoo-II-ruhm))

**Kodused tööd peavad olema lõplikult valmis esitatud vähemalt nädal enne valitud eksamiaega.**

* [projekt](https://github.com/veebirakenduste-kasutajaliidesed-2016k/vk-projekt)

### GitHub'i töövoog

1. *Fork*'i ülesande/projekti repositoorium (leiab [https://github.com/veebirakenduste-kasutajaliidesed-2016k](https://github.com/veebirakenduste-kasutajaliidesed-2016k)).
1. *Clone*'i see repositoorium enda arvutisse/serverisse ja määra repositooriumi URL kuhu edaspidi muudatusi salvestad.
  ```
  git clone https://USERNAME@github.com/USERNAME/REPOSITORY.git
  ```
1. Lisa ka oma nimi ja email repositooriumi omanikuks ([Setting your username](https://help.github.com/articles/setting-your-username-in-git/))
1. Muuda faile ülesande lahendamiseks ja *Commit*'i iga olulisem muudatus, kasutades kahte käsku.
  ```
  git add .
  ```
  ```
  git commit -m "Added this functionality to the app"
  ```
1. Veendu, et kogu kood on *Commit*'itud.
  ```
  git status
  ```
1. *Push/sync*'i GitHub'i.
  ```
  git push origin
  ```
1. [Ava *pull request*](https://help.github.com/articles/creating-a-pull-request) ülesande originaalses repositooriumis. Ülesannete tähtajaks on 24h enne järgmise tunni algust, kui pole teisiti kirjas.
1. Muudatusi ja täiendusi võib *push*'ida repositooriumisse, kuni ette antud  kuupäevani.

Tagasisidet saab otse *pull request*'i millele ootan Sinupoolseid kommentaare/mõtteid/küsimusi. Võid julgselt avada *pull request*'i kohe kui hakkad kodutöö kallal tegelama ja siis kui hätta jääd võid esitada sinna küsimuse. Maini kommentaaris minu kasutajat `@romilrobtsenkov` siis jõuan sellele kiiremini vastata.

### Nõuded

Need rakenduvad ka päris elus!

* Peab järgma "head programmeerimise stiili"
    * Muutujate nimed peavad kirjeldama muutujat ning peavad olema inglise keeles
    * Funktsiooni nimi peab olema "lühike"
    * Optimeeri koodi lugemiseks
    * Projektide jaoks tuleb kasutada objektorienteeritud lähenemist
    * Laenatud koodile tuleb viidata
* Boonuspunktid:
    * Loomingulisus (NB! nõuded peavad olema täidetud)

## Kursus

### 1. tund

1. Sissejuhatus
    * Veebiprogrammeerimise aine kokkuvõte
    * Arutleme, mis antud kursus endas hõlmab
1. Ajalugu
    * ECMAScript
    * iframe > XMLHttpRequest > AJAX
1. JS kasutusvaldkonnad
    * Lehtede interaktiivseks muutmine
    * Võrgu koormuse vähendamine
    * AJAX
    * Vormide valideerimine
    * WebSocket
    * Mängud
1. JS piirangud
    * Andmete kirjutamine serverisse
    * Ligipääs andmebaasidele
    * Ligipääs failisüsteemile
    * Akende sulgemine
    * Lõimtöötlus
    * Ligipääs teistele veebilehtedele
    * Browserite erinevused
1. Tunnis kasutatavad tööriistad
1. Javascript'is programmeerimine
    * muutujad, funktsioonid, aeg, sündmuste kuulamine, dokumendi muutmine
1. [1. kodutöö](https://github.com/veebirakenduste-kasutajaliidesed-2016k?utf8=%E2%9C%93&query=1.kodutoo)

### 2. tund

1. Iseseisva töö demo tervele klassile
1. JS rakenduse ülesehitus (objektorienteeritud kood)
    * JS "use strict" – [w3schools](http://www.w3schools.com/js/js_strict.asp), [ECMAScript 5 Strict Mode](http://ejohn.org/blog/ecmascript-5-strict-mode-json-and-more/)
    * Kasutame Singleton mustrit (Loe kindlasti mustrite kohta lähemalt [Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) by Addy Osmani)
1. Tunnitöö
    * Tee oma rakendus objektorienteerituks ümber, lähtu tunnis õpitust
    * Vaata kuidas ja mis järjekorras JS ning brauser koostööd teevad [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ) by Philip Roberts

### 3. tund

1. Mitu navigeeritavat lehekülge ühes failis | soovituslik lugemine [Reimagining Single-Page Applications With Progressive Enhancement](https://www.smashingmagazine.com/2015/12/reimagining-single-page-applications-progressive-enhancement/) by Heydon Pickering
1. [normalize.css](https://necolas.github.io/normalize.css/) ja [reset.css](http://meyerweb.com/eric/tools/css/reset/) | mis on nende erinevus, milleks kasutatakse?
1. CSSi kokkupakkijad, nt [cssminifier.com](https://cssminifier.com). PS! Kursuse teises pooles vaatame ka [Gulp](http://gulpjs.com)'i kasutusvõimalusi arendamisprotsessi kiirendamisel aga praegu piirdume online tööriistadega.

### 4. tund

1. Andmete salvestamine local storage'isse ([HTML5 local storage / web storage](http://www.w3schools.com/html/html5_webstorage.asp)). Katseta järgi palju seda [toetatud](http://caniuse.com/#search=localstorage) brauserisse mahub ([Test of localStorage limits/quota](https://arty.name/localstorage.html), palju see MB'des teeb?).
1. Kõige efektiivsem filtreerimine toimub CSS'i abil elementide näitamise ja peitmise kaudu ([stackoverflow näide](http://stackoverflow.com/a/15597786))
1. Lisa juurde täiendav funktsionaalsus, mis võimaldaks tunnis loodud rakenduses loendist elemente kustutatda. Abiks kasuta massiivist kustutamist ([slice()](http://www.w3schools.com/jsref/jsref_slice_array.asp)) ja näiteks data-atribuute ([How to Use HTML5 Data Attributes](http://www.sitepoint.com/use-html5-data-attributes/)) elementide küljes nt indexi edastamiseks, et mille peale vajutati.
1. Hea näide kustutamisest [TODO in HTML5 and plain JavaScript](http://code-maven.com/todo-in-html-and-javascript)

### 5. - 6. tund

1. Andmete salvestamine textifaili läbi PHP ja seal andmete küsimine, [AJAX](http://www.w3schools.com/ajax/)
1. PHP AJAXi piirang [Detect an AJAX Request in PHP](https://davidwalsh.name/detect-ajax)
1. GET või POSTi kasutamine andmete salvestamiseks? [vastus](http://www.w3schools.com/ajax/ajax_xmlhttprequest_send.asp)
1. Ainult samalt domeenilt andmete saamine (kui teine enda server, siis tegelikult midagi annab konfigureerida), [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)
1. ÜLESANNE, [typer mängu](https://github.com/veebirakenduste-kasutajaliidesed-2016k/typer) täiendus (tee FORK!).
  * Muuda skooriarvutuse algoritmi vasvalt maitsele (nt arvesta kulunud aega, tehtud eksimusi, sõna pikkust kui konfitsenti, juhuarve vms)
  * Salvesta vähemalt mängija nimi ja skoor tunnis õpitu abil tekstifaili, kus järjesta need
  * Mängu laadimisel teata seni kõrgeim skoor
1. Mõttekoht, kuidas oleks võimalik vältida cheatimist?

1. KORDAMINE

### 7. tund

1. Admin paneel ja rakendus eraldi
1. Võrguühenduseta töötav rakenduse meelespea
1. Failide cache'imine ja uuendamine [A Beginner's Guide to Using the Application Cache](http://www.html5rocks.com/en/tutorials/appcache/beginner/)
1. Näidisrakenduse loomine, mis teab võrgu kättesaadavust ja jälgib selle muutumist

### 8. tund
1. [Chrome remote debugging](https://developer.chrome.com/devtools/docs/remote-debugging)
1. [Add to homescreen](http://cubiq.org/add-to-home-screen) stiilis rakenduse loomine
1. [JS Device API](https://www.w3.org/standards/techs/js#w3c_all)'d
1. [Ikooni genereerija](http://realfavicongenerator.net)
1. [Chrome manifest](https://developer.chrome.com/multidevice/android/installtohomescreen)
1. [JS accelorometer](http://www.albertosarullo.com/blog/javascript-accelerometer-demo-source)

### 9.tund
1. [Google Developers console](https://console.developers.google.com)
1. [Google Maps API](https://developers.google.com/maps/documentation/javascript/examples/)
1. [Google Maps Style genereerija](http://gmaps-samples-v3.googlecode.com/svn/trunk/styledmaps/wizard/index.html)

### 10.tund
1. [Twitter API](https://dev.twitter.com/rest/public/search)
1. [Twitter API exchange](https://github.com/J7mbo/twitter-api-php/blob/master/TwitterAPIExchange.php)
 
### 11.tund
Täiendavad käsud
```
git fetch

git pull

git add failinimi.txt

git rm failinimi.txt

//kustuta juba olematu fail
git add -u 

//lisa oma nimi ja meiliaadress
git config user.name "Romil"
git config user.email "romilrobtsenkov@users.noreply.github.com"

```

## Materjalid ja tööriistad

### Tunnis kasutatud rakendused
* [Atom](https://atom.io), lisad ([emmet](https://github.com/emmetio), [jshint](https://atom.io/packages/jshint))
* koodi valideerimine [JSLint](http://jslint.com) / [JSHint](http://jshint.com)
* debug:
    * [Chrome Developer Tools](https://developer.chrome.com/devtools/index)
        * [Official debugging tutorial](https://developer.chrome.com/extensions/tut_debugging)
        * õpetus [JavaScript Diagnosis](http://www.macwright.org/2015/03/10/javascript-diagnosis.html)
    * [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)

### Kohustuslik materjal

* [Kliendipoolsed veebirakendused](http://www.tlu.ee/~jaagup/skriptkeeled/kliendirakendused.pdf)
* [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* [JavaScript Garden](http://bonsaiden.github.com/JavaScript-Garden/)
* [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [Mozilla Developer Network](https://developer.mozilla.org/en/JavaScript)
* [Learn JavaScript](https://developer.mozilla.org/en-US/learn/javascript)
* [w3schools](http://www.w3schools.com/jsref/default.asp)
* [What’s so great about JavaScript Promises?](http://blog.parse.com/learn/engineering/whats-so-great-about-javascript-promises/)

### Soovituslik lugemine

* [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)
* [JavaScript Best Practices](http://www.thinkful.com/learn/javascript-best-practices-1/)
* [JavaScript Patterns](http://shichuan.github.io/javascript-patterns/)
* [Learning Advanced JavaScript slides](http://ejohn.org/apps/learn/)
* [Static Web Apps](http://www.staticapps.org/)
* [The JavaScript Interpreter, Interpreted](http://www.slideshare.net/marthakelly/js-interpreter-interpreted) [(video)](https://www.youtube.com/watch?v=iSxNCYcPAFk)
* [Classical Inheritance in JavaScript](http://www.crockford.com/javascript/inheritance.html)
* [Partial Application in JavaScript](http://benalman.com/news/2012/09/partial-application-in-javascript/)
* [HTML5 Rocks slides](http://slides.html5rocks.com/)
* [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)
* [JS: The Right Way](http://www.jstherightway.org/)
* [Code School](https://www.codeschool.com/paths/javascript)
* [Javascript Trail Map](https://upcase.com/javascript)
* [How To Learn JavaScript Properly](http://javascriptissexy.com/how-to-learn-javascript-properly/)
* [Superhero.js](http://superherojs.com)
* [Teach Yourself to Code](http://teachyourselftocode.com/javascript)

### PHP meeldetuletus
* [PHP Coding Style Guide](http://www.php-fig.org/psr/psr-2/)
* [Veebirakenduste loomine PHP ja MySQLi abil](http://minitorn.tlu.ee/~jaagup/kool/java/loeng/veebipr/veebipr1.pdf)
* [PHP with MySQL Essential Training](http://www.lynda.com/MySQL-tutorials/PHP-MySQL-Essential-Training/119003-2.html)

#### HTML/CSS/JS sandbox'id

* [JS Bin](http://jsbin.com/)
* [CodePen](http://codepen.io/pen/)
* [JSFiddle](http://jsfiddle.net/)

### Git
* [Become a git guru.](https://www.atlassian.com/git/tutorials/)

## Litsents
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Käesolev <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">leht</span> ja kõik teised https://github.com/veebiprogrammeerimine-2015s materjalid on <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Litsensiga</a>.
