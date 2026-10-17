# Hi, I'm Allan 👋

**Analytics Engineer** based in São Paulo, Brazil. I turn messy, high-volume data into models that business teams can trust and act on.

I've spent the last 7 years working with data. Since 2021 I've been at **PagBank**, one of Brazil's largest digital banks, where I write and optimise SQL on Amazon Redshift against data covering millions of customers and their daily transactions. I also manage and lead a small analytics team there. My work covers A/B testing, campaign measurement, cost per channel and Salesforce Marketing Cloud journeys. Before that I was a Data Analyst at **RankMyAPP**.

Over the last year I've been moving toward analytics engineering. I mean dbt, tests and version control: the things that make a query you wrote six months ago still trustworthy today. This profile is where I'm putting that into practice.

I also co-founded **Appetiva**, a small software studio. Our main product is a white-label platform for short-term rental management:

- **Database-first backend:** PostgreSQL on Supabase, with the business rules in PL/pgSQL RPCs and triggers across 30 versioned migrations.
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

**Currently building with:** Airflow, BigQuery, Docker, GitHub Actions.

## Featured projects

### [financas-pessoais](https://github.com/AllanDionizio/financas-pessoais)
An end-to-end analytics engineering project. It covers six years of household finance data, modeled with dbt into a star schema, tested in CI and served through an Evidence dashboard. The same dbt project runs on DuckDB locally and on BigQuery in the cloud.

`dbt` · `DuckDB` · `BigQuery` · `Evidence` · `GitHub Actions`

<!--### [fin-data-platform](https://github.com/AllanDionizio/fin-data-platform)
A batch data platform for crypto market data. Airflow orchestrates ingestion from the CoinGecko API, loading into the warehouse and dbt transformations, all running in Docker.

`Airflow` · `Python` · `Docker` · `dbt`
-->
## Get in touch

- LinkedIn: [linkedin.com/in/allandionizio](https://www.linkedin.com/in/allandionizio/)
- Email: [allan.dionizio@outlook.com](mailto:allan.dionizio@outlook.com)

Open to remote **Analytics Engineer** and **Data Engineer** roles with teams in the Americas.
