# IT Service Operations Dashboard

Web prototype of a Power BI dashboard layout for incident and problem management, built with HTML, CSS and Chart.js. It uses sample data for a fictional company (Apex Financial Services).

## What it shows
- KPIs with change vs the same period last year: incidents opened and resolved, open backlog, SLA met, mean time to resolve, open problem tickets
- Weekly and monthly incident trend, this year vs same time last year
- Incidents by category, this year vs last year
- How incidents were resolved: permanent fix, workaround, restart, pending
- Repeating issues linked to problem tickets, with status and resolution
- Problem management pipeline: raised, RCA, workaround, permanent fix, closed
- Impact of permanent fixes: repeat incidents avoided, support effort saved

## Live demo
https://swachavh.github.io/PowerBI-Portfolio-Dashboards/06-IT-Service-Operations-Dashboard/

## Run locally
Open `index.html` in a browser. No build step is needed.

## Power BI version
The same layout can be rebuilt in Power BI Desktop with a Tickets fact table and Date, Priority and Team dimensions. Key measures: Total Tickets, Open Backlog, SLA Met %, Avg Resolution Hrs, Repeat Incident Rate, and YoY change using SAMEPERIODLASTYEAR.

## Data
All figures are sample data for illustration only. No real company data is used.

## Tech
HTML, CSS, JavaScript, Chart.js
