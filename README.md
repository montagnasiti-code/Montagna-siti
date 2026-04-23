# Montagna Web

Sito web di Montagna Web — realizzazione siti professionali per attività locali in Valtellina.

**Live:** [montagnaWeb.it](https://montagnaWeb.it)

## Deploy (GitHub Pages)

Il sito è deployato tramite GitHub Pages. Per attivarlo:
1. Vai su Settings → Pages → Source: `main` branch, root `/`
2. Imposta il dominio custom nelle impostazioni DNS del tuo provider puntando a GitHub Pages
3. Il file `CNAME` contiene il dominio custom (`montagnaWeb.it`)

## Analytics

Usa [GoatCounter](https://www.goatcounter.com) — crea un account gratuito con slug `montagnaWeb` e le visite vengono tracciate in modo privacy-friendly, senza cookie.

## Struttura

```
index.html      ← sito principale
favicon.svg     ← icona sito
robots.txt      ← istruzioni motori di ricerca
sitemap.xml     ← mappa sito per Google
CNAME           ← dominio custom GitHub Pages
.nojekyll       ← disabilita Jekyll (necessario per GitHub Pages)
assets/
  Jack.png
  Jack face.png
  desktop_phone.png
```
