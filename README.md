# Vår Matkorg – direktmejl v4

Den här versionen skickar inköpslistan direkt från webbsidan med FormSubmit. Ingen e-postapp öppnas.

## Viktigt: publicera sidan

Direktsändning fungerar när sidan ligger på en webbadress, till exempel GitHub Pages. Den fungerar inte när `index.html` öppnas direkt som en lokal `file://`-fil.

## Aktivera mottagarna en gång

1. Publicera sidan på GitHub Pages.
2. Lägg en maträtt i varukorgen.
3. Tryck **Skicka till Oliver**. Oliver får ett aktiveringsmejl från FormSubmit och godkänner länken.
4. Tryck **Skicka till Isabella**. Isabella godkänner sin aktiveringslänk.
5. Därefter skickas framtida inköpslistor direkt från sidan.

Knappen **Skicka till båda** skickar till Oliver och kopierar Isabella.

## Integritet

Mottagaradresserna ligger i sidans JavaScript och är därför synliga i källkoden på en offentlig GitHub Pages-sida. FormSubmit är en extern tjänst som behandlar formulärinnehållet för att leverera mejlet.
