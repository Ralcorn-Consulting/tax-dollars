# Where Are My Tax Dollars Going?

## Concept
Interactive web visualization showing exactly where your tax dollars go — broken down by every level of government.

## How It Works
1. User enters country, state/province, and city
2. App looks up actual government budgets for those jurisdictions (current fiscal year)
3. Shows a visual breakdown: "You paid $X in taxes. Here's exactly what you bought."

## Data Sources Needed
- **Federal:** USASpending.gov API, Treasury data, CBO budget breakdowns
- **State:** State comptroller/budget office data (varies by state)
- **Local/City:** Municipal budget data (often published as open data)
- Tax bracket calculations based on income (user input or estimate)

## Visualization Ideas
- Animated dollar bill splitting into streams flowing to categories
- Treemap / sunburst chart of spending categories
- "Your personal receipt" — itemized like a shopping receipt
- Compare your city vs national averages
- Timeline: how spending changed year over year
- Per-dollar breakdown: "For every $1 you paid: $0.24 → Defense, $0.15 → Healthcare..."

## Stack Ideas
- Single-page web app (Netlify deploy)
- D3.js or Observable Plot for visualizations
- Government APIs for live data
- Could start with federal only, expand to state/local

## Status
Idea captured Feb 9, 2026. Not started.
