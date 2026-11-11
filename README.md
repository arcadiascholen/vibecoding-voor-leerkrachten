# Intro tot vibe coding voor leerkrachten

Een praktische workshop voor leerkrachten in het secundair onderwijs. Je vertrekt van een behoefte in je eigen lespraktijk en bouwt met AI een kleine, interactieve toepassing. De workshop duurt 90 minuten. Je hebt een laptop en toegang tot een AI-tool nodig, maar geen programmeerkennis.

**[Open het leerpad](https://arcadiascholen.github.io/vibecoding-voor-leerkrachten/)**

## Wat doe je in de workshop?

- **Intro en demo:** ontdek wat vibe coding is en bekijk voorbeelden uit de lespraktijk.
- **Zelf aan de slag:** beschrijf een lesbehoefte, vergelijk oplossingen en bouw een eerste versie. Test de werking, inhoud en gebruiksvriendelijkheid. Verbeter daarna gericht en test opnieuw.
- **Delen en verder bouwen:** bewaar je toepassing, publiceer ze met Netlify en ontdek hoe je ze later kunt uitbreiden.

Bij de bouwstappen staan voorbeeldprompts die je kunt kopiëren. Wil je liever zelf typen of inspreken? Het spiekbriefje naast elke prompt geeft je de belangrijkste punten mee.

## Lokaal openen en aanpassen

Deze website is gebouwd met Astro. Je hebt Node.js 22.12 of nieuwer en npm nodig. Voer dit uit in de projectmap:

```sh
npm ci
npm run dev
```

Open [het lokale leerpad](http://localhost:4321/vibecoding-voor-leerkrachten/).

- De inhoud en volgorde van de pagina’s staan in [index.astro](src/pages/index.astro).
- De vormgeving van het leerpad staat in [workshop.css](src/styles/workshop.css).

Controleer een wijziging met `npm run check` en `npm run build`.

## Publicatie en herkomst

Het leerpad zelf staat op GitHub Pages. Bij een push naar `main` bouwt en publiceert GitHub Actions de website. Netlify is de publicatieroute die deelnemers tijdens de workshop leren gebruiken voor hun eigen toepassingen.

De technische basis en vormgeving komen uit de [AI-leerlijn van Arcadia Scholen](https://github.com/arcadiascholen/ai-leerlijn). De [GPL-3.0-licentie](LICENSE) blijft behouden.
