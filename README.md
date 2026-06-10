# Where Are the Gaps? Mapping Autism Services Across the USA

Analyzing autism service availability across all 50 US states using CDC, 
HRSA, and SAMHSA data to identify which states are failing autistic individuals 
and their families.

## Tools Used
- Python, Pandas, NumPy
- Plotly (interactive choropleth maps)
- Google Colab

## Data Sources
- CDC ADDM 2023 autism prevalence estimates
- HRSA Health Workforce data (ABA providers, diagnostic centers)
- SAMHSA behavioral health services locator
- 2020 US Census population data

## What I Built
- Interactive USA choropleth map (hover over any state for full stats)
- Best vs worst states comparison chart
- Population vs services scatter plot
- Full findings report across all 50 states

## Key Findings
- 🗺️ No state has truly adequate autism service coverage
- 🔴 California has 1.5M autistic individuals — only 2.15 services per 1,000
- 📊 New York + Texas + California = 2.8M underserved autistic Americans
- 🟢 Rhode Island leads the nation at 5.59 services per 1,000
- 🏘️ The South is consistently the most underserved region
- 📍 State averages hide severe rural vs urban gaps within states

## Visualizations
> Open the HTML files directly in your browser for fully interactive maps

- `autism_services_map.html` — USA choropleth map
- `autism_services_bars.html` — Best vs worst states
- `autism_services_scatter.html` — Population vs services scatter
