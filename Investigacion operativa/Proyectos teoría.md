# 1. ¿Qué es un proyecto?

## 1.1. Proyecto

Un proyecto es una combinación de actividades interrelacionadas que deben ejecutarse en un cierto orden antes que el trabajo pueda terminarse.

## 1.2. Tareas o actividades

Una actividad o tarea es un trabajo que requiere recursos y tiempo para su ejecución.

## 1.3. Interrelaciones

*Interrelación de actividades*: la ejecución de algunas actividades dependen de la terminación de otras.

La *sucesión de tareas* que definen al proyecto *no se repiten en el futuro y no se deben haber repetido con anterioridad* (en las mismas condiciones).

Todas las tareas tienen una predecesora y una sucesora excepto la primera y la ultima.

## 1.4. Diferencia entre proceso y proyecto

Principalmente en el proceso tenemos una estructura, en los proyectos tenemos un lugar físico donde todo pasa en este y termina siendo el objetivo. La planificación de un proceso es muy distinta a la planificación de proyectos.

## 1.5. Características

**No se repite en el futuro ni en el pasado**: no se deben haber repetido con anterioridad exactamente en las mismas condiciones. Hay proyectos que, si bien tienen las mismas actividades que un proyecto pasado, por ej. la construcción de una casa, cambian las condiciones en las que se lleva a cabo el proyecto, por ej. los recursos humanos, las situaciones presupuestarias, las condiciones del tiempo, la compartición de recursos, etc.

# 2. Ejemplos de proyectos

Las posibilidades son ilimitadas y van desde cualquier trabajo, desde el que hacemos todos los días hasta los proyectos más complicados y de mayor envergadura.

# 3. Dirección de proyectos

Dirigir un proyecto es *planificar, programar y controlar* una serie de actividades para conseguir objetivos ya definidos en cuanto a rendimiento, costos y tiempo, utilizando recursos disponibles para su ejecución.

*Los recursos son escasos* y es importante que el director de proyectos tenga especial cuidado en la asignación de los mismos.

Una complicación frecuente en la dirección de proyectos son los proyectos multidisciplinarios ya que tiene que manejarse con grupos que hablan lenguajes distintos en cuanto a lo técnico y que requieren de métodos y herramientas distintas para desarrollar sus actividades.

# 4. Planificación de proyectos

Se deben responder ciertas preguntas para poner planificar un proyecto:

- ¿Qué hay que hacer?
	- Se responde teniendo en cuanta los objetivos y el alcance del trabajo a realizar.
- ¿Cómo hay que hacerlo?
	- Metodologías y estrategias que vamos a emplear para conseguir los objetivos propuestos.
- ¿Quién debe hacerlo?
	- Los responsables de llevar cada tarea adelante.
- ¿Cuando hay que hacerlo?
	- Se responde con una programación, a cada tarea se le fija una fecha de realización.
- ¿Cuanto cuesta?
	- Se fijan costos para cada actividad y se elabora un presupuesto del proyecto.

## 4.1. Pasos en la planificación

1. Definir el problema que debe resolver el proyecto -> fijamos objetivos y se definen los alcances.
2. Estructura de desglose -> identificar las tareas individuales que componen el proyecto.
3. Calcular *costos, duración y recursos* para cada actividad.
4. Elaborar un *programa maestro* -> identificamos las relaciones de tiempo entre las tareas y con un diagrama de redes o utilización de software nos diga la fecha más temprana de finalización del proyecto, se puede usar CPM o PERT para el calculo de esta fecha.
5. Elaborar un *presupuesto global* del proyecto.

## 4.2. Identificación de las tareas individuales

Los proyectos terminados consisten en diversas tareas individuales. Para analizar los proyectos, primero debemos identificar esas tareas. Estas pueden variar tanto en el tiempo requerido para concluirlas como en su complejidad.

1. Cada tarea debe tener un comiendo y un final claros en el contexto del proyecto.
2. La terminación de cada tarea debe ser necesaria para la conclusión del proyecto.
3. El tamaño de una tarea debe estar en proporción con el control que usted pueda ejercer.

## 4.3. Obtención de estimaciones de tiempo para cada tarea

El tiempo total que lleva completar todo el proyecto depende de cuanto tiempo lleva realizar cada tarea individual. Se debe obtener el tiempo requerido para cada tarea, esto se puede hacer:

1. Confiando en experiencias pasadas en proyectos similares.
2. Consultando con las personas a cargo de cada tarea individual.
3. Usando datos anteriores.

