# 1. ¿Qué es un proyecto?

## 1.1. Proyecto

Un proyecto es una combinación de actividades interrelacionadas que deben ejecutarse en un cierto orden antes que el trabajo pueda terminarse.

## 1.2. Tareas o actividades

Una actividad o tarea es un trabajo que requiere recursos y tiempo para su ejecución.

## 1.3. Interrelaciones

*Interrelación de actividades*: la ejecución de algunas actividades dependen de la terminación de otras.

La *sucesión de tareas* que definen al proyecto *no se repiten en el futuro y no se deben haber repetido con anterioridad* (en las mismas condiciones).

Todas las tareas tienen una predecesora y una sucesora excepto la primera y la ultima.

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

**1-**      **Entradas**

- Plan de Gestión del Cronograma
- Lista de Actividades con sus atributos
- Recursos Requeridos para la Actividades. Los requisitos de los recursos asignados a las actividades, en cuanto a eficiencia y capacidad, afectarán a la duración. Por ejemplo, la duración de una actividad del Cronograma pensada para dos ingenieros sénior aumenta si sólo es posible asignar uno con experiencia suficiente. A medida que se agregan recursos o se aplican recursos más ó menos especializados a algunas de las actividades, su duración puede disminuir ó aumentar. También afectan la cantidad, disponibilidad y rendimiento de los equipos, herramientas y recursos materiales. Efectivamente, todos estos parámetros podrían afectar significativamente a la estimación de la duración de las actividades.
- Calendario de recursos. La asignación de recursos a una actividad y su disponibilidad, influyen sobre la duración de la misma.
- Enunciado del alcance del proyecto. A la hora de realizar la estimación de la duración de las actividades, deben tenerse en cuenta las restricciones y supuestos contemplados en la declaración del alcance.
- Registro de riesgos. Salida del proceso El registro de riesgos proporciona una lista de riesgos junto con los resultados del análisis de riesgos y de la planificación de la respuesta a los riesgos.
- Estructura de desglose de recursos (RBS) Resources Breakdown Structure
- Factores ambientales y activos de los procesos de la organización. Como factores ambientales que pueden influir en el proceso podemos considerar las métricas de productividad o bases de datos de estimados de duración. Como activos, información histórica, calendarios del proyecto, metodología de planificación o lecciones aprendidas.

**2-**      **Herramientas y Técnica**

- Juicio de expertos. Miembros del equipo o expertos con experiencia en proyectos similares aportan información sobre el estimado de las duraciones.
- Estimación análoga. Esta herramienta utiliza parámetros de proyectos similares anteriores para hacer la estimación actual. Como por ejemplo duraciones, presupuesto, complejidad, etc. Que suele utilizarse cuando existe una cantidad limitada de información. Utiliza información histórica y el juicio de expertos. Generalmente es menos costosa y emplea menos tiempo que otros métodos de estimación. Aunque por el contrario es menos exacta. Se conoce también como Estimación Descendente.
- Estimación paramétrica. Relación estadística entre datos históricos y otras variables para determinar la estimación de parámetros de una actividad. Utiliza valores como rendimientos estadísticos y datos del Proyecto actual. De esta forma se puede determinar cuantitativamente la duración de la actividad. Multiplicando la cantidad de trabajo a realizar por el rendimiento. Este método permite obtener valores más precisos.
- Estimación por tres valores. Este método toma en consideración el grado de incertidumbre y riesgo de la estimación. Técnica de Revisión y Evaluación de Programas (método PERT). Utiliza tres valores estimados para definir el rango aproximado de duración de una actividad:

* MÁS PROBABLE (B)
* OPTIMISTA (A)
* PESIMISTA (C)
* ESPERADA (M)

Media:

media:

$$
M=\frac{a+4b+c}{6}
$$

desv estandar

$$
\sigma=\frac{c-a}{6}
$$

varianza

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

# 12. Estimación de los tiempos de terminación de tareas

Los tiempos de terminación de estas tareas son bastantes variables debido a la incertidumbre de las condiciones climatológicas, la obtención de suministros, el mantenimiento de las relaciones laborales, etc. Así pues, una sola estimación del tiempo requiere el conocimiento de la *distribución de probabilidad* de los tiempos de terminación de cada tarea.

