![screenshot](https://camo.githubusercontent.com/c7cfb1e5bef9af3630d019527a62176ca3861e725b35adf41e3d544f9310d08a/68747470733a2f2f7075752e73682f4879726c492f376164666239313165322e706e67)

#
&nbsp;
### ⭐️  Buscamos Colaboradores️ ⭐️ 
Buscamos Devs con ganas de sumarse a los desafios que hoy tenemos en **Nubi**.

# Nubi Coding Challenge ☁️ &nbsp; ![easy](https://img.shields.io/badge/-medium-orangnge) ![time](https://img.shields.io/badge/%E2%8F%B0-60m-blue) 

&nbsp;
## Finalidad ✨

El objetivo de este desafío es desarrollar una API REST usando NodeJS. Dentro del directorio `data` encontrarás el archivo `users.json`. Utiliza ese archivo como fuente de datos para desarrollar una API que realizce las operaciones abajo descritas.
Si necesitas generar nuevos usuarios puedes usar el comando `npm run data`.

&nbsp;
## Requerimientos
Este challenge esta pensado para que pueda resolverse sin alguna libreria/dependencia particular, dejamos que puedas usar la tecnologia que creas conveniente para la resolucion del mismo.


&nbsp;
## Que esperamos una vez terminado el challenge 🏁
- un repositorio con codigo del challenge (publico)
- un readme detallado con las instrucciones para ejecutarlo
- Un endpoint para ver todos los usuarios
- Un endpoint para crear un nuevo usuario
- Un endpoint para eliminar un usuario
- Un endpoint para modificar un usuario
- Utilizar en cada endpoint una forma diferente de manejo de asincronismo (callbacks, promises, async/await)
- Usar typescript
- Que soporte QueryParams como:
  - pagination: `?page=2&limit=5`
  - sorting: `?sortBy=email&sortDirection=ascending`
  - matching: `?match[email]=jdoe@example.com`
- Seguridad (proteger los endpoints contra uso no autorizado, implementando algun mecanismo de validacion de acceso a los mismos)
- Test Unitarios
- Dockerfile y docker-compose que permita levantar la API ejecutando "docker-compose up" con todo lo necesario.
- Collection de postman o equivalente para probar todos los endpoints



&nbsp;
## Proceso de revisión ✅

Durante la revisión estamos considerando varios factores, entre ellos:
- Enfoque general para el desarrollo de API, como esten divividas las responsabilidades en el diseño.
- Estilo de código, claridad y consistencia. Corrección lógica.
- Simplicidad de la implementación.
- Buenas prácticas en el uso de docker.
- Correcto uso de dependencias npm.
- Flexibilidad de la solucion propuesta.
