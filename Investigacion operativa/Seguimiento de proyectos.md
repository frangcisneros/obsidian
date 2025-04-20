# 1. Análisis del valor ganado

Es un método que permite medir el progreso de un proyecto, pronostica el costo final y la fecha de finalización del mismo. Tiene ciertas características:

- Mide en términos de dinero los desempeños del tiempo y del costo.
- Integra el alcance, el cronograma y el presupuesto del proyecto.
- Todas las actividades dentro del proyecto ganan valor conforme el trabajo se va completando.
- Las desviaciones son analizadas, los impactos son proyectados, y las estimaciones para completar se basan en el desempeño propio del proyecto.

¿Qué se necesita para su uso?

- Definir el alcance del proyecto.
	- Determinación de los entregables del proyecto.
	- Descomposición de los entregables en paquetes de trabajos.
- Definir el plan de ejecución del proyecto.
	- Determinación de actividades y sus secuencias.
	- Estimación de las duraciones y los recursos a emplear.
	- Monitoreo y actualización del cronograma.
- Estimar el presupuesto de ejecución del proyecto.
	- Aproximación de los costos de los recursos necesarios para completar cada actividad programada.
	- Monitoreo y actualización del presupuesto.

*Valor planificado (PV)*: es el costo presupuestado del trabajo planificado para una actividad, elemento del EDT o del total del proyecto en un momento determinado.

*Costo previsto total (BAC)*: es el costo presupuestado del total del proyecto a su finalización.

*Valor ganado (EV)*: es el costo presupuestado del trabajo realmente ejecutado para una actividad, elemento del EDT o del total del proyecto en un momento determinado. El calculo del valor ganado (CPTR), se basa en las mismas reglas con las que se fue desarrollado el valor planificado (CPTP).

*Costo real (AC)*: es el costo del trabajo ejecutado para una actividad, elemento del EDT o del total del proyecto en un momento determinado.

*Variación del cronograma (SV)*: mide el desempeño del proyecto en función del cumplimiento del cronograma.

$$
VP = CPTR - CPTP
$$
- $VP>0$ -> adelanto.
- $VP<0$ -> atraso.
- $VP=0$ -> a tiempo.

*Variación del costo (CV)*: mide el desempeño del costo en función de lo incurrido al cumplir con el cronograma.

$$
VC=CPTR-CRTR
$$

- $VC>0$ -> adelanto.
- $VC<0$ -> atraso.
- $VC=0$ -> a tiempo.

*Rendimiento de costos (CPI/IDC)*: muestra la eficiencia del proyecto en función de los costos.
$$
IDC=CPTR/CRTR
$$
- $IDC=1$ -> rendimiento del costo igual a lo planificado.
- $IDC>1$ -> rendimiento del costo mayor a lo planificado.
- $IDC<1$ -> rendimiento del costo menor a lo planificado.

*Estimación a la conclusión (EAC)*: es el costo total estimado para completar el trabajo planificado a ser ejecutado.

$$
EAC=PAC/IDC
$$

Donde $PAC$ representa lo presupuestado al completar, que es el valor total presupuestado.

En la mayoría de los proyectos, el personal no sabe medir con realismo el rendimiento del trabajo.

Quizás la información de control más importante con la que cuentan los jefes de proyectos son los datos sobre la cantidad de trabajo realizado. Si no saben cuanto trabajo han cumplido, no pueden saber si están gastando de más o de menos, ni si están cumpliendo con la programación y los objetivos. El control efectivo de proyectos requiere que las organizaciones que realizan proyectos generen medidas precisas del rendimiento del trabajo.

Tradicionalmente los datos de rendimiento se recogen haciendo que el personal de proyecto informe sobre el "porcentaje de la tarea cumplida" mes a mes. Por lo general, se deja que el personal interprete lo que significa. La mayoría informa del porcentaje cumplido basándose en la intuición, su fiabilidad es muy baja, debido a que es muy probable que cinco personas que informen sobre el porcentaje de trabajo cumplido den cinco evaluaciones diferentes.

Ocasionalmente, los grupos pueden revisar lo que han gastado del presupuesto y dar ese porcentaje como su estimación del trabajo que se ha cumplido. Desgraciadamente el mundo real de la dirección de proyectos, la correlación entre el dinero gastado y el trabajo realizado es débil, por lo que esto no es una buena medida. Aún más, con este enfoque el personal del proyecto no aporta a la organización nueva información, dado que el departamento de contabilidad ya sabe cuanto del presupuesto se gastó.

