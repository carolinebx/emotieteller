# Emotiedagboek en hulpwijzer

Een eenvoudige, statische webapp om emoties te leren herkennen, bij te houden en te bespreken met een therapeut.

- Gebaseerd op een gevoelskaart met vier vakken (energie hoog/laag x gevoel vervelend/prettig)
- Dagboek met lichaamssignalen, emoties, gedachten, behoeften en acties
- Overzicht: wanneer voel ik wat, en wat werkt voor mij
- Samenvatting van de afgelopen 7 dagen om te delen met je therapeut

## Privacy

Alles wordt alleen opgeslagen in de browser van de gebruiker (`localStorage`). Er is geen server, geen account en er worden geen gegevens verstuurd. Wisselt iemand van browser of apparaat, of wist die de browserdata, dan verdwijnen de notities. Gebruik daarom de samenvatting om te bewaren.

## Deployen op Netlify

1. Zet deze map in een GitHub-repository.
2. Ga in Netlify naar **Add new site > Import an existing project** en kies de repository.
3. Laat build command leeg en zet publish directory op `.` (staat al in `netlify.toml`).
4. Klik op **Deploy**.

## Lokaal bekijken

Open `index.html` in een browser.

## Let op

Dit is een hulpmiddel en geen vervanging van professionele hulp. Bij gedachten aan zelfmoord: 113 (0800-0113) in Nederland, 1813 in Belgie.
