# Task 1
## Subtask 1
10/10
## Subtask 3
<p align="justify"> Cześć nazywam się Magda. Obecnie pracuję poza branżą IT jako asystentka projektanta sieci gazowych wysokiego ciśnienia. Od dłuższego czasu myślę o przebranżowieniu się w kierunku testera (na początku manualnego, w planach automatyzującego), dlatego szukam różnych możliwości kształcenia się w tym kierunku i zdobywania doświadczenia. Wzięłam udział w spotkaniu "Junior QA - najbardziej pożądane umiejętności i rola w zespole developerskim", które prowadziła Patrycja. Dzięki temu spotkaniu dowiedziałam się o portfolio challenge. Bardzo spodobało mi się podejście Patrycji, więc stwierdziłam, że udział w nim będzie strzałem w dziesiątkę - poznanie testowania z praktycznego punktu widzenia:)
<br>W testowaniu podoba mi się to, że jest to praca rozwojowa, wymagająca zaangażowania, ciągłego dokształcania się. Praca testera wymaga tego, żeby cały czas iść na przód i zdobywać nowe cele, a takie podejście jest dla mnie niezwykle motywujące.
<br>Projekt spodobał mi się, właśnie ze względu na praktyczne zadania, dzięki czemu poznam od podszewki pracę testera oraz usystematyzuję wiedzę teoretyczną, którą do tej pory zdobyłam.
<br>Moim celem jest wykonanie terminowo wszystkich zadań, zdobycie doświadczenia, dzięki czemu będę mogła rozpocząć poszukiwania wymarzonej pracy :)
Moje oczekiwania - to przede wszystkim feedback od mentorów, którzy wskażą mi co mogę poprawić / ulepszyć w mojej pracy.
<br>Magda
</p>

## Subtask 4
### 4.1. Na czym polega ta aplikacja? Do czego służy?
<p align="justify">
1. Aplikacja "Scouts Panel" zarządza graczami, meczami i pozwala na tworzenie raportów dla poszczególnych meczów, 
<br>2. Aplikacja pozwala na rejestrowanie graczy, po stworzeniu gracza jest możliwość jego edycji, 
<br>3. Aplikacja pozwala na dodane meczu / meczów oraz raportu / raportów dla konkretnego zawodnika (po stworzeniu meczu / raportu jest możliwość ich edycji),
<br>4. Aplikacja umożliwia przeprowadzenie meczu dla konkretnego zawodnika (na podstawie którego generowany jest raport),
<br>5. Aplikacja umożliwia wyszukiwanie konkretnych zarejestrowanych graczy (wybierając z menu głównego kategorię "GRACZE" użytkownik ma możliwość wyszukania gracza po konkretnych parametrach poprzez kontrolkę wprowadzenia "SEARCH" lub filtrując tabelę po konkretnych parametrach).
<br>6. Aplikacja pozwala na wgląd do ostatnio przeprowadzonych aktywności przez użytkowników w aplikacji tj. dodanie / aktualizacja gracza, dodanie / aktualizacja meczu, dodanie / aktualizacja raportu (na stronie głównej pojemnik "AKTYWNOSĆ").
<br> Reasumując aplikacja "Scouts Panel" pozwala na zarządzanie graczami, meczami, raportami tj. tworzenie graczy, przypisywanie do konretnych graczy meczy i raportów. Aplikacja pozwala użytkownikowi na wgląd do listy zarejestrowanych graczy, dzięki czemu użytkownik może uzyskać informacje na temat gracza w zakresie m.in. pozycji gracza, klubu, w którym gra, ilości rozegranych meczy, ilości raportów przypisanych do danego gracza i recenzji gracza. Użytkownik ma także możliwość wglądu do konkretnych meczy i raportów przypisanych do danego gracza. Aplikacja może być przydatna dla "łowców talentów".
</p>

