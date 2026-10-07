# Open Data Infrastructure for Social Impact

This project explores the design of a **structured digital data infrastructure for social-impact activity reporting**, with a focus on transforming routine activity records into consistent, analysis-ready datasets.

## Data Privacy and Source Files

The original Excel dataset is **not included in this repository** due to data protection, participant privacy, and company confidentiality requirements.

Instead, this repository documents the **data structure, reporting methodology, and digitalisation approach** without exposing personal, identifiable, or commercially sensitive information.

## Data Infrastructure and Digital Reporting

The proposed reporting workflow uses structured spreadsheets and collaborative documentation tools to establish a consistent data-entry and reporting process.

**Google Sheets** and **Google Docs** are recommended where multiple contributors need to collaborate, review, and maintain records. Microsoft Excel and Word can also be used for local data preparation and documentation where appropriate.

The infrastructure is designed to support a progression from:

**Routine activity logging → Structured dataset → Data cleaning → Analysis → Visualisation → Impact reporting**

## Data Schema Design

Before entering historical or new activity records, the dataset should be designed around the **activities participants routinely engage in**.

Rather than maintaining unstructured narrative logs, activity categories should be represented as structured fields/columns. This improves:

- Data consistency
- Data validation
- Activity-level analysis
- Participant engagement measurement
- Trend identification
- Reporting automation
- Dashboard development
- Future integration with analytics and digital platforms

Example activity fields may include:

| Field | Purpose |
|---|---|
| Date | Records when the activity took place |
| Session | Identifies the specific session |
| Participant Count | Records participation volume |
| Storytelling/Reading | Captures engagement with reading activities |
| Rhymes/Singing | Captures participation in musical activities |
| Toy/Sensory Play | Records play-based engagement |
| Creative Activities | Records arts and creative participation |
| Group Play | Captures collaborative play |
| Parent/Carer Interaction | Records interaction-focused activities |
| Other Activity | Captures activities outside predefined categories |

The exact schema should be adapted to the activities routinely delivered by each organisation.

## Data Quality and Analysis

Structuring the data at the point of collection reduces the need for extensive manual transformation later. The resulting dataset can be prepared for:

- Data cleaning and validation
- Descriptive and exploratory data analysis
- Participation and engagement metrics
- Activity frequency analysis
- Trend analysis over time
- Dashboard and visualisation development
- Automated impact reporting
- Future database or API integration

The approach provides a foundation for moving from **manual reporting processes to a reusable digital reporting infrastructure**.

## Privacy-by-Design

The project follows a privacy-conscious approach by separating the **data model and reporting methodology** from sensitive source data.

No personally identifiable information or confidential organisational records are required in the public repository. Where real participant-level data is used operationally, appropriate access controls, data-minimisation practices, and organisational data-protection requirements should be applied.

## Future Development

The proposed infrastructure can be extended into a dedicated digital reporting system capable of:

1. Collecting structured activity data.
2. Validating and standardising records.
3. Automating data cleaning and transformation.
4. Generating participation and engagement metrics.
5. Producing interactive dashboards.
6. Generating impact and grant-reporting outputs.
7. Supporting longitudinal analysis of activity and participation.
8. Providing a foundation for integration with databases, APIs, and other digital platforms.

The objective is to demonstrate how **structured data architecture can convert routine social-impact activities into reusable, analysis-ready information for evidence-based reporting and decision-making**.



### Strategic Leadership Impact — Executive Summary
This is an interactive analytics dashboard built for data entry, analysis, and reporting in a social impact setting. It was designed to assess and improve early-years community engagement sessions, tracking community events and participant engagement to inform resource allocation decisions. The pipeline feeds directly into grant-ready impact reports for local event planners and funders.

### Problem Statement
A family-focused organisation needed support to manage its weekly events through digitised record-keeping, replacing paper-based logs that made consistent reporting difficult. Digitisation was needed to increase donor confidence and support evidence-based reporting, and to strengthen the organisation's position when applying for government funding and grants through its knowledge hub.

### Operational Intelligence Architecture
I architected and deployed a centralised data pipeline and analytics dashboard to move the organisation from paper-based logging to a digital infrastructure. This dashboard serves as a business intelligence tool, giving local authorities and institutional donors access to verifiable, real-time impact metrics.

<p align="center">
  <img width="1218" height="685" alt="Stay and Play 6-Month Performance Dashboard" src="https://github.com/user-attachments/assets/5a818dd8-d85a-4496-8e33-ed7c09af56f3" />
</p>
<p align="center"><em>Stay & Play — 6-Month Performance Dashboard</em></p>

### Technical Stack
| Layer | Tooling |
|---|---|
| **Data ingestion** | Structured data collection system built on Excel and Google Sheets, enabling collaborative, multi-user data entry across sites |
| **Data engineering** | Power BI used for data modelling and analysis |
| **Visualisation layer** | Responsive dashboard tracking activity and engagement dynamics, programme resource deployment, and early-years developmental indicators |

### Measurable Community Impact
- **Programme Support Lead** — Demonstrated the ability to build data infrastructure as a product from the ground up, from data strategy and schema design through to final visualisation.
- **Digital Innovation** — Applied commercial-grade product analytics methodology to scale the operational capacity of a grassroots community initiative.
- **Data-Driven Insight** — Gave potential donors automated, visual impact insight, removing the organisation's reliance on manual reporting.