Entonces ¿Cómo se mide el rendimiento del trabajo? Esta pregunta es el tema clave, la respuesta se centra en los conceptos de valor devengado y control integrado de costes/programación.

# 2. Un método gráfico para el control integrado de costes/programación

La interpretación de datos de variación de costes y programación debe hacerse con cuidado. Si las cuentas muestran que tenemos una variación positiva del 10% en marzo, no deben sacar apresuradamente la conclusión de que ahorramos dinero. Quizás la variación positiva refleja el hecho que no hemos trabajado demasiado. Si no hicimos el trabajo, puede ser el motivo por el que no gastamos el dinero. Por lo mismo, una variación negativa no significa necesariamente que hemos gastado de más. Puede reflejar el hecho de que trabajamos más de lo planificado en marzo.

El sentido común requiere que para tener una percepción precisa de la situación de un proyecto, debemos analizar las variaciones de costes y programación de manera concurrente. Una ***variación positiva*** en los costes realmente refleja un ahorro si estamos avanzando o cumpliendo con lo programado. Una ***variación negativa*** indica exceso en los gastos si estamos retrasados en la relación a lo programado o incluso si estamos cumpliendo lo planificado.

Una manera efectiva de examinar las variaciones de costes y programación es usar curvas de costes acumulativos (también llamadas curvas de las S) y cuadros Gantt. El uso de estas herramientas de control permite al personal y los directivos evaluar la situación general del proyecto de un vistazo. Esto se ve en la figura 1.a que  muestra que el proyecto esta cumpliendo fundamentalmente su programación y la curva acumulativa de costes muestra que el dinero se esta gastando de acuerdo con el presupuesto. Esto refleja una situación en la que el progreso parece darse según lo planeado.

La figura 1.b muestra que las tareas se están cumpliendo antes de lo previsto. Al mismo tiempo, se está gastando más dinero que lo presupuestado para el período bajo estudio. Esto refleja una situación en la que se invierten recursos extra para mantener o acelerar lo programado.

La figura 1.e muestra la peor situación posible: el proyecto sufre tanto retrasos como excesos en los gastos.

El control integrado de costes/programación presentado por medios gráficos es una herramienta de comunicación efectiva. Como tal, se la puede emplear para informar de la situación del proyecto, tanto a la dirección superior como al personal, de un modo fácil de comprender. Otra ventaja de este recurso es que los paquetes de planificación comúnmente generan buenos cuadros de costes y programación, de modo que realizar los gráficos no es ningún problema.

La principal deficiencia de esta presentación es que resulta poco práctica desde el punto de vista analítico. Los gráficos dan una impresión visual de la situación del proyecto, pero por sí mismos no ofrecen más información: carecen de datos importantes como el ritmo al que se gasta el presupuesto frente a la cantidad de trabajo que se realiza, la contribución de cada tarea al cumplimiento presupuestario y de programación o el porcentaje del trabajo realizado. Además, en proyectos de tamaño medio o grande, la cantidad de cuadros Gantt y curvas de costes que se deben generar puede ser abrumadora.

![[seguimiento de proyectos figura.png]]

# 3. La regla de cincuenta-Cincuenta para medir el rendimiento del trabajo

Aquí introducimos el enfoque del valor devengado examinando uno de los métodos que los calculistas de costes han desarrollado para medir el rendimiento del trabajo. Se llama la regla del cincuenta-cincuenta.

Su empleo es bastante directo. Cuando se comienza una tarea, suponernos que hemos alcanzado la mitad de su valor, medido el valor por el coste presupuestado. Así, para una de $ 1.000, suponemos que se ha cumplido con $ 500 al momento de iniciarla, y consideramos que se ha alcanzado el valor total cuando se termina. Así, una vez cumplida nuestra tarea hipotética de $ 1.000 —sea en el plazo previsto, antes o con retraso— decirnos que hemos realizado trabajo por $ 1.000.

La utilidad de la regla del cincuenta-cincuenta para medir el cumplimiento del trabajo se puede apreciar en la figura 2. Esta figura presenta el cuadro Gantt para un proyecto muy simple de cuatro tareas. Para facilitar las cuentas, cada tarea tiene un valor presupuestado de $ 100.

![[seguimiento de proyectos figura 2.png]]

