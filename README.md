# Practica-Programacion-Septiembre
Practica Programacion Septiembre

Se pide realizar un programa en C que emule de forma rudimentaria el funcionamiento de una aplicación de gestión de bases de datos, utilizando la línea de comandos para su funcionamiento. El programa podrá gestionar varias bases de datos, cada una de las cuales estará contenida en una carpeta (directorio) distinta en el disco duro.

-------
1. Modificar el comando remove para que pida confirmacion al usuario antes de borrar 
la tabla (en caso de que no haya error) pulsar 's'+ [intro] borra la tabla, cualquier otra respuesta 
cancelara la operacion

2. Modificar el comando 'import ' para que se pueda indicar un nombre para la tabla de destino. 
Deberá Indicarse error en caso de que el nombre de la nueva tabla de destino coincida con el nombre 
de alguna de las tablas ya existentes en la base de datos activa

    import table <nombre_tabla> from <nombre_ bd> as <nueva_tabla>

3.Modificar el comando select para que se pueda indicar opcionalmente el nombre del campo por el cual ordenar el listado. 
Si dicho campo no existe se indicará con un mensaje de error (si el campo no se indica en el comando funcionará igual que antes)

select [<campo> ox <valor>] [<orden> [<campo>]]
    
-------

La aplicación admitirá tres tipos de datos, NUMERO, FECHA y TEXTO
