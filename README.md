[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=298679&assignment_repo_type=GroupAssignmentRepo)

# tc2025-actividad-6-equipo14

##### Christian Alberto Dalma Schultz
##### Octavio Iván Garduza Labastida

### How to Run

1. Se deben descargar los archivos ```Consola.c``` y ```Semaforo.c```.

2. Se deben de compilar los archivos ```Consola.c``` 1 vez y ```Semaforo.c``` 4 veces. (Se recomienda utilizar compilador el GCC).

3. Tras compilar ambos archivos, se deben inicializar todos los  semáforos, empezando siempre con los semáforos 2, 3 y 4 en cualquier orden, y terminando con el semáforo 1.

4. Después de inicializarlos, se creará una archivo ```pid_db.txt```, donde se almacenarán los PIDS de los semáforos en el mismo orden en el que fueron creados, es decir, en el orden en el que se prenderán.

5. El programa comenzará desde el primer semáforo, esperando 30 segundos en cada uno. Esto se puede apreciar en la terminal individual de cada semáforo o de forma global en la terminal de la consola.

6. En la consola, se puede usar el comando ```ctrl+Z``` para que todos los semáforos se pongan en rojo, y ```ctrl+C``` para que todos los semáforos se pongan en intermitente. Para reanudar unicamente se debe oprimir el misma comando una vez más, sea este ```ctrl+Z``` o ```ctrl+C```.

7. Para detener el programa se debe cerrar la terminal donde corre la consola.