En el contexto de las tareas de un proyecto, obtenemos tres estimaciones de tiempo para cada tarea:

 Tiempo ***más optimista***, a, es decir, el tiempo más corto en el que la tarea puede hacerse.

 Tiempo ***más pesimista***, b, es decir, el tiempo más largo que se puede llevar una tarea dentro de lo razonable.

 Tiempo ***más probable***, m, es decir, el tiempo que la tarea requiere con más frecuencia en circunstancias normales

Para una distribución beta, estas tres estimaciones de tiempos se combinan para obtener el valor esperado (medio) y la desviación estándar del tiempo de terminación de una tarea, de acuerdo con las siguientes fórmulas:

Tiempo de tarea esperado es la media.

# 13. Analaisis probabilistico del tiempo de terminacion de proyectos

Recordemos que el tiempo de terminación del proyecto calculado en la sección anterior es el tiempo de terminación *esperado*.  El tiempo de terminación real puede variar debido a que los mismos tiempos de terminación de las tareas son variables. Puesto que el tiempo de terminación esperado de 30 semanas, hasta cierto grado, no es confiable, el gerente de construcción deberá hacerse preguntas como las siguientes:

a.-¿Cuál es la probabilidad de cumplir con una fecha específica de terminación del  proyecto? Por ejemplo,¿cuál es la probabilidad de construir la casa en 32 semanas?

b.-¿Qué fecha de terminación puede cumplirse con un nivel dado de confianza? Por ejemplo, ¿cuál es la fecha última de terminación en la cual usted tiene una confianza  del 95% de cumplir?

En la práctica, la distribución real del tiempo de terminación del proyecto se aproxima mediante una distribución normal. Para utilizar esta aproximación se requieren las siguientes suposiciones:

1.- Las tareas que se determinaron como críticas utilizando los tiempos de tarea esperados  siguen siendo críticas, *incluso si varían los tiempos de terminación reales de las tareas*.

El tiempo de terminación del proyecto es la suma de los tiempos de terminación de las tareas críticas individuales *a lo largo de una trayectoria crítica.*              

***Tiempo de terminación del proyecto*** = (tiempo de terminación de la tarea 1) + (tiempo de terminación de la tarea 2) + (tiempo de terminación de la tarea 3) + (tiempo de terminación de la tarea 5) + (tiempo de terminación de la tarea 6)+(tiempo de terminación de la tarea 8) + (tiempo de terminación de la tarea 9)

2.- El tiempo  de terminación de cada tarea es *independiente* del tiempo de terminación de cualquier otra tarea.

Tiempo esperado de terminación de proyectos = suma de los tiempos esperados de terminación de todas las tareas a lo largo de esa trayectoria crítica.

Varianza del tiempo de terminación del proyecto = suma de las varianzas de los tiempos de terminación de las tareas a lo largo de esa trayectoria crítica.

# 14. Ruta critica

La ruta critica siempre es la misma.

# 15. Varianza

La media es el promedio de un valor, la desv. estandar es que tan lejos estamos de la media, la varianza es la dispersión de los datos.

# 16. CPM o PERT

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

# 17. Seguimiento de proyectos (poner en una hoja aparte)

En la mayoría de los proyectos, el personal no sabe medir con realismo el rendimiento del trabajo.

Quizás la información de control más importante con la que cuentan los jefes de proyectos son los datos sobre la cantidad de trabajo realizado. Si no saben cuanto trabajo han cumplido, no pueden saber si están gastando de más o de menos, ni si están cumpliendo con la programación y los objetivos. El control efectivo de proyectos requiere que las organizaciones que realizan proyectos generen medidas precisas del rendimiento del trabajo.

Tradicionalmente los datos de rendimiento se recogen haciendo que el personal de proyecto informe sobre el "porcentaje de la tarea cumplida" mes a mes. Por lo general, se deja que el personal interprete lo que significa. La mayoría informa del porcentaje cumplido basándose en la intuición, su fiabilidad es muy baja, debido a que es muy probable que cinco personas que informen sobre el porcentaje de trabajo cumplido den cinco evaluaciones diferentes.

Ocasionalmente, los grupos pueden revisar lo que han gastado del presupuesto y dar ese porcentaje como su estimación del trabajo que se ha cumplido. Desgraciadamente el mundo real de la dirección de proyectos, la correlación entre el dinero gastado y el trabajo realizado es débil, por lo que esto no es una buena medida. Aún más, con este enfoque el personal del proyecto no aporta a la organización nueva información, dado que el departamento de contabilidad ya sabe cuanto del presupuesto se gastó.