# 5. Creación de la tabla de precedencia para el proyecto

El tiempo de conclusión total *no* es igual a la suma de los tiempos de las tareas individuales ya que algunas tareas se pueden realizar simultáneamente. Otras no pueden comenzar hasta que ciertas tareas anteriores no hayan sido concluidas. Debemos conocer las tareas y como se relacionan entre si, para ello podemos construir una tabla que nos indique el tiempo individual de cada tarea y sus predecesoras inmediatas.

# 6. Red de proyecto

Uno de los objetivos principales de la administración de proyectos es determinar la cantidad mínima de tiempo requerido para terminar todo el proyecto. La identificación de las relaciones de precedencia entre las tareas individuales, como en la tabla anterior, es un primer paso en esa dirección. Una comprensión todavía mejor de estas relaciones puede obtenerse convirtiendo la información de precedencia en una *red de proyecto* Una red consiste en una colección finita de *nodos* y *flechas*. Una flecha conecta un nodo con otro.

# 7. Administración de proyectos usando tiempos determinísticos (CPM)

Nos interesa responder las siguientes preguntas:

1. ¿Qué tan pronto puede completarse todo el proyecto?
2. ¿Qué tareas son críticas? Las tareas críticas son las que generan un retraso en la conclusión del proyecto.

# 8. Determinación del tiempo de proyecto

Para encontrar este tiempo siempre se arranca desde el principio, determinando, para cada tarea, lo siguiente:

1. El *tiempo de inicio más inmediato* es el tiempo más inmediato en que esa tarea puede iniciarse.
2. El *tiempo de terminación más breve* es el tiempo más breve en el que esa tarea puede concluir.

- *Regla 1*: para calcular el tiempo de inicio de una tarea particular, debe conocer los tiempos de terminación de cada tarea predecesora inmediata.
- *Regla 2*: el tiempo de inicio más inmediato de una tarea de la que se conocen los tiempos de terminación de todas sus tareas predecesoras inmediatas es el máximo de esos tiempos de terminación.
- *Regla 3*:
$$
\text{Tiempo terminación más breve} = \text{Tiempo inicio inmediato}+\text{Tiempo tarea}
$$
- *Regla 4*: para calcular el último tiempo de terminación de una tarea particular, debemos conocer los últimos tiempos de inicio de cada tarea sucesora inmediata.
- *Regla 5*: respecto a una tarea de la que se conocen los últimos tiempos de inicio de todas sus tareas sucesoras inmediatas, el último tiempo de terminación de esa tarea es el mínimo de los últimos tiempos de inicio de todas las tareas sucesoras inmediatas.
- *Regla 6*:
$$
\text{Ultimo tiempo inicio} = \text{Ultimo tiempo terminación}-\text{Tiempo tarea}
$$

# 9. Identificar las tareas críticas

Crítica significa que un retraso en cualquiera de estas tareas ocasiona un retraso en todo el proyecto, los retrasos ocasionan costos adicionales, ingresos perdidos e incumplimiento de las obligaciones contractuales.

Debemos calcular lo siguiente para cada tarea:

1. *El último tiempo de terminación* que es lo más tarde que puede concluirse una tarea mientras permita que el proyecto se complete lo más pronto posible.
2. *El último tiempo de inicio* que es lo más tarde que puede iniciarse una tarea, de tal forma que finalice en su último tiempo de terminación.

***Cualquier actividad cuyo último tiempo de inicio sea igual que su tiempo de inicio más inmediato calculado en la sección anterior es crítica.***

Habiendo hecho uso de las "reglas" y los cálculos, podemos identificar las tareas críticas y no críticas, para cada tarea calculamos el *tiempo de retraso* que es la diferencia entre los tiempos de inicio últimos y más inmediatos:

$$
\text{Tiempo retraso (holgura)} = \text{Ultimo tiempo inicio}-\text{Tiempo inicio más inmediato}
$$

Los tiempos de retraso que ubicaremos en una tabla, representan la cantidad de tiempo según la cual la tarea correspondiente puede retrasarse sin retrasar todo el proyecto, *suponiendo que todas las demás tareas se realizan a tiempo*.

# 10. Técnicas de choque*

