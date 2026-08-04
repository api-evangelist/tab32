# tab32 (tab32)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
