## X. Proč si myslíme, že myslíme logicky?

Jako právě každé slovo může mít slovo **logika** několik významů, které navíc mohou různí lidé
různě chápat. Zde se bez nějakých hlubších analýz budeme držet názoru, že logika je způsob odvozování
a dokazování, který se snaží o to, aby odvozování a dokazování probíhalo podle nějakých pravidel,
která mají zajistit, že se nedopustíme chyb.
...
<!--Nejprve je třeba si uvědomit, že odvozování a dokazování probíhá v nějakém jazyce.
Přitom každý přirozený jazyk je nepřesný a sémanticky neúplný. V žádném jazyku se nedá přesně vysvětlit
význam všech jeho slov. (K tomu je potřebný metajazyk, čili bohatší jazykový systém,
který je ale zase sémanticky neúplný, a k vysvětlení svých pojmů potřebuje ještě bohatší metajazyk atd.).
Proto se pro potřeby logiky zavádí formální jazyk logiky, ve kterém se dá přesněji formulovat odvozování
a dokazování, ale který je nutně chudší než přirozený jazyk a  neodpovídá  skutečnosti,
která je bohatší. Umíme jej ale popsat v našem přirozeném jazyku (který je metajazykem vzhledem k jazyku logiky)
a umíme ho používat v různých modelech (například v matematice).

V běžném životě při řešení praktických problémů používáme přirozený jazyk a takové způsoby odvozování
a dokazování, které nezajišťují pravdivost našich závěrů v každé situaci. Stačí nám,
že je náš závěr v našich podmínkách prakticky použitelný. Myslíme si, že myslíme logicky jen proto,
že si neuvědomujeme chyby, kterých se dopouštíme.  Navíc v našich úvahách většinou mlčky připouštíme
spousty předpokladů, které si mnohdy ani neuvědomujeme, a které vůbec nemusí obecně platit.
A pokud jsou některé naše předpoklady nepravdivé, pak i když z nich něco skutečně logicky vyplývá,
nemusí to být pravda.

Jak jsme si řekli výše, odvozování a dokazování probíhá v nějakém jazyce. A tu se objevuje první otázka.
Jak rozvinutý musí být jazyk a jaké musí mít vlastnosti, aby na jeho základě mohla vzniknout nějaká logika.
A hned za tím se objeví druhá otázka, zda na základě různých jazyků mohou vzniknout různé logiky.
Mohou se množit i další otázky, třeba jak moc logika závisí na světě kolem nás nebo na tom,
jak ho vnímáme, jaká je závislost mezi naší logikou a naší matematikou a podobně.

Naše úvahy začneme od zkoumání jazyka. Připustili jsme možnost jazyka, který by měl pouze jedno slovo
– například signál značící nebezpečí. To je ale málo, abychom mohli dokazovat nějaká tvrzení.
Jak musí být jazyk minimálně rozvinutý, aby na jeho základě mohla vzniknout logika?

Odpověď na tuto otázku můžeme hledat různými způsoby. Jedna z možností je pátrat po tom,
jak vypadaly jazyk a logika u lidí na samém začátku lidské existence a jak se postupně vyvíjely.
Je dobré se nad tím zamyslet, ale abychom se neomezovali pouze na lidskou zkušenost a měli větší šanci
najít nějakou logiku pokud možno odlišnou od naší, je dobré zkoumat i jiné možnosti.
Pokusme se alespoň v představách vytvořit v počítači virtuální svět s nějakými jednoduchými pravidly
a v něm populaci tvorů, kteří se mohou učit pomocí neuronových sítí.
Celý jejich pozorovatelný svět může být pouze řetězec nul a jedniček, kde se občas podle nějakých pravidel
některé jedničky mění na nuly a některé nuly na jedničky. Předpokládejme, že na některé změny
mohou mít naši tvorové vliv a pro přežití potřebují alespoň z času na čas dosáhnout určité kombinace
nul a jedniček. Snadněji toho mohou dosáhnout, pokud budou spolupracovat.
Pokud zajistíme vhodný evoluční mechanizmus, můžeme připustit, že po nějakém čase by u nich
mohl vzniknout jazyk, kterým by se tito virtuální tvorové dorozumívali.