### 4.2. Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)
<p align="justify">
<br>1. Logowanie / wylogowywanie z systemu,
<br>2. Dodawanie nowego gracza (na stronie głównej w bloku "LINKI POMOCNICZE" zlokalizowany jest znacznik "DODAJ GRACZA", tylko z tego poziomu jest możliwość dodania gracza). Nie ma możliwości dodania gracza wybierając z menu głównego kategorię "GRACZE", z tego poziomu także powinna być możliwość dodania nowego gracza, intuicyjnie to jest pierwsze miejsce, w którym szukałabym możliwości dodania nowego gracza,
<br>3. Możliwość edycji zarejestrowanego gracza (wybierając z menu głównego kategorię "GRACZE", następnie wybierając konkretnego gracza, użytkownik zostaje przekierowany do strony z edycją konkretnego gracza),
<br>4. Dla konkretnego zawodnika jest możliwość dodania meczu (z menu głównego wybieramy kategorię "GRACZE" => wybór konkretnego zawodnika => w menu głównym po lewej stronie pojawia się kategoria "MECZE", w którą należy kliknąć => pojawia się lista wszystkich meczy dla konkretnego zawodnika, a dodanie nowego jest możliwe poprzez kliknięcie w przycisk "+DODAJ MECZ", który znajduje się nad tabelą zestawiającą mecze dla konkretnego zawodnika), tutaj rozwiązanie dodania nowego meczu dla konkretnego zawodnika jest intuicyjne.
<br>Po stworzeniu meczu dla konkretnego zawodnika jest możliwość jego edycji, dodania raportu i rozpoczęcia meczu => w ostaniej kolumnie tabeli "AKCJE" znajdują się 3 ikony, kliknięcie w pierwszą pozwala na edycję danego meczu, kliknięcie w drugą pozwala na dodanie raportu, kliknięcie w trzecią pozwala na rozpoczęcie meczu (po najechaniu kursorem na ikony wyświetlają się opisy akcji, które można wykonać po kliknięciu w daną ikonę, co ułatwia podjęcie właściwych kroków przez użytkownika),
<br>5. Dla konkretnego zawodnika w kategorii "RAPORTY", teoretycznie jest możliwe dodanie nowego raportu => z menu głównego wybieramy przycisk "GRACZE" => wybór konkretnego zawodnika => w menu głównym po lewej stronie pojawia się kategoria "RAPORTY", w którą należy kliknąć => pojawia się lista wszystkich raportów dla konkretnego zawodnika, a dodanie nowego raportu powinno być możliwe poprzez kliknięcie w przycisk "+DODAJ RAPORT", który znajduje się nad tabelą zestawiającą raporty dla konkretnego zawodnika.
<br>Funkcja ta nie działa i po nakliknięciu w przycisk "DODAJ RAPORT" zamiast możliwości dodania raportu następuje przekierowanie do zakładki "MECZE", czyli jest w tym zakresie bug, a jest to pierwsze miejsce, w którym użytkownik będzie szukał możliwości dodania raportu, czyli błąd jest dość poważny.
<br>Dodanie nowego raportu dla konkretnego zawodnika możliwe jest tylko poprzez przejście następującej ścieżki: wybór z menu głównego kategorii "GRACZE" => wybór konkretnego gracza => wybór kategorii "MECZE" => dla konkretnego meczu w kolumnie "AKCJE" kliknięcie w 2-gą ikonkę "DODAJ RAPORT" pozwala nam na dodanie nowego raportu, nie jest to działanie intuicyjne, trzeba kliknąć w kilka przycisków i zagłębić się w strukturę tej aplikacji, żeby znaleźć opcję dodania raportu z tego poziomu (czyli użytkownik musi włożyć dużo wysiłku, żeby znaleźć możliwość dodania raportu).
<br>W menu głównym, wybierając kategorię "GRACZE", następnie wybierając konkretnego gracza, na menu z lewej strony pojawia się kategoria "RAPORTY", klikając w nią wyświetla się zestawienie wszystkich raportów dla konkretnego gracza => mamy możliwość edycji istniejącego raportu (kolumna "AKCJE", kliknięcie w ikonkę długopisa). Edytując konkretny raport przyjęto moim zdaniem fajne rozwiązanie, że każdy punkt, który musimy uzupełnić jest w kilku zdaniach opisany tj. co jest oczekiwanie w zakresie wypełnienia konkretnego punktu.
<br>6. Wybierając kolejno z menu głównego kategorię "GRACZE" => wybór konkretnego gracza => wybór kategorii "MECZE", dla konretnego meczu jest możliwość rozpoczęcia meczu, wybierając z kolumny "AKCJE" trzecią ikonę "ROZPOCZNIJ MECZ". Działania użytkownika po kliknięciu w przycisk "ROZPOCZNIJ MECZ" są działaniami "na oślep". Nie wiadomo jak aplikacja w tym zakresie działa, graficznie przedstawione jest boisko oraz zlokalizowane są ikony na boiskiem. Po najechaniu kursorem na ikony nie wyświetla się komunikat, co spowoduje kliknięcie w każdą z nich, a nie wszystkie z nich są intuicyjne,
<br>7. W menu głównym wybierając kategorię "GRACZE" wyświetla się lista wszystkich graczy => dostępna jest funkcja wygenerowania pliku csv z listą graczy => nad tabelą zestawiającą wszystkich graczy są cztery ikony, klikając w pierwszą ikonę "Download CSV" możemy wygenerować plik csv,
<br>8. W menu głównym wybierając kategorię "GRACZE" wyświetla się lista wszystkich graczy => dostępna jest funkcja wydrukowania pliku pdf z listą graczy => nad tabelą zestawiającą wszystkich graczy są cztery ikony, klikając w drugą ikonę "PRINT" możemy wydrukować plik pdf,
<br>9. W menu głównym wybierając kategorię "GRACZE" wyświetla się lista wszystkich graczy => możliwe jest ukrywanie / odkrywanie wszystkich dostępnych kolumn tj. Imię, Nazwisko, Wiek, Pozycja, Klub, Recenzja, Mecze, Raporty => nad tabelą zestawiającą wszystkich graczy są cztery ikony, klikając w trzecią ikonę "VIEW COLUMNS" możemy ukrywać / odkrywać kolumny,
<br>10. W menu głównym wybierając kategorię "GRACZE" wyświetla się lista wszystkich graczy => mamy możliwość przefiltrowania rekordów po konkretnych wartościach => nad tabelą zestawiającą wszystkich graczy są cztery ikony, klikając w czwartą ikonę "FILTER TABLE" mamy możliwość przefiltrowania rekordów po konkretnych wartościach,
<br>11. Na stronie głównej jest link do kontaktu z Dev Team (przekierowanie do Slacka),
<br>12. Na stronie głównej w bloku "AKTYWNOŚĆ" wyświetlają się ostatnio dokonane aktywności tj. stworzenie / aktualizacja gracza, stworzenie / aktualizacja meczu, stworzenie / aktualizaja raportu => klikając w konkretną aktywność przekierowani zostajemy do edycji gracza / meczu / raportu,
<br>13. Aplikacja umożliwia wyszukiwanie konkretnych zarejestrowanych graczy (wybierając z menu głównego kategorię "GRACZE" użytkownik ma możliwość wyszukania gracza po konkretnych parametrach poprzez kontrolkę wprowadzenia "SEARCH"),
<br>14. Możliwość wyboru języka, w którym aplikacja się wyświeli, do wyboru opcja języka polskiego bądź angielskiego.
</p>
  
