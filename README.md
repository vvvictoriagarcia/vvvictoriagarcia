# Victoria García Ambertin

**Data Analyst & Software Developer** — Buenos Aires, Argentina (remote)

I work across the full data cycle: collecting and cleaning data, modeling and analyzing it, and turning it into dashboards, internal tools and automated workflows that support business decisions. Currently open to data analyst and junior developer positions.

[Website](https://victoriagarciaambertin.com) · [LinkedIn](https://ar.linkedin.com/in/victoria-garcia-ambertin-054607201) · [Email](mailto:vic.gar.amb@gmail.com)

---

## Experience

**AI Specialist — Good Harbor** (commercial real estate, Boston) · first person in the role · Remote · 2026–present

- **CapEx portfolio dashboard:** FastAPI app that consolidates 14 per-property CapEx sheets into budget-vs-actual views with drill-down by property and category. Deployed on Google Cloud Run with a scheduled Cloud Run Job for the daily refresh, snapshots in Cloud Storage, access restricted to the company domain via IAP, and embedded in Monday.com behind session-token verification.
- **Leasing outreach tool:** FastAPI web app on Cloud Run that suggests target uses for a vacant unit, sources nearby businesses by radius band via the Google Places API, ranks them and builds AI-generated business profiles (Anthropic API) with CSV export for the leasing team. Business enrichment with Scrapy + Zyte.
- **Acquisitions owner profiling:** Google Apps Script pipeline over Google Sheets that builds property-owner profiles and drafts email/SMS outreach with the Claude API.
- **Monday.com recurring tasks:** Sheet-driven automation that creates recurring tasks on a chosen board and assigns owners.
- **Internal platform audit:** product, infrastructure, security and scalability review of the company's internal training platform, delivered as a prioritized issue list.
- **Website security and performance:** HTTPS enforcement, security headers and CSP, CAA records and email-authentication review (SPF/DKIM/DMARC) on a WordPress/LiteSpeed site; diagnosed hosting process limits and plugin conflicts.
- **Delivery and adoption:** run requirements sessions with stakeholders, ship in validated phases within the EOS framework (weekly L10 meetings, quarterly Rocks with SMART metrics), and train end users on the tools.
- **Engineering practices:** secrets kept out of source control (environment variables, .gitignore, key rotation), least-privilege IAM on Google Cloud, and moving team projects into the company GitHub organization with connected deployments.

**Independent — Automation services** · Buenos Aires

- Build chatbots, automation workflows and websites for small businesses, including a Kommo CRM chatbot for lead handling.
- **Lead generator:** web app built on Google Apps Script and the Claude API.
- **Financial dashboard** for portfolio performance reporting.
- Built a personal-brand website with Notion as headless CMS, YouTube Data API integration and a [business calculator](https://fiorent.com.ar/calculadora-ysivendo); migrated blog content into Notion via API.

## Data Analysis

- **Data preparation:** cleaning and joining messy operational sources (bank statement exports, per-property spreadsheets, CRM and API data) into analysis-ready tables in SQL, pandas and Google Sheets.
- **Business and financial analysis:** budget vs. actual tracking for capital expenditures, cost accounting, discounted cash flow valuation and financial calculus applied to real cases.
- **Exploratory analysis:** trends, seasonality, regional and customer-segment breakdowns on e-commerce and logistics datasets (BigQuery, Python, Tableau).
- **Dashboards and reporting:** KPI dashboards in Power BI, Tableau, Streamlit and custom web apps, built for non-technical decision makers.
- **Machine learning:** supervised classification (churn prediction, model comparison by ROC-AUC), clustering, SVM and neural networks (Python and R).
- **Data quality:** auditing production data for errors, e.g. detecting false loss figures caused by an unhandled CEDEAR ratio change in an investment module.

## Selected Projects

| Project | Description | Stack |
|---|---|---|
| [dcf-valuation-model](https://github.com/vvvictoriagarcia/dcf-valuation-model) | Discounted cash flow valuation of Microsoft from historical financial statements | Python, pandas |
| [sales-eda](https://github.com/vvvictoriagarcia/sales-eda) | Exploratory analysis of 5,000 e-commerce orders: seasonality, regional and segment trends | Python, pandas, seaborn |
| [sales-dashboard](https://github.com/vvvictoriagarcia/sales-dashboard) | Interactive BI dashboard with multi-dimensional filtering | Streamlit, Plotly |
| [churn-prediction](https://github.com/vvvictoriagarcia/Churn-prediction) | Classification pipeline comparing three models; best ROC-AUC 0.744 | scikit-learn |
| [fintrack](https://github.com/vvvictoriagarcia/fintrack) | Personal finance web app with transaction tracking and category breakdown | React, TypeScript, Recharts |
| fluir | Personal finance app for young Argentines with a freemium model and an investment module for CEDEARs (local depositary receipts) | Next.js, Supabase |
| automkt | B2B multichannel lead automation (WhatsApp, Instagram, email) with per-client data isolation | n8n, Claude API, Supabase |
| olist-logistics-analysis | Delivery and logistics analysis of the Olist Brazilian e-commerce dataset (university team project) | BigQuery, Python, Tableau |

## Technical Skills

- **Languages:** Python, SQL, TypeScript, JavaScript, R, Google Apps Script, HTML, CSS
- **Data & BI:** pandas, scikit-learn, BigQuery, Power BI, Tableau, Streamlit, Plotly
- **Backend / Web:** FastAPI, Next.js, React, Supabase, WordPress
- **Cloud & DevOps:** Google Cloud (Cloud Run, Cloud Run Jobs, Cloud Storage, IAP, gcloud CLI), Git / GitHub, Vercel, basic DNS and web hosting (DNS records, email authentication)
- **AI / LLM:** Claude API (Anthropic), OpenAI API, Claude Code, prompt design for structured output
- **Integrations & Automation:** n8n, REST APIs, Google Places API, Google Workspace APIs, Monday.com API, Notion API, YouTube Data API, Scrapy + Zyte, Salesforce, Kommo CRM

## Education

- **UCEMA** — Double degree in Business Analytics and Digital Business (in progress)
- **ITBA** — Certification in Artificial Intelligence: machine learning, NLP and computer vision

## Languages

- Spanish — native
- English — Advanced (professional working daily with a US team)