Entonces ¿Cómo se mide el rendimiento del trabajo? Esta pregunta es el tema clave, la respuesta se centra en los conceptos de valor devengado y control integrado de costes/programación.

***Un método gráfico para el control integrado de costes/programación***

La interpretación de datos de variación de costes y programación debe hacerse con cuidado. Si las cuentas muestran que tenemos una variación positiva del 10% en marzo, no deben sacar apresuradamente la conclusión de que ahorramos dinero. Quizás la variación positiva refleja el hecho que no hemos trabajado demasiado. Si no hicimos el trabajo, puede ser el motivo por el que no gastamos el dinero. Por lo mismo, una variación negativa no significa necesariamente que hemos gastado de más. Puede reflejar el hecho de que trabajamos más de lo planificado en marzo.

El sentido común requiere que para tener una percepción precisa de la situación de un proyecto, debemos analizar las variaciones de costes y programación de manera concurrente. Una ***variación positiva*** en los costes realmente refleja un ahorro si estamos avanzando o cumpliendo con lo programado. Una ***variación negativa*** indica exceso en los gastos si estamos retrasados en la relación a lo programado o incluso si estamos cumpliendo lo planificado.

Una manera efectiva de examinar las variaciones de costes y programación es usar curvas de costes acumulativos (también llamadas curvas de las S) y cuadros Gantt. El uso de estas herramientas de control permite al personal y los directivos evaluar la situación general del proyecto de un vistazo. Esto se ve en la figura 1.a que  muestra que el proyecto esta cumpliendo fundamentalmente su programación y la curva acumulativa de costes muestra que el dinero se esta gastando de acuerdo con el presupuesto. Esto refleja una situación en la que el progreso parece darse según lo planeado.

La figura 1.b muestra que las tareas se están cumpliendo antes de lo previsto. Al mismo tiempo, se está gastando más dinero que lo presupuestado para el período bajo estudio. Esto refleja una situación en la que se invierten recursos extra para mantener o acelerar lo programado.

La figura 1.e muestra la peor situación posible: el proyecto sufre tanto retrasos como excesos en los gastos.

El control integrado de costes/programación presentado por medios gráficos es una herramienta de comunicación efectiva. Como tal, se la puede emplear para informar de la situación del proyecto, tanto a la dirección superior como al personal, de un modo fácil de comprender. Otra ventaja de este recurso es que los paquetes de planificación comúnmente generan buenos cuadros de costes y programación, de modo que realizar los gráficos no es ningún problema.

La principal deficiencia de esta presentación es que resulta poco práctica desde el punto de vista analítico. Los gráficos dan una impresión visual de la situación del proyecto, pero por sí mismos no ofrecen más información: carecen de datos importantes como el ritmo al que se gasta el presupuesto frente a la cantidad de trabajo que se realiza, la contribución de cada tarea al cumplimiento presupuestario y de programación o el porcentaje del trabajo realizado. Además, en proyectos de tamaño medio o grande, la cantidad de cuadros Gantt y curvas de costes que se deben generar puede ser abrumadora.

%% AGREGAR FIGURAS %%

***La regla de cincuenta-Cincuenta para medir el rendimiento del trabajo***

Aquí introducimos el enfoque del valor devengado examinando uno de los métodos que los calculistas de costes han desarrollado para medir el rendimiento del trabajo. Se llama la regla del cincuenta-cincuenta.

Su empleo es bastante directo. Cuando se comienza una tarea, suponernos que hemos alcanzado la mitad de su valor, medido el valor por el coste presupuestado. Así, para una de $ 1.000, suponemos que se ha cumplido con $ 500 al momento de iniciarla, y consideramos que se ha alcanzado el valor total cuando se termina. Así, una vez cumplida nuestra tarea hipotética de $ 1.000 —sea en el plazo previsto, antes o con retraso— decirnos que hemos realizado trabajo por $ 1.000.

La utilidad de la regla del cincuenta-cincuenta para medir el cumplimiento del trabajo se puede apreciar en la figura 2. Esta figura presenta el cuadro Gantt para un proyecto muy simple de cuatro tareas. Para facilitar las cuentas, cada tarea tiene un valor presupuestado de $ 100.

%% agregar figura %%

La tarea 1 comienza en el plazo planificado y, cuando comienza, suponemos que hemos cumplido trabajo por $ 50. La tarea 1 finaliza en el plazo fijado y al completarse anotamos que se ha alcanzado el valor total de $ 100 correspondiente.

