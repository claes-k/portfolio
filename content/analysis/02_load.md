---
Title: Load
Description: Load analysis
---

Sidladdningsanalys av svenska nyhetssajter
=============================================

En analys av laddningstider på ett urval av svenska nyhetssajter.

Urval
---------------------------------------------

Sajterna som valdes för denna analys är Aftonbladet, Expressen och SVT Nyheter. Då nyhetssajter ofta har väldigt mycket innehåll, mycket text, bild, video och reklam så passar de utmärkt för ett hastighetstest, för att se hur bra eller dåliga de är på att leverera mycket innehåll. Aftonbladet och Expressen är Sveriges två största tidningar, så mycket är jämförbart dem emellan och sedan har vi SVT Nyheter som reklam-fri kontrast för att se hur stor skillnad all reklam har på sidors laddningstid.

Metod
---------------------------------------------

I detta test så testas varje sajts huvudsida, sportsida samt en slumpvis vald artikelsida. Inspektionsverktyget i Google Chrome på Mac används för att mäta laddningstiderna på desktop, med inställning på 1440x900 stor skärm och 2x pixeldensitet. Mätningarna görs i tre omgångar där ett medel sedan tas ut. Resultaten läggs sedan in i ett Google Sheets-ark. Googles PageSpeed Insights-verktyg används också för att titta på hur väl sidorna uppfyller Googles standardiserade prestandakrav, både på desktop och mobil.

Resultat
---------------------------------------------

### Aftonbladet

![Skärmbild av Aftonbladets sajt](%base_url%/image/aftonbladet.png){.analysis-image}

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ4LQrnbv_eeFoyX18sFHi0tFPTyhsSf3osizrkYS4yNveKqlR9AGovPeOKi_Q_hAHK-RCvidfxMMg2/pubhtml?gid=1846600432&amp;single=true&amp;widget=true&amp;headers=false" class="spreadsheet"></iframe>

Då Aftonbladet i stor del existerar tack vare reklam och annonser så är det inte särskilt realistisk att säga att dom borde kapa ner på all reklam. Sidorna, trots att de innehåller så enormt mycket, laddar ändå in på acceptabel tid. Om något skulle de ta och kolla varför deras PageSpeed-poäng varierar så från en sida till en annan. Varför skiljer sig tillgängligheten från en sida till en annan?

### Expressen

![Skärmbild av Expressens sajt](%base_url%/image/expressen.png){.analysis-image}

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ4LQrnbv_eeFoyX18sFHi0tFPTyhsSf3osizrkYS4yNveKqlR9AGovPeOKi_Q_hAHK-RCvidfxMMg2/pubhtml?gid=1119258942&amp;single=true&amp;widget=true&amp;headers=false" class="spreadsheet"></iframe>

Expressen är i samma båt som Aftonbladet. Mindre reklam, inte så realistiskt. Möjligen kan de kolla på varför artikelsidan laddar in så mycket mer data i jämförelse med Aftonbladet.

### SVT Nyheter

![Skärmbild av SVT Nyheters sajt](%base_url%/image/svtnyheter.png){.analysis-image}

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ4LQrnbv_eeFoyX18sFHi0tFPTyhsSf3osizrkYS4yNveKqlR9AGovPeOKi_Q_hAHK-RCvidfxMMg2/pubhtml?gid=1427540151&amp;single=true&amp;widget=true&amp;headers=false" class="spreadsheet"></iframe>

I stort sett guldstandard på SVT. Fantastiska betyg från PageSpeed, jämna nummer i hastighetstesten. Allt tack vare frånvaron av massor, mängder, drösvis med reklam och annonser.

Analys
---------------------------------------------

Det skulle krävas en mycket större och mer ingående analys för att gå till botten med hur man kan (om man kan) optimisera Aftonbladet och Expressens sajter. Att säga åt dom att vara mer som SVT Nyheter är inte ett alternativ. Men magkänslan är att dessa massiva sajter också troligen är något utav ett stort lapptäcke där mycket funktionalitet är uråldrig i webbens mått mätt. Dessa sajter bygger inte om från grunden, utan det lär läggas på nya saker ovanpå gamla saker. Det skulle vara intressant att se om en helt ny sajt, byggd från grunden, skulle göra någon skillnad.

1. **SVT Nyheter** — I en egen klass, helt enkelt. Inte bara laddas den snabbare, men den får överlag mycket bättre betyg från PageSpeed också.
2. **Expressen** — Jag ger Expressen andraplatsen då deras PageSpeed-betyg var klart mycket bättre än Aftonbladets. Lite minus för många megabyte på artikelsidan dock.
3. **Aftonbladet** — Sticker inte ut på något positivt sätt. Sämst på PageSpeed, och mestadels lika mediokra hastighetstest som Expressen.

Trots att Aftonbladet och Expressen inte är särskilt snabba skulle jag ändå inte påstå att de är fruktansvärt långsamma heller. Men detta beror ju också på hur snabbt ditt internet är, och hur kraftfull din dator är. Aftonbladet och Expressens sajter är ganska notoriska för att vara plågsamma att besöka om man inte har en så bra dator, eller snabb uppkoppling. De 4-5 sekunder det tar dem att laddas på min dator är helt okej, så jag skulle nog säga att när man börjar komma upp i 8-10 sekunder, då blir det riktigt märkbart trögt. Så i den aspekten är det ganska otroligt ändå att dom kan klämma in så mycket innehåll på så kort laddningstid, det tyder på att dom jobbar ganska hårt ändå på att hålla nere laddningstiderna.

Referenser
---------------------------------------------

* [PageSpeed Insights](https://PageSpeed.web.dev/)
* [Aftonbladet](https://www.aftonbladet.se)
* [Aftonbladet Sport](https://www.aftonbladet.se/sportbladet)
* [Aftonbladet artikel](https://www.aftonbladet.se/nyheter/a/P4bdEX/har-stormar-skytten-in-pa-pressbyran)
* [Expressen](https://www.expressen.se)
* [Expressen Sport](https://www.expressen.se/sport)
* [Expressen artikel](https://www.expressen.se/nyheter/varlden/snokaoset-i-europa-varningen-ak-inte-hit/)
* [SVT Nyheter](https://www.svt.se)
* [SVT Nyheter Sport](https://www.svt.se/sport)
* [SVT Nyheter artikel](https://www.svt.se/nyheter/utrikes/sa-ser-andra-lander-pa-svensk-klimatpolitik--d57ghr)

Övrigt
---------------------------------------------

Analys av Claes Källarsson.