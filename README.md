# awesome-munich-data [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/tifa365/awesome-munich-data/commits/main.atom)

##### Community list of open data sources, APIs, tools, applications, and resources for Munich.

Munich is an important city for open data, civic technology, and digital public infrastructure. This list is intended to collect datasets, APIs, tools, and applications that help citizens, researchers, developers, and urban planners better understand and improve the city.

Have something to add or change? Open a pull request or issue.

------------------------------

### Table of Contents

- [Art & Street Culture](#art--street-culture)
- [Education & Schools](#education--schools)
- [Environment & Nature](#environment--nature)
- [Government & Politics](#government--politics)
- [Housing & Social](#housing--social)
- [Maps & Visualizations](#maps--visualizations)
- [Open Data Tools & APIs](#open-data-tools--apis)
- [Transportation & Mobility](#transportation--mobility)
- [Urban Planning & Land Use](#urban-planning--land-use)

------------------------------

## Art & Street Culture

- 🎨 [kunst-am-bau-muenchen](https://github.com/tifa365/kunst-am-bau-muenchen) - Exports 323 geolocated artworks (1973–2022) from the city's QUIVID art-in-architecture programme as JSON and GeoJSON, run locally because the source data is non-commercial.
- 🎧 [memory-loops-munich](https://github.com/tifa365/memory-loops-munich) - Exports 465 geolocated recordings from Michaela Melián's Memory Loops audio memorial on Nazi persecution in Munich as JSON.

------------------------------

## Education & Schools

- 📚 [openbibmuc.de](https://openbibmuc.de) - Overview of all Munich Public Library branches with a fact sheet per library and a list of recent media acquisitions.
- 🧸 [kitafinder-api-muenchen](https://github.com/tifa365/kitafinder-api-muenchen) - Unofficial OpenAPI 3.1 specification for the JSON API behind the city's [kita finder+](https://kitafinder.muenchen.de/elternportal/de/) parent portal, listing all 1,845 childcare facilities with availability status without login.

------------------------------

## Environment & Nature

- 🏊 [München badet](https://muenchenbadet.de/) - Private dashboard and map combining Isar water temperature, level, and flood alert stages from the Bavarian environment agency with live occupancy of 15 SWM pools and 8 hand-picked Isar bathing spots, publishing its own tables as CC BY 4.0 CSV and GeoJSON while the pool occupancy is scraped from swm.de without an open licence.

------------------------------

## Government & Politics

- 📑 [München Transparent](https://www.muenchen-transparent.de/) - Open-source council information system for the city council and all 25 district committees, with full-text search and a [documented](https://www.muenchen-transparent.de/infos/api) [OParl 1.0 API](https://www.muenchen-transparent.de/oparl/v1.0) covering terms back to 1996.
- 📜 [RathausMuc](https://rathausmuc.de/) - Overview of the Munich City Council and 25 district committees focused on people, with group and committee memberships, election results, profiles, and social media accounts.
- 🗳️ [München-O-Mat](https://muenchen-o-mat.de/) - [Open-source](https://github.com/olischne/muenchen_o_mat) voting advice app for the 8 March 2026 municipal election, covering 35 theses answered by 14 parties and voter groups, with the data served as CSV.
- 💰 [Münchner Haushaltsdaten](https://tifa365.github.io/haushaltsdaten-muenchen/) - [Open-source](https://github.com/tifa365/haushaltsdaten-muenchen) interactive treemap of Munich's 2026 budget expenses by policy area, product, and cost type, parsed from the city's 1,750-page budget PDF.

------------------------------

## Housing & Social

Resources to be added.

------------------------------

## Maps & Visualizations

- 🏷️ [EqualStreetNames München](https://munich.equalstreetnames.eu/de/index.html#10.86/48.155/11.5418) - Interactive map of Munich street names and the gender of their namesakes, built on an [open-source project](https://github.com/EqualStreetNames/equalstreetnames/).
- 🛣️ [Muenchner_Strassen](https://soerenetler.github.io/Muenchner_Strassen/) - Map-based scrollytelling about Munich street names and their social and historical context, built from city street and address data with Python, QGIS, and Mapbox.
- 🕰️ [muenchen.rewind](https://github.com/tifa365/muenchen.rewind) - Interactive time slider comparing Munich aerial orthophotos from 2003 to 2024 side by side, with address search.
- ⛲️ [Family-friendly Munich](https://benjaminaaron.github.io/open-bydata-lod-usecase-family-spots/) - Map of playgrounds for young children with nearby public toilets, cafés, and drinking fountains, built from Open Data Munich and OpenStreetMap as a fork of a [LOD use case](https://github.com/byte-bayern/open-bydata-lod-usecase-family-spots).

------------------------------

## Open Data Tools & APIs

- 🗂️ [Open Data Portal München](https://opendata.muenchen.de/en/) - Official city portal with 331 datasets across transport, government, education, and other categories.
- 🌱 [datengartln München](https://datengartln.de/) - Community-built explorer for 266 Munich open datasets with notebook-based data stories and curated category pages.
- 🚀 [startercode-opendata-munich](https://github.com/it-at-m/startercode-opendata-munich) - Auto-generated Python and R starter notebooks for every Munich open data portal dataset, prefilled with metadata and download links.
- 💼 [jobportal-muenchen](https://github.com/tifa365/jobportal-muenchen) - Verified OpenAPI specification and Python client for the undocumented SAP SuccessFactors search API behind the city's job portal, listing every open position.
- 🏟️ [sportanlagen-api-muenchen](https://github.com/tifa365/sportanlagen-api-muenchen) - Verified OpenAPI specification for the undocumented search API behind the city's sports facilities finder, covering 406 facilities with filters, facets, and coordinates.
- 🔌 [InfraNode](https://infranode.dev/staedte/muenchen/) - Keyless REST API, also available as an [MCP server](https://infranode.dev/mcp/), returning 82 Munich data types as JSON, from weather and transit departures to parking, crime statistics, and land values.
- 📈 [Munich in Numbers](https://www.munich-in-numbers.com/) - German-language dashboard turning 116 official Munich statistics datasets into charts, with a district-level indicator atlas and short data stories.
- 📊 [Datenraum München](https://tifa365.github.io/datenraum-muenchen/) - Unofficial prototype of a Munich urban data hub modeled after Augsburg's [Datenraum](https://smartes.augsburg.de) on the AGPL-3.0 CIVORA UI, with partly frozen data; [source repository](https://github.com/tifa365/datenraum-muenchen).
- 📋 [open-data-monitor-muenchen](https://github.com/tifa365/open-data-monitor-muenchen) - Independent audit of the 96 datasets the city administration identified in 2022, rating their open availability as of October 2026 (59 open, 16 partial, 13 public with unclear licence, 8 not found) and publishing the results as CC0 CSV with source links.

------------------------------

## Transportation & Mobility

- 🚲 [Munich Bike Data Info Graphic](https://somtom.github.io/post/munich-bike-data-info-graphic/) - Long-form analysis and infographic of Munich bicycle counting-station data covering station maps, traffic patterns, and commuting insights.
- 🚇 [MVV OpenData](https://www.mvv-muenchen.de/fahrplanauskunft/fuer-entwickler/opendata/index.html) - Official MVV developer page with GTFS feeds and CSV downloads for stops, lines, and tariff zones under CC BY.
- 🅿️ [mvv-park-and-ride-api](https://github.com/tifa365/mvv-park-and-ride-api) - OpenAPI specification for the MVV Park-and-Ride endpoint listing all 363 facilities with location, static capacity, and tariff, but no live occupancy.
- 🅿️ [data.parkraumwende.de](https://data.parkraumwende.de) - Data section of the [Parkraumwende](https://parkraumwende.de) initiative with a crowdsourced map of Munich parking garages and spaces, live city-centre garage occupancy, and mobility statistics.
- 🚆 [verspaetung.net – München Hbf](https://verspaetung.net/bahnhoefe/8000261-muenchen-hbf) - Unofficial live board of München Hbf delays and cancellations for the next 60 minutes, backed by a [documented open-data API](https://data.verspaetung.net/opendata/swagger/) with 15-minute snapshots since February 2026.
- ✈️ [munich-airport-flightsearch-api](https://github.com/tifa365/munich-airport-flightsearch-api) - Unofficial, live-verified OpenAPI specification of the AJAX endpoints behind the Munich Airport (MUC) flight search, covering arrival and departure boards, airport and airline autocomplete, and flight tracking, with parsing notes for the HTML fragments.

------------------------------

## Urban Planning & Land Use

- 🏛️ [denkmalliste-bayern](https://github.com/tifa365/denkmalliste-bayern) - Extractor and verified OpenAPI specification for the undocumented BLfD Denkmalservice, exporting roughly 198,000 Bavarian listed monuments to GeoJSON, CSV, and JSONL.

------------------------------

## Related Lists

- 🐻 [awesome-berlin-data](https://github.com/tifa365/awesome-berlin-data) - Sister list following the same structure, collecting open data sources, APIs, tools, and applications for Berlin.

------------------------------

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors to this list have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) for the full CC0 1.0 Universal dedication.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

## About

This list aims to be a practical starting point for anyone interested in Munich's open data ecosystem. Listing of a project or resource does not imply endorsement.

Last updated: 2026-10-25
