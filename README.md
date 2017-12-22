# Arboreal

Name: Beratcan Acil FEND17
GitHub pages: https://beratcan97.github.io/arboreal/

## Output from HTML checker
  "Document checking completed. No errors or warnings to show."
## Output from CSS validator
  "This document validates as CSS level 3!"
## Feedback
  * Använda gärna flera klasser i css. Ifall du vill lättre utöka stylingen på dom olika siderna.
  * Försöka göra siten lite mer säljande, tänk, skulle du köpt en produkt från denna sida.
  * Använd label till ditt formulär, som rubriker till dina inputs. (Då kan du sätta for="" på din label, samt id="" på din input)
  * Du skulle kunna sätta tel, facebook och twitter i din footer till länkar.
  * Gör gärna sidan med ett och samma språk. Mitt förslag är att bara hålla sig till engelska.
## Feedback svar
  * Flera klasser använda för styling.
  * Sidan är mer stylad med bland annat bilder och färger.
  * Label är har använts på alla formulär.
  * Tel, facebook och twitter har satts i footer med dessutomm logor.
  * Hela sidan består av nu endast av engelska.
## Responsive
Sidan är responsive och fungerar lika bra på 4k skärm som ganska små skärmar som t.ex. Iphone 4. När jag designade sidan valde jag att bygga upp sidan i "multipage" d.v.s. en sidan som inte är single page. Anledningen till mitt val var på grund utav att jag tänkte på att utveckla sidan vidare med fler information och eventuellt en webbshop. Sidans "section" del d.v.s. mittersta delen består av olika många delar på olika enheter och sidor t.ex. består sidan "Pricing" utav 3 vågrätt delar men på mobil versionen ändras dessa till lodrätt.

Jag har implementerat 2 olika media queries mindre än 1024px och mindre än 600px. Den första är för mellan stora skärman mindre än 1024px bred. Jag har valt just 1024px eftersom sidan just där börjar förlora kvalitet vid runt 1000px men jag ville få med Ipad pro med 1024x1366px så slutligen bestämde jag mig för att använda 1024px. 1024px är även ett bra val då de flesta tabletter och mindre laptops har den skärm bredden t.ex. har Ipad pro bredden 1024X1366px, Ipad med retina skärm 768x1024px och Ipad mini har lika många pixlar som Ipad retina.

Min nästa breakpoint ligger vid 600px bred då lite mindre pixlar leder till att sidan deformeras och innehållet kollapsar. Just 600px bred tycker jag är den perfekta breakpointen då de flesta mobila enheter har mindre än 600px bred. Kort fattat inkluderar max 600px alla mobila enheter som t.ex. Iphone 4,5,6,7,8 samt plus modellerna och nästan alla andra android mobiler.
## Test
  Tester är gjorda på olika webbläsare i olika operativ system. Sidan just nu fungerar på mobila plattformar (både android och Ios) och även desktop operativ system som Windows, Apple os och Ubuntu. De webbläsare som blev testade är främst Chrome, Edge, Firefox men även lite mindre använda webbläsare som t.ex. internet explorer. 
  Jag har även gjort tester på lite äldre browsers och sätt att webbsidan oftast fungera lika bra.
## Prefix från
  CSS autoprefixer använd från: https://autoprefixer.github.io/
  
  Jag har även tagit hjälp av: http://shouldiprefix.com/
## Feature queries
  Jag har använt mig utav featur queries för äldre webläsare som inte stödjer flex och som alternative til flex har jag använt float. Float är ett lite äldre element och stöds av de flesta browsers.
