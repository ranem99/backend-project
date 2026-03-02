Backend Project – npm & REST

 Projektbeschreibung

In diesem Projekt habe ich ein Node.js-Backend mit npm initialisiert und eine strukturierte Projektarchitektur aufgebaut.
Ziel war es, die Grundlagen der Backend-Entwicklung sowie zentrale Konzepte wie REST und Backend-Architekturen zu verstehen.



Projekt starten

npm install
npm run dev
```

Danach im Browser öffnen:
[http://localhost:3000]

---

Projektstruktur

routes/   API-Endpunkte
controllers/ – Logik zur Verarbeitung von Anfragen
models/ – Datenstruktur
middleware/ – Zusatzfunktionen
app.js – Einstiegspunkt


--

REST-Beispiele
 Buch-API:
- GET /books – alle Bücher abrufen  
- GET /books/:id – Buch nach ID abrufen  
- POST /books – neues Buch erstellen  
- PUT /books/:id – Buch aktualisieren  
- DELETE /books/:id – Buch löschen  




Monolith: Eine einzelne, zusammenhängende Anwendung. Einfach zu entwickeln, aber schwer zu skalieren.  
Microservices: Die Anwendung ist in viele kleine, unabhängige Dienste aufgeteilt. Modular und skalierbar, aber komplexer wie amazon 