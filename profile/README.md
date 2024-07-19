<img src="https://avatars.githubusercontent.com/u/173281245?s=200&v=4" height="100" width="100" style="border-radius:50%;overflow: hidden;">

# LibreConnect Platform
LibreConnect Platform is an open-source project aimed at improving the healthcare sector by facilitating the decentralisation and centralisation of medical data. The platform enables hospitals and healthcare professionals to collaborate effectively by sharing patient medical records, while integrating and analysing data from various external sources to improve the quality of care and data science research.

## Current problem
Hospitals and healthcare structures currently have their own IT infrastructures and systems, which makes it difficult to decentralise data and collaborate between different structures. This limits the effectiveness of care and complicates patient management.


## Project objectives

1. Decentralisation of medical data:
  - Enable hospitals and healthcare professionals to access patients' medical records via a secure, decentralised platform.
  - Facilitate collaboration between different healthcare structures to improve patient care.

2. Centralising external data:
  - Integrate data from different healthcare applications and devices (Apple Health, Medtronic, LibreLink, etc.).
  - Analyse this data to create predictive models and carry out data-science research to improve care and treatment.

## Main Features
- **Secure Access to Medical Records**: Use of modern technologies to guarantee the security and confidentiality of medical data shared between healthcare structures, with the use of security levels for access to certain data (taking into account the patient's confidence, the status of the healthcare professional, etc.).
- **External Data Integration**: Connection with various healthcare applications and devices to centralise patient data.
- **Data Analysis and Modelling**: Analysis of various data vectors to establish correlation and predict certain problems (e.g. blood glucose, bolus/basal, heart rate, sporting activity).
- **Intuitive User Interface**: Simple, ergonomic interface for ease of use by healthcare professionals.

## Architecture / technologies information
- **Micro-services architecture**
- **Infrastructure**: Kubernetes, Helm, Github Actions, Vault
- **Frontend**: React, NX, Typescript
- **Security**: Keycloak, OIDC, Oauth2
- **Languages**: Rust ([Actix.rs](https://actix.rs/)), NodeJS ([AdonisJS](https://adonisjs.com/))
- **Database**: PostgreSQL
