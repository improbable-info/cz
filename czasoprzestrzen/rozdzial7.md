## VII. Wszechświat jako automat komórkowy

Jeżeli chcemy przedstawić model wszechświata w formie automatu komórkowego,
to trzeba najpierw wyjaśnić, co to jest. Nie będziemy tu wchodzić w szczegóły,
podamy tylko definicję i prosty przykład.

Automat komórkowy jest to obiekt składający się z sieci komórek,
które mogą mieć pewien stan z określonego zbioru, który zmienia się według pewnych reguł
w zależności od stanów sąsiednich komórek. W zależności od rodzaju sieci,
możliwych wartości komórek i wyboru algorytmu mogą istnieć bardzo różne automaty komórkowe.
Najsłynniejszym chyba automatem komórkowym jest "Game of Life" ("gra w życie").
Kwadratowe komórki wypełniają płaszczyznę i mogą przyjmować jeden z dwóch stanów: być żywe albo martwe.
Stan początkowy może być dany albo wybrany losowo i reguły dotyczące zmiany stanu w następnym kroku
są następujące:

- żywa komórka umiera, gdy posiada mniej niż dwóch albo więcej niż trzech żywych sąsiadów,
jeżeli ma dwóch lub trzech żywych sąsiadów pozostaje żywa

- martwa komórka ożywa, jeżeli ma dokładnie trzech żywych sąsiadów

Już tak proste zasady mogą prowadzić do tworzenia bardzo ciekawych struktur,
które mogą na przykład same się reprodukować.

Jak można modelować Wszechświat za pomocą automatu komórkowego?
Na przykład wykorzystać trójwymiarową siatkę komórek,
dla każdej komórki ustawić stan odpowiadający jakieś ilości masy i wartościom różnych sił czy pól,
ustalić zasady jak ma się zmieniać zawartość każdej komórki w zależności od zawartości sąsiadujących komórek
i uruchomić automat. W takim modelu czas płynie zgodnie z naszym wyobrażeniem o czasie,
z tym, że istnieje najmniejszy interwał czasowy - jeden krok w działaniu automatu
- istnieje najmniejsza odległość - rozmiar komórki, istnieje stała szybkość,
z jaką mogą przemieszczać się zmiany w przestrzeni itd.
Widzimy, że taki model ma nie tylko naturalnie płynący czas, ale jednocześnie ma i pewne właściwości kwantowe.
Może to być jedna z możliwych dróg do modelowania Wszechświata...

## [VIII. Parę słów na temat przestrzeni ](rozdzial8)
