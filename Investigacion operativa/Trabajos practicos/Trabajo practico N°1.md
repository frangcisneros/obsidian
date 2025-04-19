%% CORREGIR LAS TABLAS QUE TIENEN COMAS %%

# 1. Ejercicio N°1

La siguiente tabla muestras las actividades de reubicar una Línea Eléctrica de media tensión, debido a problemas de abastecimiento eléctrico de la zona cuando se produce el encendido del alumbrado público, causando problemas con cortes a los clientes de la zona.

1. Desarrolle el diagrama de red correspondiente
![[ej n1 red de proyectos |1000]]

2. Resuelva el mismo con el método CPM. Encuentre la Ruta Crítica y el mínimo tiempo de terminación del Proyecto.
El mínimo de tiempo para terminar el proyecto es 20.64 días, esto se obtiene sumando todos los tiempos de las tareas críticas.

La ruta crítica es: A -> C -> E -> F -> J -> L -> M -> P -> Q -> S -> T

3. Cuál es el tiempo mínimo de conclusión del proyecto mediante el método PERT.
Calculamos la media de los tiempos de la ruta crítica:

| TAREA | A    | M    | B    | MEDIA       | DESV. ESTANDAR |
|-------|------|------|------|-------------|----------------|
| A     | 0.4  | 1.1  | 1.7  | 1.083333333 | 0.216666667    |
| C     | 0.55 | 0.95 | 1.5  | 0.975       | 0.158333333    |
| E     | 2    | 3.2  | 4    | 3.133333333 | 0.333333333    |
| F     | 3    | 3.7  | 4.2  | 3.666666667 | 0.2            |
| J     | 2.5  | 3.7  | 6.8  | 4.016666667 | 0.716666667    |
| L     | 1.8  | 2.1  | 2.5  | 2.116666667 | 0.116666667    |
| M     | 1.5  | 2.3  | 2.7  | 2.233333333 | 0.2            |
| P     | 0.08 | 0.11 | 0.12 | 0.106666667 | 0.006666667    |
| Q     | 0.3  | 0.48 | 0.52 | 0.456666667 | 0.036666667    |
| S     | 0.7  | 0.9  | 1.5  | 0.966666667 | 0.133333333    |
| T     | 1.8  | 2.1  | 2.4  | 2.1         | 0.1            |

El tiempo mínimo entonces es = 20.855

4. Cuál es la probabilidad que el proyecto se termine en 23 días.
Primero calculamos la desv. estándar de la ruta crítica (sumando todas las desviaciones estandar):

$$
\sigma = 2.218
$$

Entonces:

5. Indique la Ruta Critica
6. Cuál es el tiempo TOTAL que dispone para la realización de las actividades "Coordinación de ubicación de postes" y "Desenergización y conmutación de líneas"
7. Si para "Cubrir conductores antiguos" se demoran 5 días, cual es el tiempo de conclusión del proyecto.
8. Escriba las conclusiones comparando ambos métodos, CPM y PERT. (tiempo de terminación, ruta crítica, etc.)

TO: tiempo óptimo

TN: tiempo normal

TP: tiempo pésimo

| N°  | DESCRIPCION                              | PRECED. | TO   | TN   | TP   |
| --- | ---------------------------------------- | ------- | ---- | ---- | ---- |
| A   | Revisión del Trabajo                     | -       | 0.4  | 1.1  | 1.7  |
| B   | Clientes – Interrupción temporal         | A       | 0.2  | 0.55 | 0.7  |
| C   | Almacenes de requisición                 | A       | 0.55 | 0.95 | 1.5  |
| D   | Reconocimiento de trabajo                | A       | 0.32 | 0.48 | 0.9  |
| E   | Obtención de postes y materiales         | C,D     | 2    | 3.2  | 4    |
| F   | Distribución de postes                   | E       | 3    | 3.7  | 4.2  |
| G   | Coordinación de ubicación de postes      | D       | 0.31 | 0.47 | 0.8  |
| H   | Preparación                              | G       | 0.29 | 0.53 | 0.7  |
| I   | Cavar agujeros                           | H       | 2    | 2.8  | 6    |
| J   | Preparar y colocar postes                | F,I     | 2.5  | 3.7  | 6.8  |
| K   | Cubrir conductores antiguos              | F,I     | 0.5  | 1.1  | 1.5  |
| L   | Colocar nuevos conductores               | J,K     | 1.8  | 2.1  | 2.5  |
| M   | Instalación de material restante         | L       | 1.5  | 2.3  | 2.7  |
| N   | Tendido de conductor                     | L       | 1.3  | 2    | 2.4  |
| O   | Poda de arboles                          | D       | 1.5  | 2.4  | 2.5  |
| P   | Desenergización y conmutación de líneas  | B,M,N,O | 0.08 | 0.11 | 0.12 |
| Q   | Energización de nueva línea              | P       | 0.3  | 0.48 | 0.52 |
| R   | Limpieza                                 | Q       | 0.5  | 1.1  | 1.3  |
| S   | Remoción del conductor anterior          | Q       | 0.7  | 0.9  | 1.5  |
| T   | Remoción de postes anteriores            | S       | 1.8  | 2.1  | 2.4  |
| U   | Devolución de materiales a los almacenes | I       | 1.9  | 2    | 2.4  |

# 2. Ejercicio N°3

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

# 3. Ejercicio N°4

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

# 4. Ejercicio N°5

Usted esta realizando el seguimiento del proyecto constructivo de cuatro tramos de ruta, tal como se muestra en el excel y según el siguiente detalle presupuestado:

1. Tramo 1: costo estimado $350 millones (CPTP)
2. Tramo 2: costo estimado $240 millones (CPTP)
3. Tramo 3: costo estimado $200 millones (CPTP)
4. Tramo 4: costo estimado $195 millones (CPTP)

![[imagen ejercicio 5.png]]

En una instancia de control, el Tramo 1se encuentra iniciado y totalmente terminado con un costo contable (CRTR) de $390 millones, el tramo 2 se encuentra iniciado y totalmente concluido con un coste contable (CRTR) de $320 millones, el tramo 3 se encuentra iniciado y 65% de avance con un costo (CRTR) de $100 millones. El tramo 4 no se ha comenzado  pero si se ha incurrido en gastos de administración por un importe de (CRTR) $25 millones. Determinar y explicar cada índice solicitado en el contexto del proyecto:

1. VC
2. VP
3. IDC
4. EAC
