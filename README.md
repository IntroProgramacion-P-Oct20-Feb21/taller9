# Taller 9: 
## Diseño de la solución de problemas con pseudocódigo aplicando arreglos bidimensionales.

### Problema1

Dado el siguiente arreglo bidimensional; representarlo en miniespecificación y recorrerlo para presentar los valores que están de color rojo

![](https://raw.githubusercontent.com/IntroProgramacion-P-Oct20-Feb21/taller9/main/images/taller09-01.png) 

### Problema2

Dado el siguiente arreglo bidimensional; representarlo en miniespecificación y recorrerlo para presentar los valores que están de 
color verde

![](https://raw.githubusercontent.com/IntroProgramacion-P-Oct20-Feb21/taller9/main/images/taller09-02.png) 

### Problema3

Dadas las notas de tres (3) estudiantes; generar una solución que permita encontrar el promedio de las calificaciones por cada conjunto de notas de los estudiantes.
La problemática sugiere el uso de estructuras de datos.
Las notas están en un arreglo bidimensional llamado **notas**; notas tiene 3 filas y 4 columnas. 

![](https://raw.githubusercontent.com/IntroProgramacion-P-Oct20-Feb21/taller9/main/images/taller09-03-1.png) 


Los nombres de los estudiantes están en un arreglo unidimensional que tiene 3 elementos. El arreglo se llama **estudiantes**

![](https://raw.githubusercontent.com/IntroProgramacion-P-Oct20-Feb21/taller9/main/images/taller09-03-2.png)

Atención; los valores del arreglo **notas**  de la fila del índice 0 pertenecen al estudiante del índice 0 del arreglo **estudiantes**; y *así con cada fila de notas e índice de estudiantes*

Cada promedio de notas de un estudiante deberá ser almacenado en una posición de un arreglo unidimensional llamado **promedios**; resaltar que el arreglo promedios tendrá 3 elementos.

Al final se debe presentar el siguiente reporte:
```
Estudiante: Jerry Ponce tiene un promedio de ?
Estudiante: Gabriela Lewis tiene un promedio de ?
Estudiante: David Bell tiene un promedio de ?	
```

### Problema4

Se requiere ingresar las ventas totales diaras de 2 vendedores; realizadas de lunes a viernes.
Los vendedores están representados en una estructura unidimensional de dos elementos. El arreglo se llama **vendedores**
![](https://raw.githubusercontent.com/IntroProgramacion-P-Oct20-Feb21/taller9/main/images/taller09-04-2.png) 

El arreglo bimensional que permitirá almacenar las ventas diarias tiene 2 filas y 5 columnas. El arreglo se llama **ventas**

![](https://raw.githubusercontent.com/IntroProgramacion-P-Oct20-Feb21/taller9/main/images/taller09-04-1.png) 

Existe una relación entre el índice 0 del arreglo vendedores y la fila de índice 0 del arreglo ventas.

Luego de ingresar los valores se necesita presentar el total de ventas de todos los vendedores de la siguiente forma:
```
Vendedor(a) Jessica Cole	
Vendedor(a) Robert Wallace
Ha realizado un total de ? en ventas.
```