Nebudeme zde řešit problém, jak zajistit, aby uměli z vnějšího světa oddělit své druhy,
rozeznat jejich chování a mít možnost si s nimi vyměňovat nějaké signály. Jde nám teď pouze o to,
jak by se asi mohl vyvíjet jejich jazyk a jak by mohla vypadat jejich logika.
Zajímá nás zde problém, jak dalece mohou být odlišné od našich, ale takové, aby většina lidí uznala,
že už to je jazyk a logika.

Pokud model tvoříme v číslicovém počítači, kde v každé buňce paměti rozeznáváme jen dva stavy,
které obvykle označujeme nulou a jedničkou, je pravděpodobné, že pro tyto dva stavy vzniknou
i v řeči virtuálních tvorů nějaká slova. Protože význam má i pozice každé číslice,
vzniknou pravděpodobně i slova pro označení pozice, čili jakási obdoba přirozených čísel.
Můžeme předpokládat, že vytvoří slova označující jednotlivé tvory, slova pro různé kombinace nul a jedniček,
které pro ně mají nějaký praktický význam, slova pro činnosti, které budou schopni vykonávat atd.
Připomeňme si, jak nová slova mohou vznikat a jak se tvorové mohou naučit jim rozumět.
Jednou z možností je předpoklad, že tvorové mají podobné potřeby a podobné reakce,
a mohou nějakým způsobem vnímat, co se děje kolem a jak se chovají ostatní.
Jestliže někdo vytvoří nové slovo, které ostatní budou vnímat v nějaké konkrétní situaci,
pak se po několika opakováních neuronové sítě naučí spojovat toto slovo s touto konkrétní situací
a i ostatní začnou toto slovo v podobné situaci používat. Je možné, že většina pochopí nové slovo jinak,
než byl původní záměr, a význam slova se změní. Je vidět, že velmi užitečná a potřebná mohou být slova,
která by usnadnila tvorbu nových slov a pochopení jejich zamýšleného významu, čili vlastně metajazyk
k danému jazyku. Metajazyk ale vzniká současně s jazykem, mísí se s ním, vznikají nové výrazy,
k jejichž vysvětlení jsou ale potřebné další výrazy a tak se jazyk neustále rozvíjí.
Nás teď zajímá, kdy mohou vzniknout jazykové konstrukce umožňující odvozování a dokazování
a jak mohou vypadat. Zdá se, že je nutná nějaká konstrukce typu **„jestliže ..., pak ...“**,
protože bez ní je těžko mluvit o nějakém odvozování nebo dokazování. Můžeme si sice představit virtuální svět,
ve kterém se vše děje náhodně a ve kterém by tato slovní konstrukce nevznikla,
ale pak by zde asi nejen nevznikla ani žádná logika, ale ani žádní tvorové.

Pokud si připomeneme naši definici informace, jako jakousi vazbu mezi dvěma strukturami nebo jevy,
pak je vidět, že slovní konstrukce **„jestliže ..., pak ...“** odpovídá právě této vazbě a zdá se tedy,
že je natolik univerzální, že by se na jistém stupni rozvoje měla objevit v nějaké formě v každém jazyku.

Zamysleme se teď chvíli nad tím, jak vlastně my něco dokazujeme. Naše dokazování spočívá zhruba na tom,
že některá jednoduchá tvrzení považujeme za evidentně pravdivá a složitější tvrzení se snažíme převést
na řetězec kroků, z nichž první je evidentně pravdivý a každý následující vyplývá z předchozího podle pravidel,
která též považujeme za pravdivá.

