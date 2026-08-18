# ChurnDashboard_L

**LTT | لوحة التنبؤ بمغادرة العملاء** — a single-page customer churn prediction and retention dashboard for LTT (Libya Telecom & Technology).

## Overview

ChurnDashboard_L turns churn model output into actionable retention insights for the LTT retention team. It presents predicted churn risk, at-risk revenue, and recommended interventions in an Arabic (RTL) executive interface.

## Features

- **Executive Overview** — key KPIs (predicted churn rate, customers at risk, revenue at risk, retention opportunity, average churn probability, retention success rate), a churn trend chart, and an AI-generated executive summary
- **Churn Predictions** — probability distribution across customer segments and model confidence metrics (ROC-AUC, Precision, Recall, F1)
- **Customer Risk Matrix** — a heatmap prioritizing customers by churn probability × customer value
- **Churn Drivers** — ranked feature importance with model interpretation notes
- **Regional Analysis** — churn rate by region and network quality vs. churn correlation
- Filters by time period, region, customer type, and risk tier
- Priority intervention list with per-customer recommended actions
- CSV export of the current filtered risk list

## Tech Stack

Single static HTML file — vanilla JavaScript, inline CSS, and inline SVG charts. No build step, backend, or external dependencies beyond a Google Fonts import.

## Getting Started

Clone the repo and open `index.html` directly in a browser:

```bash
git clone https://github.com/weltief/ChurnDashboard_L.git
cd ChurnDashboard_L
```

Then open `index.html` in your browser (no server required).

## Data

Customer and churn data in `index.html` is currently mock/sample data for demonstration purposes.

## Status

🚧 Prototype — UI and sample data are in place; integration with a live churn model/data source is pending.

## License

TBD