En muchos proyectos la gerencia puede decidir que el tiempo de conclusión más breve no es aceptable. En tales casos, a menudo pueden usarse recursos adicionales para agilizar ciertas tareas, ocasionando una conclusión más temprana del proyecto. En este caso puede formularse un modelo de programación lineal para determinar las tareas que deben agilizarse para lograr un tiempo de conclusión deseado, y a qué costo.

## 10.1. Obtención de datos de costos adicionales para las tareas*

¿Qué tareas del proyecto pueden acortarse y en cuánto? Claro está que acortar las tareas requiere recursos adicionales, como el pago de tiempos extra, personal adicional y/o subcontrataciones. Por lo tanto, los primeros pasos son enumerar, para cada tarea:

1.  ***El tiempo de choque***, esto es, el tiempo mínimo posible en el que la tarea puede concluirse de manera realista usando recursos adicionales.
2. ***El costo de los recursos adicionales*** necesarios para acortar el tiempo de tarea a cualquier valor entre sus tiempos normales y de choque.

Para obtener el tiempo de choque se puede consultar con las personas que están directamente involucradas en la terminación de cada tarea para determinar de que forma y con que recursos se pueden acortar dichas tareas y en que valor.

Para armar el modelo de programación lineal se supone que los costos varían linealmente en el periodo en que se puede realizar la tarea. Se toman como variables de decisión los tiempos en que se pueden acortar las tareas con las restricciones correspondientes y se arma la función objetivo como la suma de los productos de las variables de decisión por el correspondiente costo unitario. Esta función objetivo es la que hay que minimizar y resolver para determinar cual variable (tarea) nos conviene acortar.

# 11. Administración de proyectos usando tiempos de tarea probabilísticos (PERT)

Cuando un proyecto está formado por actividades que en su mayoría son similares a otras ya realizadas un gran número de veces, generalmente se utiliza la programación CPM.

Sin embargo, cuando en un proyecto predominan actividades para las que no existe experiencia la dificultad sobre la estimación de la duración de las tareas es significativa. En este caso lo único que se puede hacer es conjeturar basándose en cualquier experiencia que se tenga. Generalmente los proyectos de investigación y desarrollo tienen esta característica.

En respuesta a este problema se desarrollo el sistema PERT que tiene en cuenta un intervalo de duración y la probabilidad que la duración de una actividad esté en ese intervalo. El modelo PERT clásico supone que las duraciones de las tareas son variables aleatorias estadísticamente independientes que siguen una distribución beta.

El proceso de estimar la duración de las actividades del cronograma utiliza información sobre el alcance del trabajo de la actividad. Así como sobre los tipos de recursos necesarios, las cantidades de recursos estimadas y los calendarios de disponibilidad de recursos. Las entradas para realizar las estimaciones de la duración de las actividades suelen partir de las personas del equipo del Proyecto que estén más familiarizadas con la naturaleza del contenido del trabajo de la actividad.

La estimación de la duración se elabora de forma gradual, y el proceso evalúa la calidad y disponibilidad de los datos de partida. Por ejemplo, a medida que se desarrollan la ingeniería del producto y el trabajo de diseño, se dispone de datos más detallados y precisos, por lo que mejora la exactitud de las estimaciones de la duración. De esta manera, la estimación de la duración será cada vez más exacta y de mejor calidad conforme se avance en el Proyecto.

Este proceso, es sin duda uno de los que requiere de más esfuerzo y que implica un alto riesgo. Esto es debido a que estimaciones erróneas, seguramente impliquen dedicar más tiempo a la ejecución de las actividades del planificado, lo que conlleva a un retraso en la ejecución.

Debe estimarse la cantidad de esfuerzo de trabajo requerido y la cantidad de recursos para completar la actividad. Lo cual permite determinar la cantidad de periodos de trabajo (duración de la actividad) necesarios para completar la actividad. Se deben documentar todos los datos y supuestos que respaldan el estimado de la duración de la actividad.

## 11.1. Entradas

