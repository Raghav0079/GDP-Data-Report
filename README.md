# GDP Data Analysis

This project provides data and resources for analyzing GDP per capita across countries and regions. The workspace contains raw data in CSV format and a Power BI template for interactive data visualization.

## Project Structure

```
gdp data analysis.pbit
gdp_per_capita.csv
```

- **gdp_per_capita.csv**: Contains GDP per capita data for various countries and regions over multiple years.
- **gdp data analysis.pbit**: Power BI template file for visualizing and analyzing the GDP data.

## Data Description

### gdp_per_capita.csv

- **Format**: CSV (Comma-Separated Values)
- **Columns**:
  - `Country Name`: Name of the country or region.
  - `Country Code`: ISO or custom code for the country/region.
  - `Year Columns`: Each subsequent column represents GDP per capita (in USD or specified currency) for a particular year.

#### Example Row

```
Ireland,IRL,685.61,739.27,797.00,852.13,965.13,1023.77,1074.50,...
```

- Missing values are represented by empty fields.
- Some rows represent aggregate regions or income groups (e.g., "High income", "OECD members").

### gdp data analysis.pbit

- **Format**: Power BI Template
- **Purpose**: Provides pre-built dashboards and visualizations for exploring the GDP per capita data.
- **Usage**: Open with [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).

## How to Use

### 1. Explore the Data

You can open `gdp_per_capita.csv` in Excel, Google Sheets, or any spreadsheet tool to view and filter the data.

### 2. Visualize with Power BI

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Open `gdp data analysis.pbit`.
3. When prompted, load the `gdp_per_capita.csv` file as the data source.
4. Explore the pre-built dashboards, or create your own visualizations.

### 3. Analyze Trends

- Compare GDP per capita across countries and years.
- Identify growth trends, outliers, and regional patterns.
- Filter by country, region, or income group.

## Example Analyses

- **Top 10 countries by GDP per capita in the latest year**
- **GDP per capita growth rate over the last decade**
- **Comparison between income groups (High, Middle, Low income)**
- **Regional trends (e.g., OECD, EU, Asia-Pacific)**

## Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (for `.pbit` file)
- Spreadsheet software (Excel, Google Sheets, etc.) for `.csv` file

## Notes

- The `.pbit` file is a template; you may need to specify the path to `gdp_per_capita.csv` when opening it in Power BI.
- Data may contain missing values for some countries/years.
- Some rows represent aggregate regions or economic groups, not individual countries.

## License

This project is for educational and analytical purposes. Please check the source of the GDP data for any usage restrictions.

## Contact

For questions or suggestions, please open an issue or contact
