# Laboratorio Número 2

<b>Sección:</b> 1

<b>Fecha:</b> Jueves 16 de Junio

<b>Horario:</b> 18:00

<b>Duración:</b> 2 Hora

<b>Nombre Completo del Estudiante:</b>

<b>Código:</b>

<b>Usuario gitHub:</b>

Leer detenidamente la pregunta. 

## <b>Pregunta 1:</b> 

UtecPeliculas es una `restful API` que facilita el descubrimiento para visualizar películas en las diferentes salas de la Universidad de Ingeniería y Tecnología. 

Las `APIs` te permiten listar nuevas películas, generos de películas, actores que pertenecen a alguna película, los países a los que pertenecen las peliculas y país de nacimiento de los actores.

La idea es construir los [`modelos`](./pregunta1/backend/models.py) para implementar los [`endpoints`](./pregunta1/backend/server/__init__.py), conectarlos a una base de datos `PostgresQL` llamada `peliculasdb` para guardar la información, consultarla y crear nueva data de los recursos.

## Visión General

Los modelos están vacíos, cada modelo contiene una documentación sobre que propiedades, llaves primarias (`PK`), llaves foráneas (`FK`) y usted tiene que implementarlo.

Las [`APIs`](./pregunta1/backend/server/__init__.py) están vacías, cada endpoint debe ser implementado para recuperar, buscar, actualizar, eliminar y crear a partir de una base de datos, adicionalmente permitir `CORS` para el siguiente ;<b>HOST:</b> `http://127.0.0.1:8081`

Los [`tests`](./pregunta1/backend/test_peliculas_api.py) estan vacíos, y tienen nombres muy intuitivos sobre lo que tienes que verificar con `asserts`. Cada test debe tener como mínimo el assert del `status_code`, assert de `success` o `failed`, y `assertTrue` para alguna respuesta.

Queremos que UtecPeliculas provea una `API` con todos los estandares para que los clientes puedan utilizarlo y crear una aplicación segura, entendible y escalable.


## Rúbrica

Existen 4 recursos: 
<ol>
    <li>Películas</li>
    <li>Generos</li>
    <li>Actores</li>
    <li>Paises</li>
</ol>

El puntaje máximo que se puede obtener por terminar correctamente los 9 tests por recurso es de 5 puntos y el mínimo es de 0 puntos.

Por cada recurso tenemos la siguiente Rúbrica.

| Puntajes por Modelo |                                                                                                                                                                Descripción                                                                                                                                                                |
|:-------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|          0          | 0 tests implementados, o implementados incorrectamente, sin inicializar el test cliente y el servidor<br> 0 modelos implementados, no tiene métodos o propiedades seteadas con tipos de datos correctos.<br> 0 APIs implementados o implementados incorrectamente, sin ninguna funcionalidad clara o validaciones de lógica de negocios.  |
|          1          | 3 tests implementado correctamente, inicializando el test cliente y el servidor<br> como consecuencia el modelo implementado, tiene métodos y propiedades seteadas con tipos de datos correctos.<br> y el API implementado correctamente, con funcionalidad clara y validaciones de lógica de negocios.                                   |
|          2          | 5 tests implementados correctamente inicializando el test cliente y el servidor<br> como consecuencia los modelos implementados, tienen métodos y propiedades seteadas con tipos de datos correctos.<br> y las APIs implementadas correctamente, con funcionalidades claras y validaciones de lógica de negocios.                         |
|          3          | 6 tests implementados correctamente inicializando el test cliente y el servidor<br> como consecuencia los modelos implementados, tienen métodos y propiedades seteadas con tipos de datos correctos.<br> y las APIs implementadas correctamente, con funcionalidades claras y validaciones de lógica de negocios.                         |
|          4          | 7 tests implementados correctamente inicializando el test cliente y el servidor<br> como consecuencia los modelos implementados, tienen métodos y propiedades seteadas con tipos de datos correctos.<br> y las APIs implementadas correctamente, con funcionalidades claras y validaciones de lógica de negocios.                         |
|          5          | 9 tests implementados correctamente inicializando el test cliente y el servidor<br> como consecuencia los modelos implementados, tienen métodos o propiedades seteadas con tipos de datos correctos.<br> y las APIs implementadas correctamente, con funcionalidades claras o validaciones de lógica de negocios.                         |