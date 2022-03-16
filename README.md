# DesafioTecnicoCleverIT
CLEVERIT - Desafío Técnico
Prueba QA Automation

Ejercicio 1 --------------> (QAA-01) API Temperatura

Descripción:
Crear los casos de prueba posibles para testear el siguiente microservicio GET, que recibe:
En el request la fecha del día actual en formato DD-MM-AAAA.
Dos headers, el primero es "Country", cuyo dominio de valores puede ser "Chile" o "Argentina" y el segundo es "City", cuyo dominio de
valores es "Santiago","Arica", "Chiloe" (cuando se trata de Country Chile) y "BuenosAires", "SanJuan" (cuando country es Argentina)
Cuando el resultado es positivo entrega status ok y código http 200 y en caso de error el status es "client error" y en caso de error de
conexion el status es "server error" y en el caso de codigo para cada uno de estos status se entrega los codigos http de error estándar.
Considera que cuando es un País distinto a los señalados o una ciudad distinta el response "País y Ciudad incorrectos", y que todos los
campos a ingresar son Sensitive Case.

El response del microservicio devuelve la temperaturaActual y temperaturaDiaSiguiente en formato json.

Ejercicio 2  --------------> (QAA-02) - Automatización de API

Descripción:
Tenemos la siguiente API https://jsonplaceholder.typicode.com/
Y esta API tiene los siguientes EndPoints de consulta:
- posts 100 posts
- comments 500 comments
- albums 100 albums
- photos 5000 photos
- todos 200 todos
- users 10 users

Considerando esta API y sus recursos, selecciona 3 de estos recursos y diseñar los casos de prueba funcionales que veas adecuados y luego
automatiza al menos 6 casos de prueba distintos (debe ser en Postman).

Ejercicio 3  -------------->  (QAA-03) Explicación de técnicas

Descripción:
Para ambos ejercicios 1 y 2, explicar las técnicas que usaste para generar las pruebas y donde fueron aplicadas.
Además de cuales son los puntos a tener en cuenta cuando probamos una API
