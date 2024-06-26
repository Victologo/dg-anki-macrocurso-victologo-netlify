---
{"dg-publish":true,"permalink":"/modulos-y-lecciones/enhance-main-window-configuracion-de-luis-letona/","noteIcon":"","updated":"2024-05-15T22:20:33.712+02:00"}
---


> [[7.16 📹 - Enhance main window - Anki Macrocurso\|7.16 📹 - Enhance main window - Anki Macrocurso]]

---

```
{
"book symbol": "{",
"cap value": null,
"color empty": "red",
"color empty descendant": "green",
"color zero": false,
"columns": [

{
"absolute": true,
"color": "red",
"description": "Cards you'll see today which are not new",
"header": null,
"name": "cards seen today",
"overlay": null,
"percent": false,
"present": false,
"subdeck": true
},

{

"absolute": true,
"color": null,
"description": "Cards in learning (either new cards you see again, or cards which you have forgotten recently, assuming those cards didn't graduate)",
"header": null,
"name": "learning card",
"overlay": null,
"percent": false,
"present": false,
"subdeck": true
},

{

"absolute": true,
"color": null,
"description": "Reviews which will happen later, either because a review happened recently, or because the card has many review left.",
"header": null,
"name": "learning later",
"overlay": null,
"percent": false,
"present": false,
"subdeck": true
},

{
"absolute": true,

"color": null,

"description": "Cards in learning which are due now",

"header": "En aprendizaje ahora",

"name": "learning now",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "green",

"description": "Review cards which are due today (not counting those in learning)",

"header": null,

"name": "review due",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "green",

"description": "Review cards you will see today",

"header": null,

"name": "review today",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"description": "Percent bar to do today",

"header": "<h1>Hoy🧐</h1>",

"name": "bar",

"names": [

"review today",

"learning card",

"new today",

"reviewed today"

],

"overlay": null,

"present": true,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Cards that have never been answered. Neither buried nor suspended.",

"header": null,

"name": "unseen",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Unseen cards you will see today (what Anki calls New cards). Neither buried nor suspended.",

"header": null,

"name": "new today",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of buried cards (cards you decided not to see today)/Number of suspended cards (cards you will never see unless you unsuspend them in the browser)",

"header": null,

"name": "buried/suspended",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of buried cards (cards you decided not to see today, or you saw a sibling)",

"header": null,

"name": "buried",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of suspended cards (cards you will never see unless you unsuspend them in the browser)",

"header": "Sus<br>pen<br>didas",

"name": "suspended",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "green",

"description": "Review cards you will see today (and the ones you will not see today)",

"header": "Repaso<br>Hoy",

"name": "review",

"overlay": null,

"percent": false,

"present": true,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Cards in learning which are due now (and in parentheses, the number of reviews which are due later)",

"header": "Aprendiendo<br>Hoy",

"name": "learning all",

"overlay": null,

"percent": false,

"present": true,

"subdeck": true

},

{

"absolute": true,

"color": "#598daf",

"description": "Unseen cards you will see today (what Anki calls New cards), followed by the unseen cards that you will not see today. Neither buried nor suspended.",

"header": "Nuevas<br>Hoy",

"name": "unseen new",

"overlay": null,

"percent": false,

"present": true,

"subdeck": true

},

{

"absolute": true,

"color": "yellow",

"description": "Number of cards in the deck",

"header": null,

"name": "cards",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "yellow",

"description": "Number of notes in the deck",

"header": null,

"name": "notes",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of reviewed cards with interval at least 3 weeks/less than 3 weeks",

"header": null,

"name": "mature/young",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of reviewed cards which are not yet due",

"header": null,

"name": "undue",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of reviewed cards with interval at least 3 weeks",

"header": null,

"name": "mature",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of reviewed cards with interval less than 3 weeks",

"header": null,

"name": "young",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "purple",

"description": "Number of marked notes",

"header": null,

"name": "marked",

"overlay": null,

"percent": true,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "purple",

"description": "Number of notes with a leech card",

"header": null,

"name": "leech",

"overlay": null,

"percent": true,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "magenta",

"description": "Number of reviewed cards seen today",

"header": null,

"name": "reviewed today",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "magenta",

"description": "Number of reviews done today",

"header": null,

"name": "repeated today",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "magenta",

"description": "Number of reviewed cards seen today and number of reviews",

"header": null,

"name": "reviewed today/repeated today",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Number of times you saw a question from this deck",

"header": null,

"name": "repeated",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "yellow",

"description": "Number of reviews you will see today (new, review and learning)",

"header": "Hoy<br>&#x1F7E2+&#x1F7E0+&#x1F535",

"name": "today",

"overlay": null,

"percent": false,

"present": true,

"subdeck": true

},

{

"description": "Percent bar showing the decks' repartition",

"header": "<h1>Total📚</h1>",

"name": "bar",

"names": [

"mature",

"young",

"learning card",

"unseen",

"buried",

"suspended"

],

"overlay": null,

"present": true,

"subdeck": true

},

{

"absolute": true,

"color": "yellow",

"description": "Number of cards/notes in the deck",

"header": "Total/<br>tarjetas/<br>notas",

"name": "notes/cards",

"overlay": null,

"percent": false,

"present": true,

"subdeck": true

},

{

"absolute": true,

"color": "green",

"description": "Reviewed cards which are due tomorrow",

"header": null,

"name": "due tomorrow",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Flags from 0 to 4",

"header": "Flags",

"name": "all flags",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": null,

"description": "Flags from 1 to 4",

"header": "Flags",

"name": "flags",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

},

{

"absolute": true,

"color": "Red",

"description": "Flag 1",

"header": "Flag 1",

"name": "flag 1",

"overlay": null,

"percent": false,

"present": false,

"subdeck": true

}

],

"default column color": "grey",

"do color empty": true,

"do color marked": true,

"dot in numbers": true,

"end symbol": ";",

"ended marked background color": "yellow",

"given up symbol": "/",

"hide values of parent decks": false,

"hide values of parent decks when subdecks are shown": false,

"marked background color": "powderblue",

"option": true,

"pause symbol": "="
}
```

---

> [[7.16 📹 - Enhance main window - Anki Macrocurso\|7.16 📹 - Enhance main window - Anki Macrocurso]]