### 4.3. Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?
Interfejs aplikacji nie jest intuicyjny, "atrakcyjny", treści zamieszczone w aplikacji i grafika są dosyć ubogie, nie przyciągają wzroku oraz nie zachęcają do ponownego skorzystania. 
W aplikacji praktycznie nie zastosowano obrazów, rysunków, widgetów więc jakość interakcji użytkownika z aplikacją nie będzie wysoka, co czyni ją trudno przyswajalną. Brak jest grafik, ikon, więc aplikacja przez to także traci na pozytywnym odbiorze użytkownika. Aplikacja nie jest funkcjonalna, intuicyjna, jest trudna w użyciu co może spowodować brak chęci użytkowników z jej ponownego korzystania. Wydaje mi się, że dla różnych grup odbiorców taka aplikacja nie będzie atrakcyjna tj. atrakcyjny interfejs graficzny aplikacji w obecnie panujących realiach jest niewzykle istotny, a aplikacja "Scouts Panel" nie "przyciąga wzroku" i dodatkowo jest "trudna w użyciu", więc zarówno grupa odbiorców młodszych jak i starszych nie będzie tej aplikacji postrzegać jako atrakcyjną.

### 4.4. Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).
Przy pierwszym zalogowaniu tak na prawdę nie wiemy jakie funkcjonalności są w aplikacji dostępne, musimy przeklikać wszystkie opcje, żeby dojść do tego jakie funkcjonalności są w aplikacji dostępne. Zatem aplikacja nie pozwala na szybkie i wygodne wykonanie akcji. Doświadczenia użytkownika w kontakcie z tą aplikacją nie są naturalne, intuicyjne i przebrnięcie przez całą apliakcję nie jest "przyjemne", tak więc zasada minimalnego wysiłku przy maksymalnym pożądanym efekcie nie została zachowana. Wysiłek poznawczy nie jest zminimalizowany, użytkownik musi włożyć dużo energii, żeby nauczyć się obsługi i użytkowania aplikacji. Zasada Redukcji Obciążenia Poznawczego nie została w przypadku tej aplikacji zachowana, gdyż korzystanie z interfejsu aplikacji "Scouts Panel"jest pracochłonne a dodatkowo jest trudne i intelektualnie wymagające.

Elementy składowe interfejsu tj. kontrolki wprowadzania nie pozwalają na łatwy przebieg interakcji człowieka z oprogramowaniem np. w menu jest kategoria "GRACZE", po wejściu w tą zakładkę nie ma możliwości dodania nowego gracza co jest nieintuicyjne, także po najechaniu kursorem na istniejącego gracza ciężko stwierdzić czy można edytować jego dane (po najechaniu kursorem na danego gracza kursor nie zamienia się ze strzałki w łapkę). 

Formularz dodawania nowego gracza możliwy jest tylko ze strony głównej i umieszczony jest w bloku "LINKI POMOCNICZE" - opis tego panelu jest nieintuicyjny, wydaje się, że opcja dodania nowego gracza jest jedną z ważniejszych funkcjonalności aplikacji, nawigacja po aplikacji nie jest zatem bezproblemowa (musimy poświęcić stosunkowo dużo czasu i energii, żeby opanować jakie funkcjonalności w aplikacji są dostępne).

