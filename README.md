# FAIR Data 2026 Project

FAIRification project for the English Premier League 2024/2025 match-results dataset, completed by Group 8 for the FAIR Data Engineering course.

## Group members

- Pol Cabanes Piqueras — [Cabanes02](https://github.com/Cabanes02)
- Victor Delgado Placido — [victordelgadoplacido](https://github.com/victordelgadoplacido)

## Persistent identifier namespace

Planned Group 8 namespace:

`https://w3id.org/FAIR-course-UT/2026/group08/`

The namespace will become active after the Group 8 redirect rules are accepted in the [course PID relay repository](https://github.com/luizbonino/pid-relay).

## Dataset

The project uses the English Premier League 2024/2025 match-results dataset from [DataHub](https://datahub.io/football/english-premier-league). The original CSV contains 380 matches and 22 columns. A prepared version preserves all 380 matches and contains the nine properties selected for semantic modelling.

The source dataset is licensed under the [Open Data Commons Public Domain Dedication and License 1.0](https://opendatacommons.org/licenses/pddl/1-0/).

## Repository structure

- `data/premier-league-2024-2025-original.csv` — preserved original dataset.
- `data/premier-league-2024-2025-prepared.csv` — prepared nine-column dataset.
- `data/premier-league-2024-2025-rdf.ttl` — RDF representation of the match data (pending).
- `metadata/schemas/dataset-shape.ttl` — Dataset SHACL schema.
- `metadata/schemas/distribution-shape.ttl` — Distribution SHACL schema.
- `metadata/records/` — RDF metadata records for the dataset and its distributions (pending).

## Current publication status

- [x] Original CSV
- [x] Prepared CSV
- [x] Dataset SHACL schema
- [x] Distribution SHACL schema
- [ ] RDF match data
- [ ] Dataset metadata record
- [ ] CSV distribution metadata record
- [ ] RDF distribution metadata record
- [ ] W3ID redirect rules
