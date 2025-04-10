Plan de ataque
Objetivo: El objetivo de este documento es detallar las estrategias de pruebas que se implementaran en el juego “Adivina tu número”, así como los cambios realizados en el código para que este funcionará y cumpliera con los requisitos especificados.


Casos de Pruebas
1- Número mayor que el aleatorio 
Descripción: Ingresar un valor numérico que sea mayor que el aleatorio.
Resultado esperado:  Mostrar el mensaje “Incorrecto, el número es mayor”.

2- Número menor que el aleatorio
Descripción: Ingresar un valor numérico que sea menor que el aleatorio.
Resultado esperado:  Mostrar el mensaje “Incorrecto, el número es menor”.

3- Número igual que el aleatorio
Descripción: Ingresar un valor numérico que sea igual que el aleatorio.
Resultado esperado:  Mostrar el mensaje “Felicidades, has adivinado el número aleatorio”.

4- Numero de intentos alcanzado
Descripción: alcanzar el total de números de intentos permitidos.
Resultado esperado:  Mostrar el mensaje “Ha alcanzado el total de intentos, jugar de nuevo”.

5- Reinicio del juego
Descripción: Luego de adivinar o alcanzar el número de intentos ingresar desde el botón “Reiniciar Juego”
Resultado esperado:  Mostrar el mensaje “Incorrecto, el número es menor”.

6- Validación de input no numérico
Descripción: Ingresar un valor no numérico como caracteres tipo string.
Resultado esperado:  Mostrar el mensaje “Tipo de dato incorrecto intente ingresando valores enteros (3 dígitos)”.

7- Validación de input número (flotantes)
Descripción: Ingresar un valor numérico como de tipo flotante.
Resultado esperado:  Mostrar el mensaje “Valor ingresado incorrecto, intente ingresando valores enteros (3 dígitos)”.

8- Validación de input por la cantidad de caracteres de entrada
Descripción: Ingresar más de 3 valores enteros.
Resultado esperado:  Mostrar el mensaje “Cantidad de dígitos incorrecta, intente ingresando valores enteros (3 dígitos)”.

9- Validación del input caracteres y números flotantes o decimales
Descripción: Ingresar un valor no numérico como caracteres tipo string y digitos numéricos combinados.
Resultado esperado:  Mostrar el mensaje “Tipo de datos no permitido, intente ingresando valores enteros (3 dígitos).”

Evidencias del código corregido
1- El juego se concluyó en 7 intentos máximo según las pruebas realizadas.

2- Se eliminarón espacios innecesarios para mejorar la visualización del código.

