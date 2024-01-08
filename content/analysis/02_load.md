---
Title: Laddtider
Description: This is a page about load
Template: analysis
---

# Laddtider

I denna uppgift ska jag välja ut tre olika webbplatser och studera laddtider och prestanda.
Syftet med uppgiften är bland annat att utöka mina kunskaper kring en webbsidas prestanda och användbarthet. Jag ska även utse en vinnare av testet.

## Urval

De sidor jag valde att granska i detta test var Aftonbladet, DN och Expressen. Att det blev just dessa nyhetssiter beror på att jag helt enkelt ville göra en prestandajämförelse för webbsidor inom samma branch och valde då helt enkelt tre av de största och mest besökta siterna.

### [Aftonbladet](https://www.aftonbladet.se)

[![Aftonbladets hemsida](%assets_url%/img/kmom05/Aftonbladet.jpg) {.img-medium}](%assets_url%/img/kmom05/Aftonbladet.jpg)

### [Expressen](https://www.expressen.se)

[![Expressens hemsida](%assets_url%/img/kmom05/Expressen.jpg) {.img-medium}](%assets_url%/img/kmom05/Expressen.jpg)

### [DN](https://www.dn.se)

[![Dagens Nyheters hemsida](%assets_url%/img/kmom05/Dn.jpg) {.img-medium}](%assets_url%/img/kmom05/Dn.jpg)

## Metod

De verktyg jag använt mig av under detta test var Google Pagespeed, Devloper Tools samt Microsoft Excel. Mätverktyget Google Pagespeed användes för att analysera webbsidans tillgänglighet och prestanda. Developer Tools och fliken "Nätverk" har jag använt för att mäta respektive webbsidas laddningstid, antal resurser och den totala storleken på sidans resurser. För att få ett rättvist resultat så mättes varje tre gånger och resultatet blev snittet av dessa tre försök. Vid varje försök rensades även cachen. Resultaten är bokförda i ett kalkylblad från Microsoft Excel.

## Resultat

Nedan redovisas resultatet av de genomförda testerna.

### Mätresultat

<iframe class="load-result" src="%assets_url%/img/kmom05/laddtider.htm" title="Result"></iframe>

<!-- <iframe class="load-result" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSsybsW9vY-_B5rp7bwWrYtA8y_9lCLl_d1GhqEl8Ir5-VTN1DOIM5FLHs7ekq3iNdjYuPUDcl6AKKl/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe> -->

## Analys

Här följer en sammanfattning och en diskussion kring de resultat som uppkom i samband med mina mätningar.

### Prestandaöversikt

För att sammanställa prestandaresultaten har jag använt både Google Pagespeed och Developer Tools för att mäta laddningstider och resursanvändning. Resultaten från laddtider är ett genomsnitt av tre mätpunkter som skett vid olika tidpunkter.

#### Aftonbladet

- **Mobile:** Aftonbladets mobila betyg för tillgänglighet och SEO är höga, samtidigt som prestandan är låg. Dessutom får man ej godkänt på Core web vitals.
- **Desktop:** För stationära användare så är prestandan bättre men ändå lägst betyg av samtliga sidor. Betygen för tillgänglighet och SEO är höga samtidigt som Core web vitals får ej godkänt.

- **Laddning** Laddtiden är 1.01s och den snabbaste av samtliga. Den laddar samtidigt mest resurser och har högst total storlek.

- **Betyg** Aftonbladet har genomgående bra SEO i testet och är snabbast att ladda. Man har fokuserat mycket på tillgänglighetsaspekten och även om prestandan för mobila användare är relativt instabil ger jag AB ett mer än godkänt i betyg.

- **Förbättringsförslag** Med tanke på resursstorlek så bör man överväga att optimera bilder och försöka minska storleken genom komprimering och på så vis öka laddtider. Man får ej godkänt på Web vitals vilket kan indikera att sidan inte är helt optimerad i sin layout eller rendering. Man kan även kolla över JavaScript och CSS-filer, vilket är ett förslag som gäller samtliga sidor nedan.

#### Expressen

