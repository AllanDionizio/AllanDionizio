# Hi, I'm Allan 👋

**Analytics Engineer** based in São Paulo, Brazil. I turn messy, high-volume data into models that business teams can trust and act on.

I've spent the last 7 years working with data. Since 2021 I've been at **PagBank**, one of Brazil's largest digital banks, where I write and optimize SQL on Amazon Redshift against data covering millions of customers and their daily transactions. I also lead a small analytics team there. My work covers A/B testing, campaign measurement, cost per channel and the performance of customer journeys built in Salesforce Marketing Cloud. Before that I was a Data Analyst at **RankMyAPP**.

Over the last couple years I’ve been bringing engineering practices into my analytics work. I mean dbt, tests and version control: the things that make a query you wrote six months ago still trustworthy today. This profile is where I'm putting that into practice.

I also co-founded **Appetiva**, a small software studio. Our main work so far is a management platform for a short-term rental operator:

- **Database-first backend:** PostgreSQL on Supabase, with the business rules in PL/pgSQL RPCs and triggers across versioned migrations.
- **Ingestion pipeline:** a Python service on Google Cloud Run, triggered by Cloud Scheduler, reads Airbnb booking confirmations through the Gmail API and parses guests, dates, cleaning fees, price adjustments and platform fees.
- **Safe writes:** parsed bookings land through an upsert RPC as drafts. Incomplete records go to a pending table instead of failing silently, and nothing is confirmed until a person approves it in a review queue.
- **Front-end:** Next.js 14 and TypeScript, talking directly to Supabase.

## What I work with

| Area | Tools |
| --- | --- |
| Modeling & transformation | SQL, dbt, dimensional modeling (Kimball) |
| Databases & engines | PostgreSQL (PL/pgSQL), DuckDB, Amazon Redshift |
| Cloud & pipelines | Google Cloud Run, Cloud Scheduler, Gmail API, Supabase |
| Languages | SQL, Python, TypeScript |
| BI & analytics | Power BI, Evidence |
| Domain | CRM, marketing measurement, customer analytics, fintech, short-term rentals |

**Currently learning:** Airflow, Docker, GitHub Actions.

## Featured projects

### [personal-finance-analytics](https://github.com/AllanDionizio/personal-finance-analytics)
An end-to-end analytics engineering project on six years of household finance data. Python ingests the spreadsheets, dbt models them into a tested star schema on DuckDB, and an Evidence dashboard tells the story: savings rate, returns against inflation, the liquid reserve and what the future already owes. It runs on a synthetic dataset with the same layout as the real workbooks, and GitHub Actions rebuilds, tests and publishes it on every merge.

**Live:** [dashboard](https://allandionizio.github.io/personal-finance-analytics/) · [dbt docs](https://allandionizio.github.io/personal-finance-analytics/dbt-docs/)

`Python` · `dbt` · `DuckDB` · `Evidence` · `GitHub Actions`

## Get in touch

- LinkedIn: [linkedin.com/in/allandionizio](https://www.linkedin.com/in/allandionizio/)
- Email: [allan.dionizio@outlook.com](mailto:allan.dionizio@outlook.com)

Open to remote **Analytics Engineer** and **Data Engineer** roles (UTC-3, good overlap with US time zones).
