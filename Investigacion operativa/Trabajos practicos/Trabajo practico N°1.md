%% CORREGIR LAS TABLAS QUE TIENEN COMAS %%

# Ejercicio N°3

La gerencia de World Airways desea determinar la cantidad mínima de tiempo necesaria para que un aeroplano de la vuelta, desde el momento en que alcanza la puerta hasta que se encuentra listo para salir por ella. Para tal efecto, el administrador de vuelo ha identificado las siguientes tareas que se necesitan llevar a cabo entre la llegada y la partida.

![[tabla ej n3.png]]

Las comidas no pueden ser subidas a bordo ni la limpieza del interior puede efectuarse hasta que han bajado los pasajeros. El equipaje de los pasajeros que parten no puede ser cargado hasta que se ha descargado el equipaje de los que llegan. Los pasajeros no pueden abordar la nave hasta que el interior esté limpio. La prueba de seguridad puede realizarse solamente después de que los motores han sido abastecidos de combustible y las comidas, los equipajes y los pasajeros ya están a bordo.

1. Trace la red de proyectos
La red de proyectos se dibuja con los tiempos *más probables* ($m$).

![[ej n3 red de proyectos |1000 | center]]

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

Entonces la probabilidad es (con interpolación):

$$
y = y_{0}+\frac{x-x_{0}}{x_{1}-x_{0}}\cdot \left( y_{1}-y_{0} \right)
$$

Donde, para el valor de 0.4 en la tabla:

|   x0   |   x    |   x1   |
|:----: |:----: |:----: |
|  0.07  | 0.0790 | 0.0800 |
|   y0   |   y    |   y1   |
| 0.1808 | 0.1840 | 0.1844 |

El valor calculado es $y = 0.1840$, donde calculamos la probabilidad:

$$
0.5 + 0.1840 = 0.684
$$

O sea una probabilidad de $68.4\%$.

5. La gerencia desea que el 95% de sus vuelos salgan a tiempo, suponiendo que también llegan a tiempo. ¿Cuál es la menor cantidad de tiempo (hasta el minuto más cercano) que la gerencia debería planear para el lapso entre la llegada a la puerta y la salida?

Debemos calcular:

$$
0.95 - 0.5 = x = 0.45
$$

Luego utilizando la tabla calculamos el valor de $z$:

$$
z = 1.65
$$

Y por ultimo la cantidad de minutos que la gerencia debería planear para el lapso entre la llegada a la puerta y la salida:

$$
\left( 1.65 \cdot 3.131 \right)+61.5 = 66.666
$$

6. Escriba las conclusiones comparando ambos métodos, CPM y PERT. (tiempo de terminación, ruta crítica, etc.)

Tanto como por CPM, como por PERT se llega a la misma ruta critica, sin embargo los tiempos de terminación son diferentes, siendo de 60 en CPM y 61.5 con PERT. Teniendo el metodo PERT más variables tenidas en cuenta, y considerando que se utiliza cuando se tiene poca experiencia en la tarea a desarrollar, puede llegar a ser más preciso y nos da una mejor lectura de como se desarrollarían las actividades a traves de probabilidades.

# Ejercicio N°4

Usted es el Project Manager de un proyecto que tiene una duración de 12 meses acordadas con su cliente. Cuenta con un presupuesto total de $120 millones, donde presupuesta la producción de 24 aerogeneradores a razón de 2 unidades mensuales. La situación al corte del 6 mes es la siguiente: lleva gastado $70 millones y ha producido 10 aerogeneradores.

El Director de Operaciones le pide el siguiente informe:

1. $VC$.
2. $VP$.
3. $IDC$.
4. $EAC$.

En cada caso, de una breve explicación.

| Producción total | Costo total          | Costo unitario presupuestado                 | Aerogeneradores a los 6 meses |
| ---------------- | -------------------- | -------------------------------------------- | ----------------------------- |
| $24$             | $\$120\times 10^{6}$ | $\$120\times 10^{6} / 24 = \$5\times 10^{6}$ | $10$                          |

Siendo $CRTR$ el costo del trabajo realizado hasta el momento:

$$
CRTR = \$ 70\times 10^{6}
$$

$CPTP$ es el costo presupuestado del $t$ programado, o sea si se realizan $2$ unidades mensuales, a los 6 meses deberían haber $12$ unidades y un gasto de $\$ 60\times 10^{6}$.

Por ultimo $CPTR$ es el costo presupuestado del trabajo real realizado:

$$
10 \cdot \$5\times 10^{6} = \$50\times 10^{6}
$$

Podemos empezar a calcular $VC$ (variación de costes):

$$
VC = CPTR - CRTR = \$50\times 10^{6} - \$ 70\times 10^{6} = -\$ 20\times 10^{6}
$$

$VP$ es la variación de programación:

$$
VP = CPTR - CPTP = \$50\times 10^{6} - \$ 60\times 10^{6} = - \$ 10\times 10^{6}
$$

La tasa a la que estamos consumiendo los recursos (o eficiencia), es el índice de desempeño de costes o $IDC$:

$$
IDC = CPTR / CRTR = \$50\times 10^{6} / \$ 70\times 10^{6} = 0.714
$$

Antes de calcular $EAC$ debemos definir $PAC$ que representa lo presupuestado al completar, el cual es el valor total presupuestado, o sea en este caso $\$120\times 10^{6}$.

Entonces podemos finalmente calcular el $EAC$ que es la estimación del coste final del proyecto (estimación al completar):

$$
EAC = PAC / IDC = \$120\times 10^{6} / 0.714 = \$168.067 \times 10^{6}
$$