W formularzu "DODAJ GRACZA" praktycznie nie dodano list rozwijalnych, co znacznie utrudnia wypełnienie formularza, listy rozwijalne przydatne byłyby w przypadku pola "POZIOM ROZGRYWEK", "GŁÓWNA POZYCJA", "POZYCJA ALTERNATYWNA". 
W formularzu "DODAJ GRACZA" znajdują się pola, w których nie wiadomo co wpisać np. ciężko stwierdzić co należałoby wpisać w polu "ŁĄCZY NAS PIŁKA", "90 MINUT", wypełnienie tego formularza jest nieintuicyjne.

Przechodząc ścieżkę: wybór z menu głównego kategorii "GRACZE" => wybór konkretnego gracza => w menu głównym z lewej strony ekranu pojawia się kategoria "MECZE", w którą klikamy => pojawia się zestawienie wszystkich meczów dla konkretnego gracza i dla każdego meczu mamy możliwość rozpoczęcia meczu - w kolumnie "AKCJE", po kliknięciu w trzecią ikonę "ROZPOCZNIJ MECZ". 

Po kliknięciu w ikonę "ROZPOCZNIJ MECZ" całkowicie nie wiadomo jakie akcje są możliwe do wykonania w aplikacji. Przydatna byłaby instrukcja obsługi aplikacji w tym zakresie, bo nie wiadomo jak obsłużyć tutaj działania. Mamy grafikę boiska oraz przyciski nad boiskiem - po najechaniu kursorem na przyciski, nie pojawia się żaden komunikat z opisem co będzie się działo po kliknięciu w konkretną ikonę, można się tylko domyślić i metodą prób i błędów sprawdzić co się stanie po kliknięciu / kliknięciach w konkretną ikonę, więc tak na prawdę w tym zakresie działamy na "oślep". 

Interfejs aplikacji "Scouts panel" nie jest prosty w odbiorze, nie pozwala na szybkie i sprawne posługiwanie się produktem. Interfejs nie wspiera działąń użytkownika, nie zawsze informuje o błędach, nie tłumaczy co aktualnie użytkownik robi (zwłaszcza w zakresie opcji "ROZPOCZNIJ MECZ" dla konkretnego gracza).

### 4.5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)
Aplikacja uruchomiona na najbardziej popularnych przeglądarkach Google Chrome, Firefox, Opera, Edge, na wszystkich działa.
Aplikacja uruchomiona w trybie responsywnym na urządzeniu mobilnym np. iPhone SE 375x667 ładuje się bardzo długo (wydajność na poziomie 66%), po kliknięciu we wszystkie kategorie, nie wszystkie zakładki dostosowują się do ekranu np. kategoria "GRACZE" wyświetla się w na urządzeniu mobilnym w sposób czytelny tj. kolumny dla każdego zawodnika zostały rozłożone w pionie, więc użytkownik musi przewijać tylko w dół, żeby zobaczyć wszystkie informacje dla konkretnego gracza, co jest wygodne, natomiast kategorie "MECZE" i "RAPORTY" dla konkretnego gracza nie dostosowują się do ekranu. Żeby zobaczyć wszystkie informacje użytkownik musi nawigować się w prawo / lewo, co utrudnia działanie użytkownika, powinno zostać zastosowane takie samo rozwiązanie jak w przypadku kategorii "GRACZE" tj. rozmieszczenie wszystkich informacji w orientacji pionowej. 
Dodanie nowego raportu przechodząc ścieżkę: z menu głównego wybór kategorii "GRACZE" => wybór konkretnego gracza => w menu głównym pojawia się kategoria "MECZE" => dla konkretnego meczu przewijając w prawo do kolumny "AKCJE", mamy trzy ikony, nie wiemy co spowoduje kliknięcie danej ikony na urządzeniu mobilnym (ikony nie są w żaden sposób opisane, musimy kliknąć w każdą ikonę, żeby stwierdzić jakie akcje można wykonać poprzez kliknięcie w każdą z ikon), natomiast kliknięcie w drugą ikonę pozwala na wygenerowanie nowego raportu. Na urządzeniu mobilnym uzupełnienie raportu będzie trudne, ze względu na fakt, iż strona nie dostosowuje się do ekranu, użytkownik musi nawigować się na ekranie w prawo / lewo co utrudnia działanie użytkownika i łatwo będzie pominąć, któreś z pól.