La tarea 1 comienza en el plazo planificado y, cuando comienza, suponemos que hemos cumplido trabajo por $ 50. La tarea 1 finaliza en el plazo fijado y al completarse anotamos que se ha alcanzado el valor total de $ 100 correspondiente.

La tarea 2 comienza de acuerdo con lo planificado, por lo que suponemos que hemos cumplido $ 50 del trabajo. Al momento que debe terminar sigue habiendo trabajo pendiente, por lo que no cerramos la cuenta. Anotaremos que la tarea se ha cumplido con los $ 100 de su valor solo cuando se complete.

La tarea 3 comienza con retraso. No indicamos que se ha cumplido nada del trabajo hasta que este se inicie realmente. La entrega se retrasa con respecto al plazo estipulado. No decimos que ha logrado su valor total de $ 100 hasta que se termina.

Finalmente, vemos que la tarea 4 se comienza con retraso y que al día de hoy hemos cumplido con un trabajo por valor de $ 350 de los $ 400  planificados. La medida de    $ 350 cumplida se llama valor devengado. El hecho de que se han realizado $ 350  de trabajo de los $ 400  planificados sugiere que hemos alcanzado el 87,5% de nuestro objetivo.

Nótese que no hemos dicho nada de lo que nos cuesta cumplir nuestro trabajo. Supongamos que un conjunto de hojas de control de horas trabajadas y facturas nos indica que gastamos $ 700  para lograr $ 350  de trabajo. Así por cada dólar gastado, obtuvimos cincuenta centavos de valor. Si este proyecto tiene un presupuesto total de $10.000  y si seguimos obteniendo cincuenta centavos de valor por cada dólar gastado, el coste final de este proyecto alcanzará los $ 20.000.

Este ejemplo simple demuestra el poder del enfoque de valor devengado. Nos da un método para calcular el porcentaje del trabajo cumplido. También permite medir a qué ritmo "quemamos" nuestros recursos, permitiéndonos así calcular el impacto en el presupuesto de nuestro rendimiento. Los cálculos de valor devengado pueden hacerse en cualquier nivel de la estructura de desglose del trabajo (EDT): podemos examinar el cumplimiento del proyecto desde el plano más general hasta el de las tareas individuales (es decir, el más bajo del EDT). Dicho de otro modo, el enfoque de valor devengado nos permite realizar análisis de control integrado de costes/programación de modo analítico, en contraste con el recurso gráfico analizado antes.

# 4. Otras maneras de calcular el valor devengado

Hay varias maneras de calcular el valor devengado más allá de la regla de cincuenta-cincuenta. El personal de procesamiento de datos tiende a ser muy conservador. Para ellos, la regla de cincuenta-cincuenta es desaforadamente optimista porque se basa en la premisa de que el trabajo está a medio terminar en el momento que comienza. Cualquiera que haya escrito códigos de software se da cuenta de que un programa a medie terminar no tiene ningún valor. En consecuencia, emplean la regla de cero-cien para hacer sus cálculos. Es decir, cuando se comienza una tarea, se supone que no se ha cumplido nada. Sólo cuando se completa se le da su valor total. En el ejemplo de la figura 2, el valor devengado total al día de hoy es de $ 300, de acuerdo con la regla cero-cien. Esto significa que el proyecto sólo ha alcanzado el 75% de su objetivo.

La manera más popular de determinar el valor devengado es hacer cálculos basados en la experiencia histórica. Ilustraré esto con un ejemplo simplificado de una empresa que arma ordenadores. El proceso de producción tiene cinco pasos. Primero, se instalan chips de memoria auxiliares en el motherboard. La experiencia sugiere que cuando se cumple este pasó, el proceso de armado ha llegado a la marca del 25%. Entonces se instala el motherboard en la armazón (marca del 30%). Después se instala un disco rígido en el lugar correspondiente (marca del 70%). Se conectan todos los cables (la marca del 85%) y luego la armazón se calza en la cubierta correspondiente (marca del lDO%).

Para calcular el valor devengado de cada mes, se hace una tabla de la cantidad de ordenadores en cada fase del proceso de ensamblado y se hace un promedio ponderado estimando el valor total del trabajo realizado durante el mes. Por ejemplo, supongamos que el valor del trabajo de una operación de montaje completa es de $ l00. Si en el curso de la revisión del trabajo se encuentra que se ha instalado la memoria auxiliar en cinco aparatos, entonces el valor del trabajo realizado en estos ordenadores es de 100 x 5 x 0.25 = $ 125.

