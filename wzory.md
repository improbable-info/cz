---
mathjax: true
---
## Wzory matematyczne

Aby na stornie używać wzorów,
wystarczy w konfiguracji storny (trzy minusy konfiguracja, trzy minusy na początku strony) dodać zmianną `mathjax: true`

Potem, dowolny text ubrany w podwójne dolary jest interpletowany jako wzór matematyczny.
Wzory można sobie online próbowac np tu: https://arachnoid.com/latex/ 

### Przykład

$$\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{aligned}$$

### Przy okazji...
interaktyne gry w życie też będzie można osadzić na stronie.
Tutaj przykład:
https://github.com/nomatteus/conway-game-of-life-js 

### zmienne

Zmienna site.github.repository_name = {{ site.github.repository_name }}

### indeks górny i dolny

Przydładoo <sup>górnego</sup> indeksu oraz <sub>dolnego</sub> indeksu poprzed tagi html.
Dodatkowo do do pojedynczych cyffr można uzyć odpowiedniego znaku unikodowego: E=mc² 

Lista unikodowych znaków w indeksach górnych i dolnych jest tu:
https://en.wikipedia.org/wiki/Unicode_subscripts_and_superscripts


