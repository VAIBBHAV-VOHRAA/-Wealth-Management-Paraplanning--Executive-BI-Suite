# 📊 Wealth Management & Paraplanning Firm: Executive AUM & Advisor Performance Analytics

## 📌 Project Overview
In boutique paraplanning and wealth management practices, maintaining portfolio health, tracking capital movements, and preventing client attrition are paramount. This project delivers an executive-grade Business Intelligence solution developed in Microsoft Power BI for a paraplanning firm overseeing $20.0M in Assets Under Management (AUM) across 21 High-Net-Worth (HNW) clients and 5 wealth advisors.

## Dashboard Previews

### 📊 Page 1: Executive AUM Overview📈

![Executive Overview Dashboard](https://github.com/VAIBBHAV-VOHRAA/-Wealth-Management-Paraplanning--Executive-BI-Suite/blob/main/para%20plan%20page%201%20.png?raw=true)


### Page 2: Advisor Performance & Client Retention
![Advisor Performance & Client Retention Dashboard](https://github.com/VAIBBHAV-VOHRAA/-Wealth-Management-Paraplanning--Executive-BI-Suite/blob/main/para%20plan%20page%202.png?raw=true)


## 🛠 2. Tech Stack 

*   **SQL:** Data extraction and preliminary exploration .
*   **Power BI Desktop:** Dashboard creation, data visualization, and reporting.
*   **Power Query:** Data cleaning, transformation, and shaping.
*   **DAX (Data Analysis Expressions):** Creating calculated columns and measures for advanced metrics (e.g., Profit Margin %, Average Revenue per Store, Days of Supply).
*   **Data Modeling:** Establishing relationships between sales, products, stores, and inventory tables.
*   **File Formats:** `.pbix` for development and `.png` for dashboard previews.


## 📂 3. Data Source

Platform: Kaggle

Domain: Private Banking & Wealth Management Client Portfolios

Dataset Scope:

21 Client Accounts with granular monthly balance histories.

5 Wealth Advisors: Victoria Sterling, Alexander Hayes, David O'Connor, Marcus Vance, and Eleanor Hughes.

6-Month Performance Tracking: January through June with monthly valuation snapshots.

Asset Allocation: Equity, Fixed Income, Cash & Cash Equivalents.

Transaction Logs: Granular monthly capital inflows (deposits) vs. outflows (redemptions).



## 🎯 4. Features & Highlights

### A. Business Problem
Advisor Concentration Risk: Executive leadership had no clear visibility into whether firm AUM was evenly distributed or dangerously dependent on a single senior advisor.

Delayed Outflow Detection: Capital withdrawals were uncovered weeks after departure, preventing paraplanners from intervening with proactive retention strategies.

Asset Allocation Drift: Lack of automated cross-portfolio asset classification to ensure client risk profiles aligned with investment policy mandates.

### B. Goal of the Dashboard

Provide managing partners with a 5-second pulse check on firm AUM, net monthly momentum, and asset diversification.

Deliver an operational diagnostic tool to evaluate individual advisor net flows and isolate specific flight-risk client accounts.

### C. Dashboard Walkthrough
🔹 Page 1: Executive AUM Overview (Macro Strategy)

Executive KPI Banners:

Total Clients: 21

Total AUM (Current Month - CM): $20M

Total AUM (Prior Month - PM): $19.74M

MoM Growth %: -0.15%

Monthly AUM Movement (6-Month Area Chart):

Displays macro portfolio valuation across H1, highlighting a sharp Q1 drawdown bottoming out in March at ~$17.8M, followed by an aggressive Q2 capital recovery back to $20.0M in May/June.

AUM Breakdown by Asset Class (Donut Visual):

Equity: 55.02% ($11.0M)

Fixed Income: 30.83% ($6.17M)

Cash & Equivalents: 8.49% ($1.70M)

AUM by Wealth Advisor (Ranked Bar Chart):

Victoria Sterling: $7.9M

Alexander Hayes: $4.4M

David O'Connor: $4.3M

Marcus Vance: $2.0M

Eleanor Hughes: $1.2M

Interactive Slicers: Universal filtering by Month, AdvisorName, and Year.


🔹 Page 2: Advisor Performance & Client Retention (Diagnostic & Audit)

Advisor Performance Scorecard (Matrix Grid):

Ranks advisors by Total AUM, Total Clients, MoM Growth %, and Average AUM.

Visual status indicator highlights top expander (Marcus Vance: +9.64% MoM) versus contracted books (Alexander Hayes: -8.01% MoM).

Capital Flow Dynamics by Advisor (Bi-Directional Bar Chart):

Compares gross monthly inflows (new capital) against outflows (redemptions).

Shows high liquidity turnover: Alexander Hayes generated $1.04M in gross inflows but faced $0.42M in outflows.

Client Portfolio Retention & Outflow Risks (Contracted Accounts Table):

Sorts individual accounts by contraction percentage to isolate flight risk.

Pinpoints the primary firm-wide risk driver: Ananya Raja (-23.53% contraction, falling from $1.70M to $1.30M) under Alexander Hayes.


D. Business Impact & Key Analytical Insights

Key-Person & Concentration Vulnerability:

Victoria Sterling manages ~$7.88M (~40% of the entire firm's AUM) across only 4 clients, with an average account balance of $1.97M. A departure of any single Sterling client poses an existential revenue shock to the practice.

Root Cause Analysis on Performance Drops:

While Alexander Hayes logged the sharpest contraction (-8.01% MoM), flow decomposition reveals he led the firm in new inflows ($1.04M). The net loss was driven entirely by a single $400K redemption from Ananya Raja.

High-Velocity Growth Driver:

Marcus Vance demonstrated the highest expansion velocity (+9.64% MoM), maintaining strong client retention and net-positive capital addition ($0.48M inflow vs. $0.32M outflow).

Strategic Recommendations for Firm Leadership:

Targeted Retention Review: Schedule an immediate retention touchpoint between Alexander Hayes, the senior paraplanner, and client Ananya Raja to address the drivers behind the 23.5% capital reduction.

Client Allocation Balancing: Route incoming prospects to Marcus Vance and Eleanor Hughes to build capacity and hedge key-person dependency away from Victoria Sterling.


