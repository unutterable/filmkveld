# 🎬 Filmkveld

En webapp for å velge en tilfeldig film fra Silje og Bjørn Tores DVD-samling (861 filmer!).

## Funksjoner

- **Tilfeldig filmtrekning** med animert visning
- **Stemningsfilter** — velg mellom Skummel (Horror), Spennende (Thriller), Smartysmart (Drama/Dokumentar) og Urealistisk (Fantasy/Sci-Fi/Animation)
- **Filmdetaljer fra TMDB** — plakat, user score, spilletid, sjanger, regissør, tagline, overview og cast
- **YouTube-trailer** lenket direkte fra filmkortet
- **Historikk** over tidligere trekninger i samme session
- **Ingen duplikater** — samme film foreslås aldri to ganger per session
- **Installerbar som webapp** (PWA) — legg den på hjemskjermen!

## Sett opp med GitHub Pages

1. Opprett et nytt repository på GitHub (f.eks. `filmkveld`)
2. Last opp alle filene i dette prosjektet
3. Gå til **Settings** → **Pages**
4. Under **Source**, velg `main` branch og `/ (root)`
5. Klikk **Save**
6. Etter noen sekunder er siden live på `https://<brukernavn>.github.io/filmkveld/`

## Legg til på hjemskjermen

### iPhone / iPad (Safari)
1. Åpne siden i Safari
2. Trykk på **Del**-ikonet (firkant med pil opp)
3. Velg **Legg til på Hjem-skjerm**
4. Gi den et navn og trykk **Legg til**

### Android (Chrome)
1. Åpne siden i Chrome
2. Trykk på **⋮**-menyen
3. Velg **Legg til på startskjermen** / **Installer app**
4. Bekreft

## Teknologi

- Vanilla HTML/CSS/JS — ingen byggsteg eller avhengigheter
- [TMDB API](https://www.themoviedb.org/) for filmdata og plakater
- PWA med service worker for offline-støtte
- Filmdata eksportert fra [Letterboxd](https://letterboxd.com/)

## Filstruktur

```
filmkveld/
├── index.html       # Selve appen (alt-i-ett)
├── manifest.json    # PWA-manifest
├── sw.js            # Service worker
├── icon-192.png     # App-ikon (192×192)
├── icon-512.png     # App-ikon (512×512)
└── README.md        # Denne filen
```

---

*Laget med ❤️ for filmkvelder med popcorn*
