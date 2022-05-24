# Cierre-Tema-3

<pre>
    <p align=center>

Tecnológico Nacional de México
Instituto Tecnológico de Tijuana

Departamento de Sistemas y Computación
Ingeniería en Sistemas Computacionales

Semestre:
Febrero - Junio 2022

Materia:
Lenguajes de interfaz

Docente:
M.C. Rene Solis Reyes 

Unidad:
3

Título del trabajo:
CIERRE Tema 3: Corra los programas de ARM Assembly entregados a su revisión.

Estudiantes:
Monjardín Montaño Kevin Román

    </p>
</pre>


En el presente repositorio se presentan los programas que se pueden correr del repositorio proporcionado por el profesor.

Como primer paso se creo un makefile para optimzar el tiempo de realizacion de la tarea:
</pre>
    </p>
compile_file:
	echo "Compiling $(input_file) ..."
	as -o $(input_file).o $(input_file).s
	gcc -o $(input_file) $(input_file).o
	./$(input_file)
        gdb $(input_file)
    </p>
</pre>

# Programa 1: primero.s
![image](https://user-images.githubusercontent.com/95386762/169949409-78180601-0727-4404-8cd0-751ccc89fa3f.png)

# Programa 2: stack.s

# Programa 3: scanfExample1.s

# Programa 4: sum3.s

# Programa 5: delayExample.s

# Programa 6: div9entre3.s

# Programa 7: hanoi.s

# Programa 8: sum2.s
