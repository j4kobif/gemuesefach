# Gemüsefach

Gesund kochen mit dem, was da ist – eine Website, die aus deinen Zutaten vegetarische (auf Wunsch vegane) Gerichte vorschlägt.

## Funktionen
- **Zutaten eingeben** und passende Gerichte mit geschätzter Zubereitungszeit bekommen (108 Rezepte, u. a. je 10+ griechische, deutsche, italienische und vietnamesische Gerichte, Mengen meist für 2 Portionen)
- **Eigene Rezepte**: Name, Zutaten mit Gramm, Zubereitung und Portionen eintragen; Nährwerte werden automatisch aus der Nährwerttabelle berechnet (unbekannte Zutaten auf claude.ai per Claude geschätzt) oder selbst eingetragen; bearbeiten und löschen
- **Tagesplan**: eigenes Kalorienziel und optionale Nährwertziele (Eiweiß, Kohlenhydrate, Fett, Ballaststoffe, Zucker-Obergrenze) eingeben, bereits Gegessenes abziehen und einen Plan aus Frühstück, Mittag, Abend und Snack bekommen, der nah am Ziel liegt (mit Portionsgrößen, Tauschen pro Mahlzeit, Makro-Übersicht); jede Rezeptkarte zeigt den Anteil am Tagesziel
- **Reiter „Gerichte“**: alle Rezepte auf einen Blick, mit Suche nach Gericht oder Zutat, Filtern (Küche, Mahlzeit, Zeit, nur mit meinen Geräten) und Sortierung nach Name, Zeit, kcal oder Eiweiß
- **Küchengeräte-Abfrage** beim ersten Start, jederzeit unter „Meine Küche“ änderbar – Vorschläge und Zeiten passen sich an (z. B. Airfryer statt Ofen)
- **Nährwerte**: kcal, Eiweiß, Kohlenhydrate, Zucker, Fett und Ballaststoffe pro Portion für jedes Rezept und jeden Snack, mit Mengenangaben je Zutat und % der Referenzmenge; eigener Tab mit einer sortierbaren Nährwerttabelle aller Zutaten (immer pro 100 g, mit Stückangaben wie „100 g ≈ 0,7 Orange“)
- **Aufpimpen**: optionale Extra-Zutaten für jedes Gericht
- **Unverträglichkeiten & Allergien**: Laktose, Milcheiweiß, Ei, Gluten, Nüsse, Erdnüsse, Soja, Sesam, Sellerie und Senf – Zutaten werden durch verträgliche Varianten ersetzt (z. B. laktosefreier Joghurt, glutenfreie Nudeln) oder Gerichte ausgeblendet; Allergene stehen auch in der Nährwerttabelle
- **Vegetarisch oder vegan** per Schalter – Milchprodukte und Eier werden automatisch ersetzt
- **Gesunde Snacks**: 12 selbstgemachte Alternativen, z. B. Schoko-Haselnuss-Creme mit Datteln statt Nuss-Nougat-Creme
- **Wocheneinkauf**: Grundvorrat zum Ankreuzen (nur Angekreuztes kommt auf die Liste, „Hab ich“ markiert Vorrätiges fürs Kochen), saisonales Obst & Gemüse mit Wochenkorb-Vorschlag, geschätzte Kosten pro Produkt und für die ganze Liste, Haltbarkeit und Lagerort, Liste sortiert nach Verbrauchsreihenfolge, Lager- und Spartipps; Auswertung, wie viele Gerichte der Einkauf ermöglicht, wie weit Gemüse und Obst reichen und welche Zusatzprodukte am meisten weitere Gerichte freischalten
- **Saftbar**: 14 Smoothies, Säfte, Shakes, warme Getränke und Erfrischungen ohne zugesetzten Zucker, mit Nährwerten

Alles läuft im Browser, ohne Server. Einstellungen werden im `localStorage` gespeichert.

## Starten
`index.html` im Browser öffnen oder über GitHub Pages veröffentlichen (Settings → Pages → Branch `main`).
