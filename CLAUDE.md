# Instruktioner för Claude – Vilsna själar

Du hjälper två författare (Mattias och Martin) att skriva ett rollspelsäventyr i Kult-miljö. Skriv på svenska.

## Ditt viktigaste jobb: helheten hänger ihop

- Innan du ändrar något: läs [kanon/beslut.md](kanon/beslut.md) och [kanon/sanningen.md](kanon/sanningen.md). Det som står där gäller.
- Hittar du en motsägelse: rätta den **inte** på egen hand. För in den i [arbete/motsagelser.md](arbete/motsagelser.md) och fråga.
- När ett beslut fattas: för in det i `kanon/beslut.md` med datum, och uppdatera alla filer som berörs (sök efter namnet i hela repot).
- Uppfinn inga fakta som om de vore kanon. Förslag markeras tydligt som **Förslag:**.
- `arkiv/` är källmaterial, inte kanon. Använd det som inspiration, men det som står i resten av repot gäller.

## Struktur och konventioner

- En fil per entitet. Filnamn: gemener, bindestreck, inga å/ä/ö (`herman-abrahamsson.md`).
- Varje fil i `personer/`, `platser/`, `tradar/` och `scener/` har frontmatter enligt [mallar/](mallar/). Håll fälten `relationer`, `platser`, `tradar` och `personer` aktuella – de används för konsistenskontroller.
- Länka med relativa markdown-länkar, inte `[[wikilänkar]]`.
- Spelledarhemligheter markeras med `> **Spelledarhemlighet:**`.
- Kända motsägelser i en fil markeras med `> ⚠ **Motsägelse:**` och en länk till `arbete/motsagelser.md`.

## Dramaturgiska principer (fastställda)

- Inga tvingande vägar, tunnlar eller flyktvägar som för rollpersonerna mot ett bestämt slut. Ledtrådar är erbjudanden, inte tvång.
- Spelledarpersoners kunskap är verklig och begränsad. Ingen spelar allvetande.
- Undantag: den manusstyrda scenen i forntidens Sodom är avsiktligt förskriven.

## Konsistenskontroll

När du ombeds göra en genomgång, kontrollera minst:
1. Varje person som nämns har en fil, och varje fil nämns någonstans.
2. Relationer är ömsesidiga (står A→B ska B→A finnas).
3. Varje tråd har en drivkraft, berörda personer och ett möjligt slut (öppet är okej, men det ska stå).
4. Varje scen för minst en tråd framåt.
5. Inget strider mot `kanon/beslut.md`.
