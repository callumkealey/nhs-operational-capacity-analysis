# NHS Operational Capacity Analysis

Python analysis of NHS appointment demand, capacity utilisation, service performance and missed appointments, completed as part of the LSE Data Analytics Career Accelerator.

## Business problem

The project explores how operational data can support planning and service improvement across NHS appointment networks. The analysis focuses on four questions:

- Is available capacity sufficient to meet appointment demand?
- How are appointments distributed across service settings and professional groups?
- What level of operational inefficiency is created by missed appointments?
- Could social-media trends provide supplementary indications of service pressure?

## Analytical approach

### Python

- Data ingestion and validation across multiple operational datasets
- Missing-value and data-quality checks
- Date standardisation with `pandas`
- Monthly aggregation using `groupby()`
- Exploratory data analysis
- Capacity and utilisation analysis against a benchmark
- Service-setting and professional-group comparisons
- Appointment attendance analysis
- Hashtag and keyword frequency analysis
- Stakeholder-focused visualisation

## Key findings

- Average daily appointment utilisation was approximately 800,000–1 million against a 1.2 million capacity benchmark, indicating limited headroom during higher-demand periods.
- General Practice was the dominant service setting in the available data.
- Around one million appointments were missed each month, representing a persistent operational inefficiency.
- Improved reminders, easier cancellations and alternative appointment modes were identified as potential ways to reduce missed appointments and improve capacity utilisation.
- Social-media trends may provide supplementary early-warning information about service pressure, although the available data was not sufficiently NHS-specific to treat this as a direct operational indicator.

## Files

- [`nhs_operational_capacity_analysis.ipynb`](nhs_operational_capacity_analysis.ipynb) – cleaned Python notebook containing the analysis and visualisations
- [`nhs_operational_capacity_report.pdf`](nhs_operational_capacity_report.pdf) – technical report covering methodology, findings and recommendations

## Tools

Python • pandas • matplotlib • seaborn • Excel • Data cleaning • Operational analytics • Data visualisation

## Note

This repository is presented as a portfolio example of my analytical workflow and problem-solving approach. The source datasets are not included.