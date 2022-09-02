# Practica-Programacion-Septiembre
Practica Programacion Septiembre

Se pide realizar un programa en C que emule de forma rudimentaria el funcionamiento de una aplicación de gestión de bases de datos, utilizando la línea de comandos para su funcionamiento. El programa podrá gestionar varias bases de datos, cada una de las cuales estará contenida en una carpeta (directorio) distinta en el disco duro.

-------

// ENTRA EN EDITAR PARA VERLO MEJOR

1. Modificar el comando remove para que pida confirmacion al usuario antes de borrar 
la tabla (en caso de que no haya error) pulsar 's'+ [intro] borra la tabla, cualquier otra respuesta 
cancelara la operacion OK

2. Modificar el comando 'import ' para que se pueda indicar un nombre para la tabla de destino. 
Deberá Indicarse error en caso de que el nombre de la nueva tabla de destino coincida con el nombre 
de alguna de las tablas ya existentes en la base de datos activa OK

    import table <nombre_tabla> from <nombre_ bd> as <nueva_tabla>
    
    
    import table nombre_tabla from nombre_ bd as nueva_tabla

3.Modificar el comando select para que se pueda indicar opcionalmente el nombre del campo por el cual ordenar el listado. 
Si dicho campo no existe se indicará con un mensaje de error (si el campo no se indica en el comando funcionará igual que antes)
 entra en edit para verlo bien OK

    select [<campo> ox <valor>] [<orden> [<campo>]]
    
    
    select [campo ox valor] [orden [campo]]


PON MAIN.C

4. Nuevo comando 'update' para modificar los registros de la tabla activa, 
al terminar el comando indicara por pantalla el numero de registros afectados por el cambio solicitado.
El comando cambia, de la tabla activa, todos los registros que cumplan con la condicion indicada (si no se indica condicion se cambian todos los registros de la tabla)
Si el campo no existe o el valor no es de tipo valido, se indicara con error
    
    update <campo> = <valor> [where <campo> ox <valor>]
    update campo = valor [where campo ox valor]
    
    ¿TODO OK?
    1 2 3
    
    ¿Tengo que quitar email?
    
-------

La aplicación admitirá tres tipos de datos, NUMERO, FECHA y TEXTO 

