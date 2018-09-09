## V. Intelektuální možnosti současných počítačů

Někteří lidé jsou přesvědčeni, že počítače žádnou inteligenci nemají a ani nikdy mít nebudou,
a jsou jiní, kteří tvrdí opak. Nejprve je třeba porozumět, co si každý z nich představuje pod pojmem inteligence,
a pak se zamyslet nad jejich argumentací.

Jak jsme si již dříve ukázali, každá definice je neúplná a nepřesná.
Pod pojmem inteligence si každý může představovat něco jiného.
Jestliže někdo považuje za inteligentní pouze lidi a od umělé inteligence vyžaduje,
aby byla nerozlišitelná od lidské, pak pravděpodobně má pravdu v tom, že počítače takovou inteligenci mít nemohou.
Ale nic umělého nemůže být identické s originálem. Každá napodobenina je jen zjednodušeným modelem
a odpovídá originálu jen na určité rozlišovací úrovni. Chceme-li se bavit o umělé inteligenci,
je třeba přijmout nějakou obecnější definici. Lidská inteligence je složitá, má mnoho složek
a dá se mluvit i o různých druzích inteligence. Ale často mluvíme též i o inteligenci zvířat.
Zvířata považujeme za inteligentní, pokud se rychle učí a jsou schopné řešit složité úkoly,
se kterými se dříve nesetkaly. Takto chápanou inteligenci jsme už schopni modelovat i na současných počítačích
pomocí neuronových sítí. Alespoň stručně si ukážeme, jak neuronové sítě fungují.

Základem je model neuronu, který má libovolný počet vstupů, ale pouze jeden výstup.
Výstup nějakým způsobem závisí na vstupech, přičemž to, jak je který vstup důležitý,
určují takzvané váhy. Čím je váha určitého vstupu větší, tím je tento vstup důležitější.
Učení neuronu je vlastně hledání takových vah, aby neuron dával na výstupu takovou odpověď,
jakou chceme dostat při zadaných vstupech. 

Neurony můžeme vzájemně propojovat a budovat různě složité neuronové sítě, které mají různé vlastnosti.
Odpověď neuronové sítě na konkrétní vstupní signály záleží jednak na vlastnostech neuronů
(kolik mají vstupů, jaké váhy jsou  na jednotlivých vstupech, jaká je závislost výsledného signálu neuronu
na vstupních hodnotách), ale též na množství neuronů a způsobu jejich propojení v síti
(vrstvy, zpětné vazby atd.).

Pokud má síť všechny parametry takové, že splňuje naše požadavky, to znamená,
že na každou přípustnou kombinaci vstupních signálů dává správnou odpověď, nemusíme v ní nic měnit.
Pokud se ani v budoucnosti neočekává  změna  podmínek, ve kterých síť pracuje,
nepotřebujeme žádnou inteligenci ani schopnost se učit. Tak nějak mohou fungovat instinkty.
Jak ale nastavit všechny parametry sítě, aby reagovala tak, jak chceme? Pokud si uvědomíme,
že každý neuron může mít tisíce vstupů, neuronů mohou být tisíce až miliony a různých možností propojení
je ještě mnohem víc, vidíme, že už vybrat vhodný typ sítě není vůbec jednoduché.
A nastavit ručně váhy na vstupech všech neuronů tak, aby síť reagovala tak jak chceme,
je právě nemožné. V praxi obvykle podle problému, který má neuronová síť řešit,
se volí určitý typ neuronové sítě, a pak se využívá její schopnost se učit.
Učení neuronové sítě probíhá tak, že podle nějakého pravidla se mění váhy na vstupech tak,
aby odpověď sítě byla čím dál lepší. A tu je další problém, jak určit tato pravidla.
Je tu ohromné  množství možností a právě na způsobu, jak se nastavují váhy jednotlivých vstupů,
záleží, jak rychle se síť učí a jak může být inteligentní. Nebudeme se zde zabývat podrobnostmi
teorie neuronových sítí, pouze poznamenáme, že jsou užívané různé metody, různě vhodné v různých případech.
Zjednodušeně se dá říct, že pokud je odpověď sítě správná, největší váhy se ještě zvětšují a malé zmenšují,
a pokud je odpověď sítě špatná, největší váhy se zmenšují a malé zvětšují.

