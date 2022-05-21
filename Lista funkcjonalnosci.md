# Lista funkcjonalności

## Sposób pracy nad analizą finansową

Przygotowująć rozwiązanie mAnalyser wyodrębniliśmy trzy etapy pracy z danymi, każdy ze swoimi własnymi wyzwaniami i potrzebami. 

Pierwszym etapem jest harmonizacja danych, obecnie najważniejszy filar aplikacji. Proces ten pozwala zintegrować dane z wielu źródeł, z formy nieczytelnej i nie poddające się analizie w jedną, ustrukturyzowaną bazę danych. 

Drugim etapem jest przygotowanie zasobu informacyjnego do analizy poprzez usunięcie wszystkich błędów jakie mogły się pojawić oraz oznaczenia danych na podstawie dostępnej dla analityka wiedzy spoza sprawy. 

  
![](https://lh4.googleusercontent.com/tdmXuzWVW3ILKS4yh5z1pKRdvAytLPOybyVngHNAbrSqttZY2nM01XBrEXJgqhKQ0rZzYInmOH1Jqn3ObaB2O42nQ9U-4S69gxs85Wt4Xuce4pVBuRQoPVv9rBWlOv2reIwrQ6_o6-LrzCduIw)

Trzecim, finalnym punktem jest analiza. Przygotowaliśmy szereg narzędzi do potwierdzania hipotez przez użytkownika i wygodny przegląd danych. Gotowe raporty szybko wizualizują najważniejsze informacje, wygodne filtry pozwalają na oglądanie danych z wielu różnych perspektyw. Raporty można wyzwalać z każdego miejsca aplikacji co pozwala na swobodną eksplorację danych. 

Przeanalizowane dane można na koniec, na potrzeby przygotowania raportu z analizy, wyeksportować z aplikacji. 


## Harmonizacja danych

Instytucje finansowe w Polsce nie posiadają ustandaryzowanego formatu danych i przekazują je w wielu różnych formatach, bardzo często nie przystosowanych do natychmiastowej analizy dostępnymi narzędziami analitycznymi.

Najczęstsze problemy, z którymi spotykają się analitycy to:

-   Dane przekazywane są w bardzo różnych formatach (20 głównych banków, czasami jeden bank używa kilku różnych formatów).
-   Zbiory danych zawierają dużo transakcji – brak łatwego mechanizmu odkrywania transakcji podejrzanych / nierzetelnych.
-   Różnie opisane tożsamości – brak ustandaryzowanego formatu opisu np. osób, firm.
-   Nieuporządkowany tekst w opisach przelewów – trudny do wyodrębnienia.

Analizując dane finansowe analitycy bardzo często napotykają problemy związane z dużą ilością danych, które nie posiadają ustandaryzowanego formatu. 

Przeważnie analityk spędza wiele dni nad często bardzo pracochłonnym dostosowaniem struktury danych finansowych do formatu umożliwiającego ich dalszą analizę.![](https://lh3.googleusercontent.com/a9w8Hednmd_WPmY5E6mjzIjmTEHCbt2XNUUJnaB1sG2Vd-QROWjNSE-VobOGVy_fzk2ZUVgDj8mahF4uY-ltXfLOJ8Fc30OLaYZcB27YFNRIX8kS8geVmZZacIYRXQZslfpvQSM1Ytvn6BL7Fg)
Rozwiązanie mAnalyzer firmy Matic SA pozwala na szybką standaryzację różnych typów danych finansowych oraz ich analizę i wizualizację.

### Dodawanie plików

System mAnalyser znacznie przyspiesza i upraszcza proces importowania plików do aplikacji. Dzięki zautomatyzowanym importerom użytkownik może dodać do systemu wiele plików na raz, przygotowywać je masowo do dodania do bazy danych. 

  

Dodatkowo aplikacja potrafi interpretować nagłówki wyciągów bankowych oraz nazwy plików, co dodatkowo ułatwia pracę. 

  

Lista funkcjonalności: 

-   Wczytanie wielu plików na raz - metodą drag&drop. Jednocześnie można wysłać wiele plików, niezależnie czy ich format jest taki sam. 
    
-   Możliwość zaimportowania wielu plików na raz bez konieczności ręcznego przechodzenia przez kroki importu - import masowy (plan)
    
-   Wczytywanie danych z preambuł plików oraz możliwość kopiuj/wklej w celu przypisania plików do konkretnej tożsamości
    

### Typy importowanych plików

Aplikacja ma wbudowane algorytmy do automatycznego importowania ponad 80 formatów wykazów transakcji finansowych pochodzących z różnych banków oraz algorytmy do importu z możliwością konfiguracji szablonów importu.

  

W przypadku importu automatycznego system samodzielnie dobiera odpowiedni importer do przetwarzanego wykazu transakcji.![](https://lh3.googleusercontent.com/a9w8Hednmd_WPmY5E6mjzIjmTEHCbt2XNUUJnaB1sG2Vd-QROWjNSE-VobOGVy_fzk2ZUVgDj8mahF4uY-ltXfLOJ8Fc30OLaYZcB27YFNRIX8kS8geVmZZacIYRXQZslfpvQSM1Ytvn6BL7Fg)

#### Import faktur

Aplikacja potrafi importować zestawienia faktur dla dowolnego kraju Unii Europejskiej, uwzględniając różne typy danych oraz różne stawki VAT. 

#### Import tożsamości

Aplikacja potrafi importować zestawienia osób. 

#### Import rach. bankowych 

Aplikacja potrafi importować wszystkie formaty plików (TXT/CSV/XLSX) historii rachunków bankowych. 

Lista importerów automatycznych dostępnych aktualnie w systemie przedstawiona została poniżej. Lista jest na bieżąco aktualizowana. Importery automatyczne potrafią radzić sobie z unikatowymi plikami przygotowywanymi jako zestawienia z banków. 

Ponadto istnieje możliwość importu (CSV, XLSX) dowolnych historii rachunków bankowych niezależnie od ich pochodzenia. 

![](https://lh4.googleusercontent.com/5l11Kp6xWWB5X5W_qvLe6PD0rHbugT2PZu27YmZ9ibVUad9MhkFOBwOMNkNlEdgzjQBBwL6ahTCz_rNez8qlTgljSqs9pBCp1Kqu5MmQJ16dzFkLcqRsmQfNI2CyYWlVPgpf7K-uAfOn3uGEeg)


Istnieje również możliwość importu ręcznego niezdefiniowanych formatów tabelarycznych – z możliwością wyboru i dopasowania kolumn.

#### Pełna lista rozszerzonych formatów (plan)

Pełna lista obsługiwanych typów danych w mAnalyser: 

GIIF/STIR, KRS, Księgi Wieczyste, Transakcje Western Union, Paypall, Moneygram, Kantory, Bilans Firmy, RZiS, Kąta księgowe, Wykaz nieruchomości i ruchomości, Kryptowaluty. 

Pojęcie Obsługiwane typy danych - system będzie posiadać strukturę umożliwiającą import z serializowanych plików oraz ich analizę. 

#### Szablony importu. (plan)

Proces importu jest powtarzalną czynnością i często przebiega dla plików o takiej samej strukturze (np. pliki zawierają te same kolumny, definiują ten sam format daty czy kierunek transakcji). Funkcjonalność szablonów umożliwia zapamiętanie przez system mapowania konkretnego przypadku w celu późniejszego przyśpieszenia pracy i pozbycia się z procesu importu powtarzalnych czynności. 

![](https://lh5.googleusercontent.com/Mw7EJMK52KOY4pxtcVgilkXaysHccY2ZPYqeHRujc_6BfR1pnIA7lYVRZtpyf0vrJQ143cfpcA2tZDM2PDEIPKOya9E_2iRLlKvmeFFAghBa-QCNPXHeG83JHhpmJFw4WHMpHL1J1-eOepUaOw)

### Grafowa baza danych![](https://lh3.googleusercontent.com/wnLaFujKVC4-FY2mquft4vocZlckx5hL2bylCLEeRxGm3pTsMBIR8QVeTC3RuiZiO_Vi0TVrIaJHn1xxlCdsPILBWgemIZ8tJZVYR7TyIgsg48FX7iNmRFzpC23IsMQp-Q5Ozk28EMqKPFbcBw)

W sercu silnika aplikacji umieściliśmy grafową bazę danych. Pozwala to analitykowi na zupełnie nowe podejście do interpretacji danych, ułatwia ich zrozumienie i szybką analizę stawianych hipotez. 

Biblioteka grafowa to też szereg przygotowanych dla użytkowników funkcji grafowych takich jak grupowanie społeczności, śledzenie przepływów itp. 

  
  

![](https://lh6.googleusercontent.com/Skm3WRZLZBIYBEBnQUkFg-LbpfJ89TwMp695ny7P8p5QZi3wS1UaF3VnJPumTT09-oFtTzIlBBz2RhtUQ97uBqjxGDCvoU7QA0tm3SHPAJzHemWzFc4eV1MOVEdL1Sw6dqFD3dqRmcMZNy2sYg)

### Zarządzanie słownikami 

Zdefiniowanych jest 7 podstawowych podtypów (jak np. gotówka, karta płatność, itp.). Każdy z podtypów zawiera słownik słów kluczowych, po których dopasowywane są nazwy typów transakcji występujących w różnych bankach. Słownik ten można samodzielnie rozbudowywać.

## Czyszczenie danych / usuwanie błędów

Ważnym etapem analizy finansowej jest poprawa błędów w danych. Zdarza się, że dane zawierają błędy, nieścisłości lub niepełne informacje. 

System mAnalyser posiada wbudowany mechanizm wykrywania duplikatów wszystkich zdarzeń i obiektów. Użytkownik decyduje co zrobić z wykrytymi potencjalnymi duplikatami – scalić, czy pozostawić nie scalone. Dodatkowo można suwakiem dostosować prawdopodobieństwo wystąpienia duplikatu. 

Aplikacja potrafi wyszukiwać duplikaty transakcji, faktur, tożsamości (osób, firm) czy rachunków bankowych. 

![](https://lh4.googleusercontent.com/JNVM9cb2zzcdHwVyLTqdLAb6HOomflYzPv1uO_VbkygSJ3c7IFxcFA9LHdO8m-LJqTvpwpWpMJ132Vz9jybvX66Fdd1L9j88b1ftzate0SF_wUAnjBcBIEiehiG8eMJi7eX2y-U2ntu132edOQ)

  

Dodatkowo możliwa jest masowa edycja dowolnych obiektów, zmiany połączeń pomiędzy obiektami i zdarzeniami, łączenie ze sobą danych. Aplikacja pozwala na dowolne zmiany w danych, takie jak np: 

1.  Zmiana właściciela rachunku bankowego
2.  Zmiana typów transakcji
3.  Zmiana stawek VAT faktur
4.  Edycja dowolnego pola tekstowego, np. nazwiska
5.  Zmiana waluty transakcji lub faktur

Do aplikacji można dodać dowolne dostępne typy danych oraz stworzyć między nimi połączenia, czyli np. dodać rachunki bankowe, następnie zmienić transakcje z jednego rachunku bankowego do nowego i dodać współwłaściciela rachunku. 

![](https://lh3.googleusercontent.com/EowM18XNoKBTy_PnCv5ZCq38ogYMJrGOWcGIX1ExzmmmTznmS3zNOLmo7twyo79ASyfSC6SuSZBnd3lH5KkbY6-RifijqH2uMG5Wc8LPxfzmvMt2D7HWZEnGLnmc7k1BDfgLXnRn2RU5DLpfHg)


Osobnym tematem jest zarządzanie walutami w sprawach analitycznych. Aplikacja pozwala na import dowolnych walut i ich analizę, ale w celu porównywania między sobą transakcji, faktur itp. potrzebny jest mechanizm sprowadzający każde wystąpienie pieniądza do jednolitej waluty. (plan)
  

![](https://lh3.googleusercontent.com/1avfJAjeeO-ZaRHuBVuYqUXht4AmMqheUAF_BSFMNKfbghdxYFpnWfYauCookRRQqw_xyrCMJKTPSkmxLe1xbd0jv9qA-uUB1Uek9JFq22ADEGTLSe_D1Sfw5c4ZNojAQX_PNktGMyjJoa7Ejg)

  

## Oznaczanie danych (zrozumienie danych) (plan)

Sam import danych jest jednak często niewystarczający; posiadanie tylko strzępów informacji utrudnia prowadzenie analizy. Wychodząc naprzeciw tym wyzwaniom aplikacja posiada wbudowane systemy tagowania danych oraz dedykowane funkcje analityczne umożliwiający łatwe oznaczanie. 

### Tagi (plan)

Aplikacja wyposażona jest w  słownik kategorii transakcji (tagów), dzięki któremu można automatycznie wyróżniać odpowiednio szukane transakcje (np. opłaty za energię sugerujące posiadanie majątku). Pojedyncze tagi są definicją szukanych wartości (np. część numeru konta, szukany tekst w opisie, nazwa nadawcy/odbiorcy).

  

### Funkcje analityczne (plan)

Przygotowane przez zespół ekspertów funkcje analityczne pozwalają w bardzo szybki sposób oznaczyć analizowane dane. Dzięki nim można za pomocą paru kliknięć znaleźć takie zdarzenia jak np. Wykryj przelewy sekwencyjne, Oznacz faktury krajowa/zagraniczna, Oznacz rachunki firmowy/prywatny, Oznacz typy spółek itp. Lista fukcji zawiera około 50 pozycji.   

## Analiza: Szukanie i weryfikacja hipotez

Trzecim, finalnym punktem jest analiza. Przygotowaliśmy szereg narzędzi do potwierdzania hipotez przez użytkownika. 

![](https://lh3.googleusercontent.com/bXekUGzaat7zJ2Y2NvqoPMBc0hGHDU6zdkChi3LsgcgGdfcflfAtCeoiu7VOn8EsRexTZhw6zZ5sedTp7u6YD3VbryncyYfWjEvaRtXhI8Y6WldD3xnRqtVK_KbsSTlKgffkWvM4S7KzabIPpw)

### Predefiniowane 4 raporty transakcji

W aplikacji istnieją gotowe raporty mające na celu ułatwienie pracy analityka: ![](https://lh3.googleusercontent.com/rW37PXGEGJXGjNdmDRuFfzttJl4BuZAT7UgSRpQMAKiE-iuVexiSsuOBqLxfWa9zffGRSEHi_mZ0ZX5rEPD_jo-1V0x9_mH63sx4CXDrmwnKGbTa3unMtWysYUxScy2D_pUDlUrfivSpqDLgxg)

1.  Raport transakcji dla jednej tożsamości
    
2.  Raport transakcji dla jednej tożsamości z rozróżnieniem jej wielu rachunków
    
3.  Raport transakcji pomiędzy dwoma lub więcej wybranymi tożsamościami
    
4.  Raport transakcji pomiędzy dwoma lub więcej wybranymi tożsamościami oraz innymi tożsamościami z nimi. 
    

W ramach raportu użytkownik na swoim dashboardzie znajdzie takie narzędzia jak: 

1.  Graf raportu. 
    

1.  Graf koloryzuje dane w zależności od raportu. 
    
2.  Dane na grafie można grupować i rozgrupowywać
    
3.  Przepływy na grafie można grupować i rozgrupowywać
    
4.  Z grafu można wywoływać nowe raporty 
    

3.  Wykresy. W zależności od wybranego raportu, wyświetlają się: 
    

1.  Histogram transakcji z podziałem na wchodzące i wychodzące; z dostępną minimapą dla łatwego poruszania się po dłużyszych okresach czasu. Z Podziałem na rachunki i/lub kontrahentów. 
    
2.  Wykres transakcji przychodzących oraz wykres transakcji wychodzących z podziałem na typ, kontrahenta, i rachunek bankowy. 
    
3.  Suma transakcji przychodzących z podziałem na typ, kontrahenta i rachunki bankowe. 
    

5.  Tabela z wszystkimi transakcjami dostępnymi w raporcie. W podziale na osoby wysyłające i odbierające. 
    

  
  

### Predefiniowane 3 raporty Faktur![](https://lh4.googleusercontent.com/VjXbBQxctJnKjkWvtY5z2wMXxQeU05IkB6I3Vqp1JoJhRJCfv0WjDcLZFfnq_LfIJ4jh-J9tTaeL7jS4MGHj1h-W0_0APMlEnJAJZfdOLiLJvg8hFS_rsKiATUmgpJG9Kms8zE6fAowlFh6Pdw)

W aplikacji istnieją gotowe raporty mające na celu ułatwienie pracy analityka: 

5.  Raport przepływu faktur dla jednej tożsamości
    
6.  Raport przepływu faktur pomiędzy dwoma lub więcej wybranymi tożsamościami
    
7.  Raport przepływu faktur pomiędzy dwoma lub więcej wybranymi tożsamościami oraz innymi tożsamościami z nimi. 
    

W ramach raportu użytkownik na swoim dashboardzie znajdzie takie narzędzia jak: 

4.  Graf raportu. 
    

1.  Graf koloryzuje dane w zależności od raportu. 
    
2.  Dane na grafie można grupować i rozgrupowywać
    
3.  Przepływy na grafie można grupować i rozgrupowywać
    
4.  Z grafu można wywoływać nowe raporty 
    

6.  Wykresy. W zależności od wybranego raportu, wyświetlają się: 
    

1.  Zakupy i sprzedaż SUMA brutto z stawka VAT
    
2.  Wykres VAT zakupów tożsamości 
    
3.  Wykres VAT zsprzedaży tożsamości 
    
4.  Wykres sprzedaży tożsamości per stawka VAT
    
5.  Wykres zakupów tożsamości per stawka VAT
    
6.  Histogram przepływu faktur z podziałem na wchodzące i wychodzące; z dostępną minimapą dla łatwego poruszania się po dłużyszych okresach czasu. 
    

8.  Tabela z wszystkimi transakcjami dostępnymi w raporcie. W podziale na osoby wysyłające i odbierające. 
    

### Filtrowanie raportów

W celu łatwego poruszania się po danych w raportach został przygotowany moduł filtrowania. Każdy raport można przefiltrować przez dowolnie występujące dane w systemie, każdy moduł z danymi przy swoim wyświetlaniu uwzględnia obecny filtr, w tym graf. 

  

![](https://lh6.googleusercontent.com/V0x-hkAlkdCwHn1_bOhbyt4dqnG0EJPtNjH9F5Q4Vee84ml8u38WTYcklN2o7XAZksIMoAKUmWJx7XJGQE0DvjDCEVTl5P9_0n2OdZDYn3E03xbRwO_xuAHCSqaPNqj4qgVhjBidYc1PT7iv-w)

### Pełna funkcjonalność biblioteki grafowej (plan)

  

Różne skale grafów przedstawiają różne wyzwania. W przypadku dużych grafów, kluczowa jest optymalizacja liczby wyświetlanych elementów tak, aby zwiększyć czytelność wizualizacji, nie tracąc kluczowych informacji strukturalnych. Celem takiej wizualizacji jest zrozumienie ogólnej struktury grafu i pozycji analizowanych wierzchołków. W przypadku małych i średnich grafów, istotne jest zrozumienie ich dokładnej struktury oraz analiza powiązań między konkretnymi wierzchołkami. Analityk patrzy w takiej sytuacji na pojedyncze wierzchołki i analizuje konkretne relacje i ścieżki.

  

![](https://lh4.googleusercontent.com/CsBMNx-IlO_vqL54Ml-aOz-PdyPpZ5KfHmFfgdqSiaxYc7OM99_CiIicUXDBiJ487YNt1ph8tEBnUPq85sCyEYvqD2Xwt3hjYNPRVvLvHTbkMSTDFJkxkie-C-VvINbxWx2HFrvTfd_kiyd5AQ)

  

Biblioteka będzie zawierała zestaw funkcji analitycznych, pomocnych przy interakcjach z grafem. Znaczna część funkcji zostanie zaimplementowana w WebGL, aby obliczenia dokonywały się z wykorzystaniem karty graficznej. Niektóre funkcje będą całkowicie obliczane na GPU, inne w znacznej części. Zaimplementowane zostaną następujące funkcje:

  

-   Centralności (degree, closeness, beweenness),
    
-   Znalezienie najkrótszej ścieżki między wybranymi wierzchołkami (o ile istnieje),
    
-   Znalezienie wszystkich prostych ścieżek między wybranymi wierzchołkami,
    
-   Znalezienie wierzchołków osiągalnych z wybranego wierzchołka w ustalonej odległości,
    
-   Maksymalny przepływ między wybranymi wierzchołkami.
    

  
  

Dzięki wykorzystaniu WebGL oraz kart GPU system będzie pozwalał na wygodne i użyteczne analizy grafów obejmujące duże zbiory danych, a wizualizacje będą

poprawiały jakość analiz pozwalając na skuteczniejsze wykrywanie nieprawidłowości. 

  

### Edycja zapytania do raportów/scenariusze analityczne (plan)

W przygotowaniu jest funkcjonalność dająca niemalże nieograniczone możliwości pracy z bazą danych grafowych - moduł zapytań do bazy grafowej. 

  

Dzięki niemu będzie istniała możliwość weryfikacji dowolnych hipotez użytkownika poprzez budowę zaawansowanych zapytań w formie graficznej. 

  

Dzięki wbudowanym scenariuszom w moduł edycji zapytań, opartym na unikalnej wiedzy dotyczących modeli i wzorców przestępczości ekonomicznej oraz zaawansowanych algorytmach grafowych, system będzie pozwalał analitykowi na automatyczne wykrywanie, analizowanie i kategoryzowanie przestępstw. Automatyzacja procesów analitycznych pozwoli także na dużo szybsze analizowania poszczególnych spraw i przygotowywanie raportów do postępowań karnych i kontrolnych.

  

W celu budowy scenariuszy przestępstw finansowych i ekonomicznych użyte i zaadaptowane zostaną zaawansowane algorytmy analizy grafów i sieci społecznych. Będzie to pozwalało analitykowi na budowanie szerokiej gamy własnych scenariuszy i prowadzenie własnych analiz w sposób efektywny nawet przy sprawach z bardzo dużą ilością złożonych danych (np. obejmujących wiele analizowanych tożsamości).

  

Dane wyjściowe zapytań użytkownik będzie następnie wyświetlał na w pełni zarządzalnych i konfigurowalnych raportach: 

1.  Możliwość dodawania pól wyliczeniowe w tabeli raportu
    
2.  Możliwość budowania własnych wykresów na raporcie
    

  

Unikalna wiedza bazująca na doświadczeniach praktyków w zwalczaniu przestępczości ekonomicznej będzie pozwalała analitykowi na wykrywanie i analizowanie przestępstw przy niższych kompetencjach w zakresie finansów i rachunkowości. Pozwoli to na prowadzenie większej ilości analiz przez jednego analityka a także na prowadzenie analiz w szerszym zakresie (tj. przez więcej zaangażowanych osób), a więc przełoży się na poprawienie wskaźników zwalczania przestępczości.

  

![](https://lh6.googleusercontent.com/v25X2YDvJYhgeBuoEwPv6GxIabTzfTvhW0QQginnAubLv4b9mprQRj_vINxvNrZQP78aipF4MteMb-MkrxGVBi7qt4i6rVXT0_fCb8NbX-z3N1__a1SF5-u5xCDxpEwuMhgcjMgYR5l9M8BhTg)

  
  
  

## Raportowanie
![](https://lh3.googleusercontent.com/bSB4LFYVkTygMN8n55PuIzg5QlDcwXCm_IAXG8emPGsmJUuIPJeVDOteOdsjeaFMB2UDNczw6HijtI4E7ADoTd5KfDjtHLpwWqN5njnlk3ImlHhsi3jPsp_BV_58LOSqaDang2WHc0-3RgqM5w)

### Audyt eksportu do i2 (plan)/Excell

Dane już zanalizowane/przefiltrowane można następnie wyeskportować do arkusza kalkulacyjnego lub bezpośrednio do programu i2 (plan). 

  
  
  
  

## Funkcje aplikacji

### Zarządzanie sprawami

Wszystkie analizowane dane można dzielić na sprawy. Każda sprawa może mieć zdefiniowanych użytkowników, mających dostęp do analizowanych danych w obrębie danej sprawy.

### Zarządzanie użytkownikami / Integracja z Active Directory

Aplikacja potrafi zintegrować się z systemem Active Directory, dzięki czemu użytkownicy posiadający konta AD mogą bezpośrednio logować się do mAnalysera bez potrzeby zakładania nowych kont. 

### Wersja sieciowa

Aplikacja mAnalyser działa w wersji sieciowej, to znaczy, że serwer przechowujący dane może znajdować się w dowolnej lokalizacji, innej niż komputery analityków.**

