# US Geological Survey (us-geological-survey)

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
