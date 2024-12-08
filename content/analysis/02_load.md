---
Title: Analysis
Description: Analysis of websites
---

Analys av laddningstiden på webbsidor
=======================

Uppgiften handlar om att undersöka olika webbsidors laddningstid, storlekar och potentiella förbättringar för att förbättra sidans prestanda.

Urval
-----------------------

I denna analys valdes det att undersöka spelföretags webbsidor. Kategorin valdes av anledningen att många spelföretag vill visa innehåll från sina spel och använder sig därav av mycket bilder, vilket kan påverka deras prestanda.

Metod
-----------------------

För att undersöka hur lång tid som det tar för det valda webbsidorna att ladda användes 3 verktyg, Google PageSpeed Insights och både Firefox och Edge browsers devtools med fliken Network samt google sheets.


Verktyget Google PageSpeed insights användes genom att klistra in respektive webbsidas URL länk i sidans inputfält. 


Verktygen devtools fliken Network användes genom att besöka respektive webbsida, öppna upp fliken och starta en analys. Sedan laddades sidorna om genom shift+ctrl+R medans fliken var uppe minst 3 gånger.


Verktyget Google Sheets användes för att skapa ett excelark där datan från de andra verktygen dokumenterades.

Resultat
-----------------------

### Riotgames.com

Resultaten för Riotgames.com på Google PageSpeed Insightes visade att sidans prestanda i de olika kategorierna performance, accessibility, best practices och SEO är relativt jämn för både desktop och mobil. Poäng skillnaden mellan de två är väldigt liten. Båda fick relativt dåligt resultat för performance där båda versionerna fick under 50 poäng medans i kategorierna för accessibility, best practice och SEO fick de relativt höga poäng mellan 77-87. 


I genomsnitt laddades sidan på 2.85 sekunder och den laddade 12.1MB av resurser. Baserat på resultaten från Devtoolsen var det svårt att avgöra hur stor webbsidan egentligen är, så den här rapporten valde att utgå ifrån det totala storleks värdet som Firefox Devtools gav vid den första analysen/innan första laddningen av sidan. Detta beslut gäller samtliga sidor. Det gav riotgames.com en storlek på 21 338.70 kB.  

![A screenshot of riotgames.com](../assets/img/riot.jpg "riot.com")

### Bethesda.net

Resultaten för bethesda.net på Google PageSpeed Insightes visade att sidans prestanda i de olika kategorierna var relativt jämna mellan desktop och mobil med undantaget för performance. I performance fick desktop 54 poäng medans mobil fick 15 poäng, vilket är en skillnad på 39 poäng. Däremot fick övriga kategorier liknande poäng, mellan 83-93. Överlag fick desktop mer poäng än mobil.


I genomsnitt laddades sidan på 6,22 sekunder och den laddade genomsnittligt 10,73MB av resurser. Sidans totala storlek var 11 163.10 kB.

![A screenshot of bethesda.net](../assets/img/bethesda.jpg "bethesda.com")

### Blacksaltgames.com

Resultaten för blacksaltgames.com på Google PageSpeed Insightes visade mer skillnaden mellan poängen för desktop och mobil jämfört med de övriga webbsidorna. I performance fick desktop 40 poäng medans mobil fick 61 poäng. Skillnaden mellan de två i kategorierna accessibility och SEO var relativt liten medans skillnaden i kategorin best practices var större. Där fick desktop 78 poäng och mobil fick hela 100 poäng, vilket ingen av webbsidorna har fått i någon av kategorierna.


I genomsnitt laddades sidan på 5.19 sekunder och laddade i genomsnitt 16.87MB av resurser. Sidans totala storlek var 5 428,91 kB.

![A screenshot of blacksaltgames.com](../assets/img/blacksaltg.jpg "blacksaltgames.com")

### Excelark med värdena från undersökningen

<iframe class="excel" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQki3NBraibLiYtcvzpHI-tHtxIamtz3qhH9A1X6GnIGm-vg9DG-JirjtNDv_nvcKxyxD5CaG7o052B/pubhtml?widget=true&amp;headers=false"></iframe>

Analys
-----------------------

Coming soon

Övrigt
-----------------------

Coming soon

Här länkarna till de olika sidorna som analyserades:
* [riotgames.se](https://www.riotgames.com/en)
* [bethesda.net](https://bethesda.net/en/dashboard)
* [blacksaltgames.se](https://www.blacksaltgames.com/)

<a class="backbtn" href="01_colors">Go to Colors</a>
<a class="backbtn" href="03_design_principles">Go to Design principles</a>