Lista wychwyconych błędów weryfikacja na przeglądarce Google Chrome:
- strona główna, panel logowania - przy braku podania loginu i braku hasła oraz zaznaczonej opcji języka polskiego pojawia się komunikat walidacyjny w języku angielskim,
- strona główna, przy logowaniu mamy dwa pola do wypełnienia Login i Hasło, komunikat walidacyjny w przypadku braku podania loginu lub błędnego podania loginu wyświetla się pod polem z hasłem, co jest nieczytelne / mylące, nie ma rozbicia na osobne komunikaty walidacyjne pod polem login i pod polem hasło;
- w przypadku kliknięcia przycisku "Przypomnij hasło" przekierowanie na stronę, na której należy podać hasło e'mail, przy braku podania adresu e'mail i kliknięciu w przycisk "WYŚLIJ/SEND" pojawia się komunikat "Wysłano wiadomość na podany adres e'mail" (błąd 400), nie pojawia się komunikat walidacyjny,
- w przypadku kliknięcia przycisk "Przypomnij hasło" przekierowanie na stronę, na której należy podać hasło e'mail, w przypadku kliknięcia przycisk "Przypomnij hasło" przy podaniu adresu e'mail w złym formacie i kliknięciu w przycisk "WYŚLIJ/SEND" pojawia się komunikat "Wysłano wiadomość na podany adres e'mail" (błąd 400), nie pojawia się komunikat walidacyjny,
- strona "Przypomnij hasło" - jeżeli naciśnięty zostanie przycisk "WYŚLIJ/SEND" to zarówno przy poprawnym jak i niepoprawnym podaniu adresu e'mail przycisk się blokuje i nie ma możliwości ponownego wysłania adresu e'mail, trzeba się cofnąć do strony głównej ponownie kliknąć w przycisk "Przypomnij hasło", po czym następuję przekierowanie do strony z przypomnieniem hasła, wówczas przycisk "WYŚLIJ/SEND" jest aktywny,

- przycisk "DODAJ GRACZA" na stronie głównej przekierowuje do strony, na której można dodać nowego zawodnika:

1. Nie wpisując żadnych danych i wciskając przycisk "SUBMIT" (opis przycisku w języku angielskim mimo zaznaczenia opcji języka polskiego) sposób wyświetlania się komunikatów walidacyjnych o potrzebie wypełnienia pól obowiązkowych nie jest intuicyjny - powinny zostać zaznaczone na czerwono wszystkie pola wymagane + dodany komunikat walidacyjny do każdego wymaganego pola, co zwiększyłoby czytelność wymaganych pól, a pojawia się jedynie dymek z komunikatem "WYPEŁNIJ POLE" przy pierwszym polu wymaganym "IMIĘ", który po kilku sekundach znika i tylko przy wyjściu z wymaganego pola pojawia się komunikat walidacyjny w kolorze czerwonym, iż pole jest wymagane (zaznaczona opcja języka polskiego, a komunikat walidacyjny jest w języku angielskim "REQUIRED"). W polu "IMIĘ" można wpisać błędne dane tj. można wpisać liczby. Żeby zatwierdzić wprowadzone dane musimy po wpisaniu wartości nacisnąć przycisk ENTER, jeżeli tego nie zrobimy nie zatwierdza nam wprowadzonej wartości. Po wciśnięciu przycisku ENTER i zatwierdzeniu wartości wprowadzonej w polu "IMIĘ", pojawia się dymek z komunikatem "WYPEŁNIJ POLE" przy drugim polu wymaganym "NAZWISKO", który po kilku sekundach znika i tylko przy wyjściu z wymaganego pola pojawia się komunikat walidacyjny w kolorze czerwonym, iż pole jest wymagane. W polu "NAZWISKO" można wpisać błędne dane tj. można wpisać liczby. Żeby zatwierdzić wprowadzone dane musimy po wpisaniu wartości nacisnąć przycisk ENTER, jeżeli tego nie zrobimy nie zatwierdza nam wprowadzonej wartości. Po wciśnięciu przycisku ENTER i zatwierdzeniu wartości wprowadzonej w polu "NAZWISKO", pojawia się dymek z komunikatem "WYPEŁNIJ POLE" przy trzecim polu wymaganym "DATA URODZENIA", który po kilku sekundach znika i tylko przy wyjściu z wymaganego pola pojawia się komunikat walidacyjny w kolorze czerwonym, iż pole jest wymagane. Wartość w polu "DATA URODZENIA" może być wprowadzona ręcznie, lub możemy wybrać datę z kalendarza (tutaj pojawia się błąd w zakresie możliwych dat do zatwierdzenia tj. można wybrać datę z przyszłości lub datę z dalekiej przeszłości, czyli możliwy jest wybór daty niemożliwej). Wpisując ręcznie datę niepoprawną np. 11.11.1111111 pojawia się pop-up u góry ekranu z informacją, że "NIE UDAŁO SIĘ DODAĆ GRACZA" (kod 500), ale przy polu "DATA URODZENIA" nie pojawił się komunikat walidacyjny, a ułatwiłoby to użytkownikowi stwierdzenie gdzie wprowadził błędne dane. Wpisując w polu "DATA URODZENIA" ręcznie dane, w kalendarzu data przeskakuje na datę wpisaną przez użytkownika z ręki, co utrudnia powrót do właściwego przedziału dat, jeżeli użytkownik wpisał datę niepoprawną.
Żeby zatwierdzić wprowadzone dane musimy po wpisaniu wartości nacisnąć przycisk ENTER, jeżeli tego nie zrobimy nie zatwierdza nam wprowadzonej wartości. Po wciśnięciu przycisku ENTER i zatwierdzeniu wartości wprowadzonej w polu "DATA URODZENIA", pojawia się dymek z komunikatem "WYPEŁNIJ POLE" przy czwartym polu wymaganym "GŁÓWNA POZYCJA", w polu tym korzystne byłoby zastosowanie listy rozwijalnej z możliwymi opcjami wyboru, a możliwe jest jedynie wpisanie wartości ręcznie (możliwe jest podanie wartości liczbowej, czyli podanie wartości nieprawidłowych). Żeby zatwierdzić wprowadzone dane musimy po wpisaniu wartości nacisnąć przycisk ENTER, jeżeli tego nie zrobimy nie zatwierdza nam wprowadzonej wartości. Gwiazdka przy polach wymaganych nie jest w żaden sposób opisana, na dole formularza powinna być adnotacja, że pole oznaczone gwiazdką jest wymagane. 