La tarea 2 comienza de acuerdo con lo planificado, por lo que suponemos que hemos cumplido $ 50 del trabajo. Al momento que debe terminar sigue habiendo trabajo pendiente, por lo que no cerramos la cuenta. Anotaremos que la tarea se ha cumplido con los $ 100 de su valor solo cuando se complete.

La tarea 3 comienza con retraso. No indicamos que se ha cumplido nada del trabajo hasta que este se inicie realmente. La entrega se retrasa con respecto al plazo estipulado. No decimos que ha logrado su valor total de $ 100 hasta que se termina.

Finalmente, vemos que la tarea 4 se comienza con retraso y que al día de hoy hemos cumplido con un trabajo por valor de $ 350 de los $ 400  planificados. La medida de    $ 350 cumplida se llama valor devengado. El hecho de que se han realizado $ 350  de trabajo de los $ 400  planificados sugiere que hemos alcanzado el 87,5% de nuestro objetivo.

Nótese que no hemos dicho nada de lo que nos cuesta cumplir nuestro trabajo. Supongamos que un conjunto de hojas de control de horas trabajadas y facturas nos indica que gastamos $ 700  para lograr $ 350  de trabajo. Así por cada dólar gastado, obtuvimos cincuenta centavos de valor. Si este proyecto tiene un presupuesto total de $10.000  y si seguimos obteniendo cincuenta centavos de valor por cada dólar gastado, el coste final de este proyecto alcanzará los $ 20.000.

Este ejemplo simple demuestra el poder del enfoque de valor devengado. Nos da un método para calcular el porcentaje del trabajo cumplido. También permite medir a qué ritmo "quemamos" nuestros recursos, permitiéndonos así calcular el impacto en el presupuesto de nuestro rendimiento. Los cálculos de valor devengado pueden hacerse en cualquier nivel de la estructura de desglose del trabajo (EDT): podemos examinar el cumplimiento del proyecto desde el plano más general hasta el de las tareas individuales (es decir, el más bajo del EDT). Dicho de otro modo, el enfoque de valor devengado nos permite realizar análisis de control integrado de costes/programación de modo analítico, en contraste con el recurso gráfico analizado antes.

***Otras maneras de calcular el valor devengado***

Hay varias maneras de calcular el valor devengado más allá de la regla de cincuenta-cincuenta. El personal de procesamiento de datos tiende a ser muy conservador. Para ellos, la regla de cincuenta-cincuenta es desaforadamente optimista porque se basa en la premisa de que el trabajo está a medio terminar en el momento que comienza. Cualquiera que haya escrito códigos de software se da cuenta de que un programa a medie terminar no tiene ningún valor. En consecuencia, emplean la regla de cero-cien para hacer sus cálculos. Es decir, cuando se comienza una tarea, se supone que no se ha cumplido nada. Sólo cuando se completa se le da su valor total. En el ejemplo de la figura 2, el valor devengado total al día de hoy es de $ 300, de acuerdo con la regla cero-cien. Esto significa que el proyecto sólo ha alcanzado el 75% de su objetivo.

La manera más popular de determinar el valor devengado es hacer cálculos basados en la experiencia histórica. Ilustraré esto con un ejemplo simplificado de una empresa que arma ordenadores. El proceso de producción tiene cinco pasos. Primero, se instalan chips de memoria auxiliares en el motherboard. La experiencia sugiere que cuando se cumple este pasó, el proceso de armado ha llegado a la marca del 25%. Entonces se instala el motherboard en la armazón (marca del 30%). Después se instala un disco rígido en el lugar correspondiente (marca del 70%). Se conectan todos los cables (la marca del 85%) y luego la armazón se calza en la cubierta correspondiente (marca del lDO%).

Para calcular el valor devengado de cada mes, se hace una tabla de la cantidad de ordenadores en cada fase del proceso de ensamblado y se hace un promedio ponderado estimando el valor total del trabajo realizado durante el mes. Por ejemplo, supongamos que el valor del trabajo de una operación de montaje completa es de $ l00. Si en el curso de la revisión del trabajo se encuentra que se ha instalado la memoria auxiliar en cinco aparatos, entonces el valor del trabajo realizado en estos ordenadores es de 100 x 5 x 0.25 = $ 125.

