Data analyst in Erlangen, Germany. SQL and Power BI, with Python for the parts a spreadsheet cannot do. Nineteen years of geospatial analysis and data management before that, which is where the discipline comes from: standardise the sources, document the method, report only what can be traced.

Two public repositories, built as one system: the analytics, and the generator that produced its input.

**[rfm-customer-segmentation-kupferkanne](https://github.com/ryszard-twardy/rfm-customer-segmentation-kupferkanne)** – customer analytics on synth-datagen output for a fictional brand: 15,000 customers, nine European markets. Nine-step BigQuery SQL pipeline, twelve-table star-schema Power BI model (PBIP/TMDL) with 109 DAX measures, six report pages plus a customer drillthrough, and a recommendation on where the win-back budget should go. Design decisions logged as ADRs. [Live Power BI report](https://app.powerbi.com/view?r=eyJrIjoiM2JlNGExNDMtN2U0ZS00MmYxLWE4M2ItYzMzZjhkY2ZhZWM0IiwidCI6ImNhYTk3MmQ2LWFhYTctNDE0NS1iMTgyLTA2NzkzZWY5NWVhNiJ9&pageName=46bfe20b629145b40be4).

**[synth-datagen](https://github.com/ryszard-twardy/synth-datagen)** – Python CLI that generates multi-table business datasets (retail, SaaS, fintech, logistics, pharma) with referential integrity, deterministic seeding and data-quality defects you inject on purpose: duplicate orders, cents-format inconsistency, orphan keys, type drift. MIT, CI on Python 3.11 to 3.13, [documentation](https://ryszard-twardy.github.io/synth-datagen/).

A third project, a master data cleansing pilot on 26,256 SAP ship-to records for a building-materials client, is under NDA. Case notes on request.

I use AI-assisted tooling for code and drafts. The design, the tests and the responsibility for what ships are mine, and the repositories are public so that can be checked.

Projects and contact: [ryszard-twardy.github.io](https://ryszard-twardy.github.io/) · [LinkedIn](https://www.linkedin.com/in/ryszard-twardy/) · r.twardy@proton.me