- **Mobile:** Det mobila betyget för tillgänglighet och SEO ligger båda på runt 80 och får godkänt. Prestandan har relativt lågt betyg strax nder 50. Man får även ej godkänt på Core web vitals.
- **Desktop:** För stationära användare förbättras prestanda, tillgänglighet, bästa metoder samt Wb core vitals som får godkänt.

- **Laddning** Laddtiden är 1.61s, den klart långsammaste i testet och den laddar näst flest resurser och total storlek.

- **Betyg** Expressen har genomgående bra bästa metoder i testet och prestandan är ett snäpp upp hjämfört med Aftonbladet. Tillgänligheten verkar okej. Man har sämst betyg för SEO i hela testet. Laddtiden, som är klart långsammast, gör att sidan upplevs långsam att ladda in gör att jag väljer att ge den ett ej godkänt.

- **Förbättringsförslag** En tydlig brist är SEO betygen som man skulle kunna förbättra genom att korrigera eventuella brister eller avsaknad av i rubriksättning och metataggar. Långsam laddtid kan eventuellt härledas till långsam serverrespons och bör undersökas. Man bör likt Aftonbladet sträva efter att optimera bild-storlekar och använda rätt bildformat.

#### Dagens Nyheter (DN)

- **Mobile:** DN's mobila betyg för SEO, tillgänglighet och bästa metoder är höga. Prestandabetyget är högst i testet för mobila enheter på 56. Man får, som enda sida, godkänt på Core web vitals.
- **Desktop:** För stationära användare så får prestand, tillgänglighet, bästa metoder och SEO alla över 90, vilke är väldigt imponerande. Core web vitals får dock ej godkänt.

- **Laddning** Laddtiden är 1.04s som resulterar i den näst snabbaste laddtiden. Den laddar minst resurser och även minsta totala storlek.

- **Betyg** DN har får genomgående höga betyg av PageSpeed, särskilt för stationära-användare. Bästa metoder får 100 på båda testen och prestandan för Stationära använadare får klart högre betyg än både de andra sidorna. Laddtiden är nästan lika snabb som Aftonbladet och med felmarginal så når man upp till en delad förstaplats där.

- **Förbättringsförslag** DN har ingen tydlig brist som framkommer under testet men man bör försöka arbeta med att optimera bilder, layout och minimera och optimera JavaScript- HTML och CSS-filer.

### Sammanfattning och Rangordning

Sammanfattningsvis visar alla tre webbplatserna en överlag bra prestanda. Baserat på de presenterade mätresultaten och förbättringsåtgärderna kan en rangordning fastställas.

1. **Dagens Nyheter (DN):** Utmärkt prestanda och höga PageSpeed-betyg med bra laddtider.
2. **Aftonbladet:** Ok prestanda och godkända PageSpeed-betyg med bra laddtider.
3. **Expressen:** Ok prestanda, något godkända PageSpeed-betyg. Långsam laddtid.

**Generella förbättringsåtgärder** för dessa typer av siter skulle kunna vara att optimera bilder, men när man inspekterar mer noggrant så ser man att dessa bilder inte tar så mycket plats. Tvärtom verkar man ha arbetat mycket med bild-komprimering. Det skulle kunna vara att minska mängden med bilder men även att minska antalet flash-annonser som är vanligt förekommande. Man kanske även borde arbeta mer med "lazy loading", dvs, endast ladda in de, för användaren, synliga bilderna.

### Absolut Laddningstidsgräns

En absolut gräns för laddningstider är subjektiv. För användare som mig, med dåligt tålamod, så har jag en gräns på max 1.5 sekunder. Jag tycker att under 1 sekund så upplevs laddtiden snabb. Om en sida laddas in på mer än 1.5 sekunder så känns den inte optimerad utan istället trög och långsam.

- **Aftonbladet:** Inom gränsen för en snabb webbplats.
- **Expressen:** Fallerar gränsen för en snabb webbplats. Upplevs långsam
- **Dagens Nyheter (DN):** Inom gränsen för en snabb webbplats.

### Avslutande ord

Sammanfattningsvis har alla tre webbplatserna visat okej prestanda, men DN har utmärkt sig med höga betyg och snabba laddningstider på både mobila och stationära enheter.

---

**Gruppmedlemmar:**

- Andreas Carlsson