Se puede calcular el valor devengado sobre la base de la intuición, pero es el método menos popular. En este caso, un jefe de tareas puede adivinar que ha alcanzado el 85% de su trabajo de $ 1.000, e indicar que ha cumplido trabajo por un valor devengado de   $ 850.

***Una nueva mirada a la variación de costes y programación***

La manera tradicional de medir la variación de costes ha sido restar los costes reales a los costes planificados. Una cifra negativa sugiere que se ha gastado más de lo planificado; una cifra positiva indica que se ha gastado menos que lo previsto. Por ejemplo, supongamos que para marzo programamos gastar $ 1.000, pero gastamos en realidad $ 900. Esto daría una variación de costes positiva de $ 100. Como vimos antes, esta variación de costes no puede interpretarse de un modo significativo por sí misma. Se debe examinar en conjunción con la información sobre el cumplimiento de lo programado.

Con el método del valor devengado, tomamos otro camino para calcular la variación de costes. Se computa restando los costes efectivos del valor devengado. Con el ejemplo del parágrafo anterior, si se calcula que el valor devengado es $ 850, entonces la variación de costes será de $ 850—$ 900 = — $ 50. Esto significa que pagamos $ 900 para generar $ 850  de trabajo. Para el trabajo realizado hemos gastado $ 50  de más. Nótese que la variación de costes aquí se evalúa comparándola con el valor del trabajo realizado. En este caso, no es necesario mirar el cuadro Gantt para determinar que hemos gastado de más: los datos lo indican por sí mismos. Las variaciones negativas de costes sugieren exceso de gastos, y las positivas, ahorro.

La variación de programación se define como el valor devengado menos los costes planificados. En nuestro ejemplo, esto es $ 850  — $ 1.000  = — $150. En otros términos, aunque se suponía que teníamos que cumplir con $ 1.000  de trabajo, sólo logramos $ 850, lo que nos deja con un déficit de trabajo valuado en $ 150.

Fíjese que se mide la variación de programación en unidades monetarias, no de tiempo. Al principio, esto parece peculiar porque la gente normalmente piensa en la programación en el contexto del tiempo. Sin embargo, la lógica de este enfoque se revela cuando advertimos que el valor devengado mide el rendimiento del trabajo y que cuando se realiza menos trabajo que el planificado, se producen retrasos.

La viabilidad del uso del valor devengado para medir variaciones de programación se ve con claridad cuando la variación de programación en términos de valor devengado se ilustra a través del cuadro Gantt (figuras 3a, 3b y 3c).

La figura 3a muestra un proyecto de dos tareas que sufre retrasos. La primera tarea (valuada en $ 700) se ha completado, pero la segunda (valuada en $ 300) sólo se realizó a medias. Si bien el esfuerzo planificado es de $ 1.000, el valor devengado es sólo de    $ 850. El retraso por tanto es de $ 850

— $ 1.000  = —$ 150. En general, una cifra de variación negativa en la programación indica retrasos y refleja un cuadro Gantt que muestra ese retraso, así tenga dos tareas, veinte o cien.

La figura 3b muestra un proyecto en el que se ha cumplido el trabajo planificado. Hasta hoy se suponía que tenía que haberse cumplido con $ 1. 000  de trabajo y eso es lo que se ha hecho. La variación en lo programado es de $ 1.000— $ 1.000  = 0. En general, una variación cero indica que el trabajo planificado se ha cumplido.

La figura 3c representa un proyecto en el que se ha acelerado el trabajo, por lo que se ha realizado más que el originalmente planeado. La primera tarea (valuada en $ 700) se terminó adelantada, así que comienza el trabajo en la segunda tarea. Esta (valuada en $300) comienza adelantada. Hasta hoy se suponía que debía haberse realizado trabajo por $ 1.000, mientras que en realidad se realizó trabajo por $1.200.

%% agregar figura %%

La variación en relación a lo programado es de $ 1.200  - 1$.000 = $ 200. En general, una variación de programación positiva indica que se ha realizado más trabajo que el planificado.

El control integrado de costes/programación se da cuando las variaciones de costes y programación se examinan en forma concurrente. Esto se hace en la tabla 11.1, que describe siete posibles situaciones distintas de variación de costes programación. Con el Proyecto A, se han alcanzado las metas, lo que da variaciones cero. En el Proyecto B, el valor del trabajo realizado ($600) es menos de lo planeado ($800). Además el coste efectivo de este trabajo ($800) fue mayor que el valor devengado. Por lo tanto, en el Proyecto B nos encontramos con exceso en los gastos e incumplimiento de plazos. Los otros proyectos se pueden examinar de modo similar.

