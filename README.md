# Djurgalleriet

Det här projektet är en enkel statisk första sida som visar ett galleri med stora djur. Sidan är byggd med vanlig HTML och CSS och kan serveras lokalt via ett npm-script utan något frontend-ramverk.

## Innehåll

- `index.html` innehåller sidans struktur och djurkorten.
- `styles.css` innehåller layout, färger och typografi.
- `ANIMALS.md` är källtexten med listan över djuren.
- `package.json` innehåller scriptet för lokal server.

## Kör lokalt

Kräver `npm` och `python3`.

```bash
npm run serve
```

Det startar en enkel statisk server på:

```text
http://localhost:3000
```

## Om sajten

Sidan fungerar som en första landningssida med:

- en tydlig hero-sektion
- ett responsivt galleri med djurbilder
- extern bildinläsning via Wikimedia Commons

Eftersom det är en statisk site är den enkel att vidareutveckla med fler sidor, lokal bildhantering eller JavaScript senare om det behövs.
