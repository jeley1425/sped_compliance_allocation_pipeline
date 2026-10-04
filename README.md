Special Education District Compliance Audit & Resource Allocation Pipeline

Business Case Overview
School districts face strict state and federal compliance timelines under the Individuals with Disabilities Education Act (IDEA). Failure to complete evaluations within mandatory windows results in state sanctions, loss of funding, and severe legal liabilities. This project implements a data-driven compliance audit and resource optimization pipeline. It ingests active student evaluation logs, constructs a composite Legal Risk Score, groups campuses into clear operational risk tiers using unsupervised machine learning, and executes a prescriptive reallocation matrix to target caseworker resources precisely where district financial exposure is highest.

Technical Architecture & Workflow
The system utilizes a 5-phase data infrastructure lifecycle built in Python:

- Phase 1: Compliance Ingestion Schema – Formatted an asset registry tracking 450 active student case timelines across 15 separate district campuses.
- Phase 2: Feature Engineering & Risk Indexing – Developed a composite Legal Risk Score mapping evaluation delay lengths and workload variables directly to vectorized financial litigation liabilities ($7,500 baseline per delayed file).
- Phase 3: Unsupervised Segmentation (K-Means Clustering) – Aggregated data to a campus level and applied a K-Means algorithm to automatically isolate school buildings facing severe systemic backlogs.
- Phase 4: Prescriptive Allocation Optimization – Built an automated resource triage schedule that identifies critical-tier campuses and triggers caseworker reassignments to protect public funds.
- Phase 5: Executive Dashboard Synthesis – Visualized campus-level risk scores against total financial liabilities, color-coded by institutional action thresholds.

Tech Stack Used
- Language: Python 3
- Environment: Google Colab
- Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
