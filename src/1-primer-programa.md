# Primer programa

Como primer práctica generaremos un programa que imprima un texto en la pantalla
```c
#include <stdio.h>

int main(){
	puts("Hello world");
	return 0;
}
```
## Explicación
* `#include <stdio.h>`: la directiva include es lo que se conoce como una macro, tiene como objetivo el usar código de otro archivo dentro de nuestro programa. La librería que estamos trayendo en este caso es el archivo stdio.h que contiene las funciones de entrada y salida de la terminal.

* `int main(){}`: es la función de inicio del programa, todo lo que se encuentre dentro de sus llaves es lo que se ejecutará en el programa.
 
* `puts()`: esto es una función, lo que esté dentro de sus llaves y entre comillas se va a mostrar en la terminal.

* `return 0`: Esto indica que la función main acabó correctamente, puede devolver un número, dependiendo del número que sea se le indica al sistema cómo acabó el programa. En este caso usamos 0, que indica que acabó correctamente.

## Compilación

El proceso de compilación lo haremos desde la linea de comandos. En un terminal estando en la carpeta que contiene tu archivo escribe
```
gcc nombre.c -o app
```

# Ejecución
Este programa como salida te mostrará
```
Hello world
```