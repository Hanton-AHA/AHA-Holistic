# AHA Holistic – ny hemsida

## Filer som ska laddas upp till GitHub
Ladda upp samtliga filer i denna mapp till huvudmappen i ert GitHub-repository.

Viktigt:
- Filen måste heta `style.css`, inte `style.htm`.
- CNAME-filen ska heta exakt `CNAME`, utan filändelse.
- Ta bort eller ersätt de gamla filerna innan ni laddar upp dessa.
- Behåll alla HTML-filer, `style.css`, `script.js`, `logo.jpg` och `CNAME`.

## Sidstruktur
- `index.html` – startsida
- `om-oss.html` – längre presentation av er
- `ovningar.html` – videos och övningar
- `andrum.html` – bloggöversikt
- `inlagg-valkommen.html` – första blogginlägget
- `retreats.html` – retreats, cirklar och säkerhet
- `kontakt.html` – kontaktuppgifter och formulär

## Lägga in en YouTube-video
1. Ladda upp videon på YouTube. Den kan vara offentlig eller olistad.
2. Klicka på Dela → Bädda in.
3. Kopiera iframe-koden.
4. Öppna `ovningar.html`.
5. Sök efter texten `Lägg in er YouTube-video här`.
6. Ersätt hela raden som börjar med `<div class="video-placeholder">` med iframe-koden.
7. Lägg gärna till `style="width:100%;aspect-ratio:16/9;border:0;"` i iframe-taggen.

## Skapa ett nytt blogginlägg
1. Kopiera `inlagg-valkommen.html`.
2. Döp kopian, exempelvis `inlagg-att-valja-narvaro.html`.
3. Ändra datum, rubrik och text i den nya filen.
4. Kopiera ett `<article class="post-card">...</article>` i `andrum.html`.
5. Ändra länk, datum, rubrik och introduktion så att den leder till det nya inlägget.

## Kontaktuppgifter
I `kontakt.html` ligger tillfälliga exempel:
- hello@ahaholistic.se
- @ahaholistic

Ändra dem om de inte stämmer. Sök även efter e-postadressen i samma fil eftersom den finns i formuläret.

## Domän
CNAME-filen innehåller:
www.ahaholistic.se

Ändra inte detta om det är den domän som redan är kopplad till GitHub Pages.