Se puede calcular el valor devengado sobre la base de la intuición, pero es el método menos popular. En este caso, un jefe de tareas puede adivinar que ha alcanzado el 85% de su trabajo de $ 1.000, e indicar que ha cumplido trabajo por un valor devengado de   $ 850.

# 5. Una nueva mirada a la variación de costes y programación

La manera tradicional de medir la variación de costes ha sido restar los costes reales a los costes planificados. Una cifra negativa sugiere que se ha gastado más de lo planificado; una cifra positiva indica que se ha gastado menos que lo previsto. Por ejemplo, supongamos que para marzo programamos gastar $ 1.000, pero gastamos en realidad $ 900. Esto daría una variación de costes positiva de $ 100. Como vimos antes, esta variación de costes no puede interpretarse de un modo significativo por sí misma. Se debe examinar en conjunción con la información sobre el cumplimiento de lo programado.

Con el método del valor devengado, tomamos otro camino para calcular la variación de costes. Se computa restando los costes efectivos del valor devengado. Con el ejemplo del parágrafo anterior, si se calcula que el valor devengado es $ 850, entonces la variación de costes será de $ 850—$ 900 = — $ 50. Esto significa que pagamos $ 900 para generar $ 850  de trabajo. Para el trabajo realizado hemos gastado $ 50  de más. Nótese que la variación de costes aquí se evalúa comparándola con el valor del trabajo realizado. En este caso, no es necesario mirar el cuadro Gantt para determinar que hemos gastado de más: los datos lo indican por sí mismos. Las variaciones negativas de costes sugieren exceso de gastos, y las positivas, ahorro.

La variación de programación se define como el valor devengado menos los costes planificados. En nuestro ejemplo, esto es $ 850  — $ 1.000  = — $150. En otros términos, aunque se suponía que teníamos que cumplir con $ 1.000  de trabajo, sólo logramos $ 850, lo que nos deja con un déficit de trabajo valuado en $ 150.

Fíjese que se mide la variación de programación en unidades monetarias, no de tiempo. Al principio, esto parece peculiar porque la gente normalmente piensa en la programación en el contexto del tiempo. Sin embargo, la lógica de este enfoque se revela cuando advertimos que el valor devengado mide el rendimiento del trabajo y que cuando se realiza menos trabajo que el planificado, se producen retrasos.

La viabilidad del uso del valor devengado para medir variaciones de programación se ve con claridad cuando la variación de programación en términos de valor devengado se ilustra a través del cuadro Gantt (figuras 3a, 3b y 3c).

La figura 3a muestra un proyecto de dos tareas que sufre retrasos. La primera tarea (valuada en $ 700) se ha completado, pero la segunda (valuada en $ 300) sólo se realizó a medias. Si bien el esfuerzo planificado es de $ 1.000, el valor devengado es sólo de    $ 850. El retraso por tanto es de $ 850

— $ 1.000  = —$ 150. En general, una cifra de variación negativa en la programación indica retrasos y refleja un cuadro Gantt que muestra ese retraso, así tenga dos tareas, veinte o cien.

La figura 3b muestra un proyecto en el que se ha cumplido el trabajo planificado. Hasta hoy se suponía que tenía que haberse cumplido con $ 1. 000  de trabajo y eso es lo que se ha hecho. La variación en lo programado es de $ 1.000— $ 1.000  = 0. En general, una variación cero indica que el trabajo planificado se ha cumplido.

La figura 3c representa un proyecto en el que se ha acelerado el trabajo, por lo que se ha realizado más que el originalmente planeado. La primera tarea (valuada en $ 700) se terminó adelantada, así que comienza el trabajo en la segunda tarea. Esta (valuada en $300) comienza adelantada. Hasta hoy se suponía que debía haberse realizado trabajo por $ 1.000, mientras que en realidad se realizó trabajo por $1.200.

![[seguimiento de proyectos figura 3.png]]

La variación en relación a lo programado es de $ 1.200  - 1$.000 = $ 200. En general, una variación de programación positiva indica que se ha realizado más trabajo que el planificado.

El control integrado de costes/programación se da cuando las variaciones de costes y programación se examinan en forma concurrente. Esto se hace en la tabla 11.1, que describe siete posibles situaciones distintas de variación de costes programación. Con el Proyecto A, se han alcanzado las metas, lo que da variaciones cero. En el Proyecto B, el valor del trabajo realizado ($600) es menos de lo planeado ($800). Además el coste efectivo de este trabajo ($800) fue mayor que el valor devengado. Por lo tanto, en el Proyecto B nos encontramos con exceso en los gastos e incumplimiento de plazos. Los otros proyectos se pueden examinar de modo similar.

