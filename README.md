# Ejercicios básicos MS-DOS
## · Ejercicio 1:
1.![alt text](https://github.com/carlosblancoj/Ejercicio2_Sistemas/blob/main/msdos_1.PNG)
2.     cd .\APLI\EXCEL\TABLAS
3.     cd \
4.     tree .\PROG
5.     rd .\PROG\PASCAL
6.     cd .\VARIOS
       md ..\APLI\WORD\PRACT
7.     cd .\APLI\WORD\PRACT
       tree ..\APLI\EXCEL
8.     cd .\APLI\EXCEL\TABLAS
       tree \
9.     cd .\APLI
       md ..\VARIOS\AGENDA
10.     rd .\APLI\EXCEL
11.     md NUEVO
12.     cd .\APLI\WORD\PRACT 
        tree ..
## · Ejercicio 2
1.     start notepad EJER.txt
       type EJER.txt
2.     copy EJER.txt ..\VARIOS\AGENDA
3.     del EJER.txt
4.     edit ..\VARIOS\AGENDA EJER.txt
5.     copy EJER.TXT ..\PROG\BASIC
6.     ren EJER.TXT FICHERO.TXT
7.     move FICHERO.TXT ..\PROG\BASIC
8.     edit ..\VARIOS\AGENDA EJER.txt && move NUEVO.TXT ..\PROG\BASIC
9.     
## · Ejercicio 3
1.     rd .\APLI\ACCESS && md .\APLI\ASTRO
2.     
3.     cd .\APLI\ASTRO\CIENCIA && tree ..\HISTORIA
4.     edit .\HISTORIA\DATOS1 TYCHO.TXT
5.     edit .\HISTORIA\DATOS2 KEPLER.TXT
6.     copy .\DATOS1\TYCHO.TXT ..\CIENCIA
7.     move .\DATOS1\TYCHO.TXT .\DATOS2
8. 
9.     edit .\CIENCIA\KEPLER.TXT
10.     ren .\CIENCIA\KEPLER.TXT GALILEO.TXT
## · Ejercicio 4
1.     cd \ && md TECINFO
2.     edit .\TECINFO HARD.TXT
3.     edit .\TECINFO SOFT.TXT
4.     move .\TECINFO .\APLI
5. 
6.     rd .\TECINFO
7.     copy .\APLI\HARD.TXT .\VARIOS && copy .\APLI\SOFT.TXT .\VARIOS
       xcopy -d .\APLI .\VARIOS
 8. 	   
