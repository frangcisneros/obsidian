# Ejercicio N°3
La gerencia de World Airways desea determinar la cantidad mínima de tiempo necesaria para que un aeroplano de la vuelta, desde el momento en que alcanza la puerta hasta que se encuentra listo para salir por ella. Para tal efecto, el administrador de vuelo ha identificado las siguientes tareas que se necesitan llevar a cabo entre la llegada y la partida.

![[tabla ej n3.png]]

Las comidas no pueden ser subidas a bordo ni la limpieza del interior puede efectuarse hasta que han bajado los pasajeros. El equipaje de los pasajeros que parten no puede ser cargado hasta que se ha descargado el equipaje de los que llegan. Los pasajeros no pueden abordar la nave hasta que el interior esté limpio. La prueba de seguridad puede realizarse solamente después de que los motores han sido abastecidos de combustible y las comidas, los equipajes y los pasajeros ya están a bordo.

1. ==Trace la red de proyectos.==
%% ACA NO SE SI DEBO CALCULAR EL TIEMPO MEDIO PARA HACER EL DIAGRAMA DE RED O SE USA EL MÁS PROBABLE %%
Primero calcularemos el tiempo medio de cada tarea en base a los tiempos optimistas, probables y pesimistas, ademas de dar las dependencias de cada tarea.

El tiempo medio se calcula con:

$$
\frac{a+4m+b}{6}
$$
Donde:
- a -> tiempo *más optimista*.
- b -> tiempo *más pesimista*.
- m -> tiempo *más probable*.

| TAREA | TIEMPO MEDIO (min) |  DEPENDENCIAS  |
| :---: | :----------------: | :------------: |
|   A   |       15.33        |       -        |
|   B   |       25.83        |       -        |
|   C   |       31.17        |       -        |
|   D   |       15.33        |       A        |
|   E   |       15.33        |       A        |
|   F   |       20.83        |       B        |
|   G   |       20.83        |       D        |
|   H   |         10         | C - E - F - G  |

![[ej n3 red de proyectos | center | 10000]]


2. ==Calcule el tiempo de terminación más temprano utilizando CPM==
3. ==Calcule el tiempo de terminación esperado más breve utilizando el método PERT, identifique la trayectoria crítica y determine la varianza del tiempo de terminación del proyecto.==
%% TENGO DUDAS CON LOS VALORES QUE UTILIZO ACA, NO ENTIENDO SI ES EL VALOR PESIMISTA EL QUE DEBO USAR%%
El calculo de *inicio más inmediato* de una tarea es el máximo de los tiempos de terminación de sus tareas predecesoras (o sea el tiempo pesimista).
%% ¿NO SE SI TENGO QUE USAR EL TIEMPO MEDIO PARA CALCULAR ESTO? %%
El tiempo de *terminación más breve o inmediato* es la suma del tiempo de inicio más inmediato más el tiempo de la tarea en cuestión (el cual se usará el tiempo medio)

| TAREA | TIEMPO DE INICIO MAS INMEDIATO | TIEMPO DE TERMINACIÓN MAS BREVE |
| ----- | ------------------------------ | ------------------------------- |
| A     | 0 min                          | 15.33 min                       |
| B     | 0 min                          | 25.83 min                       |
| C     | 0 min                          | 31.17 min                       |
| D     | 20 min                         | 35.33 min                       |
| E     | 20 min                         | 35.33 min                       |
| F     | 35 min                         | 55.83 min                       |
| G     | 40 min                         | 60.83 min                       |
| H     | 115 min                        | 125 min                         |
%% NO ESTOY SEGURO DE ESTO %%
El tiempo de terminación más temprano del proyecto es de 125 min
%% NO ESTOY SEGURO DE ESTO %%
La ruta critica seria la de A-D-G-H ya que es la secuencia más larga.

La *varianza del tiempo de terminación del proyecto* se calcula como la suma de las varianzas de los tiempos de terminación de las tareas a lo largo de esa trayectoria crítica.
%% EN EL PP LO ELEVA AL CUADRADO NO SE POR QUE%%


| TAREA | B   | A   |
| ----- | --- | --- |
| A     |     |     |
| B     |     |     |
| C     |     |     |
| D     |     |     |
| E     |     |     |
| F     |     |     |
| G     |     |     |
| H     |     |     |


4. Cuál es la probabilidad de ser capaz de partir en una hora.
5. La gerencia desea que el 95% de sus vuelos salgan a tiempo, suponiendo que también llegan a tiempo. ¿Cuál es la menor cantidad de tiempo (hasta el minuto más cercano) que la gerencia debería planear para el lapso entre la llegada a la puerta y la salida?
6. Escriba las conclusiones comparando ambos métodos, CPM y PERT. (tiempo de terminación, ruta crítica, etc.)