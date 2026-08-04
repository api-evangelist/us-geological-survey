# US Geological Survey (us-geological-survey)

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

The US Geological Survey is a scientific agency of the United States government that conducts research on the natural resources, natural hazards, and environmental health of the United States. The USGS is responsible for monitoring and assessing the country's water, energy, mineral, and biological resources, as well as investigating geological hazards such as earthquakes, volcanoes, landslides, and floods. USGS provides a broad portfolio of public REST APIs covering earthquake data, water resources, geomagnetism, mapping, seismic design, and scientific data catalogs - all available without cost as US Government works.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Earth Science
- Earthquakes
- Water Data
- Geospatial
- Hazards
- Environment

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### USGS Earthquake Catalog API

The USGS Earthquake Catalog API implements the FDSN Event Web Service Specification, providing real-time and historical access to global earthquake data from the USGS National Earthquake Information Center. Query by time, location, magnitude, depth, and other parameters. Returns data in GeoJSON, QuakeML, KML, CSV, or text formats. No authentication required.

- **Human URL:** [https://earthquake.usgs.gov/fdsnws/event/1/](https://earthquake.usgs.gov/fdsnws/event/1/)

#### Tags

- Earthquakes
- Seismology
- Hazards
- Federal Government

#### Properties

- [Documentation](https://earthquake.usgs.gov/fdsnws/event/1/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/openapi/usgs-earthquake-catalog-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usgs-earthquake-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USGS Water Data OGC API

The USGS Water Data OGC APIs provide OGC-compliant interfaces to USGS water data including real-time continuous measurements from automated sensor networks, daily summary values, field measurements, and monitoring location metadata. Covers streamflow, gage height, groundwater levels, water quality, and hundreds of other parameters. API key required. Legacy WaterServices decommissioning in Q1 2027.

- **Human URL:** [https://api.waterdata.usgs.gov](https://api.waterdata.usgs.gov)

#### Tags

- Water Data
- Hydrology
- Streamflow
- Federal Government

#### Properties

- [Documentation](https://api.waterdata.usgs.gov)
- [OpenAPI](https://api.waterdata.usgs.gov/ogcapi/v0/openapi?f=json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/openapi/usgs-water-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usgs-earthquake-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USGS ScienceBase Catalog API

The USGS ScienceBase Catalog API provides access to USGS scientific data management infrastructure, enabling upload, documentation, sharing, and dynamic data services for USGS research datasets and scientific publications.

- **Human URL:** [https://www.sciencebase.gov/catalog/](https://www.sciencebase.gov/catalog/)

#### Tags

- Scientific Data
- Research
- Catalog
- Federal Government

#### Properties

- [Documentation](https://www.sciencebase.gov/catalog/)
- [Swagger U I](https://www.sciencebase.gov/catalog/swagger-ui.html)
- [Postman Collection](collections/usgs-earthquake-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USGS Geomagnetism Web Service

The USGS Geomagnetism Web Service provides programmatic access to geomagnetic data collected by USGS magnetic observatories across the United States and territories, supporting navigation, space weather, and geophysical research.

- **Human URL:** [https://www.usgs.gov/tools/web-service-geomagnetism-data](https://www.usgs.gov/tools/web-service-geomagnetism-data)

#### Tags

- Geomagnetism
- Magnetic Data
- Federal Government

#### Properties

- [Documentation](https://www.usgs.gov/tools/web-service-geomagnetism-data)
- [Base U R L](https://geomag.usgs.gov/ws/edge/)
- [Postman Collection](collections/usgs-earthquake-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USGS Seismic Design Data Web Services

The USGS Seismic Design Data Web Services provide parameter values from seismic design reference documents for building and infrastructure design, supporting compliance with ASCE 7 and other engineering standards.

- **Human URL:** [https://earthquake.usgs.gov/ws/designmaps/](https://earthquake.usgs.gov/ws/designmaps/)

#### Tags

- Seismic Design
- Engineering
- Hazards
- Federal Government

#### Properties

- [Documentation](https://earthquake.usgs.gov/ws/designmaps/)
- [Postman Collection](collections/usgs-earthquake-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USGS National Map Services

The USGS National Map services provide geospatial data and elevation products via OGC web services, REST APIs, and download services covering topographic data, imagery, hydrography, boundaries, transportation, structures, and land cover for the United States.

- **Human URL:** [https://apps.nationalmap.gov/api/](https://apps.nationalmap.gov/api/)

#### Tags

- Mapping
- Geospatial
- Topography
- Federal Government

#### Properties

- [Documentation](https://apps.nationalmap.gov/api/)
- [Postman Collection](collections/usgs-earthquake-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/usgs)
- [LinkedIn](https://www.linkedin.com/company/usgs)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
