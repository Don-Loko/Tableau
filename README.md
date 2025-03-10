🚗📈 Analiza cen samochodów i popytu na rynku amerykańskim

Opis projektu

Projekt przedstawia interaktywną analizę rynku samochodów używanych sprzedawanych na terenie Stanów Zjednoczonych. Analiza uwzględnia wpływ stanu technicznego pojazdu, lokalizacji sprzedaży oraz osiągnięć najlepszych sprzedawców na ceny i popyt na auta.

Dzięki stworzonemu dashboardowi możliwe jest szczegółowe zbadanie wpływu różnych czynników, takich jak kondycja samochodu, przebieg oraz miejsce sprzedaży na cenę końcową pojazdu. Dashboard umożliwia również ocenę wyników sprzedaży najlepszych dealerów samochodowych.

Źródło danych

Źródło: Kaggle

Liczba rekordów: 558 838

Liczba kolumn: 16

Zakres czasowy: od 16.12.2014 do 24.06.2015

Szczegóły zbioru danych

Najważniejsze kolumny:

sellingprice: Cena sprzedaży pojazdu.

mmr: Estymowana wartość rynkowa pojazdu (Manheim Market Report).

condition: Stan techniczny pojazdu (skala od 1 do 49).

odometer: Przebieg pojazdu (w milach).

color: Kolor samochodu.

state: Stan USA, w którym sprzedano samochód.

seller: Sprzedawca pojazdu.

saledate: Data sprzedaży.

Brad 1, body, model, year: Marka, model, budowa oraz rocznik pojazdu.

Dashboard i jego elementy

Dashboard zawiera kilka interaktywnych wizualizacji:

Mapa cieplna sprzedaży samochodów w USA – regionalne różnice sprzedaży.

Średnia cena sprzedaży i popularność kolorów – wpływ koloru auta na cenę.

Wpływ przebiegu i stanu technicznego na cenę – relacje pomiędzy przebiegiem, stanem auta i ceną sprzedaży.

Cena sprzedaży a estymowana wartość rynkowa (MMR) – porównanie cen sprzedaży z prognozą.

Top 10 sprzedawców – analiza najlepszych sprzedawców (z dodatkowym wykresem rocznym po kliknięciu przycisku z klawiszem ALT).

Funkcje interaktywne

Dashboard oferuje interaktywne filtry:

Rok produkcji auta

Zakres przebiegu pojazdu (odometer)

Średnia cena sprzedaży (sellingprice)

Grupy kondycji pojazdu (condition co 5 jednostek)

Wybrane wykresy mogą pełnić funkcję interaktywnych filtrów dla całego dashboardu.

Jak uruchomić projekt

Dashboard dostępny jest publicznie na Tableau Public:

👉 Otwórz dashboard – [analiza cen samochodów USA] (https://public.tableau.com/app/profile/piotr.kosi/vizzes)

Wnioski i obserwacje

Kondycja pojazdu i lokalizacja mają istotny wpływ na końcową cenę sprzedaży.

Wyraźna jest sezonowość sprzedaży pojazdów oraz zróżnicowanie cen według kolorów.

Dealerzy z czołowych miejsc osiągają istotnie lepsze wyniki sprzedaży.

Występuje dziwna anomalia w cenach i róznicą między MMR w przedziale condition 3 - 5, prawdopodobnie wywołana pojedynczymi sprzedażami rzadkich egzemplarzy.

Technologia

Dashboard wykonany został w programie Tableau Desktop.

Autor

Piotr Kosidlak📧 Kontakt: Profil Tableau Public
