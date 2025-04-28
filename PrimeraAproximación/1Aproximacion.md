# POSIBLE PLANTEAMIENTO DE LA APP

## LOGIN:

El login estaria basado en una base de datos con los siguientes campos:
1.  **ID:** INT, NOT NULL, AUTOINCREMENT, PRIMARY KEY
2.  **NAME:** STRING 255, NOT NULL
3.  **SURNAME:** STRING 255, NOT NULL
4.  **EMAIL:** STRING 255, NOT NULL
5.  **USER:** ENUM(Teacher,Student), NOT NULL

Con esta tabla llamda `Login` recogemos un id autoincremental y único por cada estudiante que se registre. Recogemos los datos de nombre apellido y correo con la categoria a la que pertenece si profesor o alumno, criterio que luego nos sirve para mostrar las estadisticas de los resultados obtenidos en el test.

## TEST:
Esta parte se podría abordar de diferentes formas, tener unicamente 10 preguntas con las 4 opciones de respuesta cada una, o con muchas preguntas y que se eligan 10 al azar, en donde en una tabla llamada `TEST` podemos tener los campos: 
1. **ID:** INT, NOT NULL, AUTOINCREMET, PRIMARY KEY
2. **QUESTION:** STRING 255, NOT NULL
3. **ANSWER:** STRING 255, NOT NULL

En esta tabla tenemos las preguntas que vamos a realizar en el cuestionario con la respuesta correcta y posteriormente usaremos los siguientes criterios de calificación: Bien +1; No contestada -0,125; Mal -0,25. Para aplicar los criterios de calificación se tiene que comparar las entradas de las respuestas de la tabla `STATS` y luego ejecutar la puntuación. 

## STATS
En este apartado tenemos una tabla llamada `STATS` en donde se guardaran, las respuestas a cada pregunta del test indicada por el usuario y su puntuación, Si esta seleccionada y es correcta +1, si esta seleccionada y es incorrecta -0,25, y si esta sin seleccionar -0,125. Donde posteriormente se recogerá tambien la puntuación total de cada pregunta y se podrá obtener la calificación. En esta tabla también podremos obtener estadisticas de pregunta más fallada, cual es la respuesta mas repetida dentro de las preguntas, etc.

1. **ID:** INT, NOT NULL, AUTOINCREMENT, PRIMARY KEY
2. **Apellidos:** STRING 255, NOT NULL
3. **R1:** STRING 255 
4. **R2:** STRING 255
5. **R3:** STRING 255
6. **R4:** STRING 255
7. **R5:** STRING 255
8. **R6:** STRING 255
9. **R7:** STRING 255
10. **R8:** STRING 255
11. **R9:** STRING 255
12. **R10:** STRING 255
13. **NOTA**: INT, NOT NULL

En esta base de datos podemos obtener todos los registros de los alumnos en cuanto a las preguntas contestadas que luego se pueden mostrar en gráficos o como se desee.


# ⚠️ DIFICULTADES

- ENCONTRAR LA APLICACIÓN PARA DESARROLLARLO
- DISTRIBUCIÓN DEL TRABAJO ENTRE TODOS YA QUE LA GRAN PARTE PERTENECE AL AMBITO INFORMÁTICO