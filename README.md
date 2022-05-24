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

Como primer paso se creó un Makefile para optimizar el tiempo de realización de la tarea:

```bash
compile_file:
	echo "Compiling $(input_file) ..."
	as -o $(input_file).o $(input_file).s
	gcc -o $(input_file) $(input_file).o
	./$(input_file)
        gdb $(input_file)
```

# Programa 1: primero.s
![image](https://user-images.githubusercontent.com/95386762/169950140-1dccaa80-a3f2-4b6e-911f-e057cd37f0c1.png)


# Programa 2: stack.s
![image](https://user-images.githubusercontent.com/95386762/169950766-f8423e5f-1f1f-45ba-9c40-a41e6952d5cc.png)


# Programa 3: scanfExample1.s
![image](https://user-images.githubusercontent.com/95386762/169951338-d0f75fc0-d76c-471a-b0a7-431bf5faca24.png)
<br>
![image](https://user-images.githubusercontent.com/95386762/169952389-e4ef6070-764d-44d3-9919-0f209619bec5.png)


# Programa 4: sum3.s
![image](https://user-images.githubusercontent.com/95386762/169951494-487ce216-2cd7-4c06-a2a6-a51961632079.png)
<br>
![image](https://user-images.githubusercontent.com/95386762/169952446-aceeb885-9297-4c01-9f8e-0a97ac04fcbd.png)


# Programa 5: delayExample.s
![image](https://user-images.githubusercontent.com/95386762/169951617-0ddb3342-2224-4187-bf88-eab6a8c60750.png)


# Programa 6: div9entre3.s
![image](https://user-images.githubusercontent.com/95386762/169951785-caef1bfc-b69c-4933-a022-dbb6c5c9122e.png)


# Programa 7: hanoi.s
![image](https://user-images.githubusercontent.com/95386762/169951861-86035800-e9c7-4d9b-bea8-ba44b2497aab.png)


# Programa 8: sum2.s
![image](https://user-images.githubusercontent.com/95386762/169951559-52fda703-be8b-4519-a078-7bbdcb30e334.png)

