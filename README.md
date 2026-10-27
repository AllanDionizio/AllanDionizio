# Hi, I'm Allan 👋

**Analytics Engineer** based in São Paulo, Brazil. I turn messy, high-volume data into models that business teams can trust and act on.

I've spent the last 7 years working with data. Since 2021 I've been at **PagBank**, one of Brazil's largest digital banks, where I write and optimize SQL on Amazon Redshift against data covering millions of customers and their daily transactions. I also lead a small analytics team there. My work covers A/B testing, campaign measurement, cost per channel and the performance of customer journeys built in Salesforce Marketing Cloud. Before that I was a Data Analyst at **RankMyAPP**.

Over the last couple years I’ve been bringing engineering practices into my analytics work. I mean dbt, tests and version control: the things that make a query you wrote six months ago still trustworthy today. This profile is where I'm putting that into practice.

I also co-founded **Appetiva**, a small software studio. Our main work so far is a management platform for a short-term rental operator.

## What I work with

| Area | Tools |
| --- | --- |
| Modeling & transformation | SQL, dbt, dimensional modeling (Kimball) |
| Databases & engines | PostgreSQL (PL/pgSQL), DuckDB, Amazon Redshift |
| Cloud & pipelines | Google Cloud Run, Cloud Scheduler, Gmail API, Supabase, Docker, GitHub Actions |
| Languages | SQL, Python, TypeScript |
| BI & analytics | Power BI, Evidence |
| Domain | CRM, marketing measurement, customer analytics, fintech, short-term rentals |

**Currently learning:** Airflow.

## Featured projects

### [personal-finance-analytics](https://github.com/AllanDionizio/personal-finance-analytics)
An end-to-end analytics engineering project on six years of household finance data. Python ingests the spreadsheets, dbt models them into a tested star schema on DuckDB, and an Evidence dashboard tells the story: savings rate, returns against inflation, the liquid reserve and what the future already owes. It runs on a synthetic dataset with the same layout as the real workbooks, and GitHub Actions rebuilds, tests and publishes it on every merge.

**Live:** [dashboard](https://allandionizio.github.io/personal-finance-analytics/) · [dbt docs](https://allandionizio.github.io/personal-finance-analytics/dbt-docs/)

`Python` · `dbt` · `DuckDB` · `Evidence` · `GitHub Actions`

### [airbnb-booking-pipeline](https://github.com/AllanDionizio/airbnb-booking-pipeline)
A production data pipeline, rewritten clean-room for publication. It reads Airbnb's booking and cancellation emails from Gmail, parses them, converts USD at the Brazilian central bank's PTAX rate and loads them into Postgres through SQL functions that make every email idempotent. Anything it cannot settle on its own (an unknown listing, a double booking, a cancellation) waits in a review queue for a person instead of being dropped or guessed. Regression fixtures, integration tests against Postgres in CI, a Docker image and four architecture decision records; every email and amount in it is synthetic.

`Python` · `PostgreSQL` · `Gmail API` · `Docker` · `GitHub Actions`

## Get in touch

- LinkedIn: [linkedin.com/in/allandionizio](https://www.linkedin.com/in/allandionizio/)
- Email: [allan.dionizio@outlook.com](mailto:allan.dionizio@outlook.com)

Open to remote **Analytics Engineer** and **Data Engineer** roles (UTC-3, good overlap with US time zones).
