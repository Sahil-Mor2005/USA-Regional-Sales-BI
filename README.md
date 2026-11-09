# USA Regional Sales BI Dashboard

An interactive **Microsoft Power BI** project for exploring sales performance across products, sales channels, time periods, and US regions.

## Dashboard pages

### 1. Index
A landing and navigation page for the report.

### 2. Sales Overview
A high-level view of sales performance, featuring:
- Key performance indicators
- Sales and profit trends over time
- Top 10 products
- Sales-channel comparison
- Regional sales comparison

### 3. Regional Performance
A geographic and city-level view, featuring:
- State-level sales distribution on a map
- Top 10 cities
- Sales-team performance details
- Interactive region and month filters

## Data model

The report model contains these six tables:
- `Sales`
- `Customers`
- `Products`
- `Locations`
- `Sales_Team`
- `State_Regions`

## Tools

- **Microsoft Power BI Desktop** — report building and interactive visualization

The PBIX file is the source report. Specific DAX measures, Power Query transformations, and source-data provenance should be described only where verified from the original workflow.

## Dashboard screenshots

Add exported report screenshots to a `screenshots/` folder and update these image paths:

| Sales Overview | Regional Performance |
|---|---|
| ![Sales Overview](screenshots/sales-overview.png) | ![Regional Performance](screenshots/regional-performance.png) |

## How to view

1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Download this repository.
3. Open `USA Regional Sales BI.pbix` in Power BI Desktop.
4. If prompted, configure access to the original data source and refresh the model.
5. Explore the report pages and use the slicers to filter the analysis.

## Business questions explored

- Which products are among the top contributors to sales?
- How does sales performance differ by channel?
- How do sales and profit move over time?
- Which states, cities, and regions show stronger sales performance?
- How does performance vary across the sales team?

## Repository structure

```text
USA-Regional-Sales-BI/
├── USA Regional Sales BI.pbix
├── README.md
└── screenshots/
    ├── sales-overview.png
    └── regional-performance.png
```

## Sharing note

Before publishing the PBIX and its underlying data, make sure you have permission to share them and that the file contains no confidential or personally identifiable information.

## Author

**Sahil Mor**

[GitHub Profile](https://github.com/Sahil-Mor2005)
