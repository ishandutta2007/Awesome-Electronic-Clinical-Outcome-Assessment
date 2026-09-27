# Awesome-Electronic-Clinical-Outcome-Assessment

## Top Electronic Clinical Outcome Assessment (eCOA) Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Patient-Reported Outcomes, Clinical Outcome Assessments & Decentralized Trial Data Capture*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Electronic Clinical Outcome Assessment (eCOA)**. These tools help clinical research teams collect patient-reported outcomes (ePRO), clinician-reported outcomes (ClinRO), observer-reported outcomes (ObsRO), and performance outcomes (PerfO) in clinical trials, registries, and real-world evidence studies.



**Examples** include Clario eCOA, Signant Health, YPrime, Medable, Kayentis, THREAD Research, CRF Health, IQVIA eCOA, ERT, and eClinical Solutions (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom eCOA workflows, and transparent clinical data management — ideal for academic research centers, non-profits, and organizations that need full control over sensitive patient data without per-patient SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Clario eCOA](https://clario.com/)**  

  Leading eCOA provider formed from the merger of ERT and Bioclinica. Provides ePRO, ClinRO, ObsRO, and PerfO instruments with device provisioning, patient support, and regulatory compliance. Scientific expertise in endpoint validation and translation.



- **[Signant Health](https://www.signanthealth.com/)**  

  Clinical outcome assessment specialist with deep expertise in eCOA, eConsent, and ePRO. Known for scientific rigor in instrument design, linguistic validation, and rater training across neuroscience, psychiatry, and pain research.



- **[YPrime](https://www.yprime.com/)**  

  eClinical technology platform providing eCOA, ePRO, IRT, and clinical data management. Known for rapid deployment, flexible solutions, and strong customer support.



- **[Medable](https://www.medable.com/)**  

  Decentralized clinical trial platform with eCOA, ePRO, eConsent, and remote data collection. BYOD (bring your own device) support and patient-centric trial design.



- **[Kayentis](https://www.kayentis.com/)**  

  eCOA specialist with expertise in ophthalmology, respiratory, and dermatology. Provides electronic diaries, questionnaires, and patient engagement tools.



- **[THREAD Research](https://www.threadresearch.com/)**  

  Decentralized clinical trial platform with ePRO, eCOA, remote patient monitoring, and virtual visit tools. Focused on bringing clinical research into patient homes.



- **[CRF Health](https://www.crfhealth.com/)**  

  eCOA and ePRO pioneer (now part of Signant Health). Early innovator in electronic clinical outcome assessment with global reach.



- **[IQVIA eCOA](https://www.iqvia.com/)**  

  eCOA platform within IQVIA's clinical research ecosystem. Provides ePRO, eCOA, eConsent, and patient engagement integrated with IQVIA's broader data and analytics capabilities.



- **[ERT](https://www.ert.com/)**  

  eCOA and cardiac safety specialist (now part of Clario). Provides ePRO, eCOA, respiratory endpoints, and imaging solutions with scientific consulting.



- **[eClinical Solutions](https://www.eclinicalsol.com/)**  

  eClinical data management platform (elluminate) supporting eCOA and ePRO data integration, analysis, and reporting across clinical trials.



## Open-Source GitHub Projects



- **[OpenClinica Participate](https://docs.openclinica.com/)**  

  Participant-facing module within the OpenClinica EDC platform providing **ePRO and eCOA** capabilities. Device-agnostic solution allows participants to complete questionnaires and diaries anywhere, anytime **without app installation** — accessed via web browser on computer, tablet (iPad), or smartphone (iPhone). Features just-in-time notifications and reminders via SMS or email, offline data capture capability, and Public URL forms for self-registration. Data entered offline automatically uploads when device reconnects. OpenClinica Community Edition is open-source; Participate module may require enterprise licensing .



- **[LibreClinica](https://github.com/reliatec-gmbh/LibreClinica)**  

  Community-driven fork of OpenClinica providing GCP-compliant EDC with **ePRO/eCOA support via OpenRosa API backend**. This integration enables mobile data collection through the **ODK (Open Data Kit) ecosystem**, allowing patients to complete questionnaires on Android devices offline and sync when connectivity is available. Supports full audit trails, electronic signatures, discrepancy management, and CDISC ODM-XML export. **LGPL-3.0**, Java-based, actively maintained .



- **[REDCap](https://projectredcap.org/)**  

  Research Electronic Data Capture platform used by over 1.6 million researchers at 6,000+ institutions in 150+ countries. **Free for non-profit organizations** (REDCap Consortium). Supports ePRO/eCOA through surveys, and the **REDCap Mobile App** enables offline data collection on iOS and Android devices with sync-back capability. **MyCap** is a companion participant-facing mobile app (standard in REDCap v13.0+) that captures patient-reported outcomes via customizable surveys and active tasks using device sensors, with automatic sync when online. Supports participant engagement features including messaging and announcements .



- **[JTrack](https://www.fz-juelich.de/de/inm/inm-7/leistungen/tools/jtrack)**  

  Open-source digital biomarker platform from Forschungszentrum Jülich for **remote monitoring and Ecological Momentary Assessment (EMA)**. Three components: **JTrack Social** (passive smartphone sensor data collection and active annotation), **JTrack EMA+** (questionnaire-based data collection), and server infrastructure for centralized data storage. Enables researchers to collect digital phenotyping data including smartphone usage, sensor data, self-reports on daily events, and ecological momentary assessments. Study-specific sensor and data combinations configurable. Participants enroll via QR code. **Open source**, privacy-compliant (GDPR) .



- **[GESIS AppKit](https://osf.io/download/mkxv9/)**  

  Open-source app-based mobile data collection infrastructure for research. Features two-tier login code system for participant management (anonymous general codes or identified personal codes), flexible scheduling of surveys (enrollment, immediate push, or scheduled delivery), and questionnaire item types including Likert scales, text, numeric, single/multiple choice, and image upload. Basic filtering logic (continue-stop). **Open source** .



- **[MyCap](https://projectmycap.org/)**  

  Customizable participant-facing mobile app **freely available to REDCap users**. Captures patient-reported outcomes and active tasks (activities performed using device sensors) based on a REDCap project. Available on iOS and Android at no cost. Supports offline data collection with automatic sync when connectivity returns. Provides a centralized study "home" for participants with secure two-way messaging and announcements. Local notifications schedule task reminders (default 8 AM in participant's timezone). Push notifications for ad hoc researcher messages. Participants join via QR code or App Link .



- **[clinicedc](https://github.com/clinicedc/)**  

  Django-based clinical trial data management framework from Botswana-Harvard AIDS Institute Partnership. Provides modular Python packages for building EDC systems. Includes **edc-qol** package providing Quality of Life instrument classes: **EQ-5D-3L** and **SF-12 Health Survey** models and forms for Django projects. Part of a comprehensive set of modules covering consent, scheduling, data collection, quality assurance, adverse events, and analysis. **GPL-3.0** .



- **[MII Kerndatensatz PRO Modul](https://github.com/medizininformatik-initiative/kerndatensatzmodul-proms)**  

  German Medical Informatics Initiative's **Patient-Reported Outcome module** FHIR Implementation Guide. Includes **PROMIS-29 Profile v2.1** (all 7 domains with scoring), **PROMIS Cognitive Function SF4a**, **PHQ-9 with T-scores**, and **EQ-5D-5L**. Provides standardized FHIR resources for PRO data exchange and integration. **CC0-1.0** license. npm package available .



- **[eq5d R Package](https://cran.r-project.org/web/packages/eq5d/)**  

  Methods for analyzing **EQ-5D** data and calculating index scores. Supports **EQ-5D-3L and EQ-5D-5L** health state descriptions (mobility, self-care, usual activities, pain/discomfort, anxiety/depression) and EQ-VAS visual analogue scale. Includes country-specific value sets for utility index calculation, crosswalk value sets, and a Shiny app for calculation and visualization via web browser using CSV or Excel files. **Open source**, CRAN package .



### Additional Strong Open-Source Options



- **EDC Platforms with ePRO**: **OpenClinica** (Participate module), **LibreClinica** (OpenRosa/ODK integration), **REDCap** (free for non-profits, MyCap companion app) .

- **Mobile Data Collection**: **ODK** (Open Data Kit ecosystem, Android-based), **JTrack** (EMA + sensor data), **GESIS AppKit** (flexible survey scheduling) .

- **PRO Instruments**: **clinicedc/edc-qol** (EQ-5D-3L, SF-12 in Django), **MII PRO Module** (PROMIS, PHQ-9, EQ-5D-5L as FHIR), **eq5d** R package (analysis and scoring) .

- **PROMIS Instruments**: The **PROMIS** item banks themselves are **freely available** for research use (registration required), with over 200 peer-reviewed measures covering physical, mental, and social health. Assessment Center API provides programmatic access .



**Frameworks for building custom systems**: Combine **REDCap** + **MyCap** for a free, non-profit-friendly ePRO foundation, **OpenClinica Participate** or **LibreClinica** + **ODK** for EDC-integrated eCOA, **JTrack** for EMA and passive sensor data, and **edc-qol** or **MII PRO Module** for standardized PRO instruments (EQ-5D, PROMIS, PHQ-9). Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- eCOA platforms handle sensitive clinical trial and patient data; ensure compliance with 21 CFR Part 11, GCP, HIPAA, and GDPR.

- **Open-source reality**: Mature open-source ePRO/eCOA foundations exist (**REDCap**, **OpenClinica**, **LibreClinica**, **JTrack**), but they typically require configuration and validation for specific trial needs. Commercial platforms (Clario, Signant, Medable) provide fully validated, regulatory-ready solutions with scientific consulting, device provisioning, and 24/7 patient support that open-source alternatives cannot match without significant investment.
