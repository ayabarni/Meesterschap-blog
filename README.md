


### Meesterschap Blog

Dit is mijn Meesterschap blog voor de minor Web. In deze website verzamel ik mijn proces, vakken, Weekly Nerds, leerdoelen en reflecties.

De website is bedoeld als een persoonlijk overzicht van wat ik de afgelopen periode heb gemaakt, geleerd en onderzocht.



## Inhoud 

De website bestaat uit de volgende onderdelen:

- **Home**  
  Een overzichtspagina met links naar alle onderdelen van mijn blog.

- **Proces**  
  Een timeline met Sprint 0, Hackathon en een placeholder voor de Meesterproef.

- **Vakken**  
  Een overzicht van de vakken API, Human Centered Design, CSS en Browser Technologies.

- **Weekly Nerd**  
  Verslagen van de Weekly Nerd sessies, met per sessie een korte samenvatting, leerpunten en nieuwe termen.

- **Leerdoelen**  
  Drie leerdoelen waar ik richting de Meesterproef verder aan wil werken.

## Ontwerpkeuzes

Ik heb gekozen voor een visuele stijl met kaarten, zachte kleuren en duidelijke typografie. De homepage werkt als een overzichtsbord, zodat de bezoeker snel kan zien welke onderdelen er zijn en makkelijk kan doorklikken.

De pagina’s hebben elk een eigen vorm: de vakken en Weekly Nerds werken met tabs, het proces is weergegeven als timeline en de leerdoelen staan als aparte kaarten. Zo blijft de website overzichtelijk, maar voelt elke pagina toch passend bij de inhoud.
** Thema’s

Voor deze website heb ik twee thema’s gemaakt.

 ### Thema 1 — Procesbord

Het standaard thema is gebaseerd op een procesbord met sticky notes en papierachtige vormen.  
Dit past bij mijn Meesterschap blog, omdat de website verschillende onderdelen van mijn leerproces verzamelt: vakken, Weekly Nerds, proces, leerdoelen en reflecties.

De losse kaarten op de homepage werken als notities op een bord. Zo voelt de website als een verzameling van inzichten, stappen en onderdelen die samen mijn ontwikkeling laten zien.

### Thema 2 — Dark

Het tweede thema is geïnspireerd op de Hackathon en het project **Nebula Xplorer**.  
Dit thema gebruikt donkere kleuren en zachte accenten, waardoor de website een meer ruimtelijke sfeer krijgt.

Met de knop rechtsboven kan de gebruiker wisselen tussen de twee thema’s. De gekozen theme wordt opgeslagen met `localStorage`, zodat de keuze behouden blijft wanneer de gebruiker naar een andere pagina gaat.

## Omzetten naar Astro

Mijn blog was eerst opgebouwd als een gewone statische website met losse HTML-, CSS- en JavaScript-bestanden. Tijdens het omzetten naar Astro heb ik de structuur verdeeld over een algemene layout, aparte pagina’s en herbruikbare components.

De basisstructuur van de website staat in `Layout.astro`. Pagina’s zoals `index.astro`, `proces.astro`, `vakken.astro`, `weekly-nerds.astro` en `leerdoelen.astro` gebruiken deze layout. Herhalende onderdelen, zoals cards en procesitems, zijn omgezet naar components.

Voor cards met dezelfde structuur heb ik gewerkt met `Astro.props`, arrays en `.map()`. Hierdoor kan ik dezelfde component meerdere keren gebruiken met andere content. Voor onderdelen met verschillende inhoud, zoals de procesitems, heb ik een `<slot />` gebruikt.

De styling is verdeeld over `global.css`, paginastijling en componentstijling. Globale onderdelen zoals fonts, body-styling en dark mode staan in `global.css`. Styling die bij één pagina of component hoort, staat dichter bij dat onderdeel.

Door deze omzetting is mijn code overzichtelijker, minder herhalend en makkelijker aan te passen.

bronnen:
- https://www.magnific.com/free-photo/blank-brown-paper-textured-wallpaper_11295638.htm#fromView=keyword&page=1&position=2&uuid=2d48d8b0-b43e-4bd0-ac53-e12511f683f8&query=Brown+paper
-omzetten naar astro prpces:
https://chatgpt.com/share/6a3955d4-16e4-83ed-8b14-a047b6980d65