***Desarrollar un nuevo vocabulario***

Uno de los aspectos confusos del enfoque plenamente desarrollado del valor devengado es que tiene su propia terminología y no se conforma al sentido habitual de las palabras. Cuando enseño el enfoque de valor devengado, encuentro que los alumnos gastan más energía en tratar de dominar el vocabulario que los conceptos.

En el enfoque de valor devengado, al coste planificado se lo llama coste presupuestado de trabajo programado (CPTP). El coste real se llama coste real de trabajo realizado (CRTR). Tanto el CPTP como el CRTR se corresponden exactamente con lo que se entiende tradicionalmente por costes planificados y reales respectivamente. El valor devengado se llama coste presupuestado de trabajo realizado (CPTR).

Con este nuevo vocabulario, definimos la variación de programación corno:

VP= CPTR – CPTP

|   |   |   |   |   |   |
|---|---|---|---|---|---|
|***Tabla 1.         Distintas situaciones de variación de costes y programación***|   |   |   |   |   |
||Coste planificado|Costes reales|Valor devengado|Variación de costes|Variación de programación|
|Proyecto A<br><br>Proyecto B<br><br>Proyecto C<br><br>Proyecto D<br><br>Proyecto E<br><br>Proyecto F<br><br>Proyecto G|800<br><br>800<br><br>800<br><br>800<br><br>800<br><br>800<br><br>800|800<br><br>800<br><br>600<br><br>1000<br><br>600<br><br>1200<br><br>400|800<br><br>600<br><br>1000<br><br>1000<br><br>800<br><br>1000<br><br>600|0<br><br>-200<br><br>200<br><br>0<br><br>200<br><br>-200<br><br>200|0<br><br>-200<br><br>200<br><br>200<br><br>0<br><br>200<br><br>00|

***Definimos la variación de costes como:***

***VC = CPTR—CRTR***

Se computa el porcentaje de un trabajo realizado como:

***% completado = l00 x CPTR/CPTP***

La tasa a la que estamos consumiendo nuestros recursos —también se la puede interpretar como una tasa de eficiencia— se llama el índice de desempeño de costes (IDC) y se calcula como:

***IDC = CPTR/CRTR***

La estimación del coste final del proyecto se llama estimación al completar (EAC) y se computa como:

***EAC = PAC/IDC,***

Donde PAC representa lo presupuestado al completar, que es el valor total presupuestado. El EAC nos permite predecir los costes finales sobre la base de la eficiencia lograda en el rendimiento del trabajo por cada dólar realmente gastado. Si el presupuesto de un proyecto es de $500.00  (es decir, PAC = $500.000) y se generan ochenta centavos de trabajo por cada dólar gastado (es decir, IDC = 0,8), el coste final estimado del proyecto será $500.000 /0,8 o $625.000  (es decir, EAC = $ 625.000).

***La recolección de datos***

En los proyectos muy grandes y complejos, la recolección de datos sobre las tareas realizadas se puede hacer bastante complicada. La manera en que las empresas la tratan es dándoles a gerentes de contabilidad de costes (GCC) la responsabilidad de hacerlo. En los proyectos grandes, un GCC individual puede tener la responsabilidad en tareas de millones de dólares.

Los datos principales en los que se centran los GCC son cifras que les permitan estimar la cantidad de trabajo realizado (es decir, valor devengado). Lo hacen recorriendo la organización y preguntando a los jefes de tareas cuánto de su trabajo han completado. Los GCC saben cuáles son los hitos, así que sus investigaciones van dirigidas en gran medida a conocer si se ha cumplido el programa.

Los GCC también tienen la responsabilidad de tomar los datos brutos y hacer con ellos informes de valor devengado. Son la primera línea de defensa en la identificación de fallas en el cumplimiento del plan. Cada mes descubren estas fallas, y alertan a la dirección.

