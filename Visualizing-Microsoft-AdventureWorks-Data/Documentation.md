# AdventureWorks Sales Dashboard

Executive Power BI report for the **AdventureWorks** company (bike and accessories retailer), covering revenue, orders, profit, returns, products and customers, with targets and month-over-month comparison.

![Executive Summary](Previews/page1.png)

## Report Pages
| Page | Content |
|---|---|
| **Exec Summary** | Monthly revenue, orders and returns vs. previous month, orders by category and subcategory, return rate by product, top products by orders and profit, sales by territory |
| **Product Detail** | Revenue, orders and profit vs. targets, price adjustment simulation (what-if parameter), weekly trend |
| **Customer Detail** | Customers by income level, occupation, gender and age, top customers by revenue and orders |

## Data Model
Star schema built from the CSV files in `Data/`:
- **Facts:** `AW_Sales` (2015–2017), `AW_Returns`
- **Dimensions:** `AW_Calendar_Lookup`, `AW_Customers_Lookup`, `AW_Products_Lookup`, `AW_Product_Subcategory_Lookup`, `AW_Product_Category_Lookup`, `AW_Territories_Lookup`

## DAX Measures (examples)
Total Revenue, Total Profit, Total Orders, Total Returns, Return Rate, Prev Month Revenue/Orders/Returns (time intelligence), Revenue Target, Order Target, Adjusted Price and Adjusted Profit (what-if parameter).

## Previews
Full report preview: [`Previews/preview.pdf`](Previews/preview.pdf)