I když budeme mít neuronovou síť s odpovídajícím množstvím  neuronů s vhodnými pravidly nastavování vah
a se strukturou vhodnou pro danou oblast problémů, dost velký vliv na výsledek učení může mít i to,
jaké váhy jsou nastaveny na vstupech na začátku. Je těžké určit nějaké obecné zásady,
jaké počáteční hodnoty vybrat, takže často se volí náhodně.
(Je možné, že i u lidí je různé nadání způsobeno pouze různými hodnotami počátečních vah v neuronech).
Ještě větší vliv na výsledek učení sítě mají vstupní údaje, na kterých se síť učí.

Přes všechny tyto potíže je již mnoho užitečných aplikací využívajících neuronové sítě,
například při rozpoznávání obrazu, písma, podpisů nebo při různých analýzách a předpovědích.

Někomu se může zdát, že učení, které spočívá na změně vah vstupních signálů neuronů je moc primitivní
a neodpovídá tomu, jak se učí lidé. Ale z jedné strany vůbec nemáme jistotu, že u lidí
vystupuje něco podstatně jiného, a z druhé strany nám nejde o to, aby umělá inteligence fungovala identicky
jak lidská, ale stačí nám, že se bude chovat inteligentně. A jisté prvky inteligence zde již jsou.
Zvláště že kromě učení s učitelem (kdy zadáváme na vstupy určité vzorové hodnoty,
porovnáváme výstup s očekávaným výsledkem a podle velikosti odchylky jsou váhy měněny tak,
aby se chyba zmenšila) je možné též učení bez učitele, kde není znám výstup
(a tedy ani velikost chyby) a neuronová síť si sama třídí vstupní signály do skupin
a reaguje na typického zástupce, nebo si přizpůsobí topologii vlastnostem vstupu.
A možnosti neuronových sítí jsou patrně mnohem větší, než si myslíme, jem je zatím neumíme plně využít.

Pokud si znovu připomeneme třeba žábu, a její mozek si budeme modelovat pomocí neuronové sítě,
uvědomíme si, že se síť může naučit rozeznávat různé objekty, ale nemá možnost se naučit,
že před velkým objektem má utíkat, protože každé takové setkání, pokud neuteče, pro ni znamená konec existence.
Takové chování může ale vzniknout přirozeným výběrem v určité populaci jedinců.
Takže kromě neuronových sítí bude dobré se zmínit též o evolučních programech
(čili programech, které využívají nějaké prvky evoluce). 

Vzorem pro evoluční programy byly principy vývoje v přírodě. Využíváme zde jistou populaci objektů,
které mají vlastnosti, které nás zajímají, zapsány v nějakém řetězci (analogie chromozomů).
Je definován způsob křížení, čili jak z vlastností rodičů odvozovat vlastnosti potomků,
způsob hodnocení jedince a počet jedinců, kteří přecházejí do další generace.
Kromě toho jsou ještě možné mutace, čili náhodné změny některých vlastností.

U evolučních programů nenajdeme nic, co bychom mohli nazvat inteligencí, ale mohou nalézt řešení i tam,
kde není možné určit algoritmus pro řešení daného problému. Kromě toho, pro nás mají speciální význam,
protože jak jsme si ukázali výše, existují vlastnosti, které se jedinec sám nemůže naučit.
Musí je buď zdědit nebo získat náhodnou mutací (nebo se naučit ve skupině,
co už ale vyžaduje spoustu dalších předpokladů).

Použili jsme zde termín „evoluční programy“ pro všechny programy, které využívají nějaké prvky evoluce
(např. genetické algoritmy). Při aplikaci evolučních metod na samo programování, kde máme populaci programů,
které se množí, kříží a mutují, se používá termín „evoluční (genetické) programování“.
Teoreticky má takové programování ohromné možnosti, mohou vzniknout programy,
které budou řešit zadanou úlohu lépe a rychleji, než programy napsané programátory,
ale složitost evolučních mutací u úloh tohoto typu je pro současné počítače pravděpodobně příliš velká.

