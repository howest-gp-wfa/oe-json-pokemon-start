# oe-pokemon

## Voor je begint ...
Voor deze opdracht maken we een bevraging naar een echte (eigen) online bron.
Hiervoor maken we gebruik van Github pages. **deze moet nog door jou ingesteld worden**.

Wanneer je je eigen repository voor deze oefening gemaakt hebt doe je het volgende:
* Ga via de browser naar jouw online repository
* Klik op 'Settings'
* Zoek naar in de settings naar 'Github pages'
* Selecteer in de twee dropdowns dat je de `master` branch als build source voor je Github page wil gebruiken in combinatie met de `/docs` folders.
* **Klik op save**

Wanneer je opgeslaan hebt, verschijnt er bovenaan een link naar waar je repository gepubliceerd werd. Beschouw deze als de rootfolder. Vervolgens kun je de json-file online raadplegen via: `https://url-naar-jouw-github-pages/api/pokemon.json`.

## Opzet van de oefening
Je hebt nu een online bron die jouw gegevens over de allereerste 9 pokémons aanlevert. Schrijf nu, zoals gewoonlijk, JavaScript code die de online bron aanspreekt om de pokemons weer te geven op je 'pokedex'.

Met andere woorden: bevraag eerst je online bron via een `fetch()` en/of een `XMLHttpRequest`, lees de ontvangen json-data uit en geef ze weer in het HTML-element met id `pokedexscreen`.

Zorg ervoor dat je op de pokedex een lijst toont van alle pokemons die je ontvangt in json.
Elke pokemon heeft bovendien een lijst van types. Toon ook alle types van de pokemon.