- Plan de Gestión del Cronograma
- Lista de Actividades con sus atributos
- Recursos Requeridos para la Actividades.
Los requisitos de los recursos asignados a las actividades, en cuanto a eficiencia y capacidad, afectarán a la duración. Por ejemplo, la duración de una actividad del Cronograma pensada para dos ingenieros sénior aumenta si sólo es posible asignar uno con experiencia suficiente. A medida que se agregan recursos o se aplican recursos más ó menos especializados a algunas de las actividades, su duración puede disminuir ó aumentar. También afectan la cantidad, disponibilidad y rendimiento de los equipos, herramientas y recursos materiales. Efectivamente, todos estos parámetros podrían afectar significativamente a la estimación de la duración de las actividades.
- Calendario de recursos.
La asignación de recursos a una actividad y su disponibilidad, influyen sobre la duración de la misma.
- Enunciado del alcance del proyecto.
A la hora de realizar la estimación de la duración de las actividades, deben tenerse en cuenta las restricciones y supuestos contemplados en la declaración del alcance.
- Registro de riesgos.
Salida del proceso El registro de riesgos proporciona una lista de riesgos junto con los resultados del análisis de riesgos y de la planificación de la respuesta a los riesgos.
- Estructura de desglose de recursos (RBS) Resources Breakdown Structure
- Factores ambientales y activos de los procesos de la organización.
Como factores ambientales que pueden influir en el proceso podemos considerar las métricas de productividad o bases de datos de estimados de duración. Como activos, información histórica, calendarios del proyecto, metodología de planificación o lecciones aprendidas.

## 11.2. Herramientas y Técnica

- Juicio de expertos.
Miembros del equipo o expertos con experiencia en proyectos similares aportan información sobre el estimado de las duraciones.
- Estimación análoga.
Esta herramienta utiliza parámetros de proyectos similares anteriores para hacer la estimación actual. Como por ejemplo duraciones, presupuesto, complejidad, etc. Que suele utilizarse cuando existe una cantidad limitada de información. Utiliza información histórica y el juicio de expertos. Generalmente es menos costosa y emplea menos tiempo que otros métodos de estimación. Aunque por el contrario es menos exacta. Se conoce también como Estimación Descendente.
- Estimación paramétrica.
Relación estadística entre datos históricos y otras variables para determinar la estimación de parámetros de una actividad. Utiliza valores como rendimientos estadísticos y datos del Proyecto actual. De esta forma se puede determinar cuantitativamente la duración de la actividad. Multiplicando la cantidad de trabajo a realizar por el rendimiento. Este método permite obtener valores más precisos.
- Estimación por tres valores.
Este método toma en consideración el grado de incertidumbre y riesgo de la estimación. Técnica de Revisión y Evaluación de Programas (método PERT). Utiliza tres valores estimados para definir el rango aproximado de duración de una actividad:

* MÁS PROBABLE (B)
* OPTIMISTA (A)
* PESIMISTA (C)
* ESPERADA (M)

![[ditribucion beta.jpg]]

En la técnica PERT, el tiempo de la actividad se considera como una variable aleatoria según una distribución de probabilidad Beta como se presenta en el gráfico a continuación: Las fórmulas estadísticas detrás de la distribución PERT se resumen en la tabla a continuación:

Media:

$$
M=\frac{a+4b+c}{6}
$$

Desv. estandar

$$
\sigma=\frac{c-a}{6}
$$

Varianza

$$
\sigma^{2}
$$

Duración del proyecto: ($M$ tiempos en el camino critico)

$$
\sum_{}^{}M
$$

Varianza del proyecto: varianzas en el camino critico

$$
\sum_{}^{}\sigma^{2}
$$

## 11.3. Estimación de los tiempos de terminación de tareas

Los tiempos de terminación de estas tareas son bastantes variables debido a la incertidumbre de las condiciones climatológicas, la obtención de suministros, el mantenimiento de las relaciones laborales, etc. Así pues, una sola estimación del tiempo requiere el conocimiento de la *distribución de probabilidad* de los tiempos de terminación de cada tarea.

En el contexto de las tareas de un proyecto, obtenemos tres estimaciones de tiempo para cada tarea:

- Tiempo ***más optimista***, $a$, es decir, el tiempo más corto en el que la tarea puede hacerse.
- Tiempo ***más pesimista***, $b$, es decir, el tiempo más largo que se puede llevar una tarea dentro de lo razonable.
- Tiempo ***más probable***, $m$, es decir, el tiempo que la tarea requiere con más frecuencia en circunstancias normales

Para una distribución beta, estas tres estimaciones de tiempos se combinan para obtener el valor esperado (medio) y la desviación estándar del tiempo de terminación de una tarea, de acuerdo con las siguientes fórmulas:

$$
\text{Tiempo de tarea esperado}=\frac{a+4m+b}{6}
$$

$$
\text{Desviación estandar}=\frac{b-a}{6}
$$

## 11.4. Análisis probabilístico del tiempo de terminación de proyectos

