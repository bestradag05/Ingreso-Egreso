# Ingresos y Egresos
El Sistema de Control de Ingresos y Egresos es una aplicación desarrollada en JavaScript que utiliza los conceptos de Programación Orientada a Objetos (POO),
Herencia y Arrow Functions para permitir a los usuarios administrar y calcular el porcentaje de sus egresos con respecto a sus ingresos.

El sistema consta de varias clases que representan entidades clave y sus relaciones. A continuación, se describen algunas de las clases y sus funcionalidades:

# Clase "Dato": 
Esta es la clase base que representa una transacción, que puede ser un ingreso o un egreso. Tiene propiedades como "valor" (valor de la transacción), "descripcion"
(una breve nota sobre la transacción). También tiene métodos para obtener y establecer sus propiedades. 

# Clase "Ingreso" (Hereda de "Dato"): 
Esta clase hereda de la clase "Dato" y representa una transacción de tipo ingreso. Además de las propiedades heredadas, puede tener una propiedad adicional, como 
"id" que representa el identificador de cada ingreso generado.

# Clase "Egreso" (Hereda de "Dato"): 
Al igual que la clase "Ingreso", esta clase hereda de "Dato" y representa una transacción de tipo egreso. Además de las propiedades heredadas, puede tener propiedades
adicionales, como "id" que representa el identificador de cada ingreso generado.

# Archivo "app.js": 
Este archivo es el núcleo del sistema y es responsable de aplicar la logica de todas las transacciones de ingresos y egresos. Tiene una lista de transacciones realizadas
y métodos para agregar nuevas transacciones, calcular el total de ingresos y egresos, y calcular el porcentaje de los egresos con respecto a los ingresos. Además, la 
aplicación utiliza Arrow Functions para definir algunos métodos de las clases, lo que permite una sintaxis más concisa y clara.


