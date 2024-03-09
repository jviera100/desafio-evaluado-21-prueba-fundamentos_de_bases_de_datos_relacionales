Prueba - Fundamentos de bases de datos
relacionales
En esta prueba validaremos nuestros conocimientos de SQL. Para lograrlo, necesitarás
aplicar lo aprendido en las unidades anteriores.
Lee todo el documento antes de comenzar el desarrollo individual, para asegurarte de tener
el máximo de puntaje y enfocar bien los esfuerzos.
// Tiempo asociado: 2 horas cronológicas.
Descripción
La prueba consiste en realizar un video explicando cada uno de los requerimientos. Debes ir
ejecutando las acciones descritas en requerimientos y explicar lo que estás haciendo.
Resuelve los requerimientos previo a grabar y guárdalos en un archivo de texto.
● El video lo debes subir a youtube o vimeo en modo público. Si prefieres, puedes
marcarlo como no listado de forma que solo quienes tengan el link puedan
acceder a él.
● Al final debes compartir en el LMS el link de acceso al video.
● ⚠️ ¡Importante! Para que el desafío sea evaluado el entregable tiene que ser un
video y con postgreSQL instalado.
Nota:
● No es necesario grabar con la cámara encendida, solo pantalla y sonido.
● No es necesario que el sonido sea perfecto pero debe poder escucharse bien
para poder evaluar correctamente el desafío.
_ 1
www.desafiolatam.com
Requerimientos
Dado el siguiente modelo:
1. Crea el modelo (revisa bien cuál es el tipo de relación antes de crearlo), respeta las
claves primarias, foráneas y tipos de datos.
(1 punto)
2. Inserta 5 películas y 5 tags, la primera película tiene que tener 3 tags asociados, la
segunda película debe tener dos tags asociados.
(1 punto)
3. Cuenta la cantidad de tags que tiene cada película. Si una película no tiene tags debe
mostrar 0.
(1 punto)
_ 2
www.desafiolatam.com
Dado el siguiente modelo:
4. Crea las tablas respetando los nombres, tipos, claves primarias y foráneas y tipos de
datos.
(1 punto)
5. Agrega datos, 5 usuarios y 5 preguntas, la primera pregunta debe estar contestada
dos veces correctamente por distintos usuarios, la pregunta 2 debe estar contestada
correctamente sólo por un usuario, y las otras 2 respuestas deben estar incorrectas.
(1 punto)
a. Contestada correctamente significa que la respuesta indicada en la tabla
respuestas es exactamente igual al texto indicado en la tabla de preguntas.
6. Cuenta la cantidad de respuestas correctas totales por usuario (independiente de la
pregunta).
(1 punto)
7. Por cada pregunta, en la tabla preguntas, cuenta cuántos usuarios tuvieron la
respuesta correcta.
(1 punto)
8. Implementa borrado en cascada de las respuestas al borrar un usuario y borrar el
primer usuario para probar la implementación.
(1 punto)
9. Crea una restricción que impida insertar usuarios menores de 18 años en la base de
datos.
(1 punto)
10. Altera la tabla existente de usuarios agregando el campo email con la restricción de
único.
(1 punto)
_ 3
www.desafiolatam.com
Consideraciones y recomendaciones
Si no tienes una herramienta para grabar pantalla puedes utilizar cualquiera de las
siguientes:
● Loom.
● Vidyard.
● Plugin grabador de pantalla.
_ 4
www.desafiolatam.com
