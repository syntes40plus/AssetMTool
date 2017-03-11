# AssetMTool

Projekt ma na celu utworzenie systemu rejestracji i zarządzania majątkiem / zasobami przedsiębiorstwa (nieruchomości, pojazdy, urządzenia).  

Tak więc na początek będzie to wersja konsolowa, stopniowo rozwijana (może doczeka się wersj okienkowej i webowej).


#Etap I

W I etapie projektu ma powstać szkielet aplikacji tj. Interfejs oraz konstruktory obiektów jak też klasa umożliwiająca ich wywołanie. Na tym etapie obiekty nie będą przechowywane w bazie a jedynie przechowywane w tymczasowej klasie "bazie" z użyciem jakiejś kolekcji. Aby umożliwić wybór przy dodanie różnych rodzajów obiektów użyty zostanie typ ENUM. 

W tym etapie także powina postac logika pozwalająca na: 
1. Wybór rodzaju akcji tj. dodawanie, wyszukanie, edycja, usuwanie.
2. Wybór rodzaju obiektu na jakim akcja jest wywoływan. 
Czyli menu konsolowe. 

Jeśli chodzi o strukturę projektu,  tworzymy 3 pakiety na potrzeby obiektów, logiki oraz aplikacji. 

#Etap II  

Na tym etapie logika palikacji powinna być rozszerzona o możliwość zapisu , odczytu obiektów do pliku (np tekstowy). 
(?) Serializacja (?) 

#Etap III 

Zmiana logiki na zapis do bazy danych. W moim przpadku będzie to MySQL. Tak więc niezbędne będzie stworzenie klasy realizującej logikę dostępu do bazy danych i obsługę obiektów 

Dodatkowo: 
funkcjonalność umożliwiająca dodawanie/usuwanie użytkowników , logowanie ;
funkcjonalność umożliwiająca dodawanie dokumentów do bazy (powiązanych ze składnikiem majątku) ;


