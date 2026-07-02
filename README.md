# Analiza wyników sprzedaży i marży – Power BI

Projekt przedstawia interaktywny dashboard stworzony w **Power BI**, umożliwiający analizę wyników sprzedaży, marży oraz realizacji KPI na poziomie kategorii i podkategorii produktów.

## Cel projektu

Celem projektu było przygotowanie raportu wspierającego analizę wyników sprzedażowych oraz identyfikację najbardziej rentownych grup produktowych.

Dashboard umożliwia odpowiedź na następujące pytania biznesowe:

- Które podkategorie generują najwyższą sprzedaż?
- Które produkty osiągają najwyższą marżę?
- Jak wygląda realizacja założonych KPI?
- Jak zmieniała się sprzedaż w czasie?
- Które obszary wymagają dodatkowej analizy?

---

## Wykorzystane technologie

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

## Funkcjonalności raportu

Raport zawiera:

- analizę sprzedaży według kategorii i podkategorii,
- analizę marży oraz marży procentowej,
- wskaźniki KPI sprzedaży i marży,
- formatowanie warunkowe,
- ikony KPI,
- miniwykresy (Sparklines),
- dynamiczne filtrowanie danych według roku, kwartału oraz podkategorii.

---

## Model danych

Raport został oparty na modelu danych obejmującym informacje o:

- zamówieniach,
- produktach,
- klientach,
- lokalizacjach,
- kalendarzu.

Model umożliwia analizę danych sprzedażowych w różnych przekrojach biznesowych.

---

# Podgląd dashboardu

### Widok główny

![Dashboard sprzedaży i marży](screenshot/dashboard-sprzedaz-marza.png)

### Widok z zastosowanymi filtrami

![Dashboard sprzedaży i marży - wybrane podkategorie](screenshot/dashboard-sprzedaz-marza-wybrane-podkategorie.png)

---

## Zawartość repozytorium

- `Sales & Profitability Dashboard.pbix` – raport Power BI
- `Data/Data.xlsx` – dane źródłowe
- `screenshot/` – zrzuty ekranu dashboardu
- `README.md` – opis projektu

---

## Najważniejsze miary DAX

Projekt wykorzystuje między innymi następujące miary:

- Sprzedaż
- Marża
- Marża %
- Sprzedaż KPI
- Marża KPI
- Zmiana sprzedaży rok do roku (PY)
- Średnia wartość zamówienia

---

## Zakres zaprezentowanych umiejętności

W projekcie wykorzystano:

- modelowanie danych,
- tworzenie relacji pomiędzy tabelami,
- projektowanie modelu w układzie gwiazdy,
- transformacje danych w Power Query,
- tworzenie miar w języku DAX,
- budowę interaktywnych dashboardów,
- projektowanie KPI,
- formatowanie warunkowe,
- analizę sprzedaży i marży,
- projektowanie raportów biznesowych.

---

## Wnioski biznesowe

Dashboard umożliwia szybką identyfikację najbardziej rentownych kategorii i podkategorii produktów oraz ocenę realizacji celów sprzedażowych.

Zastosowanie wskaźników KPI, formatowania warunkowego oraz miniwykresów pozwala szybko zidentyfikować obszary wymagające dalszej analizy i wspiera podejmowanie decyzji biznesowych.
