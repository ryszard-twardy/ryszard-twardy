Data analyst in Erlangen, Germany. SQL and Power BI, with Python for the parts a spreadsheet cannot do. Nineteen years of geospatial analysis and data management before that, which is where the discipline comes from: standardise the sources, document the method, report only what can be traced.

Two public repositories, built as one system: the analytics, and the generator that produced its input.

**[rfm-customer-segmentation-kupferkanne](https://github.com/ryszard-twardy/rfm-customer-segmentation-kupferkanne)** – customer analytics on synth-datagen output for a fictional brand: 14,967 customers, nine European markets. Ten-step BigQuery SQL pipeline plus two analytical views, twelve-table Power BI semantic model (PBIP/TMDL) with 105 DAX measures, six report pages plus a customer drillthrough, and a randomised holdout pilot design that tests the discount rate and the allocation before either changes the playbook. Design decisions logged as ADRs. [Case study](https://ryszard-twardy.github.io/kupferkanne/) · [Live Power BI report](https://ryszard-twardy.github.io/kupferkanne/report/). Release: [v1.3.0](https://github.com/ryszard-twardy/rfm-customer-segmentation-kupferkanne/releases/tag/v1.3.0) · Notebooks: [GitHub Pages](https://ryszard-twardy.github.io/rfm-customer-segmentation-kupferkanne/).

**[synth-datagen](https://github.com/ryszard-twardy/synth-datagen)** – Python CLI that generates multi-table business datasets (retail, SaaS, fintech, logistics, pharma) with referential integrity, deterministic seeding and data-quality defects you inject on purpose: duplicate orders, cents-format inconsistency, orphan keys, type drift. MIT, CI on Python 3.11 to 3.13, [documentation](https://ryszard-twardy.github.io/synth-datagen/).

A third project, a master data cleansing pilot on 26,253 SAP-exported ship-to records for a building-materials client, is confidential. Case notes on request.

I use AI-assisted tooling for code and drafts. The design, the tests and the responsibility for what ships are mine, and the repositories are public so that can be checked.

Portfolio: [ryszard-twardy.github.io](https://ryszard-twardy.github.io/) · Contact: [LinkedIn](https://www.linkedin.com/in/ryszard-twardy/) · r.twardy@proton.me
