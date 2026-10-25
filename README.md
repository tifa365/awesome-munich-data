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
- [Open-Data-Monitor München](#open-data-monitor-münchen)

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

Resources to be added.

------------------------------

## Government & Politics

- 📑 [München Transparent](https://www.muenchen-transparent.de/) - Open-source council information system for the city council and all 25 district committees, with full-text search and a [documented](https://www.muenchen-transparent.de/infos/api) [OParl 1.0 API](https://www.muenchen-transparent.de/oparl/v1.0) covering terms back to 1996.
- 📜 [RathausMuc](https://rathausmuc.de/) - Overview of the Munich City Council and 25 district committees focused on people, with group and committee memberships, election results, profiles, and social media accounts.
- 🗳️ [München-O-Mat](https://muenchen-o-mat.de/) - [Open-source](https://github.com/olischne/muenchen_o_mat) voting advice app for the 8 March 2026 municipal election, covering 35 theses answered by 14 parties and voter groups, with the data served as CSV.

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
- 🔌 [InfraNode](https://infranode.dev/staedte/muenchen/) - Keyless REST API, also available as an [MCP server](https://infranode.dev/mcp/), returning 82 Munich data types as JSON, from weather and transit departures to parking, crime statistics, and land values.
- 📈 [Munich in Numbers](https://www.munich-in-numbers.com/) - German-language dashboard turning 116 official Munich statistics datasets into charts, with a district-level indicator atlas and short data stories.
- 📊 [Datenraum München](https://tifa365.github.io/datenraum-muenchen/) - Unofficial prototype of a Munich urban data hub modeled after Augsburg's [Datenraum](https://smartes.augsburg.de) on the AGPL-3.0 CIVORA UI, with partly frozen data; [source repository](https://github.com/tifa365/datenraum-muenchen).

------------------------------

## Transportation & Mobility

- 🚲 [Munich Bike Data Info Graphic](https://somtom.github.io/post/munich-bike-data-info-graphic/) - Long-form analysis and infographic of Munich bicycle counting-station data covering station maps, traffic patterns, and commuting insights.
- 🚇 [MVV OpenData](https://www.mvv-muenchen.de/fahrplanauskunft/fuer-entwickler/opendata/index.html) - Official MVV developer page with GTFS feeds and CSV downloads for stops, lines, and tariff zones under CC BY.
- 🅿️ [mvv-park-and-ride-api](https://github.com/tifa365/mvv-park-and-ride-api) - OpenAPI specification for the MVV Park-and-Ride endpoint listing all 363 facilities with location, static capacity, and tariff, but no live occupancy.
- 🅿️ [data.parkraumwende.de](https://data.parkraumwende.de) - Data section of the [Parkraumwende](https://parkraumwende.de) initiative with a crowdsourced map of Munich parking garages and spaces, live city-centre garage occupancy, and mobility statistics.
- 🚆 [verspaetung.net – München Hbf](https://verspaetung.net/bahnhoefe/8000261-muenchen-hbf) - Unofficial live board of München Hbf delays and cancellations for the next 60 minutes, backed by a [documented open-data API](https://data.verspaetung.net/opendata/swagger/) with 15-minute snapshots since February 2026.

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

------------------------------

## Open-Data-Monitor München

### Verfügbarkeit der 96 Datensätze aus der Bestandsaufnahme 2022 – Stand 25. Oktober 2026

Übernommen aus dem [Münchner Open-Data-Monitor](https://github.com/tifa365/open-data-monitor-muenchen) (CC0 1.0). Die Tabelle wird dort per Skript aus [zwei CSV-Dateien](https://github.com/tifa365/open-data-monitor-muenchen/tree/main/daten) erzeugt; Korrekturen bitte als Issue oder Pull Request im Monitor-Repository, nicht hier.

Die Tabelle verbindet die **ursprüngliche Liste der Stadtverwaltung aus dem Jahr 2022** mit einer **unabhängigen Einschätzung der Verfügbarkeit zum 25. Oktober 2026**. Die Einstufungen stammen aus einer unabhängigen Recherche im Münchner Open-Data-Katalog, in den Geodiensten und auf Fachseiten. Für Katalogdatensätze gilt grundsätzlich DL-DE-BY 2.0, für MVV- und MVG-Daten CC BY 4.0; Abweichungen stehen in der Lizenzspalte. Statusdefinitionen, Spalten und Belegstufen: [METHODIK.md](https://github.com/tifa365/open-data-monitor-muenchen/blob/main/METHODIK.md).

| Status | Anzahl |
| --- | ---: |
| ✅ Offen verfügbar | 59 |
| 🟡 Teilweise verfügbar | 16 |
| 📄 Öffentlich zugänglich, offene Lizenz unklar | 13 |
| ❌ Keine passende Quelle nachgewiesen | 8 |
| **Gesamt** | **96** |

| Nr. | Stelle (2022) | Datensatz / Datenangebot (2022) | Vermerk 2022 | Status 2026 | Einstufung im Detail | Rechercheanmerkung | Fundstelle | Lizenz |
| ---: | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Baureferat | Öffentliche Spielplätze und Freizeitanlagen in München | Bestehenden Datensatz aktualisieren | 🟡 Teilweise verfügbar | 🟡 Teilweise | Öffentliche Spielplätze, CSV. Kein vollständiger Bestand sämtlicher Freizeitanlagen nachgewiesen. | [Link](https://opendata.muenchen.de/dataset/oeffentliche-spielplaetze-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 2 | Baureferat | Points of Interest an der Isar | Bestehenden Datensatz aktualisieren | ✅ Offen verfügbar | ✅ Offen | POIs an der südlichen Isar, CSV; räumlich auf die südliche Isar bezogen. | [Link](https://opendata.muenchen.de/dataset/points-of-interest-an-der-sudlichen-isar) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 3 | Baureferat | Öffentliche Toiletten | Bestehenden Datensatz aktualisieren | ✅ Offen verfügbar | ✅ Offen | WC-Standorte, unter anderem CSV und Geodaten. | [Link](https://opendata.muenchen.de/dataset/wc_finder) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 4 | Baureferat | Müllsammelbehälter an der Isar | Bestehenden Datensatz aktualisieren | ✅ Offen verfügbar | ✅ Offen | Müllsammelbehälter an der Isar, CSV mit Koordinaten. | [Link](https://opendata.muenchen.de/dataset/muellsammelbehaelter-an-der-isar) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 5 | Baureferat | Linienhafte Darstellung des Blindenleitsystems in der Münchner Altstadt | GeoDaten | ✅ Offen verfügbar | ✅ Offen | Blindenleitsystem Altstadt – Fußgängerzone, Geodaten/CSV. | [Link](https://opendata.muenchen.de/dataset/baut_blindenleitsystem_altstadt) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 6 | Baureferat | Knoten-Kanten-Modell der Straßen im Stadtgebiet München | GeoDaten | ✅ Offen verfügbar | ✅ Offen | Straßennetzgraf Baureferat Tiefbau, Geometrien und Abschnittsdaten. | [Link](https://opendata.muenchen.de/dataset/baut_strassenabschnitte_wu) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 7 | Filmwochen | Feste Mitarbeiter:innen der Internationalen Münchner Filmwochen GmbH | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Filmfest München, CSV enthält ausdrücklich feste Mitarbeitende; Daten 2019–2023. | [Link](https://opendata.muenchen.de/dataset/filmfest-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 8 | Filmwochen | Views beim digitalen FILMSCHOOLFEST MUNICH 39 ½, 12.–22. November 2020 | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Filmfest München: Ressourcenbeschreibung nennt ungefähr 10.000 Views plus 1.200 Zuschauende weiterer Veranstaltungen; CSV fasst sie als 11.200 zusammen. | [Link](https://opendata.muenchen.de/dataset/filmfest-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 9 | Filmwochen | Besucher:innen des 38. FILMFEST MÜNCHEN, 1.–10. Juli 2021 | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Filmfest München, Jahr 2021 enthalten. | [Link](https://opendata.muenchen.de/dataset/filmfest-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 10 | Flughafen München GmbH | Events | Bisher nur Nennung | ❌ Keine passende Quelle nachgewiesen | ❌ Nicht nachgewiesen | Kein passender offen lizenzierter Veranstaltungsdatensatz nachgewiesen. | – | – |
| 11 | Flughafen München GmbH | Flüge | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Monatszahlen Flugverkehr: Flugbewegungen und Fluggäste als Statistik, keine einzelnen Flüge oder Live-Flugpläne. | [Link](https://opendata.muenchen.de/dataset/monatszahlen-flugverkehr) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 12 | Flughafen München GmbH | Points of Interest | Bisher nur Nennung | ❌ Keine passende Quelle nachgewiesen | ❌ Nicht nachgewiesen | Kein passender offen lizenzierter POI-Bestand des Flughafens nachgewiesen. | – | – |
| 13 | Gasteig | Veranstaltungssäle Gasteig HP8 | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Gasteig-Daten enthalten Saalnamen je Jahr; kein vollständiger Saal-Stammdatensatz mit Ausstattung und Kapazitäten. | [Link](https://opendata.muenchen.de/dataset/besucher-und-veranstaltungen-gasteig-hp8-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 14 | Gasteig | Anzahl Veranstaltungen Gasteig HP8 | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Gasteig-Daten, CSV bis 2024. | [Link](https://opendata.muenchen.de/dataset/besucher-und-veranstaltungen-gasteig-hp8-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 15 | Gasteig | Anzahl Besucher*innen der Veranstaltungen Gasteig HP8 | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Gasteig-Daten, nach Veranstaltungsort, bis 2024. | [Link](https://opendata.muenchen.de/dataset/besucher-und-veranstaltungen-gasteig-hp8-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 16 | Gesundheitsreferat | Statistische Friedhöfe (so im Original) | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Bestattungen und Beisetzungen, CSV bis 2025; zusätzlich Friedhofsliste. | [Link](https://opendata.muenchen.de/dataset/bestattungen-beisetzungen-staedtische-friedhoefe-muenchen), [Link 2](https://opendata.muenchen.de/dataset/liste-staedtische-friedhoefe-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 17 | Gesundheitsreferat | Gesundheitsschutz | Bisher nur Nennung | ❌ Keine passende Quelle nachgewiesen | ❌ Nicht nachgewiesen | Kein eindeutig zuordenbarer Datensatz. Die ursprüngliche Bezeichnung ist sehr unspezifisch. | – | – |
| 18 | GEWOFAG | Bestand | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Wohnungen Münchner Wohnen, CSV mit GEWOFAG und GWG. | [Link](https://opendata.muenchen.de/dataset/wohnungen-muenchner-wohnen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 19 | GEWOFAG | Freifinanzierte Wohnungen | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Wohnungsdaten, eigene Spalte. | [Link](https://opendata.muenchen.de/dataset/wohnungen-muenchner-wohnen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 20 | GEWOFAG | Fremdverwaltung | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Wohnungsdaten, eigene Spalte. | [Link](https://opendata.muenchen.de/dataset/wohnungen-muenchner-wohnen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 21 | GEWOFAG | Öffentlich geförderte Wohnungen | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Wohnungsdaten, eigene Spalte. | [Link](https://opendata.muenchen.de/dataset/wohnungen-muenchner-wohnen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 22 | GEWOFAG | Sonderwohnformen | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Wohnungsdaten, eigene Spalte. Die tatsächlich heruntergeladene Datei enthält 2018–2023. | [Link](https://opendata.muenchen.de/dataset/wohnungen-muenchner-wohnen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 23 | IT-Referat | Fernzugriffsberechtigungen, Januar 2020–Juli 2021 | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Fernzugriffsberechtigungen, CSV nach Datum und Organisationseinheit. | [Link](https://opendata.muenchen.de/dataset/fernzugriffe) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 24 | Kammerspiele | Statistische Daten je Spielzeit | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Sitzplätze Kammerspiele und Schauburg, Spielzeiten 2017/18–2021/22. Keine umfassende Spielzeitstatistik. | [Link](https://opendata.muenchen.de/dataset/sitzplaetze-spielstaetten-muenchner-kammerspiele-schauburg) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 25 | Kommunalreferat | Münchner Adressen | GeoDaten | ✅ Offen verfügbar | ✅ Offen | Münchner Adressen, kommaseparierte TXT-Datei mit Straße, Hausnummer und Stadtbezirk. | [Link](https://opendata.muenchen.de/dataset/adressen_opendata) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 26 | Kommunalreferat | Stadtgrundkarte München | GeoDaten | 🟡 Teilweise verfügbar | 🟡 Teilweise | Digitale Stadtkarte als offener WMS. Kein vollständiger Vektorexport der ursprünglichen Stadtgrundkarte nachgewiesen. Für enthaltene bayerische Hausumringe gilt zusätzlich CC BY 4.0. | [Link](https://opendata.muenchen.de/dataset/g_stadtkarte_wms) | [DL-DE-BY 2.0; Hausumringe CC BY 4.0](https://www.govdata.de/dl-de/by-2-0) |
| 27 | Kreisverwaltungsreferat | Bevölkerungszahlen | Stat. Amt | ✅ Offen verfügbar | ✅ Offen | Bevölkerung in den Stadtbezirken und Monatszahlen Bevölkerung. | [Link](https://opendata.muenchen.de/dataset/bevoelkerung-stadtbezirken), [Link 2](https://opendata.muenchen.de/dataset/monatszahlen-bevoelkerung) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 28 | Kreisverwaltungsreferat | Geburtenrate, Sterberate, Sterbealter | Stat. Amt | ✅ Offen verfügbar | ✅ Offen | Indikatorenatlas: Geburtenrate, Sterberate, Durchschnittsalter Gestorbener, CSV. | [Link](https://opendata.muenchen.de/dataset/indikatorenatlas-bevoelkerung-allgemeine-geburtenrate-83r65mct), [Link 2](https://opendata.muenchen.de/dataset/indikatorenatlas-bevoelkerung-rohe-sterberate-83r65mct), [Link 3](https://opendata.muenchen.de/dataset/indikatorenatlas-bevoelkerung-durchschnittsalter-gestorbene-83r65mct) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 29 | Kreisverwaltungsreferat | Wohndauer | Stat. Amt | ✅ Offen verfügbar | ✅ Offen | Wohndauer an der Adresse und Wohndauer in München. | [Link](https://opendata.muenchen.de/dataset/indikatorenatlas-bevoelkerung-wohndauer-adresse-83r65mct), [Link 2](https://opendata.muenchen.de/dataset/indikatorenatlas-bevoelkerung-wohndauer-muenchen-83r65mct) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 30 | Kreisverwaltungsreferat | Einbürgerungsquote | Stat. Amt | 🟡 Teilweise verfügbar | 🟡 Teilweise | Monatszahlen Einbürgerungen und Anteil Eingebürgerter. Letzterer ist nicht automatisch dieselbe Kennzahl wie eine jährliche Einbürgerungsquote. | [Link](https://opendata.muenchen.de/dataset/monatszahlen-einbuergerungen), [Link 2](https://opendata.muenchen.de/dataset/indikatorenatlas-bevoelkerung-eingebuergerte-83r65mct) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 31 | Kreisverwaltungsreferat | Wahlen | Stat. Amt | ✅ Offen verfügbar | ✅ Offen | Beispielsweise Stadtratswahl 2026, maschinenlesbare Ergebnisse als ZIP/CSV. | [Link](https://opendata.muenchen.de/dataset/stadtratswahl-2026-ergebnisse-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 32 | Kreisverwaltungsreferat | Kfz-Bestand / Kfz-Neuzulassungen | Stat. Amt | ✅ Offen verfügbar | ✅ Offen | Kfz-Bestand und Kfz-Erstzulassungen, CSV. | [Link](https://opendata.muenchen.de/dataset/monatszahlen-kfz-bestand), [Link 2](https://opendata.muenchen.de/dataset/monatszahlen-kfz-neuzulassungen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 33 | M-Arbeit | Arbeitsgelegenheiten für langzeitarbeitslose Menschen | Bisher nur Nennung | ❌ Keine passende Quelle nachgewiesen | ❌ Nicht nachgewiesen | Die offene MBQ-Projektliste ist ein verwandtes Angebot, aber kein nachgewiesener Ersatz für die konkrete Liste der Arbeitsgelegenheiten. | [Link](https://opendata.muenchen.de/dataset/projekte-des-muenchner-beschaeftigungs-und-qualifizierungsprogramms-mbq) | – |
| 34 | M-Arbeit | Ansprechpersonen: Übersicht der verantwortlichen Personen | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | Kontaktseite Münchner Arbeit; keine offene Datensatzlizenz nachgewiesen. | [Link](https://www.muenchner-arbeit.de/kontakt) | – |
| 35 | M-Arbeit | Ateliervermietung: städtisch geförderte Ateliers für professionelle Kunst- und Kulturschaffende | Bisher nur Nennung | ❌ Keine passende Quelle nachgewiesen | ❌ Nicht nachgewiesen | Kein passender offener Datensatz zur Vermietungsübersicht nachgewiesen. | – | – |
| 36 | M-Arbeit | amiga-Veranstaltungen: Karrierezentrum für internationale Fachkräfte | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | amiga verweist auf Veranstaltungstermine; kein offen lizenzierter Veranstaltungsfeed nachgewiesen. | [Link](https://stadt.muenchen.de/infos/amiga.html) | – |
| 37 | M-Klinik | Geburten München Klinik | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Geburten München Klinik, CSV 2017–2025. | [Link](https://opendata.muenchen.de/dataset/geburten-in-der-muenchen-klinik-ggmbh) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 38 | M-Klinik | Notfallversorgung München Klinik | Bisher nur Nennung | ❌ Keine passende Quelle nachgewiesen | ❌ Nicht nachgewiesen | Kein passender offener Klinikdatensatz nachgewiesen. | – | – |
| 39 | Mobilitätsreferat | Verkehrsmengendaten | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Raddauerzählstellen 2026, CSV. Eine umfassende Veröffentlichung der Verkehrsmengen aller Verkehrsmittel ist damit nicht belegt. | [Link](https://opendata.muenchen.de/dataset/daten-der-raddauerzaehlstellen-muenchen-2026) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 40 | Mobilitätsreferat | Parkhäuser | Bestehenden Datensatz aktualisieren | ✅ Offen verfügbar | ✅ Offen | Parkhäuser München, CSV und JSON. Stammdaten, keine Live-Belegung. | [Link](https://opendata.muenchen.de/dataset/parkhaeuser-munchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 41 | Mobilitätsreferat | Mobilitätsstationen | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Mobilitätspunkte, Geodaten und Ausstattungsmerkmale. | [Link](https://opendata.muenchen.de/dataset/opendata_ruhver_mp_standort_point) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 42 | Münchner Gewerbehöfe | Belegung Gewerbehöfe ab 2010 | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Belegung Gewerbehöfe, CSV; tatsächliche Werte 2010–2023. | [Link](https://opendata.muenchen.de/dataset/belegung-gewerbehoefe) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 43 | Münchner Gewerbehöfe | Aufnahme Existenzgründer im MTZ ab 2013 | Bisher nur Nennung | ❌ Keine passende Quelle nachgewiesen | ❌ Nicht nachgewiesen | Kein entsprechender offener Zeitreihendatensatz gefunden. | – | – |
| 44 | MVV | Haltestellenliste | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Haltestellenliste MVV, CSV, CC BY 4.0. | [Link](https://opendata.muenchen.de/dataset/haltestellenliste-mvv) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 45 | MVV | Soll-Fahrplandaten (GTFS) | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | MVV-Gesamtnetz GTFS, ZIP, CC BY 4.0. | [Link](https://opendata.muenchen.de/dataset/soll-fahrplandaten-mvv-gesamtnetz-gtfs) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 46 | MVV | Linienliste | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Linienliste MVV, CSV, CC BY 4.0. | [Link](https://opendata.muenchen.de/dataset/linienliste-mvv) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 47 | MVV | Haltestellen mit Tarifzuordnung | PDF | ✅ Offen verfügbar | ✅ Offen | Tarifzonenzuordnung, inzwischen CSV statt nur PDF; CC BY 4.0. | [Link](https://opendata.muenchen.de/dataset/haltestellen-mit-tarifzuordnung-mvv) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 48 | Olympiapark | Olympiapark München in (Corona-)Zahlen 2020 | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Monatszahlen Freizeit enthalten Besucherzahlen der Olympiapark-Einrichtungen auch für 2020; kein vollständiges Kennzahlenpaket des Geschäftsberichts. | [Link](https://opendata.muenchen.de/dataset/monatszahlen-freizeit) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 49 | Olympiapark | Olympiapark München in Zahlen 2019 | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Monatszahlen Freizeit, ebenso für 2019. | [Link](https://opendata.muenchen.de/dataset/monatszahlen-freizeit) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 50 | Olympiapark | Besucher:innen der Freizeit- und Tourismuseinrichtungen in Prozent | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Monatszahlen Freizeit enthalten absolute Besucherzahlen. Die ursprünglich genannte Prozentverteilung ist nicht als identischer Datensatz nachgewiesen. | [Link](https://opendata.muenchen.de/dataset/monatszahlen-freizeit) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 51 | Park und Ride GmbH | Übersicht P+R-Anlagen | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | P+R-Anlagen München, CSV mit Standorten und Stellplätzen. | [Link](https://opendata.muenchen.de/dataset/p-r-anlagen-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 52 | Park und Ride GmbH | Belegungsprognosen P+R-Anlagen | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | P+R-Belegungsprognosen, CSV nach Tageszeit und Wochentag. Erfahrungsbasierte Prognosen, keine Echtzeitbelegung. | [Link](https://opendata.muenchen.de/dataset/p-r-anlagen-belegungsprognosen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 53 | Personal- und Organisationsreferat | Personalstand der Landeshauptstadt München 2015–2019 | PDF | 🟡 Teilweise verfügbar | 🟡 Teilweise | Personalstand, CSV ab 2017. Die ursprünglichen Jahre 2015/2016 sind damit nicht abgedeckt. | [Link](https://opendata.muenchen.de/dataset/personalstand-der-landeshauptstadt-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 54 | Personal- und Organisationsreferat | Gesamtbeschäftigte mit nichtdeutscher Staatsangehörigkeit nach Nationalitäten, 31.12.2019 | PDF | ✅ Offen verfügbar | ✅ Offen | Nichtdeutsche Gesamtbeschäftigte nach Staatsangehörigkeit, CSV. | [Link](https://opendata.muenchen.de/dataset/nichtdeutsche-gesamtbeschaeftigte-der-landeshauptstadt-muenchen-nach-staatsangehoerigkeit) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 55 | Personal- und Organisationsreferat | Personalstand nach Beschäftigtengruppe 2015–2019 | PDF | 🟡 Teilweise verfügbar | 🟡 Teilweise | Personalstand nach Beschäftigtengruppen, CSV ab 2017. | [Link](https://opendata.muenchen.de/dataset/personalstand-der-landeshauptstadt-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 56 | Personal- und Organisationsreferat | Beschäftigte nach Referaten, Eigenbetrieben und Stiftungen | PDF | ✅ Offen verfügbar | ✅ Offen | Kernbeschäftigte nach Organisationseinheiten, CSV; Abgrenzung auf Kernbeschäftigte beachten. | [Link](https://opendata.muenchen.de/dataset/kernbeschaeftigte-nach-referaten-eigenbetriebe-und-stiftungen-landeshauptstadt-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 57 | Personal- und Organisationsreferat | Beschäftigte nach Altersgruppen, Arbeitszeit und Geschlecht | PDF | ✅ Offen verfügbar | ✅ Offen | Entsprechende Kernbeschäftigtenstatistik, CSV. | [Link](https://opendata.muenchen.de/dataset/kernbeschaeftigte-nach-altersgruppen-arbeitszeit-und-geschlecht-landeshauptstadt-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 58 | Personal- und Organisationsreferat | Beschäftigte nach Statusgruppen, Arbeitszeit und Geschlecht | PDF | ✅ Offen verfügbar | ✅ Offen | Entsprechende Kernbeschäftigtenstatistik, CSV. | [Link](https://opendata.muenchen.de/dataset/kernbeschaeftigte-nach-statusgruppen-arbeitszeit-und-geschlecht-landeshauptstadt-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 59 | Personal- und Organisationsreferat | Beschäftigte nach Altersgruppen, Statusgruppen und Geschlecht | PDF | ✅ Offen verfügbar | ✅ Offen | Entsprechende Kernbeschäftigtenstatistik, CSV. | [Link](https://opendata.muenchen.de/dataset/kernbeschaeftigte-nach-altersgruppen-statusgruppen-und-geschlecht-landeshauptstadt-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 60 | Referat für Bildung und Sport | Fit-im-Park-Sportangebote | Datensatz liegt vor | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich / Lizenzzuordnung offen | Freizeitportal; ein GeoJSON-Abruf für Fit im Park 2026 funktioniert. Die verlinkten Lizenzmetadaten beziehen sich auf den allgemeineren FreizeitSport-/Hallensportdienst; die Zuordnung zum konkreten Sommerbestand bleibt unklar. | [Link](https://geoportal.muenchen.de/portal/freizeit/), [Link 2](https://geoportal.muenchen.de/geoserver/rbs_wfs/ows?service=WFS&version=1.1.0&request=GetFeature&typeName=rbs_wfs:fip_2026&outputFormat=application/json) | – |
| 61 | Referat für Bildung und Sport | Kindertagesbetreuungseinrichtungen in München | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Kindertagesbetreuungseinrichtungen, CSV mit Einrichtungen und Adressen. | [Link](https://opendata.muenchen.de/dataset/kindertagesbetreuungseinrichtungen-in-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 62 | Referat für Bildung und Sport | Schulen und Schülerzahlen | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Schulen und Schüler*innenzahlen, CSV; statistische Übersicht nach Schularten. | [Link](https://opendata.muenchen.de/dataset/schulen-und-schuelerzahlen-in-muenchen) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 63 | Referat für Bildung und Sport | Outdoor-Sportangebote | Datensatz liegt vor | 🟡 Teilweise verfügbar | 🟡 Teilweise | FreizeitSport-/Hallensportprogramm, CSV enthält auch Outdoor-Angebote wie Nordic Walking. Kein vollständiger Bestand sämtlicher Outdoor-Sportmöglichkeiten. | [Link](https://opendata.muenchen.de/dataset/hallensportprogramm) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 64 | Referat für Klima und Umwelt | Versiegelungskarte | GeoDaten | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | Bodenversiegelung; im RKU-WMS ist auch Bodenversiegelung 2023 enthalten. Quellenangaben sind vorgeschrieben; eine eindeutig bezeichnete offene Lizenz konnte ich nicht belegen. | [Link](https://stadt.muenchen.de/infos/bodenversiegelung.html), [Link 2](https://geoportal.muenchen.de/geoserver/rku/ows?service=WMS&request=GetCapabilities) | – |
| 65 | Referat für Klima und Umwelt | Messergebnisse des städtischen freiwilligen NO₂-Messnetzes | GeoDaten | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | Immissionsmessungen München, einschließlich Ergebnissen 2026. Kein eindeutig offen lizenzierter maschinenlesbarer Bestand dieses konkreten Messnetzes nachgewiesen. | [Link](https://stadt.muenchen.de/infos/immissionsmessungen-muenchen.html) | – |
| 66 | Referat für Klima und Umwelt | Solarpotentialkarte | GeoDaten | ✅ Offen verfügbar | ✅ Offen, als Kartendienst | Solarpotenzialanalyse 2018. Kataloglink defekt; funktionierender GSM-WMS, Layer solarpotenzial_globalstrahlung. | [Link](https://opendata.muenchen.de/dataset/solarpotenzial_globalstrahlung_p_02), [Link 2](https://geoportal.muenchen.de/geoserver/gsm/ows?service=WMS&request=GetCapabilities) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 67 | Referat für Klima und Umwelt | Geothermiekarte | GeoDaten | 🟡 Teilweise verfügbar | 🟡 Teilweise offen bestätigt | Im RKU-WMS funktionieren Geothermie-Layer. Für „Thermische Leistung bei 100 m Brunnenabstand“ ist CC BY 4.0 ausdrücklich dokumentiert. Nicht alle Teilkarten einzeln lizenzgeprüft. | [Link](https://geoportal.muenchen.de/geoserver/rku/ows?service=WMS&request=GetCapabilities), [Link 2](https://geoportal.muenchen.de/csw?service=CSW&version=2.0.2&request=GetRecordById&elementSetName=full&outputSchema=http://www.isotc211.org/2005/gmd&id=983df6e7-a480-47c5-a5d6-70a171efeb00) | [CC BY 4.0 (nur Layer „Thermische Leistung bei 100 m Brunnenabstand“)](https://creativecommons.org/licenses/by/4.0/) |
| 68 | Referat für Klima und Umwelt | Altlasten | GeoDaten | ❌ Keine passende Quelle nachgewiesen | ❌ Kein offener Gesamtbestand nachgewiesen | Altlastenauskunft erfolgt grundsätzlich als Einzelauskunft für Eigentümer oder Bevollmächtigte. | [Link](https://stadt.muenchen.de/service/info/sachgebiet-altlasten-abbruche/1074272/) | – |
| 69 | Referat für Klima und Umwelt | Entsorgungspflichtige Anlagen | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise / Zuordnung | Abfallentsorgungsanlagen, Geodaten/CSV. Fachlich naheliegender Treffer; die Identität mit dem unscharf bezeichneten ursprünglichen Bestand ist nicht belegt. | [Link](https://opendata.muenchen.de/dataset/abfall_betrieb_opendata) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 70 | Referat für Klima und Umwelt | Bezirksschornsteinfeger | Bisher nur Nennung | 🟡 Teilweise verfügbar | 🟡 Teilweise | Kehrbezirke, CSV/GeoJSON. Enthält Bezirksgeometrien und Kennungen, keine Namen und Kontaktdaten der Schornsteinfeger. | [Link](https://opendata.muenchen.de/dataset/kehrbezirke_opendata) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 71 | Referat für Stadtplanung und Bauordnung | Flächennutzungsplan | GeoDaten | ✅ Offen verfügbar | ✅ Offen, als Kartendienst | Digitaler Flächennutzungsplan, WMS. | [Link](https://opendata.muenchen.de/dataset/g_fnp) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 72 | Referat für Stadtplanung und Bauordnung | Globalstrahlung Dächer | GeoDaten | ✅ Offen verfügbar | ✅ Offen, als Kartendienst | Solarpotenzialanalyse 2018; funktionierender GSM-WMS, siehe Nr. 66. | [Link](https://opendata.muenchen.de/dataset/solarpotenzial_globalstrahlung_p_02), [Link 2](https://geoportal.muenchen.de/geoserver/gsm/ows?service=WMS&request=GetCapabilities) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 73 | Referat für Stadtplanung und Bauordnung | Wärmedichte der Gebäude | GeoDaten | ✅ Offen verfügbar | ✅ Offen, als Kartendienst | Wärmedichte, WMS. | [Link](https://opendata.muenchen.de/dataset/gebaeude_waermedichte_o_geb_03) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 74 | Referat für Stadtplanung und Bauordnung | Potential für Grundwasserwärmepumpen | GeoDaten | ✅ Offen verfügbar | ✅ Offen, als Kartendienst | Grundwasserpotenzial, WMS auf Baublockebene. | [Link](https://opendata.muenchen.de/dataset/enp_baublock_grundwasserpotential_einteilig_25832) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 75 | Referat für Stadtplanung und Bauordnung | Städtische Bevölkerungsprognose | GeoDaten | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | Bevölkerungsprognose 2025–2045, Demografiebericht Teil 1. Offener strukturierter Datensatz nicht nachgewiesen. | [Link](https://stadt.muenchen.de/infos/bevoelkerungsprognose.html) | – |
| 76 | Referat für Stadtplanung und Bauordnung | Bevölkerungsprognose für die Stadtbezirke | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | Bevölkerungsprognose, Demografiebericht Teil 2 für die 25 Stadtbezirke. | [Link](https://stadt.muenchen.de/infos/bevoelkerungsprognose.html) | – |
| 77 | Referat für Stadtplanung und Bauordnung | Umgriffe der Erhaltungssatzungen | GeoDaten | ✅ Offen verfügbar | ✅ Offen, als Kartendienst | Gebiete mit Erhaltungssatzungen, WMS. | [Link](https://opendata.muenchen.de/dataset/erhalt_umgriff) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 78 | Sozialreferat | Anzahl der gestellten Anträge auf geförderten Wohnraum | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich / Bericht | Wohnungsmarktbeobachtung und Berichte zur Wohnungssituation; keine passende offen lizenzierte CSV-Zeitreihe nachgewiesen. | [Link](https://stadt.muenchen.de/infos/wohnungsmarktbeobachtung-muenchen.html) | – |
| 79 | Sozialreferat | Anzahl der registrierten Haushalte für geförderten Wohnraum | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich / Bericht | Bericht zur Wohnungssituation 2024–2025; keine entsprechende offene Datenreihe nachgewiesen. | [Link](https://stadt.muenchen.de/dam/jcr%3Ac3b309dc-4645-4788-bd83-7749faceb273/LHM_Bericht_Wohnbausituation_24_25_RZ01.pdf) | – |
| 80 | Sozialreferat | Mietspiegel | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | Mietspiegel 2025 mit Rechner, Broschüre und Dokumentation. Kein aktueller offen lizenzierter Rohdatensatz nachgewiesen. | [Link](https://2025.mietspiegel-muenchen.de/) | – |
| 81 | Sozialreferat | Sozialbürgerhäuser | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Sozialbürgerhäuser, CSV und Geodaten. | [Link](https://opendata.muenchen.de/dataset/bestand_sbh_opendata) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 82 | Sozialreferat | Vollstationäre Pflegeeinrichtungen | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Vollstationäre Pflegeeinrichtungen, CSV und Geodaten. | [Link](https://opendata.muenchen.de/dataset/vollst_pflegeeinrichtung_opendata) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 83 | Sozialreferat | Familienangebote | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich, technisch abrufbar | GeoJSON-Dienst Familienangebote funktioniert. Lizenz nicht verlässlich zuordenbar: Der Metadatenverweis des Dienstes führt zu einem anderen Thema. | [Link](https://geoportal.muenchen.de/geoserver/soz_wfs/ows?service=WFS&version=1.1.0&request=GetFeature&typeName=soz_wfs:familienangebote&outputFormat=application/json) | – |
| 84 | Sozialreferat | Angebote der offenen Kinder- und Jugendarbeit | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich, nicht als offen bestätigt | Im Sozialreferats-WMS vorhanden. Die Metadaten verlangen für die Webdienstnutzung eine gesonderte Vereinbarung. | [Link](https://geoportal.muenchen.de/geoserver/soz_wfs/ows?service=WMS&request=GetCapabilities), [Link 2](https://geoportal.muenchen.de/csw?service=CSW&version=2.0.2&request=GetRecordById&elementSetName=full&outputSchema=http://www.isotc211.org/2005/gmd&id=84c2d584-9685-4e71-b34b-01c04d160754) | – |
| 85 | Sozialreferat | Unterkünfte für Geflüchtete und Wohnungslose ab 48 Bettplätzen | Bisher nur Nennung | 📄 Öffentlich zugänglich, offene Lizenz unklar | 📄 Öffentlich | Unterkunftsübersicht mit Liste und Karte, Stand Juni 2026; zusätzlich Geoportal. Offene Lizenz nicht nachgewiesen. | [Link](https://stadt.muenchen.de/infos/unterkuenfte-fuer-gefluechtete.html), [Link 2](https://geoportal.muenchen.de/portal/unterkuenfte/) | – |
| 86 | Stadtkämmerei | Ordentliche Erträge und Aufwendungen der LHM-Produkte | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Erträge und Aufwendungen, CSV. | [Link](https://opendata.muenchen.de/dataset/ordentliche-ertraege-und-aufwendungen-produkte-der-lhm) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 87 | Stadtkämmerei | Bilanzsumme, Eigenkapital und Eigenkapitalquote der LHM | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Bilanzkennzahlen, CSV. | [Link](https://opendata.muenchen.de/dataset/bilanzsumme-eigenkapital-und-eigenkapital-quote-lhm) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 88 | Stadtkämmerei | Schuldenstand der LHM, Hoheitshaushalt | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Schuldenstand, CSV. | [Link](https://opendata.muenchen.de/dataset/schuldenstand-hoheitshaushalt-lhm) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 89 | Stadtkämmerei | Pro-Kopf-Verschuldung der LHM, Hoheitshaushalt | Datensatz liegt vor | ✅ Offen verfügbar | ✅ Offen | Pro-Kopf-Verschuldung, CSV. | [Link](https://opendata.muenchen.de/dataset/pro-kopf-verschuldung-lhm-hoheitshaushalt) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 90 | Stadtwerke München | Fahrten mit dem MVG Rad | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen, historischer Bestand | MVG-Rad-Fahrten, CSV-Dateien in ZIP; Katalog nennt bis September 2025. | [Link](https://opendata.muenchen.de/dataset/fahrten-mit-dem-mvg-rad) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 91 | Stadtwerke München | ÖPNV-Netz der MVG | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | MVG-GTFS enthält Haltestellen und Routenverläufe; CC BY 4.0. | [Link](https://opendata.muenchen.de/dataset/mvg-fahrplandaten-solldaten) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 92 | Stadtwerke München | Sollfahrplandaten der MVG (GTFS) | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | MVG-Sollfahrplandaten, direkter GTFS-Download, CC BY 4.0. | [Link](https://opendata.muenchen.de/dataset/mvg-fahrplandaten-solldaten), [Link 2](https://www.mvg.de/static/gtfs/google_transit.zip) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 93 | Tierpark Hellabrunn | Besucherzahlen | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Daten Tierpark Hellabrunn, CSV 2008–2025. | [Link](https://opendata.muenchen.de/dataset/daten-tierpark-hellabrunn) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 94 | Tierpark Hellabrunn | Tierarten | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Kennzahlen und detaillierte Tierbestandslisten. | [Link](https://opendata.muenchen.de/dataset/daten-tierpark-hellabrunn), [Link 2](https://opendata.muenchen.de/dataset/tierbestandsliste-tierpark-hellabrunn) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 95 | Tierpark Hellabrunn | CO₂-Verbrauch (so im Original) | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Tierparkdaten, eigene Spalte in Tonnen, bis 2025. | [Link](https://opendata.muenchen.de/dataset/daten-tierpark-hellabrunn) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |
| 96 | Tierpark Hellabrunn | Anzahl der Artenschutzprojekte | Bisher nur Nennung | ✅ Offen verfügbar | ✅ Offen | Tierparkdaten, jährliche Anzahl, bis 2025. | [Link](https://opendata.muenchen.de/dataset/daten-tierpark-hellabrunn) | [DL-DE-BY 2.0](https://www.govdata.de/dl-de/by-2-0) |

Quellen: [Sitzungsvorlage V 05865 (2022)](https://www.muenchen-transparent.de/dokumente/7132160), [Sitzungsvorlage V 17861 (2025)](https://www.muenchen-transparent.de/dokumente/9285003). Die Einstufung ist eine unabhängige Recherche und keine offizielle Bewertung der Landeshauptstadt München.

Last updated: 2026-10-25
