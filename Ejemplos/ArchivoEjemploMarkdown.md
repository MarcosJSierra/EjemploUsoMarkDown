# Ejemplo Markdown Basico

## Formateando Texto

Una de las principales aplicaciones del Markdown es el formateo de texto, para este fin nos ofrece una serie de herramientas desde varios niveles de titulos, como puede verse tambien con HTML, hasta el aplicar cursiva, negritas o bien crear bloques de codigo como notas o pequeñas explicaciones. 

### Titulos

Simbolo | Descripción 
---|---
\# | Titulo 1
\#\# | Titulo 2
\#\#\# | Titulo 3
\#\#\#\# | Titulo 4


# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
#####  Titulo 5

### Cursiva y Negrita

Simbolo | Descripción | Ejemplo
---|---|---
\*Texto\*| Pone el texto encerrado entre los asteriscos en cursiva| *Texto*
\*\*Texto\*\*| Pone el texto encerrado entre los asteriscos dobles en negrita | **Texto**
\_Texto\_| Pone el texto encerrado entre los guiones bajos en cursiva| _Texto_
\_\_Texto\_\_| Pone el texto encerrado entre los guines bajos dobles en negrita | __Texto__

*Texto En cursiva 1*

_ Texto en cursiva 2 _

** Texto en Negrita 1 **

__ Texto en negrita 2 __

### Notas
Simbolo | Descripción 
---|---
\> Texto | Pone un texto como una nota.


> Esto es una nota aclarativa :eyes:

### Hipervinculos 

```markdown
	[Texto visible](https://Enlace.com)
```

[Enlace a Blog](https://entreunosyceros.home.blog/)

## Listas 

Simbolo | Descripción 
---|---
\* Elemento 1 | Crea un elemento de una lista no ordenada.
1\. Elemento 1 |  Crea un elemento de una lista ordenada. Se pueden utilizar tabulaciones para indcar que un elemento es sub elemnto de otro. 
\- [  ] Tarea 1 | Crea una tarea pendiente de completar
\- [ ] Tarea 1 | Crea una tarea completada.

## Lista ordenadas 
### Ejemplo 1
1. Elemento 
2. Elemento
3. Elemento
	1. Elemento
	2. Elemento
	3. Elemento

## Ejemplo 2
1. Elemento
2. Elemento 
3. Elemento
	- Elemento
	- Elemento
## Listas sin orden
### Ejemplo 1
- Elemento 
- Elemento
- Elemento
	- Elemento
	- Elemento
	- Elemento

### Ejemplo 2
- Elemento
- Elemento 
- Elemento
	1. Elemento
	2. Elemento

## Tareas pendientes
- [x] Tarea 1
- [x] Tarea 2
- [ ] Tarea 3

## Incrustando código

Simbolo | Descripción 
---|---
\`\`\`nombrelenguaje| Con esto se abre un bloque de codigo que se incrustara en nuestro Markdonw. Para que se reconozca el lenguaje debemos indicar de que lenguaje se trata.
\`\`\`| Para el cierre de el bloque de código se utiliza las tres comillas sin indicar el nombre del lenguaje.


```javascript
	console.log('hola mundo'); 
```

## Incrustando Literales

Simbolo | Descripción 
---|---
\\simbolo | inserta el simbolo dentro de nuestro texto.

> Incrustando literal 
\>  

## Tablas

cabecera 1 | cabecera dos | cabecera 3
---|---|---
1 | contenido 1 | *1*
2 | contenido 2 | **2**
3 | contenido 3 | **_1_**


## Imagenes, separadores y Emojis 


Simbolo | Descripción
---|---|---
\:emoji\: | inserta el emoji que indiquemos segun su identificador
\!\[Alt. Text\]\(URL\) | Inserta la imagen que se encuentra en la dirección indicada en el URL, en caso no encontrarla coloca el texto que le indiquemos.

:eyes: :exclamation:

![Esto deberia ser una imagen](./imagen_ejemplo_1)
![Esto deberia ser una imagen](./imagen_ejemplo_2)
 
## Contacto
* [Blog](https://entreunosyceros.home.blog/)
* [Post del Blog](https://entreunosyceros.home.blog/)
