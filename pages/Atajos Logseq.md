-
	- # 1.  Estilos  básicos  de  texto
	  | Estilo | Cómo escribirlo | Resultado |
	  | ---- | ---- | ---- |
	  | Negrita | `**texto**` | **texto** |
	  | Itálica | `*texto*` o `_texto_` | *texto* |
	  | Negrita + Itálica | `***texto***` | **texto** |
	  | Tachado | `~~texto~~` | ~~texto~~ |
	  | Resaltado | `^^texto^^` | texto resaltado |
	  | Código inline | ``codigo`` | `codigo` |
	  ---
	- 2.  Encabezados ( Headings)
		- Sirven para estructurar páginas.
		- | Nivel | Sintaxis |
		  | ---- | ---- | ---- |
		  | H1 | `# Título` |
		  | H2 | `## Título` |
		  | H3 | `### Título` |
		  | H4 | `#### Título` |
		  ---
	- 3.  Listas
		- Lista con viñetas
			- item
			- item
			- item
		- Lista numerada
			- 1. item
			  2. item
			  3. item
	- 4. Checkboxes (tareas)
		- | Tipo | Sintaxis |
		  | ---- | ---- | ---- |
		  | Tarea pendiente | `TODO tarea` |
		  | En progreso | `DOING tarea` |
		  | Hecha | `DONE tarea` |
		  | Cancelada | `CANCELED tarea` |
		  | Checkbox simple | `- [ ] tarea` |
		  | Checkbox completado | `- [x] tarea` |
	- 5. Links y referencias
		- Link  a  página
		  
		  ```
		  [[Nombre de la página]]
		  ```
		- Link  a  bloque
		  
		  ```
		  ((block-id))
		  ```
		- URL  externa
		  
		  ```
		  [texto](https://link.com)
		  ```
	- 6. Embeds
		- Incrustar  página
		  ```
		  {{embed [[Nombre de pagina]]}}
		  ```
		- Incrustar  bloque
		  ```
		  {{embed ((block-id))}}
		  ```
	- 7.  Citas
	  ```
	  > texto citado
	  ```
	  Resultado: texto citado
	- 8.  Bloques  de  código
	  ```javascript
	  console.log("hola")
	  ```
	- 9.  Separadores
	  ```
	  ---
	  ```
	  
	  Genera una línea horizontal.
	- 10.  Tablas
	  | Col1 | Col2 |
	  |------|------|
	  | A | B |
	  | C | D |
	- 11.  Etiquetas ( tags)
	  ```
	  #tag
	  ```
	  o
	  ```
	  #[[tag]]
	  ```
	- 12.  Propiedades
	  Se usan mucho en **bases de conocimiento**.
	  ```
	  propiedad:: valor
	  ```
	  Ejemplo:
	  ```
	  autor:: Ignacio
	  tema:: UX Research
	  ```
	- # 13.  Bloques  especiales  de  Logseq
		- Query
		  
		  ```
		  {{query (todo TODO)}}
		  ```
		- Card ( para  flashcards)
		  ```
		  pregunta #card
		  respuesta
		  ```
	- 14.  Atajos  de  teclado  útiles
		- | Atajo | Función |
		  | ---- | ---- | ---- |
		  | `Tab` | Indentar bloque |
		  | `Shift + Tab` | Desindentar |
		  | `Enter` | Nuevo bloque |
		  | `Shift + Enter` | Salto de línea dentro del bloque |
		  | `Ctrl + B` | Negrita |
		  | `Ctrl + I` | Itálica |
		  | `Ctrl + K` | Insertar link |
		  | `Ctrl + Shift + H` | Resaltar |
		  | `Ctrl + /` | Mostrar comandos |
	- **Tip importante en Logseq**
		- En lugar de recordar toda la sintaxis, podés escribir:
		  ```
		  /
		  ```
		  y aparece el **menú de comandos**, desde donde podés insertar:
			- tablas
			- código
			- citas
			- queries
			- templates
			- embeds