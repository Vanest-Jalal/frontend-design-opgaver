# Din refleksion

Skriv her:

`:has()` er en god løsning i denne opgave, fordi kortene kan styles ud fra det indhold, de allerede har. Derfor behøver man ikke tilføje ekstra classes i HTML, fx en class til kort med billede eller en class til kort uden overskrift.

For eksempel kan `.card:has(img)` bruges til at finde de kort, der indeholder et billede, mens `.card:not(:has(img))` finder de kort, der ikke gør.
