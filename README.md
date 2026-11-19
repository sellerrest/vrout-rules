# vrout-rules

The GeoSite and GeoIP directories are exports of the supplied Fixnet snapshots. Source SHA-256 digests are recorded in catalog.json. Each category's rules.yaml is a mihomo classical rule provider. geosite-attributes.json preserves the original domain attributes. icon-sources.json records where the original site icons were retrieved.

Use the **Rule lists** card in vrout to install a catalog release. The downloadable ZIP includes the search index and optimized providers.

## Service presets

The services directory contains 71 mihomo classical providers. For the 70 services with observed Fixnet DNS selectors, the selectors were expanded using the converted GeoSite database. CloudFlare uses the GeoSite and GeoIP entries with that name. Presets also include GeoIP entries where the referenced GeoSite tags have matching GeoIP tags.

See service-sources.json for provenance per preset. These presets describe the observed DNS selectors and the associated public geodata. Fixnet's separate encrypted packet filter and service-specific priority are outside this dataset.
