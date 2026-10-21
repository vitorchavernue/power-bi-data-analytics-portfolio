# Paris 2024 Olympics Dashboard

Interactive Power BI report analyzing the **Paris 2024 Olympic Games**: participation, medal distribution by country, discipline and gender, athletes' profile and historical results.

![Overview](Previews/page2.png)

## Report Pages
| Page | Content |
|---|---|
| **Home** | Navigation menu |
| **Overview** | Key highlights, total countries, teams and athletes, medals by country and by gender, world map |
| **Athletes** | Athletes by gender, age category and country; medals by discipline |
| **Country** | Medal breakdown (gold, silver, bronze) by country and discipline |
| **Historical** | Medal tally evolution by country across Olympic editions |

## Data
Public Paris 2024 datasets (`Data/`): athletes, medallists, medals, medal totals, teams, events, schedules, venues and historical medal tally.

## Data Model & DAX
- Dedicated measures table (`Olympic_Measures`) with KPIs such as total athletes, participating countries and teams, total medals and medals by type.
- Calculated columns for athlete age categories.
- Relationships between athletes, medallists and country tables for cross-filtering.

## Highlights
- Custom page navigation and modern UI with consistent theme.
- Dynamic text summary ("Key Highlights") driven by measures.

## Previews
Full report preview: [`Previews/preview.pdf`](Previews/preview.pdf)
