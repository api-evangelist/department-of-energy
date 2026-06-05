# Department of Energy (department-of-energy)

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
