# Sales & Commercial Analytics Dashboard (Excel & BI)

Kompleksowy projekt analityczno-raportowy Business Intelligence zrealizowany w środowisku Microsoft Excel, oparty na relacyjnym modelu gwiazdy (Star Schema) oraz automatyzacji przetwarzania danych sprzedażowych.

## Kluczowe elementy projektu
- **Modelowanie danych (Star Schema):** rozdzielenie danych na tabelę faktów (`fact_sales`) oraz tabele wymiarów (`dim_customer`, `dim_product`, `dim_date`).
- **Wskaźniki efektywności (KPI):** monitorowanie przychodów, marży, wolumenu sprzedaży oraz struktury koszykowej klientów.
- **Interaktywny Dashboard:** dynamiczne filtrowanie danych przy użyciu fragmentatorów (slicers), osi czasu oraz tabel i wykresów przestawnych.
- **Automatyzacja:** wykorzystanie formuł zaawansowanych i makr VBA do obsługi odświeżania i czyszczenia danych.

## Podgląd Dashboardu
<img width="2102" height="1104" alt="dashboard_preview" src="https://github.com/user-attachments/assets/51e3bb2b-48f8-477a-8abc-99fd08012a25" />

## Struktura plików
- `sales_analytics_dashboard.xlsm` – główny skoroszyt analityczny z dashboardem i warstwą analityczną.
- `/data/` (`dim_*.csv`, `fact_sales.csv`) – zbiory danych wejściowych w relacyjnym układzie hurtowni danych.
- `opis_dashboard_JG_AG_kosmetyki.pdf` – pełna dokumentacja projektowa i biznesowa interpretacja wyników.

## Technologie
- Microsoft Excel, Power Query, VBA, Data Modeling (Star Schema), KPI Analysis
