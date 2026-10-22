# pokemon-excel-dashboard
An interactive Pokémon analytics dashboard built in Microsoft Excel, exploring 801 Pokémon across seven generations using PivotTables, PivotCharts, KPI cards, and slicers.
# Project objective
Explore how Pokémon are distributed across generations and primary types, how common Legendary Pokémon are, and how average battle statistics vary across generations. The dashboard is designed for interactive exploration rather than prediction or classification.
Tools and techniques
- Microsoft Excel: data preparation, structured tables, PivotTables and PivotCharts
- Data cleaning: standardising fields, separating the source abilities list into individual columns, and preparing gender-percentage fields
- Analysis: counts by generation and primary type; Legendary versus non-Legendary counts; average Attack, Defense, and Speed
- Dashboard design: three KPI cards, four charts, and two slicers for Generation and Legendary status
Dashboard features
Feature	What it shows
Total Pokémon KPI	Number of Pokémon in the current filter selection
Legendary Pokémon KPI	Count of Legendary Pokémon in the current selection
Average Attack KPI	Average Attack stat in the current selection
Pokémon Distribution by Generation	Number of Pokémon introduced in each generation
Legendary vs Non-Legendary	Relative share of Legendary and non-Legendary Pokémon
Pokémon by Primary Type	Counts by type1 (not both types)
Average Battle Stats by Generation	Average Attack, Defense, and Speed by generation
Interactive slicers	Filter connected charts and KPIs by generation and Legendary status

# Selected findings
With all generations included in the dashboard:
- 801 Pokémon records are analysed.
- 70 are marked Legendary (about 8.7% of the analysed records).
- Generation 5 has the most Pokémon (156); Generation 6 has the fewest (72).
- The overall average Attack shown by the dashboard is approximately 77.9.
These are descriptive findings from the workbook, not claims about Pokémon game balance or competitive strength.
Dataset and attribution
The project uses The Complete Pokemon Dataset, described by its publisher as covering 802 Pokémon across the first seven generations. The dataset description credits data scraped from (https://www.kaggle.com/datasets/rounakbanik/pokemon)

Record-count note: The source description states 802 Pokémon, while this workbook analyses 801 records. The difference has not been independently reconciled and should not be interpreted as a documented cleaning exclusion.

# Dataset link: Add the original Kaggle dataset page URL here before publishing, so readers can find and credit the source directly.
How to explore
1. Download Pokemon_Analytics_Dashboard.xlsx.
2. Open it in the desktop version of Microsoft Excel.
3. Navigate to the Dashboard worksheet.
4. Use the Generation and Legendary Status slicers to explore the data.
5. Clear slicer filters to return to the full dataset.

# Project scope
This is an exploratory Excel dashboard, not a Legendary Pokémon classifier, predictive model, or competitive team optimiser. The primary-type chart uses only the type1 field.
# What I learned
This project helped me practise cleaning a real-world dataset, creating and connecting PivotTables, selecting meaningful summary statistics, troubleshooting linked KPI calculations, and designing an interactive dashboard that communicates findings clearly.