# 6. Desarrollar un nuevo vocabulario

Uno de los aspectos confusos del enfoque plenamente desarrollado del valor devengado es que tiene su propia terminología y no se conforma al sentido habitual de las palabras. Cuando enseño el enfoque de valor devengado, encuentro que los alumnos gastan más energía en tratar de dominar el vocabulario que los conceptos.

En el enfoque de valor devengado, al coste planificado se lo llama coste presupuestado de trabajo programado (CPTP). El coste real se llama coste real de trabajo realizado (CRTR). Tanto el CPTP como el CRTR se corresponden exactamente con lo que se entiende tradicionalmente por costes planificados y reales respectivamente. El valor devengado se llama coste presupuestado de trabajo realizado (CPTR).

Con este nuevo vocabulario, definimos la variación de programación corno:

$$
VP= CPTR – CPTP
$$

Distintas situaciones de variación de costes y programación:

|            | Coste planificado | Costes reales | Valor devengado | Variación de costes | Variación de programación |
| ---------- | ----------------- | ------------- | --------------- | ------------------- | ------------------------- |
| Proyecto A | 800               | 800           | 800             | 0                   | 0                         |
| Proyecto B | 800               | 600           | 600             | -200                | -200                      |
| Proyecto C | 800               | 1000          | 1000            | 200                 | 200                       |
| Proyecto D | 800               | 1000          | 1000            | 0                   | 200                       |
| Proyecto E | 800               | 8000          | 800             | 200                 | 0                         |
| Proyecto F | 800               | 1000          | 1000            | -200                | 200                       |
| Proyecto G | 800               | 600           | 600             | 200                 | 0                         |

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

![[seguimiento de proyectos figura 4.png]]

***¿Cuándo es apropiado el enfoque de valor devengado?***

El enfoque de valor devengado fue creado originalmente para dar a los contratistas de proyectos gubernamentales y jefes de programas estatales una guía acerca de cómo hacer el seguimiento del trabajo en proyectos grandes y complejos. Debido a que el sistema totalmente desarrollado de valor devengado se rige por instrucciones detalladas que crean una carga administrativa sustancial, se ha supuesto que este en foque sólo es apropiado para proyectos del orden de los $100.000.000 o más. Usarlo en proyectos más pequeños sería como tratar de matar un mosquito con una escopeta.

El enfoque de valor devengado puede dar a los jefes de proyecto elementos de juicio muy valiosos con respecto a los progresos incluso en proyectos pequeños. Si un proyecto tiene información sobre costes planificados y si los datos de costes reales se están informando con precisión y puntualidad, se puede utilizar con provecho el enfoque de valor devengado. Ofrece un sustituto numérico para el uso de cuadros Gantt y curvas de costes acumulativos. Si bien estas herramientas gráficas sirven al objetivo de comunicar visual- mente los avances del proyecto, el enfoque de valor devengado es más poderoso desde el punto de vista analítico.

Con datos bien actualizados, un sistema de valor devengado puede medir con precisión el trabajo realizado, la proporción cumplida de nuestro plan y la tasa a la que consumirnos los recursos de nuestro presupuesto. Incluso puede ofrecer la capacidad de hacer pronósticos en cifras gruesas con el cómputo del EAC. Nótese que estos análisis pueden realizarse en cualquier nivel del EDT.

El uso del enfoque de valor devengado tiene dos limitaciones principales. Una es la disponibilidad de datos precisos y oportunos sobre costes. Desgraciadamente, la mayoría de las organizaciones con las que trabajo no han establecido sistemas para recoger tales datos. Sospecho que estas organizaciones representan, no la excepción, sino la regla. Es difícil imaginar cómo puede una organización pensar en dirigir sus proyectos efectivamente sin tales datos.

Una *segunda limitación* es de formación. Para que funcione de modo apropiado el enfoque de valor devengado, todos los integrantes de la organización que tienen que ver con la función de dirección de proyectos deben entender su funcionamiento. Por ejemplo, deberían poder leer y entender un informe con base en el valor devengado. "Todos" incluye a la máxima dirección empresarial. Si sus integrantes no estudian este enfoque para saber cómo puede aportar mayores elementos de juicio sobre la realización de los proyectos, entonces se pierde gran parte de su utilidad.