Recordemos que el tiempo de terminación del proyecto calculado en la sección anterior es el tiempo de terminación *esperado*.  El tiempo de terminación real puede variar debido a que los mismos tiempos de terminación de las tareas son variables. Puesto que el tiempo de terminación esperado de 30 semanas, hasta cierto grado, no es confiable, el gerente de construcción deberá hacerse preguntas como las siguientes:

1. ¿Cuál es la probabilidad de cumplir con una fecha específica de terminación del  proyecto? Por ejemplo,¿cuál es la probabilidad de construir la casa en 32 semanas?
2. Qué fecha de terminación puede cumplirse con un nivel dado de confianza? Por ejemplo, ¿cuál es la fecha última de terminación en la cual usted tiene una confianza  del 95% de cumplir?

En la práctica, la distribución real del tiempo de terminación del proyecto se aproxima mediante una distribución normal. Para utilizar esta aproximación se requieren las siguientes suposiciones:

1. Las tareas que se determinaron como críticas utilizando los tiempos de tarea esperados  siguen siendo críticas, *incluso si varían los tiempos de terminación reales de las tareas*. El tiempo de terminación del proyecto es la suma de los tiempos de terminación de las tareas críticas individuales *a lo largo de una trayectoria crítica.* ***Tiempo de terminación del proyecto*** = (tiempo de terminación de la tarea 1) + (tiempo de terminación de la tarea 2) + (tiempo de terminación de la tarea 3) + (tiempo de terminación de la tarea 5) + (tiempo de terminación de la tarea 6)+(tiempo de terminación de la tarea 8) + (tiempo de terminación de la tarea 9)
2. El tiempo  de terminación de cada tarea es *independiente* del tiempo de terminación de cualquier otra tarea. Tiempo esperado de terminación de proyectos = suma de los tiempos esperados de terminación de todas las tareas a lo largo de esa trayectoria crítica. Varianza del tiempo de terminación del proyecto = suma de las varianzas de los tiempos de terminación de las tareas a lo largo de esa trayectoria crítica.

$$
T = 3+7+6+3+5+5+1 = 30
$$

Varianza del tiempo de terminación del proyecto = suma de las varianzas de los tiempos de terminación de las tareas a lo largo de esa trayectoria crítica.

$$
V=\left( 0.333 \right)^{2}+\left( 1.333 \right)^{2}+\left( 0.333 \right)^{2}+\left( 0.667 \right)^{2}+\left( 1 \right)^{2}+\left( 0 \right)^{2}=3.889
$$

3. a.-¿Cuál es la probabilidad de terminar una casa en 32 semanas?

La respuesta a esta pregunta es equivalente a encontrar el área que se encuentra a la izquierda del 32 bajo una distribución normal con una media de 30 y una desviación estándar de 1.972.

$$
z=\frac{32-\text{Media}}{\text{Desv. Estandar}}=\frac{32-30}{1.972}=1.014
$$

$$
0.5+0.3447=0.8447
$$

En otras palabras, la probabilidad de construir la casa en 32 semanas es de 84,47%.

b.- ¿Qué fecha de terminación deberá darse de modo que se tenga 95% de confianza de  que la casa estará terminada en ese tiempo?

Para responder a esta pregunta, usted necesita determinar el punto *x* donde el área bajo la distribución normal que se encuentra a la izquierda del punto es de 0.95.

$$
z=1.645=\frac{x-\text{Media}}{\text{Desv. Estandar}}=\frac{x-30}{1.972}
$$

Resolviendo tenemos que *x* = 33.24 semanas.

# 12. CPM o PERT

La principal diferencia entre el método de PERT y la ruta crítica CPM es el nivel de certeza en torno a la duración de las actividades.

| CPM                                                                                               | PERT                                                                                                                            |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Modelo determinista                                                                               | Modelo probabilístico                                                                                                           |
| Gestiona las actividades predecibles del proyecto                                                 | Gestiona actividades inciertas del proyecto                                                                                     |
| Enfoque en compensaciones de tiempo-costo                                                         | Enfoque en alcanzar o minimizar la duración de un proyecto                                                                      |
| Estimación única para cada actividad (una duración determinada), tenemos un tiempo determinístico | Tiene tres estimaciones para cada actividad, usaremos una *distribución beta* para determinar el tiempo de duración de la tarea |

Ambos analizan los siguientes componentes:

- Lista de tareas necesarias.
- Duración estimada de cada tarea.
- Dependencias de las tareas.
