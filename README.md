Lighthouse-test – Veldverkenner Bloemenveld Frankendael
Link: https://youneselkharraz.github.io/the-client-website/#kaart

Performance: 85 · Accessibility: 87 

De website behaalde een Accessibility-score van 87 en een Performance-score van 85. Beide scores vallen in het oranje gebied (50–89). Dat betekent dat Lighthouse een paar aandachtspunten heeft gevonden.

Verbeterpunten:

Contrast: De Latijnse plantnamen (<p class="latijn">), zoals Lamium album, Achillea millefolium en Oenothera biennis, hebben te weinig contrast met de lichte achtergrond. De lichte olijfkleur is daardoor slecht leesbaar, vooral voor mensen die minder goed zien. Volgens WCAG moet normale tekst een contrast van minimaal 4.5:1 hebben.
Oplossing: de tekstkleur van .latijn donkerder maken en daarna controleren met de contrastchecker in Chrome DevTools.
Performance: De pagina laadt redelijk snel, maar haalt nog geen 90. Afbeeldingen kleiner maken en comprimeren kan de laadtijd verbeteren.

Conclusie: Het belangrijkste toegankelijkheidsprobleem is het lage contrast van de Latijnse plantnamen. Na het aanpassen van de kleur voer ik de Lighthouse-test opnieuw uit om te controleren of de score verbetert.
