# Sales Analysis Dashboard (Excel)

An Excel project that analyzes 1,000 sales records (Arabic data) of computer products across Egyptian governorates, using Pivot Tables, PivotCharts, Slicers, and formulas.

## Dashboard

![Dashboard](images/dashboard.png)

## Pivot Table

![Pivot](images/pivot.png)

## Dataset

| Column | Meaning |
|---|---|
| رقم العملية | Order ID |
| اسم الموظف | Employee name |
| التاريخ | Date |
| المنتج | Product |
| الفئة | Category |
| المحافظة | Governorate |
| المدينة | City |
| الكمية | Quantity |
| سعر الوحدة | Unit price |
| المجموع | Total (sales amount) |
| صافي الربح | Net profit |
| حالة الطلب | Order status |
| طريقة الدفع | Payment method |

## Key Insights

All figures count **completed orders only** (canceled, returned, and in-shipping orders are excluded).

- **Total sales:** 12,748,750
- **Total net profit:** 11,897,070
- **Top product:** Lenovo laptop
- **Top city:** الدقي (Dokki)
- **Top 5 products by sales:** Lenovo, Dell, and HP laptops, then Samsung and LG monitors

## Workbook Sheets

| Sheet | Content |
|---|---|
| Raw_Data | The source data (table named `SalesTable`) |
| Pivot_Analysis | Pivot tables behind the charts |
| analysis | Supporting analysis |
| dashboard | KPIs, charts, and slicers |

## How to Use

1. Open `excel/sales_analysis.xlsx`.
2. Go to the `dashboard` sheet.
3. Use the slicers (Governorate, Category, Payment Method) to filter the charts.

Note: the four KPI cards at the top are formulas on the full table, so they are not affected by the slicers.

## Tools

Microsoft Excel: Pivot Tables, PivotCharts, Slicers, SUMIFS, INDEX, SORTBY, UNIQUE.

## Project Structure

```
sales-analysis-excel/
├── README.md
├── data/sales_data.csv
├── excel/sales_analysis.xlsx
└── images/
```