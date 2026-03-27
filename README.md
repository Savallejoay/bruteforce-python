1.-Descripción

Este trabajo implementa un algoritmo simple de fuerza bruta en Python que intenta adivinar una contraseña de prueba generada por el usuario.

El objetivo es demostrar cómo funcionan estos ataques y evidenciar la vulnerabilidad de contraseñas débiles.

2.-Cómo ejecutar el programa
Descargar el archivo y ejecutar el archivo .py 

3.-Cómo funciona?
-Se define una contraseña objetivo dentro del código.
-Se usa un alfabeto limitado (por ejemplo: letras minúsculas).
-El programa genera combinaciones posibles desde longitud 1 en adelante.
-Cada combinación se compara con la contraseña.
Cuando coincide:
	-Se muestra la contraseña encontrada
	-Número de intentos
	-Tiempo de ejecución
Ejemplos de Salida:
1.-
Contraseña encontrada: uide
Intentos: 5039737
Tiempo: 5.298568964004517 segundos
2.-
Contraseña encontrada: 2026
Intentos: 13315241
Tiempo: 15.718999147415161 segundos
3.-
Contraseña encontrada: igaf
Intentos: 2171928
Tiempo: 2.2668983936309814 segundos
Reflexion
Si una contraseña tiene 8 o más caracteres y combina mayúsculas, minúsculas, números y símbolos, el número de combinaciones posibles crece exponencialmente esto hace que un ataque de fuerza bruta requiera una cantidad de tiempo mucho mas grande volviéndose prácticamente inviable por eso es importante utilizar contraseñas largas y complejas
