### TODO

1. Obten mediante verbo `GET` el mapping del nuevo indice 'coches'
2. Mediante el uso del verbo `PUT`añade un nuevo coche con las siguientes caracteristicas
```json
  "marca" : "Ferrari",
  "modelo": "F40",
  "fecha_compra":"01-08-2004",
  "pais":"Italia",
  "precio":65200,
   "location":  
    "lat": 42.83,
    "lon": 12.83
 #################################
    "marca" : "Renault",
  "modelo": "R16",
  "fecha_compra":"11-01-1974",
  "pais":"Francia",
  "precio":1200.88,
   "location": { 
    "lat": 42.12,
    "lon": 0.34
 #################################
     "marca" : "Seat",
  "modelo": "Toledo",
  "fecha_compra":"09-09-2000",
  "pais":"España",
  "precio":3000.88,
   "location": { 
    "lat": 41.12,
    "lon": 0.34
```


. Crea un indice llamado 'coches' usando el comando `PUT` Los campos, tipo de dato y formato se detallan acontinuación.

| Campo        | Tipo      | Formato    |
|--------------|-----------|------------|
| descripcion  | text      |            |
| fecha_compra | date      | dd-MM-yyyy |
| marca        | text      |            |
| pais         | text      |            |
| modelo       | text      |            |
| precio       | float     |            |
| location     | geo_point |            |