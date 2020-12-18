# Trabajo-Final

## **Aclaraciónes de cada uno de los casos**

### Caso 1
En este caso utilizaremos la propiedad ***"flex-direction"*** para seleccionar como queremos que se organicen nuestros contenedores, en este caso en particular, queremos que sigan una estructura de columna, para eso utilizaremos ***"flex-direction: column;"***.

### Caso 2
En este caso vamos a utilizar la propiedad ***"justify-content"*** la cual utilizaremos para alinear nuestros contenedores, para este caso, buscamos alinear nuestros contenedores al final \(final de la linea, no del documento\), por lo cual utilizaremos ***"justify-content: flex-end;"***.

### Caso 3
Para este caso, volveremos a utilizar la propiedad ***"justify-content"***, pero en este caso en vez de alinear nuestros contenedores, haremos que estos se separen dejando un espacio constante entre ellos y el principio y el final de la linea, para esto aplicaremos ***"justify-content: space-around;"***.

### Caso 4
Este caso es bastante similar al caso anterior, la propiedad no varia pero si varia como la aplicaremos, en este caso el espacio de separación sigue siendo constante, pero esta vez no dejaremos espacio entre un contenedor y el principio y final de la linea, para eso aplicaremos  ***"justify-content: space-between;"***.

### Caso 5
Este caso tiene algunas similitudes con el primero, pero en este utilizaremos una propiedad y una especificación diferente,es el caso de ***"align-items"***, la cual comparte cierta similitud con ***"justify-content"***, siendo diferenciadas porque la segunda limita la alineación a una única linea y la primera alinea teniendo en cuenta todo el espacio del documento.

### Caso 6
En este caso se pueden apreciar las similitudes entre ***"justify-content"*** y ***"align-items"***, a simple vista podríamos determinar que se esta utilizando la propiedad ***"justify-content: flex-start;"***, el cual tendría resultado similar a la que estamos utilizando ahora mismo ***"align-items: flex-start"***, esto es debido a que lo que esta haciendo la propiedad ***"align-items: flex-start"*** es alinear los contenedores en torno a la primera linea del documento, dando el mismo resultado que si situáramos ***"justify-content: flex-start;"*** en la primera linea de dicho documento.

### Caso 7
Para este caso utilizaremos la propiedad ***"align-items: stretch;"*** las cual hace que los contenedores sean estirados de modo que el tamaño transversal de sus límites sea el mismo de la línea, manteniendo sus restricciones de anchura y altura.

### Caso 8
Este caso es similar al sexto caso, pero como queremos alinear los contenedores en la ultima linea de documento utilizaremos ***"align-items: flex-end"***.

### Caso 9
En este caso, utilizaremos dos propiedades a la vez, ***"flex-wrap:wrap;"***, la cual la utilizaremos para separar los contenedores en diferentes lineas si estos no entran en una única linea, ademas, para añadir un espacio de separación entre nuestros contenedores utilizaremos ***"align-content: space-around;"***, propiedad que nos hace recordar a la del caso tres, solo que en este caso la separación sera vertical y no horizontal.

### Caso 10
Este caso es similar al caso nueve, guardando cierto paralelismo con la relación del caso tres y el caso cuatro, este también consistirá en cambiar la propiedad ***"align-content: space-around;"*** por la propiedad ***"align-content: space-between;"*** para que no haya espacios entre los contenedores y el principio y final de documento.

### Caso 11
Este caso es similar al caso siete, solo que en este utilizaremos ***"flex-wrap:wrap;"*** debido a la existencia de numerosos contenedores, los cuales no caben en una única linea, así que usaremos ***"align-content: stretch;"*** en vez de ***"align-items: stretch;"***.

### Caso 12
En este caso volveremos a utilizar ***"flex-wrap:wrap;"*** debido a la existencia de numerosos contenedores, los cuales no caben en una única linea, así que usaremos  ***"align-content: center;"*** para alinearlos al centro del documento.

### Caso 13
Este caso comparte similitudes con el anterior, solo que en este buscamos alinear las lineas de contenedores al principio del documento, así que utilizaremos ***"flex-wrap:wrap;"*** y ***"align-content: flex-start;"***.

### Caso 14
En este caso haremos lo mismo que en el anterior, solo que ahora alinearemos en torno al final del documento, así que en vez de ***"align-content: flex-start;"***.
sera ***"align-content: flex-end;"***. \(Como recomendación, en estos tipos de casos es de bastante ayuda predefinir el área del documento o primer contenedor para que se distingan de mejor maneras estos casos\)

### Caso 15
Este caso constituye una ampliación del caso siete, en este caso definiremos cierto ancho para cada contenedor y así poder diferenciarlos, esto se hace a través de la propiedad ***"flex-grow"*** a la cual le iremos dando valores, en este caso 1, 4, 1, 10 respectivamente a cada uno de los contenedores, quedando así:
* ***"flex-grow: 1;"***
* ***"flex-grow: 4;"***
* ***"flex-grow: 1;"***
* ***"flex-grow: 10;"***

### Caso 16
En este caso no usaremos la propiedad ***"flex-wrap:wrap;"*** sino que utilizaremos su contraria, ***"flex-wrap:nowrap;"*** la cual impedirá la separación en dos lineas de los contenedores, reduciéndolos hasta que solo haga falta una linea para contenerlos 