Je možné, že rychleji bychom mohli získat zajímavé výsledky aplikací evolučních metod na neuronové sítě.
Viděli jsme výše, že možnost kombinací různých struktur sítě, typů neuronů, nastavení vah a způsobů jejich změn
je ohromná, ale pokud by někdo měl jistou dávku štěstí a pomocí genetických algoritmů nalezl správné parametry,
pak by i na současných počítačích mohl získat neuronové sítě, které by již měly dost velkou inteligenci.
Pro samu inteligenci není potřebná ohromná paměť a rychlost operací.
Naopak, kdybychom měli k dispozici  neomezenou paměť a neomezenou  rychlost operací,
každý problém bychom mohli řešit čistě mechanicky a nepotřebovali bychom k tomu inteligenci.
Jen tak mimochodem - už vůbec žádnou inteligenci by nepotřeboval ten, kdo by všechno věděl,
protože by nemusel řešit žádné problémy ani nic nového se učit. 

Je ještě jedna oblast, o které bychom se zde měli zmínit, a to **buněčné (celulární) automaty**.
Původně byly vytvořeny jako model struktury, která dokáže vytvořit svou vlastní kopii,
ale dá se při jejich použití modelovat právě všechno. Kromě jiného je možné pomocí buněčných automatů
realizovat libovolný klasický program. Při jejich použití se dá též pochopit jak z jedné buňky může vzniknout
složitý organismus nebo některé vlastnosti evoluce, které se jinak zdají nepravděpodobné.

Nejprve si vysvětleme, co to vlastně buněčný automat je. Můžeme si jej představit jako síť nebo mřížku z buněk,
které spolu sousedí. Mohou být uspořádány v řadě, v rovině nebo nějak jinak.
Každá z buněk může být v jednom z několika stavů, přičemž možných stavů může být libovolný počet,
ale v nejjednodušším případě stačí dva. Stav buněk se mění v jednotlivých krocích podle určitých pravidel,
která mají tři základní vlastnosti:

    • pro všechny buňky platí stejná pravidla,
    • výpočty ve všech buňkách probíhají zároveň,
    • nový stav buňky závisí pouze na jejím aktuálním stavu a stavu buněk v jejím bezprostředním okolí.
    
Jedním z nejznámějších buněčných automatů je „Hra života” (Game of Life).
Na dvourozměrné mřížce buňky mohou mít dva stavy – jsou mrtvé nebo živé. Pravidla jsou taková,
že živá buňka zůstane v následujícím kroku živá, pokud má kolem sebe dvě nebo tři živé buňky,
jinak umírá, a mrtvá buňka v následujícím kroku ožívá v případě, že má kolem sebe právě tři živé buňky.
I tak jednoduchá pravidla mohou vést ke složitému chování: mohou například vznikat obrazce,
které periodicky umírají a zase ožívají (blinkers – blikači), které se mohou přemísťovat
(gliders - kluzáky), vypouští kluzáky (guns – střelci) nebo putují a v stopě zanechávají blikače
(star ships – hvězdné lodě).

Příklady buněčných automatů jsou uvedeny v Příloze A.

Chování buněčných automatů závisí na počáteční konfiguraci a můžeme je rozdělit do čtyř skupin.
V nejjednodušším případě vývoj spěje vždy do stavu, ve kterém se již stav buněk nemění.
Může též nastat situace, ve které vývoj spěje k jednoduchým periodickým strukturám,
které se neustále opakují. Někdy může dojít k  chaotickému, náhodně vypadajícímu chování
a konečně nejzajímavější skupina, kde vzniká složité chování.
Při srovnání těchto skupin s programy odpovídá první skupina triviálním programům bez cyklů,
druhá programům, které se triviálně zacyklí, třetí odpovídá generátoru náhodných čísel,
a čtvrtá programům, které dělají něco zajímavého.
