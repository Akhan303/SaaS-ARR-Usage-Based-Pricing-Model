**Business Impact: Enabled founders and investors to evaluate subscription vs usage-based pricing strategies, quantify ARR uplift potential, and make data-driven fundraising decisions with confidence.**
**Project Overview**

This project develops an ARR forecasting simulator that compares flat subscription pricing against usage-based pricing. By incorporating customer segments, churn dynamics, and acquisition growth, it provides leadership and investors with a complete picture of how pricing strategy impacts revenue trajectories.

The model supports interactive scenario testing so executives can instantly see how changes in customer mix, churn, or pricing levers affect ARR growth and uplift.

**The S.T.A.R.**

Situation:
SaaS clients lacked credible ARR and LTV/CAC growth models for fundraising. Traditional flat subscription projections ignored the impact of customer usage heterogeneity and churn, resulting in unrealistic forecasts.

**Task:**
Develop a pricing and forecasting framework to:

Compare ARR outcomes under flat subscription vs usage-based pricing

Model churn dynamics by customer cohort (Heavy, Medium, Light)

Incorporate acquisition growth to simulate real SaaS expansion

Quantify ARR uplift %, ARPU shifts, and investor-grade KPIs

**Action:**

Simulated usage telemetry (API calls, seats, GB consumed) by cohort

Applied churn rates (1% heavy, 3% medium, 6% light) to model retention

Built ARR bridges for subscription vs usage-based pricing

Integrated acquisition logic (new users per month + growth rate)

Designed interactive Colab notebook with sliders to test pricing levers

Computed KPIs: ARR, ARPU, LTV, CAC, Payback, Uplift %

Visualized revenue trajectories to highlight strategy trade-offs

**Result:**

Forecasted a +15% ARR uplift under usage-based pricing in investor scenarios

Exposed downside risk when cohorts skew toward light users

Delivered an investor-ready tool to prove pricing strategy credibility

**Key Features**

ARR Forecasting: Compares Subscription vs Usage-Based models

Customer Segments: Heavy, Medium, Light cohorts with unique churn + usage

Acquisition Modeling: Add new users monthly with compounding growth

Pricing Levers: Adjust Base $, API $, Seat $, GB $ and Minimum Commit

Interactive Analysis: Sliders for real-time scenario testing in Google Colab

Executive KPIs: ARR, ARPU, Uplift %, LTV, CAC, Payback

Investor-Ready Visuals: Clear ARR trajectory charts with uplift % highlights

How to Run

Install requirements

pip install numpy pandas matplotlib ipywidgets


(Optional for PDF reporting)

pip install reportlab


Open the notebook

Google Colab: upload SaaS_ARR_Pricing_Simulator.ipynb

Jupyter Notebook: run locally

Run the cells (Blocks 1–6 for base model, Block 7 unified interactive sliders).

Use sliders to adjust:

Customer mix (Heavy/Medium/Light %)

Pricing (Base, API, Seat, GB, Minimum Commit)

Acquisition (New Users/month, Growth Rate)

Technologies Used

Python (numpy, pandas)

Data Visualization: matplotlib, ipywidgets (interactive charts)

SaaS Finance Concepts: ARR, LTV, CAC, Payback

(Optional) ReportLab for PDF export
