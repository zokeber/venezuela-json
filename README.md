Venezuela-JSON
================

Venezuela states, cities, municipalities and parishes in format JSON for MongoDB.

### MongoDB import

For importing JSON data into MongoDB, please use:
```bash

mongoimport --jsonArray --db your_ddatabase --collection your_collection --type json --file states-cities.json

```

### Reference

1. Wikipedia Listas de Parroquias de cada estado de Venezuela https://es.wikipedia.org/wiki/Categor%C3%ADa:Anexos:Parroquias_de_Venezuela
2. Wikipedia Lista de Municipios de Venezuela por entidad federativa https://es.wikipedia.org/wiki/Anexo:Municipios_de_Venezuela

### Revisions
* 26 February 2014
* 30 December 2013

