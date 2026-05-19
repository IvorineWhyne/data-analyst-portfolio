# Power BI Projects

This folder contains all Power BI dashboards and reports for my data analysis portfolio.

## 📊 Projects

### Apocalypse Food Prep Analysis
**Status**: Completed  
**File**: `First Visualization.pbix`

#### Project Description
This project demonstrates a foundational workflow in Microsoft Power BI, utilizing a sample dataset to analyze shopping habits and cost optimization for long-term food storage. The analysis identifies the most cost-effective stores for essential survival supplies to optimize future shopping strategies.

#### Goal
Determine the most cost-effective store for essential survival supplies to optimize future shopping habits.

#### Data Source
- **Primary**: `../Apocolypse Food Prep.xlsx`
- **Format**: Excel workbook with purchase records
- **Contains**: Shopping data across multiple stores (Walmart, Target, Costco) with product types, prices, and purchase dates
- **Last Updated**: May 2026

#### Key Processes

**Data Transformation**
- Used Power Query Editor to clean and prepare the dataset
- Renamed columns for clarity (e.g., 'Date' → 'Date Purchased')
- Filtered out non-essential items (e.g., milk)
- Standardized data formats for consistent analysis

**Visualization Building**
1. **Total Spend by Store** - Stacked Column Chart
   - Compares aggregate spending across all three retailers
   - Identifies overall spending patterns by store

2. **Price Comparison by Product** - Clustered Column Chart
   - Displays price variations for specific items (rice, dried beans, etc.)
   - Highlights which stores offer the best prices for individual products
   - Enables product-level shopping optimization

#### Key Insights

**Overall Finding**
Costco emerged as the most cost-effective store for the majority of food prep items, offering competitive pricing across most product categories.

**Strategic Recommendation**
While Costco is the primary recommendation for bulk purchases, the dashboard reveals that buying specific items like rice at Target can yield additional savings. This insight enables a more nuanced shopping strategy—leveraging Costco for most items while selectively purchasing certain products from other retailers for maximum savings.

#### Tools Used
- **Microsoft Power BI Desktop**
- **Power Query** (data transformation)
- **DAX** (data analysis expressions for calculations)
- **Excel** (data source)

#### How to Use
1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Open `First Visualization.pbix`
3. Interact with the visualizations:
   - Use slicers to filter by store or product
   - Hover over charts for detailed values
   - Explore drill-through features for product-level analysis
4. Review pricing trends and make data-driven shopping decisions

#### Dashboard Features
- Store comparison metrics
- Product-level price analysis
- Spending trend visualization
- Cost optimization recommendations
- Interactive filters for custom analysis

---

## 📁 Folder Structure

```
power-bi/
├── README.md (this file)
├── First Visualization.pbix (main dashboard file)
└── report-exports/
    ├── apocalypse-food-prep-summary.pdf
    ├── total-spend-by-store.png
    └── price-comparison-by-product.png
```

## 🔗 Related Files

- Raw data: `../Apocolypse Food Prep.xlsx`
- Main portfolio: `../README.md`

---

*Last Updated: May 2026*
