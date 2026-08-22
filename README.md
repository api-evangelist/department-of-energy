# Department of Energy (department-of-energy)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The U.S. Department of Energy (DOE) provides extensive open data and APIs across its national laboratories and program offices. Notable APIs are published by the Energy Information Administration (EIA) for energy statistics, the Office of Scientific and Technical Information (OSTI) for research and publications, the National Renewable Energy Laboratory (NREL, rebranding as NLR) developer network for renewables and alternative fuels, and the Buildings Performance Database (BPD).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/department-of-energy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-energy/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** Public

## Tags

- Buildings
- Electricity
- Energy
- Federal Government
- Open Data
- Renewables
- Research
- Solar
- Statistics

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### EIA Open Data API V2

The U.S. Energy Information Administration (EIA) Open Data API v2 is a fully RESTful implementation of EIA's public energy statistics. Routes are arranged in a logical hierarchy across petroleum, natural gas, coal, electricity, nuclear, renewables, total energy, international, and consumption series. Requests require a free api_key obtained from the EIA Open Data portal and return up to 5,000 rows per request as JSON or XML.

- **Human URL:** [https://www.eia.gov/opendata/](https://www.eia.gov/opendata/)
- **Base URL:** `https://api.eia.gov/v2`

#### Tags

- Coal
- Electricity
- Energy Statistics
- Natural Gas
- Petroleum
- Renewables

#### Properties

- [Documentation](https://www.eia.gov/opendata/documentation.php)
- [Developer](https://www.eia.gov/developer/)
- [A P I  Browser](https://www.eia.gov/opendata/browser/)
- [Sign Up](https://www.eia.gov/opendata/register.php)
- [Reference  P D F](https://www.eia.gov/opendata/documentation/APIv2.1.0.pdf)
- [OpenAPI](openapi/department-of-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/department-of-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OSTI DOE PAGES API

The DOE PAGES (Public Access Gateway for Energy and Science) REST API provides programmatic access to publications resulting from DOE-funded research, hosted by the Office of Scientific and Technical Information (OSTI). The API supports search and retrieval of bibliographic records and full-text links for journal articles, accepted manuscripts, and technical reports.

- **Human URL:** [https://www.osti.gov/pages/api/v1/docs](https://www.osti.gov/pages/api/v1/docs)
- **Base URL:** `https://www.osti.gov/pages/api/v1`

#### Tags

- Bibliographic
- OSTI
- Publications
- Research

#### Properties

- [Documentation](https://www.osti.gov/pages/api/v1/docs)
- [Reference](https://www.osti.gov/api)
- [Postman Collection](collections/department-of-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OSTI ELINK API

The OSTI ELINK API is the Office of Scientific and Technical Information's submission and retrieval interface for DOE research records. It supports submission of metadata and full text by DOE-funded research organizations, and it powers public retrieval interfaces for OSTI.GOV.

- **Human URL:** [https://www.osti.gov/elink/](https://www.osti.gov/elink/)
- **Base URL:** `https://www.osti.gov/elink`

#### Tags

- ELINK
- Metadata
- OSTI
- Submission

#### Properties

- [Documentation](https://www.osti.gov/elink/)
- [A P I](https://www.osti.gov/api)
- [Postman Collection](collections/department-of-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NREL/NLR Developer Network APIs

The National Renewable Energy Laboratory (NREL, transitioning to NLR) Developer Network publishes a portfolio of REST APIs covering solar resource and PV simulation, alternative fuels and stations, electricity utilities and rates, transportation, geothermal, and energy economics. All APIs share a common API key model issued through api.data.gov. Existing developer.nrel.gov consumers must migrate to developer.nlr.gov by April 30, 2026.

- **Human URL:** [https://developer.nlr.gov/](https://developer.nlr.gov/)
- **Base URL:** `https://developer.nlr.gov/api`

#### Tags

- Alternative Fuels
- Buildings
- Electricity
- Geothermal
- NREL
- Renewables
- Solar
- Transportation

#### Properties

- [Documentation](https://developer.nlr.gov/docs/)
- [Solar  A P Is](https://developer.nlr.gov/docs/solar/)
- [Electricity  A P Is](https://developer.nlr.gov/docs/electricity/)
- [Sign Up](https://api.data.gov/signup/)
- [Data  Catalog](https://data.nlr.gov/)
- [Postman Collection](collections/department-of-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Buildings Performance Database API

The Buildings Performance Database (BPD) is a DOE repository of anonymized empirical performance records for commercial and residential buildings. The BPD API allows partners to query aggregate distributions and compare cohorts of buildings across attributes such as building type, vintage, climate zone, and energy use intensity.

- **Human URL:** [https://www.energy.gov/eere/buildings/application-programming-interface](https://www.energy.gov/eere/buildings/application-programming-interface)
- **Base URL:** `https://api.example.com`

#### Tags

- BPD
- Benchmarking
- Buildings
- Energy Efficiency

#### Properties

- [Documentation](https://www.energy.gov/eere/buildings/application-programming-interface)
- [Postman Collection](collections/department-of-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Department of Energy Open Data Catalog

The DOE participates in Data.gov by publishing thousands of dataset records under the doe-gov organization. These datasets cover energy consumption, generation, environmental impact, R&D, and more, and are accessible through Data.gov's CKAN-compatible API.

- **Human URL:** [https://catalog.data.gov/organization/doe-gov](https://catalog.data.gov/organization/doe-gov)
- **Base URL:** `https://catalog.data.gov/api/3`

#### Tags

- CKAN
- Datasets
- Open Data

#### Properties

- [Documentation](https://catalog.data.gov/organization/doe-gov)
- [Open  Energy  Data](https://www.energy.gov/data/open-energy-data)
- [C K A N  Reference](https://docs.ckan.org/en/2.8/api/)
- [Postman Collection](collections/department-of-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/energy)
- [Website](https://www.energy.gov)
- [Open  Energy  Data](https://www.energy.gov/data/open-energy-data)
- [Developer  Portal](https://api.data.gov/)
- [E I A](https://www.eia.gov)
- [O S T I](https://www.osti.gov)
- [N R E L  Developer](https://developer.nlr.gov/)
- [Open  Energy  Data  Initiative](https://data.openei.org/)
- [Energy  Data e Xchange](https://edx.netl.doe.gov/)
- [Data.gov  D O E  Catalog](https://catalog.data.gov/organization/doe-gov)
- [News](https://www.energy.gov/news)
- [Privacy Policy](https://www.energy.gov/privacy)
- [GitHub Organization](https://github.com/doe-doe)
- [JSON-LD](json-ld/department-of-energy-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/department-of-energy-vocabulary.yml)
- [Capabilities](capabilities/department-of-energy-capabilities.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
