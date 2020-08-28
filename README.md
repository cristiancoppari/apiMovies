# Documentacion

# Endpoints :

## --> http://localhost:3000/movies

## --> http://localhost:3000/series

## MOVIES

### Listado completo de películas --> http://localhost:3000/movies

// Muestra un listado de todas películas

### Detalle de película --> http://localhost:3000/movies/:id

// Muestra el detalle de 1 pelicula en particular

### Agregar nueva película --> http://localhost:3000/movies/create

// Agrega una nueva película.
// Se deben tener en cuenta los siguientes campos:
{ title, rating, awards, release_date, length }

## SERIES

### Listado completo de series --> http://localhost:3000/series

// Muestra un listado completo de series

### Detalle de serie --> http://localhost:3000/series/:id

// http://localhost:3000/api/series/1

### Agregar nueva serie --> http://localhost:3000/series/create

// Agrega una nueva serie.
// Se deben contemplar los siguientes campos :
{ title, release_date, end_date}