Jeden z problémů je, jak určit, která tvrzení jsou evidentně pravdivá. V matematice, nebo nějakém modelu,
je můžeme definovat nebo předpokládat. Ve skutečném světě to nevíme a musíme se dohodnout.
Pokud přijmeme za pravdivá jiná tvrzení, než někdo jiný, dojdeme k jiným závěrům. Někomu se může zdát,
že to není žádný problém, že o základních pravdách se může každý přesvědčit. Bohužel nemůže
a přijímá je jako fakt pod vlivem rodiny, školy, společnosti nebo v důsledku vlastních zkušeností a úvah.
Abychom mohli cokoliv dokázat, musíme vyjít z nějakých předpokladů, které považujeme za pravdivé bez důkazu.
Pokud se dá z našich předpokladů stvořit model světa, který je shodný s naší zkušeností a je použitelný v praxi,
můžeme považovat naše předpoklady za pravdivé, ale vůbec to neznamená, že musí platit vždy a všude.

Kromě toho, že k dokazování potřebujeme tvrzení, která považujeme za pravdivá bez důkazu,
máme tu ještě sám problém pravdivosti. V klasické logice se pracovalo s výroky, o kterých se předpokládalo,
že mohou být pouze buď pravdivé nebo nepravdivé. Pravdivým se někdy přiřazovala hodnota „1“ a nepravdivým „0“.
Pokud se tu pokusíme o nějaké porovnání logiky s matematikou, pak to odpovídá takové úrovni matematiky,
kde umíme počítat jenom do dvou.

Tříhodnotová logika připouští ještě třetí hodnotu – neznámo, které přiřazuje hodnotu ½ .
Při porovnání s čísly to ale neodpovídá zlomkům, ale spíše by se této hodnotě měla přiřadit nula,
pravdě jednička a nepravdě minus jedna. Odpovídá to zhruba v matematice zavedení nuly.
Další zobecnění, které by odpovídalo v matematice zavedení reálných čísel, bylo zavedení fuzzy logiky,
kde stupeň pravdivosti může být vyjádřen libovolným reálným číslem mezi nulou a jedničkou.

Všechny tyto logiky jsou ale stále v souladu s našimi zkušenostmi. K novým logickým závislostem,
které nevyplývají z naší každodenní zkušenosti, nás přivedly až kvantové jevy. Zde se například objevuje něco,
co by se dalo nazvat „odmocnina z negace“. S využitím kvantových jevů se dá sestrojit logická branka,
která dává zdánlivě náhodný výsledek, ale dvě takové branky za sebou dávají negaci.
Něco takového jsme dříve neznali. Pokud si znovu uděláme porovnání s matematikou,
odpovídá to zhruba imaginární jednotce u komplexních čísel. Stále zde vidíme velmi úzkou souvislost
mezi logikou a matematikou. Jako další zobecnění logiky bychom tedy mohli hledat něco,
co by odpovídalo hyperkomplexním číslům.

Jedna z možných cest je tedy další zobecňování logiky současně s dalším rozvojem matematiky.
Znovu se zde ale objevuje otázka, jak dalece by se mohla nějaká matematika lišit od naší?

Pokusme se představit si, jak by mohla vypadat matematika u našich virtuálních tvorů.
Připustili jsme, že si vytvoří slova pro označení pozice, čili jakousi obdobu přirozených čísel.
Ale vzhledem k tomu, že jejich prostor bude mít konečný počet buněk, bude u nich existovat největší možné číslo,
do kterého když dodáme jedničku, tak dostaneme znovu nejmenší číslo. Pravděpodobně vůbec nedojdou k pojmu nekonečno,
úplně jinak u nich bude vypadat indukce a celá jejich matematika bude možná operovat jen na konečné množině čísel.

Jen tak mimochodem, v našem vesmíru možná též existuje největší číslo. Uznáváme, že existuje nejmenší délka,
nejmenší částečka hmoty, největší rychlost, že náš vesmír trvá jen konečnou dobu.
Možná tedy v našem vesmíru existuje i největší možná vzdálenost, největší možná hmota,
největší možné množství částic atd. Pokud v reálném světě  neexistuje nekonečno,
pak by mělo existovat jisté číslo tak velké, že nic v našem vesmíru nemůže být větší než toto číslo.

