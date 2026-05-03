# US Geological Survey

The US Geological Survey is a scientific agency of the United States government that conducts research on the natural resources, natural hazards, and environmental health of the United States. The USGS is responsible for monitoring and assessing the country's water, energy, mineral, and biological resources, as well as investigating geological hazards such as earthquakes, volcanoes, landslides, and floods. USGS provides a broad portfolio of public REST APIs covering earthquake data, water resources, geomagnetism, mapping, seismic design, and scientific data catalogs - all available without cost as US Government works.

**URL:** [https://www.usgs.gov](https://www.usgs.gov)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

`Federal Government` `Earth Science` `Earthquakes` `Water Data` `Geospatial` `Hazards` `Environment`

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

## APIs

| API | Description |
|-----|-------------|
| [USGS Earthquake Catalog API](https://earthquake.usgs.gov/fdsnws/event/1/) | FDSN event web service for real-time and historical earthquake data |
| [USGS Water Data OGC API](https://api.waterdata.usgs.gov) | OGC-compliant water measurements, daily values, and monitoring locations |
| [USGS ScienceBase Catalog API](https://www.sciencebase.gov/catalog/) | Scientific data management and catalog services |
| [USGS Geomagnetism Web Service](https://www.usgs.gov/tools/web-service-geomagnetism-data) | Geomagnetic data from USGS observatories |
| [USGS Seismic Design Data Services](https://earthquake.usgs.gov/ws/designmaps/) | Seismic design parameters for engineering applications |
| [USGS National Map Services](https://apps.nationalmap.gov/api/) | Topographic, elevation, and geospatial data services |

## OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [Earthquake Catalog API](openapi/usgs-earthquake-catalog-openapi.yml) | OpenAPI 3.0 spec for USGS earthquake catalog |
| [Water Data OGC API](openapi/usgs-water-data-openapi.yml) | OpenAPI 3.0 spec for USGS water data services |

## Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [Earthquake API Rules](rules/usgs-earthquake-api-rules.yml) | Spectral rules for USGS earthquake API conventions |

## Naftiko Capabilities

### Workflow Capabilities

| Capability | Description |
|------------|-------------|
| [Earth Science Monitoring](capabilities/earth-science-monitoring.yaml) | Combined earthquake and water data monitoring |

### Shared API Definitions

| Shared Definition | Description |
|-------------------|-------------|
| [USGS Earthquake Catalog](capabilities/shared/usgs-earthquake-catalog.yaml) | Shared definition for earthquake catalog API |
| [USGS Water Data](capabilities/shared/usgs-water-data.yaml) | Shared definition for water data OGC API |

## JSON Schema

| Schema | Description |
|--------|-------------|
| [Earthquake Feature](json-schema/usgs-earthquake-feature-schema.json) | Schema for USGS earthquake GeoJSON feature |

## JSON Structure

| Structure | Description |
|-----------|-------------|
| [Earthquake Feature Structure](json-structure/usgs-earthquake-feature-structure.json) | Field documentation for earthquake events |

## JSON-LD

| Context | Description |
|---------|-------------|
| [USGS Context](json-ld/us-geological-survey-context.jsonld) | Linked data context for USGS earth science data |

## Examples

| Example | Description |
|---------|-------------|
| [Earthquake Query Example](examples/usgs-earthquake-query-example.json) | Example GeoJSON response from earthquake catalog |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [USGS Vocabulary](vocabulary/us-geological-survey-vocabulary.yml) | Domain vocabulary for seismology, hydrology, and geospatial science |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
