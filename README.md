# Documentación
[Docsaurius](https://danielhu7.github.io/Markdown-test/docsaurius-test/build/)

# Markdown

Esta hoja proporciona una descripción general de elementos de markdown

---
---

## Sintaxis Basica

---
---

## Titulos

 " # " Nos mostrara una linea de tilulo,  mientras mas " # " se usen an inicio de un titulo menor sera su tamaño

## Esto es un Titulo

### Esto es un subtitulo

---

## Parrafos y saltos de linea

Para crear un nuevo parrafo solo debera pulsar intro 2 veces.

Para realizar un salto de linea y empezar una frase en otra linea dentro del mismo parrafo, tendrás que pulsar dos veces la barra espaciadora antes de pulsar una vez intro.

---

## Cuadro de texto

 Los bloques de texto se obtendran usando Tab al iniciar el texto, sin estos espacios el texto sera un texto normal

Esto es un texto normal

    Esto es un cuadro de texto

---

## *Cursiva* **Negrita** ~~Tachado~~

Para obtener alguno de estos 3 tipos de escritura Se utilizara

     " * "   para *Cursiva*
     " ** "  para **Negrita**
     " ~~ "  para ~~Tachado~~
     " *** " para ***Negrita y cursiva***

---

## Tablas

 Las tablas se generaran utilizando

    1. Para una lista numerada
    *  Para una lista sin numerar
    -  Para una lista sin numerar
    +  Para una lista sin numerar

Para crear tablas bajo otras se agregaran 4 espacios o un tab.  
Utilizando diferentes signos la tabla pondra un espacio entre ellas.

 Lista numerada

1. Elemento 1
2. Elemento 2
3. Elemento 3

 Lista sin numerar

* Uno
- Dos
+ Tres

Tabla anidada

- Elemento
    - Elemento
        - Elemento

---

## Tablas 2

Markdown permite dibujar tablas mediante plecas (|). Para crear encabezados que se distingan visualmente del resto del contenido, se subrayan las celdas correspondientes con guiones

Columna 1|Columna 2|  
\|--------|--------|  
\|    A    |    B    |  
\|    C    |    D    |  

Columna 1|Columna 2|
|--------|--------|
|    A    |    B    |
|    C    |    D    |

---

## Listas

Markdow permitira crear listas de verificacion colocando * []

* [x] A  
* [ ] B  
* [ ] C  

---

## Linea horizontal

Una linea horizontal sera colocada en la hoja al poder alguno de los siguientes signos en una linea de 3 --- *** ___

---
---
---

## Cita Textual

se obtendra un cuadro de cita al utilizar > al inicio de un reglon 

> Hola mundo

Tambien se podran poner citas dentro de otras con >>

> Hola mundo.
>
>> Esto es una cita dentro de otra
>
> La cita principal terminaria aqui

---

## Bloque de codigo

Poner un texto entre `` generara un bloque de codigo

`Esto es una linea de codigo`

---

## Link

Para agregar un link se pondra un titulo entre [] y la direccion del link entre ()

    [Nombre enlace](Link)

[Hola mundo](https://www.google.com/search?client=firefox-b-d&q=Hola+mundo)

Para un mayor orden tanto con las imagenes como con los Links podras podras generar enlaces con referencias

    [Nombre enlace][Nombre Referencia]  
    [Referencia]:https://www.example.com

[TEST][Blog]


[Blog]: https://www.example.com/

Los links automaticos seran generados si se coloca uun link entre <>

<https://www.example.com>


---

## Imagen

Para agregar una imagen sera lo mismo pero andes del [] se agregara un !

    ![Nombre enlace](Link)

![Flor](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Nelumno_nucifera_open_flower_-_botanic_garden_adelaide.jpg/1200px-Nelumno_nucifera_open_flower_-_botanic_garden_adelaide.jpg)

---

## Notas al pie de la pagina

Puedes colocar [^Nota1] notas en el pie de página [^Nota2] fácilmente.  

[^Nota1]: Aquí encuentras el texto de la nota al pie de página.  

[^Nota2]: **Las notas de pie de página** pueden *formatearse* también.
Estas pueden ocupar varias líneas.

---

## Omitir Markdown

Para que markdow no interpete los simbolos solo se debe utiluzar una \ al inicio  

\#  
\[]  
\-  
\*  

## Referencias cruzadas


Las referencias cruzadas sirven para añadir links a partes especificas de tu documento

Quiero que [este enlace](#referencias-cruzadas) vaya al encabezado de referencias cruzadas.
---

## Notas al pie de la pagina (esto aun no sirve)
 
