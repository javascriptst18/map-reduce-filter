# Map, filter & reduce

I `index.js` finns en array med objekt. Längre ner i filen så finns ett antal funktioner som filterar denna array och plockar ut vissa värden och returnerna dessa värden. Just nu använder koden vanliga for-loopar som vi använt tidigare. Målet i denna övning är att konvertera dessa till att använda funktionerna `map`, `reduce` samt `filter`. **Alla funktioner är redan färdigskrivna och själva funktionaliteten ska inte ändras.**

## Uppgift

* Du/ni ska konvertera dessa funktioner som använder "vanliga for-loopar" till att använda `map`, `reduce` och `filter`. Gå först igenom den ursprungliga koden och försök förstå vad funktionerna gör innan du försöker konvertera. Fokusera på en funktion i taget. Den enklaste är den första och sedan ökar svårighetsgraden

Funktionerna besvarar följande frågor:
* Skriv ut namnen på alla länder i databasen.
* Hur många bor i hela (arrayen) världen?
* Hur många bor i Europa?
* Vilket land har minst befolkning i världen?
* Vad är medelbefolkningen för länder i Afrika?
* Finns det något land som har mer än 50000000 invånare?
* Vilka länder har mellan 8 och 15 miljoner invånare?

## Länklista

* https://medium.com/humans-create-software/a-dirt-simple-introduction-to-higher-order-functions-in-javascript-b33bf9e19056
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter