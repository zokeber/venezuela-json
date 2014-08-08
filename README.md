#  ![] (http://i.imgur.com/88FpuUJ.png) Venezuela-JSON

Creemos que las bases de datos No-SQL son geniales, por ello queremos ofrecele a los desarrolladores venezolanos un recurso útil para sus proyectos. Básicamente, **Venezuela-JSON** es un documento en formato [JSON] (http://es.wikipedia.org/wiki/JSON) que agrupa todos los estados, ciudades, municipios y parroquias de Venezuela.

Inspirado en el excelente trabajo de [**marydn**] (https://github.com/marydn) en [venezuela-sql] (https://github.com/marydn/venezuela-sql) y motivado por la ausencia de proyectos de éste tipo, **Venezuela-JSON** apunta a ser la mejor elección para todo aquél que  requiera la organización territorial de Venezuela en `.json`.

# Uso
El documento `venezuela.json` es ideal para ser importado a una base de datos No-SQL. Como sabemos que existen muchas soluciones de este tipo, te dejamos las instrucciones necesarias para importarlo a algunas de las más conocidas.

#### MongoDB

Para importar `venezuela.json` a [MongoDB] (http://www.mongodb.com/mongodb-overview) sólo debes escribir en tu consola:

```bash
mongoimport --jsonArray --db tu_base_de_datos --collection tu_coleccion --type json --file "/ruta/a/venezuela.json"
```
#### Couchbase

*Pendiente*

#### CouchDB

*Pendiente*

#### Cassandra

*Pendiente*

#### Riak

*Pendiente*

# Referencias

- [Municipios de Venezuela] (https://es.wikipedia.org/wiki/Anexo:Municipios_de_Venezuela)
- [Parroquias de Venezuela] (https://es.wikipedia.org/wiki/Categor%C3%ADa:Anexos:Parroquias_de_Venezuela)



