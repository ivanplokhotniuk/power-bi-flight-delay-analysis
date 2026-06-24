# Analiza lotów w USA – Power BI

Projekt końcowy wykonany w **Microsoft Power BI**, którego celem jest analiza punktualności, opóźnień, odwołań oraz natężenia ruchu lotniczego w Stanach Zjednoczonych.

## Opis projektu

Analiza została wykonana na podstawie danych o lotach w USA z 2015 roku. Projekt obejmuje przygotowanie danych w Power Query, budowę modelu danych, utworzenie miar DAX oraz przygotowanie czterech interaktywnych stron raportu.

## Zakres analizy

Raport składa się z czterech arkuszy:

1. **Podsumowanie**
   - liczba wszystkich lotów,
   - poziom punktualności,
   - liczba odwołanych lotów,
   - średnie opóźnienie,
   - analiza miesięczna,
   - struktura statusów lotów.

2. **Analiza czasu**
   - punktualność według dnia tygodnia,
   - liczba lotów i udział opóźnień według godziny,
   - statusy lotów według pory dnia,
   - mapa cieplna opóźnień według miesiąca i godziny.

3. **Linie lotnicze i lotniska**
   - ranking punktualności linii lotniczych,
   - liczba lotów i udział opóźnień według linii,
   - ranking dużych lotnisk z największym udziałem opóźnień,
   - rozmieszczenie i natężenie ruchu na lotniskach.

4. **Przyczyny opóźnień i odwołań**
   - łączny czas opóźnień według przyczyny,
   - przyczyny odwołania lotów,
   - odwołane loty według miesiąca i przyczyny,
   - podstawowe wskaźniki dotyczące odwołań i przekierowań.

## Najważniejsze wyniki

- przeanalizowano około **5,82 mln lotów**,
- około **81,0% lotów** uznano za punktualne,
- odwołano około **90 tys. lotów**,
- średnie opóźnienie opóźnionych lotów wyniosło około **58,9 minuty**,
- największą przyczyną opóźnień był **późny przylot poprzedniego samolotu**,
- najczęstszą przyczyną odwołania lotów była **pogoda**,
- najwyższą punktualność osiągnęły **Hawaiian Airlines**, **Alaska Airlines** i **Delta Air Lines**,
- udział opóźnionych lotów zwiększał się w kolejnych godzinach dnia.

## Technologie

- Microsoft Power BI Desktop
- Power Query
- DAX
- model danych w układzie gwiazdy
- wizualizacje interaktywne
- analiza danych przestrzennych

## Źródło danych

Dataset:

**2015 Flight Delays and Cancellations**

Źródło: Kaggle / U.S. Department of Transportation

Pliki źródłowe:

- `flights.csv`
- `airlines.csv`
- `airports.csv`

## Pobranie projektu Power BI

Plik `.pbix` jest zbyt duży, aby umieścić go bezpośrednio w repozytorium GitHub.

Można go pobrać z Google Drive:

[**Pobierz projekt Power BI (.pbix)**](https://drive.google.com/file/d/11Ob4-hNzVp9mYk9nJm4kTw4GzzpCnJ6v/view?usp=sharing)

> Upewnij się, że plik na Google Drive ma ustawiony dostęp: „Każda osoba mająca link”.

## Raport PDF

Pełny raport opisujący źródła danych, przygotowanie danych, model, miary DAX, wyniki i wnioski znajduje się w pliku:

[`Raport_Analiza_lotow_Ivan_Plokhotniuk.pdf`](Raport_Analiza_lotow_Ivan_Plokhotniuk.pdf)


```

## Uruchomienie projektu

1. Pobierz plik `.pbix` z Google Drive.
2. Otwórz go w Microsoft Power BI Desktop.
3. Wszystkie dane są zapisane wewnątrz modelu, dlatego raport można przeglądać bez dodatkowych plików CSV.
4. Do ponownego odświeżenia danych może być konieczne wskazanie lokalizacji plików źródłowych.

## Autor

**Ivan Plokhotniuk**

Projekt wykonany jako projekt końcowy z analizy danych w Power BI.
