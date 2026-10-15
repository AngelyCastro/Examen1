# SAVIA — examen N.º 1

Proyecto estático HTML + CSS. Abrir `index.html` en el navegador. No necesita dependencias.

El sitio incluye la página Inicio y las plantillas `pages/menu.html`, `pages/equipo.html` y `pages/eventos.html` con contenido central pendiente. Siga exclusivamente las especificaciones del examen para conocer el comportamiento esperado. No modifique el tema general ni sustituya el proyecto por otro.

## Diagnóstico de cinco incidencias

| N.º | Comportamiento observado | Causa técnica y ubicación | Corrección realizada | Prueba de verificación | Autor |
|---|---|---|---|---|---|
| 1 | Tres tarjetas una debajo de otra| se estaba utilizando flex, style.css linea 123|se cambio  display grid  se uso grid-template-columns|![alt text](image-1.png)![alt text](image.png)  | Angely, Amanda, Valeria|
| 2 |Al sleccionar nuestra carta dirigia eventos, no tenia navbar |tenia una una direccion de pagina incorrecta y tanto en eventos, menu y equipos hacia falta el navbar![alt text](image-4.png) ![alt text](image-3.png)|Se corrigio la ruta y cada una de las pantallas se agrego el nav ![alt text](image-2.png) ![alt text](image-5.png) ![alt text](image-6.png) |![alt text](image-7.png) |  Angely, Amanda, Valeria|
| 3 |Al dar click no dirigia a nuestra carta |La direccion estaba incompleta ![alt text](image-8.png)| en la linea 30 ![alt text](image-9.png)| ![alt text](image-10.png)| Angely, Amanda, Valeria |
| 4 | El boton esta rojo|El btn tenia estilo del id incorrecto![alt text](image-11.png) |El id tenia un color distinto, se puso una variable adecuada![alt text](image-13.png) |![alt text](image-12.png) | Angely, Amanda, Valeria |
| 5 |Todo se encontraba en una sola linea |Se veia todo en una sola linea, porque el media el max esta para 750px no 375px ![alt text](image-15.png) | Se cambio el 750px por 375px ![alt text](image-16.png)|![alt text](image-14.png) |  Angely, Amanda, Valeria|

## Responsables de las funcionalidades

| Estudiante | Página asignada | Rama | Commits principales |
|---|---|---|---|
| | | | |

## Evidencias Git

| Funcionalidad/corrección | PR hacia develop | Revisor | Resultado de merge / conflicto si ocurrió |
|---|---|---|---|
| | | | |

## Verificación final
Registrar las pruebas de funcionamiento a 1280 px y 375 px, enlaces y páginas.