Odnośnie pozostałych nie wymaganych pól w formularzu z edycją / dodaniem gracza:
- pole "E-MAIL" - po podaniu nieprawidłowych danych i kliknięciu w przycisk "SUBMIT" nie pojawia się komunikat walidacyjny, że wprowadzone dane są nieprawidłowe. Po wpisaniu w polu e'mail np. wartości "0" i wciśnięciu przycisku "SUBMIT" wyskakuje pop-up z informacją "NIE UDAŁO SIĘ ZAKTUALIZOWAĆ GRACZA" (kod 400), po kilku sekundach pop-up znika, korzystniejszy byłby komunikat walidacyjny wyświetlający się bezpośrednio pod polem "E-MAIL" o nieprawidłowym formacie wprowadzonych danych,
- pole "TELEFON" - można wprowadzić nieprawidłowe dane, które są akceptowane przez system, powinny być akceptowane jedynie wartości liczbowe, a system akceptuje także podanie wartości znakowych np. po wpisaniu w polu "TELEFON" wartości "p", następnie zatwierdzeniu Enterem pojawia się pop-up z komunikatem "Zapisano gracza" (kod 200),
- pole "WAGA" - jest możliwość wpisania litery "e" z klawiatury, powinna być całkowicie zablokowana opcja wpisywania liter, innych liter nie można wpisać. Po próbie zatwierdzenia wagi z wpisaną literą "e" wyskakuje dymek przy polu "WAGA" z komunikatem "Wprowadź liczbę". System akceptuje w polu "WAGA" jedynie wartości liczbowe, ale przyjmuje wartości liczbowe ujemne (kod 200) co jest defektem. Przy wpisywaniu liczb zmiennoprzecinkowych pojawia się komunikat walidacyjny, z którego wynika, że akceptowane są tylko liczby wartości integer, ale można wprowadzić niewiarygodne dane w zakresie wagi np. wartość 2 (kod 200), aplikacja akceptuje taką wagę gracza, powinny być akceptowane wartości z możliwego do zachowania zakresu wagi,
- pole "WZROST" - jest możliwość wpisania litery "e" z klawiatury, powinna być całkowicie zablokowana opcja wpisywania liter, innych liter nie można wpisać. Po próbie zatwierdzenia wzrostu z wpisaną literą "e" wyskakuje dymek przy polu "WZROST" z komunikatem "Wprowadź liczbę". System akceptuje w polu "WZROST" jedynie wartości liczbowe, ale można wpisać wartości ujemne, które są akceptowane (kod 200) co jest defektem. Przy wpisywaniu liczb zmiennoprzecinkowych pojawia się komunikat walidacyjny, z którego wynika, że akceptowane są tylko liczby wartości integer, ale można wprowadzić niewiarygodne dane w zakresie wzrostu np. wartość 1 (kod 200), aplikacja akceptuje taki wzrost gracza, a powinny być akceptowane wartości z możliwego do zachowania zakresu wzrostu,
- pole "KLUB" - brak rozwijalnej listy z możliwością wyboru pozycji, trzeba wpisać wartość ręcznie. Akceptowane są nieprawidłowe dane tj. wartości liczbowe np. wpisując wartość "1" system akceptuje tą wartość (kod 200),
- pole "POZIOM ROZGRYWEK" - brak rozwijalnej listy z możliwością wyboru pozycji, trzeba wpisać wartość ręcznie,
- pole "POZYCJA ALTERNATYWNA" - brak rozwijalnej listy z możliwością wyboru pozycji, trzeba wpisać wartość ręcznie. Akceptowane są nieprawidłowe dane tj. wartości liczbowe np. wpisując wartość "1" system akceptuje tą wartość (kod 200),
- pole "OSIĄGNIĘCIA" - nieintuicyjne pole, nie wiadomo co powinno się w tym polu podać, jeżeli powinien być to krótki opis, pole do wypełnienia powinno mieć inną formę - większego prostokąta z podaną max liczbą znaków,
- przycisk "DODAJ JĘZYK" - brak rozwijalnej listy z możliwością wyboru języka, trzeba wpisać wartość ręcznie. Akceptowane jest niepoprawny format danych tj. wartości liczbowe np. zakceptowana jest wartość "9" (kod 200), powinny być akceptowane jedynie wartości znakowe,
- pole "ŁĄCZY NAS PIŁKA" - zupełnie nie wiadomo co należałoby w tym polu wpisać,
- pole "90 MINUT" - zupełnie nie wiadomo co należałoby w tym polu wpisać,
- pole "PROFIL FACEBOOK" - intuicyjnie powinien podany być tutaj link do naszego profilu na Facebooku => klikając w niego powinniśmy zostać przekierowani na podany adres, jednak w aplikacji po podaniu adresu nie generuje się link,
- przycisk "DODAJ LINK Z YOUTUBE" - akceptowany jest niepoprawny format danych (np. wprowadzona wartość "98" jest akceptowana). Wpisując poprawny adres strony nie generuje się link, adres trzeba skopiować i wprowadzić do przeglądarki, nie ma możliwości bezpośrednio kliknięcia w link i przekierowania na wskazaną stronę

