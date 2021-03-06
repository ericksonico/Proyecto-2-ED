# Proyecto-2-ED
## Simulación de un sistema de captura y representación de estadísticas en Java

Este proyecto fue hecho para la materia de Estructuras de Datos.
El menú contiene las siguientes opciones: 

```
1. Registrar alumno con número de cuenta y edad
2. Mostrar distribución de alumnos por edades
3. Mostrar gráfica ordenada por edades
4. Imprimir ́arbol de alumnos
5. Salir
```
Se usó una tabla hash para guardar los datos de los alumnos. El número de cuenta también se almacena en un árbol binario para que se pueda imprimir en la opción 4.

### Ordenamiento utilizado
Se hace uso del algoritmo de ordenamiento BubbleSort, con una modificación para que ordene dos arreglos, uno con elementos tipo *int* y otro de *Strings*

### Paquetes usados
Se usaron los siguientes paquetes de java

- javax.swing.JPanel
- javax.swing.JFrame
- javax.swing.*
- java.awt.Graphics
- java.awt.Color
- java.util.Hashtable
- java.util.InputMismatchException

### Entorno donde fue probado
- Ubuntu 20.04.3

### Funcionamiento

Es necesario ejecutar los siguientes dos comandos en la terminal. Suponiendo que está en la carpeta src:
```
javac Prueba.java
java Prueba
```
Para ejecutar el programa con las imágenes, estas se deben sacar de la carpeta donde se encuentran y colocarse al nivel de la clase Prueba.
