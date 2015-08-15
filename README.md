# EjerciciosEspai capitulo 9 
Ejercicios para el curso de C++

Ejercicios capítulo 9
1. Explica para qué sirve declarar una función como const
2. ¿Qué ventajas ofrece separar la declaración de una función de su definición?
3. En el capítulo anterior hicimos una práctica final, la gestión de un garaje. Adapta el código para que
la declaración y definición estén separadas, esto es divide en un .h y un .cpp las clases Vehículo y
Plaza.
4. En la misma práctica ya utilizamos una clase como dato miembro de otra, esto es dentro de Plaza
guardamos objetos Vehículo. Esta vez añadiremos a Vehículo un objeto tipo Radio, que tendrá las
funciones encender, apagar(), sintonizar() y variarVolumen().
Claves:
- Define las variables como privadas
- Declara métodos accesores para las mismas
- Crea un constructor en el que indiquemos la marca de la radio, así como los valores iniciales de
los miembros de la nueva clase.
- Separa la declaración de la definición en un .h y un .cpp

5. Práctica final del capítulo
Vamos a crear una aplicación para gestionar una liga de fútbol. El programa tendrá las siguientes
opciones:
1. Introducir equipo: Nos permite añadir un equipo a la liga
2. Eliminar equipo: Nos permite eliminar un equipo
3. Introducir Partidos de la Jornada: De forma manual, emparejaremos los equipos para la jornada
actual.
4. Resultado Partidos de la Jornada: Queremos guardar el resultado de la jornada actual. Cuando
se introduzca el último resultado de partido, avanzamos de jornada. Este hecho se le debe
notificar al usuario.
5. Mostrar partidos: Mostramos los emparejamientos y resultados de la jornada actual.
6. Mostrar liga: Mostramos todos los partidor y resultados de la liga hasta el momento.
7. Salir
Utiliza las clases que consideres necesarias. Como sugerencia podrían ser Equipo, Partido y Liga.
Un partido esta compuesto de 2 equipos. Una jornada, de varios partidos. Y una liga, de varias
jornadas.
