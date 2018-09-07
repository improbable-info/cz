## VII. Vesmír jako buněčný automat

Jestliže chceme představit model vesmíru jako buněčný automat, musíme si nejprve vyjasnit,
co to ten buněčný automat vlastně je. Nebudeme se tu zabývat detaily, uvedeme pouze definici a jednoduchý pŕíklad. 

**Buněčný automat** je objekt skládající se z sítě buněk, které mohou nabývat jeden z možných stavů z určitého souboru,
který se mění podle zadaných pravidel v závislosti na stavu sousedních buněk.
Podle druhu sítě, možných hodnot buněk a volby algoritmu mohou existovat nejrůznějši buněčné automaty.
Nejznámějším buněčným automatem je asi "Game of Life" ("Hra života").
Čtvercové buňky uložené v rovině mohou nabývat jeden ze dvou stavů : být živé nebo mrtvé.
Počáteční stav může být zadán nebo vybrán náhodně a pravidla pro výpočet stavu v následujícím kroku jsou následující:

- živá buňka umírá, jestliže má měně než dva anebo více než tři živé sousedy,
jestli má dva nebo tři živé sousedy zůstává živá

- mrtvá  buňka ožívá, jestliže má přesně tři živé sousedy 

Již tak jednoduchá pravidla mohou vést k vytvoření velmi zajímavých struktur,
které se mohou například samy reprodukovat.

Jak je možné modelovat vesmír pomocí buněčných automatů? Například využít trojrozměrnou síť buněk,
v každé buňce ustavit parametry odpovídající nějakému množství hmoty a různých sil nebo hodnotám pole,
nastavit pravidla, jak se má měnit obsah každé buňky v závislosti na stavu sousedních buněk a spustit automat.
V takovém modelu čas plyne shodně s naší představou o plynutí času, s tím, že zde máme nejmenší časový interval
- jeden krok v činnosti automatu - existuje též nejmenší vzdálenost - rozměr buňky, existuje největší rychlost,
jakou se mohou šířit změny v prostoru atd. Vidíme, že takový model má nejen přirozeně plynoucí čas,
ale má též jisté kvantové vlastnosti. Může to být jedna z cest, jak modelovat vesmír...

## [VIII. Několik slov o prostoru](rozdzial8)
