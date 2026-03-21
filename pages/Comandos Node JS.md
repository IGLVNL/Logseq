- **Node**
	- Es el comando que inicia el interprete interactivo de Node **REPL**
	- Todo lo que se escriba en ese entorno se interpreta como código JS, no como comando, sirve para hacer pruebas de código.
	- ***Comandos permitidos dentro del modo REPL***
	  collapsed:: true
		- **.break**
		  collapsed:: true
			- A veces te quedas atascado, esto te saca. Lo que hace es **interrumpir la entrada actual** en el REPL. Si estabas escribiendo una línea de código incompleta o te quedaste en medio de una expresión, `.break` cancela esa entrada y te devuelve al prompt limpio para que puedas seguir escribiendo. Es como un “reset” de la línea actual, pero sin cerrar la sesión completa (a diferencia de `.exit`, que sí termina el REPL).
		- **.clear**
		  collapsed:: true
			- Limpia la línea actual o interrumpe la entrada que estabas escribiendo.
		- **.editor**
		  collapsed:: true
			- **Entrar en modo editor**. Te permite abrir un mini editor dentro del REPL para escribir varias líneas de código. Cuando terminas, se ejecuta todo junto.
		- **.exit**
		  collapsed:: true
			- Cierra la sesión interactiva y vuelves a la terminal normal.
		- **.help**
		  collapsed:: true
			- Imprime el mensaje de ayuda con todos los comandos disponibles.
		- **.load**
		  collapsed:: true
			- Ejecuta el contenido de un archivo JavaScript dentro del REPL. Ejemplo:
			- ```
			  .load miArchivo.js
			  ```
		- **.save**
		  collapsed:: true
			- Permite guardar todas las instrucciones que ejecutaste en la sesión en un archivo. Ejemplo:
			- ```
			  .save historial.js
			  ```
		- **Ctrl+C**
		  collapsed:: true
			- aborta expresión actual
		- **Ctrl+D**
		  collapsed:: true
			- Sale del modo REPL
	- Si una línea no devuelve nada, entonces aparece el mensaje *undefined*
- **node 'nombreArchivo.js'**
	- Ejecuta el codigo del archivo especificado
-