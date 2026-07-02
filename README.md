# Analiza wyników sprzedaży 2020–2023 – Power BI

Projekt przedstawia interaktywny dashboard stworzony w **Power BI**, umożliwiający analizę wyników sprzedaży w latach 2020–2023 z wykorzystaniem wskaźników KPI, porównań do celów sprzedażowych oraz analiz regionalnych i branżowych.

## Cel projektu

Celem projektu było przygotowanie raportu wspierającego monitorowanie wyników sprzedaży oraz ocenę realizacji założonych celów biznesowych.

Dashboard umożliwia odpowiedź na następujące pytania biznesowe:

- Jak zmieniała się sprzedaż w latach 2020–2023?
- Czy sprzedaż osiągnęła założony cel?
- Które województwa generują najwyższą sprzedaż?
- Które branże osiągają wyniki powyżej średniej sprzedaży?
- Jak zmienia się średnia wartość zamówienia?
- Jak wygląda dynamika sprzedaży rok do roku?

---

## Wykorzystane technologie

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

## Funkcjonalności raportu

Raport zawiera:

- analizę sprzedaży według województw,
- analizę sprzedaży według branż,
- porównanie sprzedaży do średniej,
- wskaźniki KPI,
- analizę realizacji celu sprzedażowego,
- dynamiczne filtrowanie danych według:
  - roku,
  - kwartału,
  - województwa,
- formatowanie warunkowe,
- interaktywne wizualizacje.

---

## Model danych

Raport został oparty na modelu danych obejmującym informacje o:

- zamówieniach,
- klientach,
- produktach,
- przedstawicielach handlowych,
- lokalizacjach,
- kalendarzu.

Model został zaprojektowany w układzie gwiazdy, umożliwiając szybkie agregowanie danych i analizę wyników sprzedaży z różnych perspektyw.

---

## Podgląd dashboardu

### Rok 2021

![Dashboard 2021](Screenshots/dashboard-2021.png)

### Rok 2022

![Dashboard 2022](Screenshots/dashboard-2022.png)

### Rok 2023

![Dashboard 2023](Screenshots/dashboard-2023.png)

---

## Zawartość repozytorium

- `Sales-Performance-Dashboard.pbix` – raport Power BI
- `Data.xlsx` – dane źródłowe
- zrzuty ekranu dashboardu
- `README.md` – opis projektu

---

## Najważniejsze miary DAX

Projekt wykorzystuje między innymi następujące miary:

- Sprzedaż
- Marża %
- Średnia wartość zamówienia
- Sprzedaż vs cel
- Zmiana sprzedaży rok do roku (PY)
- Średnia sprzedaż według branży
- Średnia sprzedaż według województwa

---

## Zakres zaprezentowanych umiejętności

Projekt prezentuje umiejętności w zakresie:

- modelowania danych,
- projektowania modelu gwiazdy,
- tworzenia relacji pomiędzy tabelami,
- transformacji danych w Power Query,
- tworzenia miar w języku DAX,
- projektowania KPI,
- analizy sprzedaży,
- analizy danych regionalnych,
- analizy danych branżowych,
- projektowania interaktywnych dashboardów.

---

## Wnioski biznesowe

Dashboard umożliwia bieżące monitorowanie wyników sprzedaży oraz ocenę realizacji założonych celów biznesowych.

Zastosowanie wskaźników KPI, porównania do średniej sprzedaży oraz analiz regionalnych pozwala szybko zidentyfikować województwa i branże osiągające najlepsze wyniki oraz obszary wymagające dodatkowej uwagi. Raport wspiera proces podejmowania decyzji biznesowych poprzez czytelną prezentację kluczowych wskaźników efektywności.