Po naciśnięciu przycisku "SUBMIT" zostajemy przekierowani na stronę edycji gracza, po kliknięciu w przycisk "CLEAR" (mimo zaznaczonej opcji języka polskiego, napis wyświetla się w języku angielskim) powinny zostać wyczyszczone wszystkie dane gracza, a usuwane są tylko dane z pól nieobowiązkowych, wartości podane w polach obowiązkowych zmienione mogą zostać tylko poprzez ręczne wejście w poszczególne pola.

- MENU GŁÓWNE => KATEGORIA GRACZE
1. Będąc na stronie z listą wszystkich graczy w górnym panelu jest opcja wyszukiwania danych, niestety nie jest wiadomo, po której kolumnie dane będą wyszukiwane, trzeba ręcznie wpisywać wartości, żeby sprawdzić po których kolumnach wartości są wyszukiwane. Wyszukiwanie nie działa dla kolumny WIEK, RECENZJA, MECZE, RAPORTY.
Mając zaznaczoną opcję języka polskiego napis przy lupce jest w języku angielskim "SEARCH" a powinno być "SZUKAJ".
2. Mając zaznaczoną opcję języka polskiego opis ikon w prawym, górnym rogu okna po najechaniu na nie kursorem (ściągnięcie pliku csv, wydruk, widok, filtrowanie tabeli) jest w języku angielskim.
3. Opcja filtrowania tabeli - wpisanie w dowolnym polu zadanej przez nas wartości, powoduje wyszukanie podanych wg naszych kryteriów rekordów. 
Chcąc wrócić do pełnej listy graczy musimy w polu, w którym wprowadziliśmy wartość usunąć wprowadzone dane i wcisnąć ENTER, wówczas pojawia się pełna lista graczy. Przycisk RESET znajdujący w oknie filtrowania, usuwa jedynie wprowadzoną przez nas ręcznie wartość, ale nie przywraca widoku pełnej listy graczy, co powinno intuicyjnie nastąpić.

