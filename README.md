#  ![] (http://i.imgur.com/88FpuUJ.png) Venezuela-JSON

Estados, Ciudades, Municipios y Parroquias de Venezuela en formato JSON.

# Uso
El documento `venezuela.json` es ideal para ser importado a una base de datos No-SQL. Por ello, te dejamos las instrucciones necesarias para lograrlo.

### MongoDB

Para importar `venezuela.json` a [MongoDB] (http://www.mongodb.com/mongodb-overview) sólo debes escribir en tu consola:

```bash
mongoimport --jsonArray --db tu_base_de_datos --collection tu_coleccion --type json --file "/ruta/a/venezuela.json"
```

# Referencias

- [Municipios de Venezuela] (https://es.wikipedia.org/wiki/Anexo:Municipios_de_Venezuela)
- [Parroquias de Venezuela] (https://es.wikipedia.org/wiki/Categor%C3%ADa:Anexos:Parroquias_de_Venezuela)



