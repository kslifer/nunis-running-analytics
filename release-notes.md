# Nunis Running Analytics: Release Notes
## Major Releases
- In Development: Automated provisioning of GCP services with a Terraform pipeline / Containerization of the Cloud Function
- June 27, 2020: [Cloud Function Data Ingestion MVP](#cloud-function-data-ingestion-mvp)


## Detailed Release Notes
### Cloud Function Data Ingestion MVP
A functional MVP of the process to ingest data from the Strava API into BigQuery has been completed and released in the [nunis-ingest-gcf](https://github.com/kslifer/nunis-ingest-gcf) repo.

This bootstraps some of the expected long-term foundation of the solution, but lacks all of the desired automation. Refactoring is unavoidable, and will be developed and released in a separate repo.
