# Título del Proyecto

Este README.md se escribió como un tutorial de archivos en formato "MarkDown". Se espera que en este primer parrafo se haga una descripción general del proyecto y su objetivo principal (breve pero clara) y una descripción del uso del código (detallada y ordenada). Las secciones que podría tener (cuando sea relevante) un buen README.md son:

* Descripción general
* Proceso de instalación
* Ejemplo de ejecución del programa
* Autores y Colaboradores
* Tipo de Licencia
* Agradecimientos
* Lista de archivos y breve descripción de su función
* Lista de Bugs conocidos aun sin resolver
* Lista de ideas que se podrían implementar o mejorar en el proyecto
* Referencias 

## Instalación

Normalmente aqui se deben describir los pasos para copiar (o clonar) el proyecto y ejecutarlo en la máquina local del colaborador para que lo pueda probar o pueda comenzar a desarrollar nuevas funcionalidades. Se deben describir:
* Los prerequisitos de hardware y software para que el paquete funcione. 
* La instalación previa de otros paquetes o dependencias necesarios.
* Los pasos de instalacion, compilación y ejecución del paquete. 

### Prerrequisitos  (Título de tercer nivel) 

Explicar aquí aquellos elementos que se deben adquirir antes y el proceso de instalación paso a paso. De preferencia redactar un procedimiento 100% confiable o anexar comentarios en caso de problemas. En algunos casos se necesitará clonar algún repertorio. Los comandos se deben escribir en una caja separada con letra recta y considerando que se escribe en el la línea de comando (Shell) de Linux:

```
$ Aquí se ponen los comandos a escribir en una Terminal
```

### Proceso de instalación  (Título de tercer nivel)

Aquí se describe paso a paso como se instala y compila el paquete para asegurarse que está funcionando correctamente. 

Escribir el primer paso: 

```
$ Comandos a ejecutar
```

Y así sucesivamente hasta que se termine de instalar adecuadamente. Explicar cual es el resultado esperado. En caso de errores remitir a algún procedimeinto de recuperación o reinstalación. Cabe mencionar que no es buena idea incluir dentro de README.md secciones completas del código. Es preferible usar hipervículos. 

En ocasiones es necesario explicar algún comando dentro de un párrafo, como por ejemplo `mkdir` . Para lograr esto se pone entre apóstrofes invertidos la palabra deseada:
``` `mkdir` ```


### Ejemplo de ejecución del programa  (Título de tercer nivel)

Aquí se debe proporcionar un ejemplo típico de uso del programa. Comentando aquello que sea necesario conocer para ejecutar el programa.

```
$ Comando ejemplificativo o un pedazo de código a editar o modificar antes de compilar.
```

## Recomendaciones para escribir en el README.md

En esta sección se mostrarán formas útiles de presentar información.

Se pueden utilizar diferentes tamaños de título para establecer una estructura en el documento. Para cambiar el nivel del título se utiliza `#`, donde la cantidad de símbolos corresponde al nivel de la cabecera. Es decir:

```
# Primero nivel
## Segundo nivel
### Tercer nivel
#### Cuarto nivel
```

Una lista de opciones se puede crear comenzando la linea con un asterisco y espacio, * + <space>, en cada una de ellas:
* Opción uno
* Opción dos
* Opción tres
  - Opción 3.1
  - Opción 3.2
  - Opción 3.3

### Hipervínculos

Para poner un hipervínculo se pone el texto activo entre corchetes [] seguido del hipervínculo entre paréntesis (), como por ejemplo:

``` [Maven](https://maven.apache.org/) - Dependency Management. ```

El resultado es el siguiente:

