# Sales & Commercial Analytics Dashboard (Excel & BI)

Kompleksowy projekt analityczno-raportowy Business Intelligence zrealizowany w środowisku Microsoft Excel, oparty na relacyjnym modelu gwiazdy (Star Schema) oraz automatyzacji przetwarzania danych sprzedażowych.

## Kluczowe elementy projektu
- **Modelowanie danych (Star Schema):** rozdzielenie danych na tabelę faktów (`fact_sales`) oraz tabele wymiarów (`dim_customer`, `dim_product`, `dim_date`).
- **Wskaźniki efektywności (KPI):** monitorowanie przychodów, marży, wolumenu sprzedaży oraz struktury koszykowej klientów.
- **Interaktywny Dashboard:** dynamiczne filtrowanie danych przy użyciu fragmentatorów (slicers), osi czasu oraz tabel i wykresów przestawnych.
- **Automatyzacja:** wykorzystanie formuł zaawansowanych i makr VBA do obsługi odświeżania i czyszczenia danych.

## Podgląd Dashboardu
*(w tym miejscu wklej zrzut ekranu `dashboard_preview.png` metodą przeciągnij i upuść)*

## Struktura plików
- `sales_analytics_dashboard.xlsm` – główny skoroszyt analityczny z dashboardem i warstwą analityczną.
- `/data/` (`dim_*.csv`, `fact_sales.csv`) – zbiory danych wejściowych w relacyjnym układzie hurtowni danych.
- `opis_dashboard_JG_AG_kosmetyki.pdf` – pełna dokumentacja projektowa i biznesowa interpretacja wyników.

## Technologie
- Microsoft Excel, Power Query, VBA, Data Modeling (Star Schema), KPI Analysis
