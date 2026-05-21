# Movie Analytics Dashboard

An interactive Power BI dashboard analyzing movie industry trends across Bollywood and Hollywood, covering revenue, budget, profit, actor performance, and language distribution.

## About the Project

This project was built as part of the BS Data Science program (Section 8A) at Saylani University. The dataset was compiled from multiple online sources, then cleaned, merged, and customized to fit the analysis requirements. The dashboard was built entirely in Power BI Desktop.

## Dataset

The dataset consists of 5 relational tables:

| Table | Key Fields |
|-------|-----------|
| movies | movie_id, title, industry, studio, language_id, year |
| financials | movie_id, budget_in_usd, revenue_in_usd |
| actors | actor_id, name |
| movie_actor | movie_id, actor_id (bridge table) |
| languages | language_id, name |

Calculated measures include Total Profit, ROI, Avg Rating, Budget Category, Year Group, Actor Revenue, Profit By Actor, and Total Movies By Actor.

## Dashboard Pages

**Main Dashboard** - KPI cards (Total Movies, Revenue, Budget, Profit, Avg Rating), Revenue by Year line chart, Top 5 Hit and Flop Movies bar charts, Movies by Language pie chart, Revenue by Industry donut chart, with Industry, Language, Studio, and Year slicers.

**Actor Analysis** - Movies By Actor and Revenue By Actor bar charts with actor-level KPIs and actor name slicer.

**Financial Analysis** - Budget vs Revenue area chart, Profit Analysis column chart, High vs Low Budget donut chart, with ROI, Total Budget, and Profit KPI cards.

**Industry Analysis** - Bollywood vs Hollywood revenue comparison column chart and Industry Growth Over Time line chart with series breakdown.

**Language Analysis** - Revenue by Language donut chart and Movies by Language bar chart with Total Languages and Total Movies KPI cards.

## Files

| File | Description |
|------|------------|
| [Movies.pbix](https://github.com/chaudhary47/Movie-Analysis-Dashboard/blob/main/Movies.pbix) | Power BI Dashboard file |
| [Movie_Dashboard_Presentation.pptx](https://github.com/chaudhary47/Movie-Analysis-Dashboard/blob/main/Movie_Dashboard_Presentation.pptx) | Project presentation slides |

## How to View the Dashboard

1. Download [Movies.pbix](https://github.com/chaudhary47/Movie-Analysis-Dashboard/blob/main/Movies.pbix)
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Use the slicers and navigation buttons to explore different pages

## Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions) for calculated measures

## Author

**Muhammad Ali Zaib**
Roll Number: SU92-BSDSM-F22-009
Section 8A | BS Data Science
