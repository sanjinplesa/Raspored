# Raspored Sati

Interaktivni raspored sati s izmjeničnim tjednima (Tjedan A i Tjedan B).

## Značajke

- ✅ Prikaz trenutnog tjedna (A ili B) koji se automatski određuje
- ✅ Navigacija po tjednima (prethodni/sljedeći tjedan)
- ✅ Gumb "Danas" za brzi povratak na trenutni dan
- ✅ Istaknuti trenutni dan u tjednu
- ✅ Export rasporeda u iCal format za mobilni kalendar
- ✅ Responzivni dizajn

## Instalacija

```bash
npm install
```

## Pokretanje

```bash
npm run dev
```

Aplikacija će biti dostupna na `http://localhost:5173`

## Build

```bash
npm run build
```

## Korištenje

1. **Navigacija po tjednima**: Koristite gumbove "Prethodni tjedan" i "Sljedeći tjedan" za pomicanje kroz raspored
2. **Povratak na danas**: Kliknite gumb "Danas" za brzi povratak na trenutni tjedan i dan
3. **Export u kalendar**: Kliknite "Export u Kalendar" za preuzimanje .ics datoteke koja se može uvesti u bilo koji kalendar aplikaciju (Google Calendar, Apple Calendar, Outlook, itd.)

## Struktura rasporeda

- **Tjedan A**: 3., 5. i 7. razredi ujutro
- **Tjedan B**: 4., 6. i 8. razredi ujutro

Raspored se automatski mijenja između Tjedna A i Tjedna B na osnovu broja tjedna u godini.
