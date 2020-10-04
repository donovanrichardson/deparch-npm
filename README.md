# deparch

`deparch` will allow users to quickly spin up an API to provide trip departure information from various transit agencies. This project is inspired by the practice, common in Japan, of creating departure timetables which show scheduled departure times buses and trains. The virtual absence of this practice in the United States led me to create this.

`deparch` works by fetching GTFS feeds from [OpenMobilityData] and importing them into a PostgreSQL database using `knex`.

