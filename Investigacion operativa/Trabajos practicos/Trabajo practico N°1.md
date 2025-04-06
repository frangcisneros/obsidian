# Ejercicio N°3
La gerencia de World Airways desea determinar la cantidad mínima de tiempo necesaria para que un aeroplano de la vuelta, desde el momento en que alcanza la puerta hasta que se encuentra listo para salir por ella. Para tal efecto, el administrador de vuelo ha identificado las siguientes tareas que se necesitan llevar a cabo entre la llegada y la partida.

![[tabla ej n3.png]]

Las comidas no pueden ser subidas a bordo ni la limpieza del interior puede efectuarse hasta que han bajado los pasajeros. El equipaje de los pasajeros que parten no puede ser cargado hasta que se ha descargado el equipaje de los que llegan. Los pasajeros no pueden abordar la nave hasta que el interior esté limpio. La prueba de seguridad puede realizarse solamente después de que los motores han sido abastecidos de combustible y las comidas, los equipajes y los pasajeros ya están a bordo.

1. Trace la red de proyectos
La red de proyectos se dibuja con los tiempos *más probables* ($m$).


![[ej n3 red de proyectos | center | 10000]]


2. Calcule el tiempo de terminación más temprano utilizando CPM

| TAREA | TIEMPO DE INICIO MAS INMEDIATO | TIEMPO DE TERMINACIÓN MAS BREVE |
| ----- | ------------------------------ | ------------------------------- |
| A     | 0 min                          | 15 min                          |
| B     | 0 min                          | 25 min                          |
| C     | 0 min                          | 30 min                          |
| D     | 15 min                         | 30 min                          |
| E     | 15 min                         | 30 min                          |
| F     | 25 min                         | 45 min                          |
| G     | 30 min                         | 50 min                          |
| H     | 50 min                         | 60 min                          |
El tiempo de terminación más temprano del proyecto es de 60 min, lo cual corresponde a la suma de todos los tiempos de terminación de las tareas de la ruta critica, en este caso A, D, G y H.

3. Calcule el tiempo de terminación esperado más breve utilizando el método PERT, identifique la trayectoria crítica y determine la varianza del tiempo de terminación del proyecto

El calculo de la media se hace de la siguiente forma:
$$
\frac{a+4m+b}{6}
$$

El de la desv. estandar:
$$
\frac{b-a}{6}
$$

Y la varianza:
$$
$$

$$
\left( \frac{b-a}{6} \right)^2
$$

Donde:
- a -> más optimista.
- b -> más pesimista.
- m -> más probable.

| TAREA | a  | m  | b  | MEDIA       | DESV. ESTANDAR | VARIANZA    |
|-------|----|----|----|-------------|----------------|-------------|
| A     | 12 | 15 | 20 | 15,33333333 | 1,333333333    | 1,777777778 |
| B     | 20 | 25 | 35 | 25,83333333 | 2,5            | 6,25        |
| C     | 27 | 30 | 40 | 31,16666667 | 2,166666667    | 4,694444444 |
| D     | 12 | 15 | 20 | 15,33333333 | 1,333333333    | 1,777777778 |
| E     | 12 | 15 | 20 | 15,33333333 | 1,333333333    | 1,777777778 |
| F     | 15 | 20 | 30 | 20,83333333 | 2,5            | 6,25        |
| G     | 15 | 20 | 30 | 20,83333333 | 2,5            | 6,25        |
| H     | 10 | 10 | 10 | 10          | 0              | 0           |


%% NO ESTOY SEGURO DE LO SIGUIENTE %%
Para calcular el tiempo esperado de la terminación del proyecto se suman todos los valores de la ruta critica la cual es la misma que se identifico anteriormente (A, D, G y H), lo cual da como resultado:
$$
15.333+15.333+20.833+10 = 61.5
$$
La varianza se calcula como la sumatoria de las varianzas de la ruta critica:
$$
1.777+1.777+6.25+0=9.805
$$
La desv. estandar es:
$$
\sqrt{9.805} = 3.131
$$

4. Cuál es la probabilidad de ser capaz de partir en una hora.
$$
z = \frac{60 - 61.5}{3.131} = 0.479
$$

Entonces la probabilidad es 

5. La gerencia desea que el 95% de sus vuelos salgan a tiempo, suponiendo que también llegan a tiempo. ¿Cuál es la menor cantidad de tiempo (hasta el minuto más cercano) que la gerencia debería planear para el lapso entre la llegada a la puerta y la salida?
6. Escriba las conclusiones comparando ambos métodos, CPM y PERT. (tiempo de terminación, ruta crítica, etc.)