Předpoklad, že ke každému číslu existuje číslo ještě větší, se nám zdá samozřejmý, ale vede k různým matematickým
i logickým paradoxům spojeným s nekonečnem. Zrovna tak naše představa nekonečné přímky, roviny atd.
je sice geniálním výtvorem naší abstrakce, ale nemusí vůbec odpovídat skutečnosti kolem nás
a může nás mýlit v našem chápání světa.

Jak si ale představit konečnou číselnou osu? Jedna z možností je třeba představit si číselnou osu jako kružnici,
na které zvolíme jeden bod jako nulu, jedničce přiřadíme bod na kružnici o čtvrt kružnice vpravo,
dvojce o čtvrt plus jedna osmina kružnice vpravo, trojce o čtvrt plus jedna osmina plus jedna šestnáctina
kružnice vpravo atd. Čím větší číslo, tím blíže bude protilehlému bodu na kružnici.
Záporná čísla pak budou analogicky na kružnici vlevo. Pokud připustíme možnost nekonečného dělení kružnice,
dostaneme na kružnici nekonečně mnoho celých čísel. Pokud ale uznáme, že existuje minimální vzdálenost,
kterou již nemůžeme rozdělit, pak dostaneme i největší číslo, do kterého když dodáme jedničku,
tak překročíme bod ležící na kružnici naproti nuly a dostaneme nejmenší možné číslo (největší číslo s minusem).
Analogicky si můžeme představit konečnou množinu komplexních čísel na povrchu koule atd.

Úvahy o inteligentních tvorech s omezeným počtem buněk paměti zvýrazňují ještě jednu věc,
kterou si často neuvědomujeme. Velikostí paměti, jakou máme k dispozici, je omezena velikost a složitost modelu,
jaký si můžeme vytvořit. Omezená velikost paměti vede k tomu, že se mozek musí snažit o neustálou kompresi
všech informací. Nejsnadnější komprese je tam, kde se vyskytují různá opakování podobných fragmentů,
různé symetrie nebo závislosti podle nějakého jednoduchého vztahu. Pokud to nestačí, pak je třeba pominout detaily.
Může to být příčinou našich problémů s pochopením vědomí, protože každý model lidského mozku
vytvořený v lidském mozku bude pravděpodobně hodně zjednodušeným přiblížením skutečnosti,
a vždy v něm mohou chybět nějaké podrobnosti, které mohou být podstatné. Stupeň možné komprese
může mít též souvislost s tím, co se nám líbí. Něco, co je sice nové, ale podobné něčemu, co už známe,
nebo obsahuje nějaké symetrie, opakující se fragmenty, rytmy a podobně.

To, že jsme připustili jako hodně pravděpodobné, že každá inteligence na jistém stupni vývoje dojde
k nějaké obdobě slovní konstrukce typu **„jestliže ..., pak ...“**, neznamená, že dojde také ke stejnému chápání
příčinnosti, jak ji chápeme my. Už z toho prostého důvodu, že může úplně jinak chápat čas.
I když pro nás se může ukázat couvání v čase nemožné, není žádný problém stvořit v počítači virtuální svět,
kde couvání v čase bude úplně normální a běžný jev. A jsou ještě další možnosti, které mohou mít vliv
na vznik jiné logiky. Zatím jsme se bavili o číslicových počítačích, protože jsou v dnešní době nejběžnější
a mohlo by se zdát, že se na nich dá modelovat cokoliv (pravděpodobně nedá). O jiných typech počítačů
si povíme v některé z následujících kapitol, nyní si všimneme jen jedné maličkosti.
Náš jazyk je diskrétní (nespojitý), skládá se z jednotlivých slov ze kterých tvoříme logické výroky.
Je možné, že jazyk založený třeba na vůních může mít nějaké vlastnosti, které si neumíme ani představit.
Zdá se nám, že můžeme modelovat úplně všechno, ale můžeme modelovat pouze to, co umíme vymyslet.
A je těžké vymyslet něco úplně nového a odlišného od všeho, co známe.

Nad tím, odkud se vlastně berou nové nápady, se zamyslíme v další kapitole.

## [XI. Odkud se berou nové nápady](rozdzial11) -->
