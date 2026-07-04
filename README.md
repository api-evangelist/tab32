# tab32 (tab32)

tab32 is a cloud-based dental practice management, imaging, and analytics platform for dental practices and dental service organizations (DSOs). Founded in 2012 and running on Google Cloud Platform, tab32 offers an all-in-one "100% cloud" system covering scheduling, clinical charting, imaging with AI radiology detection, revenue cycle / insurance, patient engagement, and an open data warehouse.

tab32 also offers a real, **commercial API**. It is powered by Google Apigee, is HIPAA and SOC 2 Type II compliant, and exposes tab32's `patient`, `provider`, `schedule`, `charts`, `notes`, `ledger`, and `payments` data objects.

## API Access Model

Access is **partner-gated, not open self-service.** The API is offered to DSOs and third-party developers who reach it through tab32's developer API portal after establishing a partnership or enterprise relationship. tab32's public site describes the API's data objects, developer portal, documentation, and sample resources, but it does **not** publish endpoint reference paths, base URLs, or authentication details openly — those live behind the developer portal. Accordingly, the API entries in this catalog are **modeled** from tab32's publicly documented data objects and API messaging; their endpoint paths are illustrative, not confirmed.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tab32/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tab32/refs/heads/main/apis.yml)

## Tags

- Dental
- Practice Management
- Healthcare
- Cloud Dental Software
- DSO
- HIPAA
- Patient Data
- Partner API

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs (Modeled)

The following logical APIs are modeled from tab32's documented API data objects (patient, provider, schedule, charts, notes, ledger, payments). Endpoint paths are not published publicly.

### tab32 Patients API
Access to the tab32 patient data object — demographics, contact and insurance details, and patient records — for integrating patient management into CRM, patient-facing apps, and enterprise systems.

### tab32 Providers API
Access to the tab32 provider data object — dentists, hygienists, and other practitioners across a practice or DSO's locations.

### tab32 Schedule API
Access to the tab32 schedule data object — appointments, availability, and booking — supporting online booking, recall, and scheduling integrations.

### tab32 Charts API
Access to the tab32 charts data object — clinical / periodontal charting and treatment planning data.

### tab32 Notes API
Access to the tab32 notes data object — clinical and progress notes attached to patient and encounter records.

### tab32 Ledger API
Access to the tab32 ledger data object — patient and practice financial ledger, charges, and insurance claim / revenue-cycle data.

### tab32 Payments API
Access to the tab32 payments data object — patient payments and transaction records (tab32 integrates payment processing via Stripe).

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tab32)
- [Website](https://tab32.com)
- [Documentation](https://tab32.com/application-programming-interface)
- [Plans](plans/tab32-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
