## PRACTICA SENCILLA CON CSS GRID
Una sencilla practica de css responsive sin algun framework, solo utilizando css grid, y media querys, utilizando:
* `display: grid;`: Para crear las celdas que necesitaremos.
* `repeat`: Esto nos permite realizar un ciclo al puro estilo for en javascript o cualquier otro lenguaje de programacion.
* `auto-fit`: Esta palabra reservada no permite autocompletar un elemento dentro de unas columnas o unos grid en los espacios que son requeridos.
* `minmax`: Esta palabra reservada nos permite definir el tamanio de las regillas como el minimo `15rem` y el maximo `1fr`;
* `grid-template-columns: repeat(auto-fit, minmax(15rem,1fr));` Esto nos permite crear las columnas que quesieramos.
* `grid-template-columns: repeat(12, 1fr);`: Nos permite crear las columnas de las rejillas, siendo el primer dato, la cantidad de columnas que se quiere que tenga el elemento, y el segundo dato el espacio que se quiere que tenga las columnas, en este caso una fraccion de todo el elemento.
* `grid-template-rows: repeat(12, .40fr);`: Al igual que el comando de arriba, este nos permite crear filas en vez de columnas.
* `grid-gap: 20px;`: Este comando nos permite darle un espaciamiento interno entre los elementos, mas no los laterales.
* `grid-column: span 10;`: Este comando nos permite dimencionar las columnas, tambien se podrian poner `grid-column-end` o `grid-column-start` para dimencionar el inicio y el final de la columnas.
* `span`: Este comando nos permite fusionar varias columnas o filas. dandole un numero que serian los espacios que queremos fusionar.  
* `grid-row: 2/12;`: Sucede semejante a `grid-column` solo que este comando redimenciona las filas, y el dato `2/12` quiere decir que comenzara en la fila 2 hasta la fila 12.



- Pruebas realizadas en los navegadores Brave y Opera.