[Maven](https://maven.apache.org/) - Dependency Management.

En ocasiones se desea tener texto exactamente abajo del anterior. El comportamiento normal de README.md es que se requiere una linea en blanco entre dos párrafos para que estén separados. Sin embargo se pueden poner un párrafo inmediatamente después de otro, si al final del primero le anexamos 3 espacios en blanco. Aqui abajo un ejemplo:

[ROS](http://ros.org) - Robotic Operating System.   
[GitHub](https://help.github.com/en/articles/basic-writing-and-formatting-syntax) - Basic writing and formatting syntax

Se pueden anexar EMOJIS como por ejemplo :+1:, :shipit:.  Una lista completa se puede encontrar en:
1. [https://www.webfx.com/tools/emoji-cheat-sheet/](https://www.webfx.com/tools/emoji-cheat-sheet/).  
2. [https://emoji-cheat-sheet.com](https://emoji-cheat-sheet.com).


Tambien se pueden anexar imagenes usando los caracteres `![ ]` y entre paréntesis la dirección absoluta o relativa del archivo imagen. A continuación se muestra un ejemplo: 

```
![Texto descriptivo de la imagen](images/GitHub-Logo.png)
![](http://www.ros.org/wp-content/uploads/2016/05/kinetic.png)
```
Este es el resultado:

![Texto descriptivo de la imagen](images/GitHub-Logo.png)
![](http://www.ros.org/wp-content/uploads/2016/05/kinetic.png)

También se pueden poner tablas, separando columnas con el símbolo | y donde cada renglón es una nueva fila. Aqui un ejemplo:

```
| Cantidad | Descripción | Precio Unitario | Subtotal |
| --- | --- | --- | --- |
| 1 | Tarjeta Arduino | 100.00 | 100.00 |
| 2 | Potenciómetros | 10.00 | 20.00 |
| 10 | Resistencias de 1K| 1.00 | 10.00 |
```
Este es el resultado:

| Cantidad | Descripción | Precio Unitario | Subtotal |
| --- | --- | --- | --- |
| 1 | Tarjeta Arduino | 100.00 | 100.00 |
| 2 | Potenciómetros | 10.00 | 20.00 |
| 10 | Resistencias de 1K| 1.00 | 10.00 |

A continuación damos una lista de buenas referencias para aprender a escribir en MarkDown:
* https://guides.github.com/features/mastering-markdown/
* https://help.github.com/en/articles/basic-writing-and-formatting-syntax 
* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

## Autores y Colaboradores

* **Nombre completo** - *Adscripción o rol* - [Forma de contacto](http://homepage.cem.itesm.mx/aaceves) 
* **Alejandro Aceves-López** - *Profesor de planta* - [WebPage](http://homepage.cem.itesm.mx/aaceves) 


## Tipo de Licencia

Es de gran importancia saber y dar a conocer el tipo de licencia de uso que tiene el software. Existen muchas variantes. Para conocer rápidamente la diferencia entre ellas, sugerimos visitar:  https://tldrlegal.com/ 

## Agradecimientos

Siempre es una buena construmbre agradecer a todos aquellos que nos han apoyado significativamente en el proyecto con sus comentarios o controibuciones aunque no sean parte del equipo de desarrollo. También se suele agradecer a las instituciones que apoyan con fondos monetarios en forma de becas, pago de viáticos, gastos, etc.

## Lista de archivos

Incluir lista de archivos y la breve descripción de su función.

## Lista de Bugs conocidos aun sin resolver

En ocasiones el software que se desarrolla falla bajo ciertas condiciones conocidas. Podría ser que no tiene secuencias de validación y por tanto el usuario debe tener cuidado como usa el software para que no falle. Cuando estas situaciones son conocidas, es buena constumbre informarlas.

## Referencias 

Incluir referencias o bibliografia de apoyo para mayor entendimiento. Usar el formato IEEE.

1. Author Initial.  Author Surname, 'Title', Year Published. [Online]. Available: http://Website URL. [Accessed: 10- Oct- 2013].
2. Anonymous. 'Guide: How to cite a Website in IEEE style' [Online]. Available: http://www.citethisforme.com/guides/ieee/how-to-cite-a-website, [Accessed: 06- Jun- 2019].