- MENU GŁÓWNE => KATEGORIA GRACZE => WYBÓR KONKRETNEGO GRACZA => KATEGORIA MECZE Z MENU GŁÓWNEGO => KOLUMNA AKCJE, PIERWSZA IKONA "EDYCJA MECZU":
1. Przycisk "CLEAR" nie powoduje wyczyszczenia danych, żeby zmienić dane musimy ręcznie wklikiwać się w każde pole, 
2. Przy polach obowiązkowych z gwiazdką (brak wyjaśnienia, że pola z gwiazdką są obowiązkowe) komunikaty walidacyjne mimo zaznaczonej opcji języka polskiego wyświetlają się w języku angielskim,
3. W polu "DRUŻYNA ZAWODNIKA" powinna być lista rozwijalna,
4. W polu "DRUŻYNA PRZECIWNIKA" powinna być lista rozwijalna,
5. W polu "ZDOBYTE GOLE" jest możliwość wpisania litery "e" z klawiatury, powinna być całkowicie zablokowana opcja wpisywania liter, innych liter nie można wpisać. Po próbie zatwierdzenia pola "ZDOBYTE GOLE" z wpisaną literą "e" wyskakuje dymek przy polu "ZDOBYTE GOLE" z komunikatem "Wprowadź liczbę",
6. W polu "STRACONE GOLE" jest możliwość wpisania litery "e" z klawiatury, powinna być całkowicie zablokowana opcja wpisywania liter, innych liter nie można wpisać. Po próbie zatwierdzenia pola "STRACONE GOLE" z wpisaną literą "e" wyskakuje dymek przy polu "STRACONE GOLE" z komunikatem "Wprowadź liczbę",
7. Wartość w polu "DATA" może być wprowadzona ręcznie, lub możemy wybrać datę z kalendarza (tutaj pojawia się błąd w zakresie możliwych dat do zatwierdzenia tj. można wybrać datę z przyszłości lub datę z dalekiej przeszłości, czyli możliwy jest wybór daty niemożliwej). Wpisując ręcznie datę niepoprawną np. 11.11.1111111 pojawia się pop-up u góry ekranu z informacją, że "NIE UDAŁO SIĘ ZAKTUALIZOWAĆ MECZU" (kod 500), ale przy polu "DATA" nie pojawił się komunikat walidacyjny, a ułatwiłoby to użytkownikowi stwierdzenie gdzie wprowadził błędne dane. Wpisując w polu "DATA" ręcznie dane, w kalendarzu data przeskakuje na datę wpisaną przez użytkownika z ręki, co utrudnia powrót do właściwego przedziału dat, jeżeli użytkownik wpisał datę niepoprawną,
8. W polu "KOLOR KOSZULKI" powinna być lista rozwijalna, powinna być możliwość wprowadzania tylko wartości znakowych, a można wprowadzać liczby,
9. W polu "LIGA" powinna być lista rozwijalna,
10. W polu "CZAS GRY" jest możliwość wpisania litery "e" z klawiatury, powinna być całkowicie zablokowana opcja wpisywania liter, innych liter nie można wpisać. Po próbie zatwierdzenia pola "CZAS GRY" z wpisaną literą "e" wyskakuje dymek przy polu "CZAS GRY" z komunikatem "Wprowadź liczbę". W polu można wpisać liczby ujemne oraz zero - defekt,
11. W polu "NUMER" jest możliwość wpisania litery "e" z klawiatury, powinna być całkowicie zablokowana opcja wpisywania liter, innych liter nie można wpisać. Po próbie zatwierdzenia pola "NUMER" z wpisaną literą "e" wyskakuje dymek przy polu "NUMER" z komunikatem "Wprowadź liczbę". W polu można wpisać liczby ujemne oraz zero - defekt,
12. Pole "WEB MATCH" i "GENERAL" pomimo zaznaczonej opcji języka polskiego opisane są w języku angielskim, dodatkowo nie wiadomo czego dotyczą i czego oczekuje się do wpisania przez użytkownika w ramach tych pól,
13. Pole "RECENZJA" akceptuje jedną literę "e", ale jej nie akceptuje, po kliknięciu w przycisk "SUBMIT" wyskakuje dymek przy polu "RECENZJA" z komunikatem "Wprowadź liczbę". Z listy rozwijalnej można wartości liczbowe, ale nie wiadomo czego to pole dotyczy.

- MENU GŁÓWNE => KATEGORIA GRACZE => WYBÓR KONKRETNEGO GRACZA => KATEGORIA MECZE Z MENU GŁÓWNEGO => KOLUMNA AKCJE, DRUGA IKONA "DODAJ RAPORT":
1. Kliknięcie w ikonę "DODAJ RAPORT" przekierowuje użytkownika do strony tworzenia raportu, na której podane jest "ID GRACZA" i "ID MECZU", w tym oknie przycisk "CLEAR" nie działa, jedynie przycisk "SUBMIT" działa, po kliknięciu w niego użytkownik zostaje przekierowany do strony stworzonego raportu meczowego,
2. W oknie ze stworzonym raportem, dla wszystkich punktów, które należy uzupełnić tj. "WSTĘP", "I. INTELIGENCJA BOISKOWA", "II. MENTALNOŚĆ", "III. PODSUMOWANIE", "IV. RECENZJA" można podjąć działania w zakresie stylizacji tekstu - są ikony, zlokalizowane pod opisami informacyjnymi dla każdego z punktów. Po najechaniu kursorem na poszczególne ikony opisy wyświetlają się w języku angielskim mimo zaznaczonej opcji języka polskiego. Block-quote nie działa. W polu "RECENZJA" mamy opis przyznawanych punktów - w opisie mamy punkty od 1 do 5 w zakresie liczb całkowitych, natomiast zaznaczając gwiazdki możemy dać połówki punktów, nie ma spójności między opisem przydzielanych punktów, a możliwością zaznaczania z ręki liczby punktów,
3. W dolnej stopce zamieszczony jest link do strony www.futbolkolektyw.pl, po klinknięciu w link następuję przekierowanie do nieistniejącej strony "404 Not Found",
  </p>