En proyectos más pequeños, es antieconómico contratar GCC para hacer el seguimiento de los datos. Se puede hacer el seguimiento del rendimiento del trabajo de diversas maneras sin incurrir en mayores costes administrativos. Al emplear algo como la regla cincuenta-cincuenta o de cero-cien, basta con responder a la pregunta: ¿Se ha comenzado tal tarea? ¿Se terminó? El uso inteligente de hitos también puede facilitar la medición del rendimiento del trabajo (por ejemplo "Hemos alcanzado veinte de treinta hitos, cada hito representa cien horas hombre de trabajo. Por tanto, hemos cumplido dos tercios de nuestro objetivo"). Como último recurso, se puede medir el rendimiento del trabajo adivinando (por ejemplo, "La experiencia me indica que hemos cumplido con aproximadamente el 85% del esfuerzo planificado").

***Análisis de tendencia con el enfoque valor devengado***

El análisis de valor devengado puede emplearse para determinar tendencias generales en el rendimiento, Esto se ilustra en la figura A, que muestra las tendencias en los costes reales (CRTR), en el valor devengado (CPTR) y en los costes planificados (CPTP). Si todo marcha exactamente de acuerdo con lo planeado, las curvas que expresan estas tres medidas deben verse como una sola línea. Las desviaciones de la curva de CRTR de la de valor devengado indican variación de costes. Las desviaciones de la curva de CPTP de la de valor devengado indican variación de programación.

La Figura A muestra que en los primeros meses de este proyecto hubo abundantes variaciones de costes y programación. Tanto la CRTR como la CPTP son sustancialmente mayores que la CPTR, lo que indica variaciones negativas. Sin embargo, con el paso del tiempo, el tamaño de estas variaciones se reduce y para el mes 8 virtualmente han desaparecido, indicando que el proyecto está bajo control.

El uso de un cuadro como este puede ofrecer a los gerentes una visión de alto nivel de la situación de un proyecto con solo echar un vistazo. Si el cuadro indica que el proyecto en general funciona bien, no hay necesidad de abrumar a los gerentes con tablas detalladas de datos numéricos. Si el cuadro indica que hay problemas, esto podría sugerir la necesidad de estudiar más detalles.

%% agregar figura %%

***¿Cuándo es apropiado el enfoque de valor devengado?***

El enfoque de valor devengado fue creado originalmente para dar a los contratistas de proyectos gubernamentales y jefes de programas estatales una guía acerca de cómo hacer el seguimiento del trabajo en proyectos grandes y complejos. Debido a que el sistema totalmente desarrollado de valor devengado se rige por instrucciones detalladas que crean una carga administrativa sustancial, se ha supuesto que este en foque sólo es apropiado para proyectos del orden de los $100.000.000 o más. Usarlo en proyectos más pequeños sería como tratar de matar un mosquito con una escopeta.

El enfoque de valor devengado puede dar a los jefes de proyecto elementos de juicio muy valiosos con respecto a los progresos incluso en proyectos pequeños. Si un proyecto tiene información sobre costes planificados y si los datos de costes reales se están informando con precisión y puntualidad, se puede utilizar con provecho el enfoque de valor devengado. Ofrece un sustituto numérico para el uso de cuadros Gantt y curvas de costes acumulativos. Si bien estas herramientas gráficas sirven al objetivo de comunicar visual- mente los avances del proyecto, el enfoque de valor devengado es más poderoso desde el punto de vista analítico.

Con datos bien actualizados, un sistema de valor devengado puede medir con precisión el trabajo realizado, la proporción cumplida de nuestro plan y la tasa a la que consumirnos los recursos de nuestro presupuesto. Incluso puede ofrecer la capacidad de hacer pronósticos en cifras gruesas con el cómputo del EAC. Nótese que estos análisis pueden realizarse en cualquier nivel del EDT.

El uso del enfoque de valor devengado tiene dos limitaciones principales. Una es la disponibilidad de datos precisos y oportunos sobre costes. Desgraciadamente, la mayoría de las organizaciones con las que trabajo no han establecido sistemas para recoger tales datos. Sospecho que estas organizaciones representan, no la excepción, sino la regla. Es difícil imaginar cómo puede una organización pensar en dirigir sus proyectos efectivamente sin tales datos.

Una *segunda limitación* es de formación. Para que funcione de modo apropiado el enfoque de valor devengado, todos los integrantes de la organización que tienen que ver con la función de dirección de proyectos deben entender su funcionamiento. Por ejemplo, deberían poder leer y entender un informe con base en el valor devengado. "Todos" incluye a la máxima dirección empresarial. Si sus integrantes no estudian este enfoque para saber cómo puede aportar mayores elementos de juicio sobre la realización de los proyectos, entonces se pierde gran parte de su utilidad.
