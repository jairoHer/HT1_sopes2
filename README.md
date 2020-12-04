# HT1_sopes2

```
>funcion my_proc_show
```

Esta funcion es la que se encarga de leer la estructura de linux sysinfo, en donde se extrae la informacion de la Ram y se puede obtener la RAM
total y la RAM libre. Tambien aqui sabiendo ambos valores se puede obtener el procentaje de utilizacion de la Ram de la maquina

```
>funcion __init test_init
```
Esta funcion se encarga de crear el modulo y agregarlo a la lista de modulos de kernel de linux. Aqui se coloca el nombre como se accedera a
la informacion e la carpeta /proc

```
>funcion my_proc_open
```

Esta funcion se encarga de ejecutar la funcion my_proc_show
