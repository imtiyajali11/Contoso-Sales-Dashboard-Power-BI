# Contoso Sales Interactive Dashboard and Insights

Power BI assignment project built on the Contoso Sales sample dataset. The report highlights product performance, sales performance, natural language Q&A, smart narrative insights, and key influencer analysis for SalesAmount.

## Project Files

- `Interactive dashboard and insights Contoso.pbix` - Main Power BI Desktop report file.
- `Interactive dashboard and insights Contoso.pbip` - Power BI Project file for source-control friendly editing.
- `Interactive dashboard and insights Contoso.Report/` - Report definition files.
- `Interactive dashboard and insights Contoso.SemanticModel/` - Semantic model definition files.
- `Assignment 1.pdf` - Assignment/export reference document.

## Dataset

Dataset source:

https://itv-contentbucket.s3.ap-south-1.amazonaws.com/Exams/Power+BI/DAX/Contoso+Sales+Sample+for+Power+BI+Desktop.pbix

The report uses Contoso Sales data with sales, product, geography, calendar, channel, store, and promotion tables.

## Dashboard Pages

### Sales Trend

Shows sales movement over time using SalesAmount.

### Sales Analysis

Highlights sales performance by dimensions such as manufacturer, product, geography, and time.

### Product Analysis

Focuses on product-level performance, including product categories, product names, and manufacturer contribution.

### AI Insights

Includes the assignment's AI-driven visuals:

- Q&A visual for asking natural language questions about the Contoso sales data.
- Smart Narrative for the complete dashboard.
- Smart Narrative for the Manufacturer Performance chart.
- Key Influencers visual analyzing SalesAmount by:
  - Manufacturer
  - ProductName
  - ContinentName

## Key Assignment Requirements Covered

- Product analysis dashboard visuals.
- Sales analysis dashboard visuals.
- Power BI Q&A visual.
- Smart Narrative on a specific chart.
- Smart Narrative on the complete dashboard.
- Key Influencers analysis for SalesAmount explained by manufacturer, product name, and continent.

## How To Open

1. Open `Interactive dashboard and insights Contoso.pbix` in Power BI Desktop.
2. If Power BI prompts you to apply changes or refresh visuals, allow it.
3. Go to the `AI Insights` page to review Q&A, Smart Narrative, and Key Influencers visuals.

## Enable Q&A If Disabled

If the Q&A visual is disabled in Power BI Desktop:

1. Go to `File > Options and settings > Options`.
2. Select `Current file > Data Load`.
3. Enable `Turn on Q&A to ask natural language questions about your data`.
4. Click `OK`.
5. Save, close, and reopen the report.

## Example Q&A Questions

Try these in the Q&A visual:

- `total sales amount by manufacturer`
- `sales amount by continent`
- `top products by sales amount`
- `sales amount by year`
- `manufacturer sales trend`

## Notes

- The `.pbix` file is approximately 52 MB, which is below GitHub's 100 MB single-file limit.
- The `.pbip` project structure is included so report metadata can be reviewed in GitHub.
- Q&A in Power BI depends on current file settings and may need to be enabled locally after opening the report.

# Contoso-Sales-Dashboard-Power-BI
