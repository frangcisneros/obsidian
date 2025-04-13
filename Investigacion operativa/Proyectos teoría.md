# 1. Proyectos

Un proyecto es una combinación de actividades interrelacionadas que deben ejecutarse en un cierto orden antes que el trabajo pueda terminarse.

# 2. Tareas o actividades

Una actividad o tarea es un trabajo que requiere recursos y tiempo para su ejecución.

*Interrelación de actividades*: la ejecución de algunas actividades dependen de la terminación de otras.

Todas las tareas tienen una predecesora y una sucesora excepto la primera y la ultima.

# 3. Dirección de proyectos

Dirigir un proyecto es *planificar, programar y controlar* una serie de actividades para conseguir objetivos ya definidos en cuanto a rendimiento, costos y tiempo, utilizando recursos disponibles para su ejecución.

Los recursos son escasos y es importante que el director de proyectos tenga especial cuidado en la asignación de los mismos.

# 4. Planificación de proyectos

Se deben responder ciertas preguntas:

- ¿Qué hay que hacer?
- ¿Cómo hay que hacerlo?
- ¿Quién debe hacerlo?
- ¿Cuando hay que hacerlo?
- ¿Cuanto cuesta?

## 4.1. Pasos en la planificación

1. Definir el problema -> fijamos objetivos y se definen los alcances.
2. Estructura de desglose -> identificar las tareas individuales que componen el proyecto.
3. Calcular *costos, duración y recursos* para cada actividad.
4. Elaborar un *programa maestro* -> identificamos las relaciones de tiempo entre las tareas, se puede usar CPM o PERT.
5. Elaborar un *presupuesto global* del proyecto.

### 4.1.1. Identificación de las tareas individuales

1. Cada tarea debe tener un comiendo y un final claros en el contexto del proyecto.
2. La terminación de cada tarea debe ser necesaria para la conclusión del proyecto.
3. El tamaño de una tarea debe estar en proporción con el control que usted pueda ejercer.

### 4.1.2. Obtención de estimaciones de tiempo para cada tarea

El tiempo total que lleva completar todo el proyecto depende de cuanto tiempo lleva realizar cada tarea individual. Se debe obtener el tiempo requerido para cada tarea, esto se puede hacer:

1. Confiando en experiencias pasadas en proyectos similares.
2. Consultando con las personas a cargo de cada tarea individual.
3. Usando datos anteriores.

# 5. Red de proyecto

Una red de proyecto se utiliza para comprender de una mejor forma las relaciones entre las tareas individuales. Una red consiste en una colección infinita de *nodos* y *flechas*. Una flecha conecta un nodo con otro.

# 6. Administración de proyectos usando tiempos determinísticos (CPM)

Nos interesa responder las siguientes preguntas:

1. ¿Qué tan pronto puede completarse todo el proyecto?
2. ¿Qué tareas son críticas? Las tareas críticas son las que generan un retraso en la conclusión del proyecto.

# 7. Determinación del tiempo de proyecto

Para encontrar este tiempo siempre se arranca desde el principio, determinando, para cada tarea, lo siguiente:

1. El *tiempo de inicio más inmediato* es el tiempo más inmediato en que esa tarea puede iniciarse.
2. El *tiempo de terminación más breve* es el tiempo más breve en el que esa tarea puede concluir.

- Regla 1: para calcular el tiempo de inicio de una tarea particular, debe conocer los tiempos de terminación de cada tarea predecesora inmediata.
- Regla 2: el tiempo de inicio más inmediato de una tarea de la que se conocen los tiempos de terminación de todas sus tareas predecesoras inmediatas es el máximo de esos tiempos de terminación.
- Regla 3: tiempo de terminación más breve = tiempo de inicio más inmediato + tiempo de tarea.
- Regla 4: para calcular el último tiempo de terminación de una tarea particular, debemos conocer los últimos tiempos de inicio de cada tarea sucesora inmediata.
- Regla 5: respecto a una tarea de la que se conocen los últimos tiempos de inicio de todas sus tareas sucesoras inmediatas, el último tiempo de terminación de esa tarea es el mínimo de los últimos tiempos de inicio de todas las tareas sucesoras inmediatas.
- Regla 6: ultimo tiempo de inicio = ultimo tiempo de terminación - tiempo de tarea.

# 8. Identificar las tareas críticas

Crítica significa que un retraso en cualquiera de estas tareas ocasiona un retraso en todo el proyecto, los retrasos ocasionan costos adicionales, ingresos perdidos e inclumplimiento de las obligaciones contractuales.

Debemos calcular lo siguiente:

1. *El último tiempo de terminación* que es lo más tarde que puede concluirse una tarea mientras permita que el proyecto se complete lo más pronto posible.
2. *El último tiempo de inicio* que es lo más tarde que puede iniciarse una tarea, de tal forma que finalice en su último tiempo de terminación.

Cualquier actividad cuyo último tiempo de inicio sea igual que su tiempo de inicio más inmediato calculado en la sección anterior es crítica.

%% MEZCLAR ESTA SECCIÓN CON LAS REGLAS ANTERIORES %%

Habiendo hecho uso de las "reglas" y los calculos pertinentes, podemos identificar las tareas críticas y no críticas, para cada tarea calculamos el *tiempo de retraso* que es la diferencia entre los tiempos de inicio últimos y más inmediatos: tiempo de retraso = ultimo tiempo de inicio - tiempo de inicio más inmediato.

Los tiempos de retraso que ubicaremos en una tabla, representan la cantidad de tiempo según la cual la tarea correspondiente puede retrasarse sin retrasar todo el proyecto, *suponiendo que todas las demás tareas se realizan a tiempo*.

# 9. Administración de proyectos usando tiempos de tarea probabilísticos (PERT)

Cuando un proyceto está formadoo por actividades que en su mayoría son similares a otras ya realizadas un gran número de veces, generalmente se utiliza la programación CPM, pero cuando hay actividades para la cuales no tenemox experiencia en la dificultad sobre la estimación de la duración de las tareas es significativa, en este caso se puede conjeturar basandose en cualquier experiencia

# 10. Ruta critica

La ruta critica siempre es la misma.

# 11. Varianza

La media es el promedio de un valor, la desv. estandar es que tan lejos estamos de la media, la varianza es la dispersión de los datos.
