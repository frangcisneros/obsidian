# 1. Definición

Es la ciencia de la administración (también conocida como investigación de operaciones) que utiliza modelos matemáticos y la computadora para ayudar a tomar decisiones racionales frente a problemas de administración complejos.

# 2. Fases del estudio de un problema de investigación operativa

- Identificación y definición del problema.
	- Descripción clara del objetivo.
	- Identificación de alternativas o estrategias de decisión.
	- Reconocimiento de las restricciones y requisitos.
- Formulación del modelo matemático.
- Solución del modelo.
- Análisis de los resultados (Sensibilidad)
- Implementación de los resultados finales

# 3. Problemas básicos que enfrenta

## 3.1. Modelos deterministicos

Un problema en el que toda la información necesaria para obtener una solución se conoce con certeza.

- Programación lineal.
- Transporte y asignación.
- Programación entera lineal.
- Administración de proyectos.

## 3.2. Modelos estocasticos

Un problema en el que parte de la información no se conoce con certeza, sino mas bien se comporta de una manera probabilistica.

- Decisiones - inteligencia de negocios.
- Modelos de colas.
- Simulación - montecarlo.
- Pronostico.
- Teoria de juegos.

# 4. Metodología de la investigación operativa

![[metodologia de la inv. operativa]]

1. **DEFINICIÓN DEL PROBLEMA:** el primer paso es identificar, comprender y describir, en términos precisos, el problema que la organización enfrenta. En algunos casos el problema está bien definido, y en otras puede NO estarlo y se requiere de bastantes discusiones y consensos entre los distintos miembros del equipo
2. **DESARROLLO DE UN MODELO MATEMÁTICO Y RECOLECCIÓN DE DATOS:** una vez constituido el modelo existen muchas técnicas matemáticas disponibles para obtener la mejor solución. Para establecer el problema se comienza definiendo:
	1. **_variables de decisión /variables / variables controlables_**: cantidad cuyo valor se puede controlar y es necesario determinar para solucionar un problema o decisión.
	2. **_función objetivo_**: el objetivo global de un problema de decisión expresado en forma matemática en términos de los datos y de las variables de decisión. Debidos a las pautas no se pueden elegir valores arbitrarios para las variables por lo que se origina limitaciones, q son restricciones sobre los valores de variables de un modelo impuesto por condiciones externas.
	3. **_datos / parámetros incontrolables_**: información conocida en un problema de decisión que no se puede controlar pero que se puede usar para determinar la solución.
3. **RESOLUCIÓN DEL MODELO MATEMÁTICO:** en este paso se deben obtener valores numéricos para las variables, las técnicas de resolución son las siguientes:
	1. **Método Ópticos:** producen los mejores valores para las variables, satisfaciendo simultáneamente las limitaciones y proporcionan el mejor valor para la función objetivo.
	2. **Métodos Heurísticos:** producen valores que satisfacen todas las limitaciones, pero no necesariamente son óptimos, y proporcionan valores aceptables para la función objetivo.
4. **VALIDACIÓN, INSTRUMENTACIÓN Y CONTROL DE LA SOLUCIÓN:** es decir, revisa la solución cuidadosamente para ver que los valores tienen sentidos y que las restricciones pueden llevarse a cabo. Alguna de la razón para hacer esto son:
	1. El modelo matemático puede no haber captado todas las limitaciones del problema.
	2. Ciertos aspectos del problema pueden haberse pasado por alto.
	3. Los datos pueden haberse estimado o registrado incorrectamente, tal vez al introducirlos a la computadora.
	4. También es importante darse cuenta de que, aun dado el modelo y la solución que pueden ser válidos, tal vez no sea factible llevarlo a cabo porque puede haber implicaciones condutales o políticas que no pueden incluirse en el modelo.

Los resultados y posterior instrumentación deben ser supervisados cuidadosamente para asegurar q la solución trabaja según lo deseado y porque también el problema y los datos pueden cambiar con el tiempo

5. **MODIFICACIÓN DEL MODELO:** si durante el paso de validación se encuentra que la solución no puede llevarse a cabo debe regresarse a la etapa de formulación del problema y hacer cuidadosamente las modificaciones apropiadas, para reflejar con mayor exactitud el problema real. Este proceso se puede reiterar.

# 5. TOMA DE DECISIONES: Usos de los Modelos de Investigación de Operaciones

Dependiendo del impacto temporal:

- **DECISIONES ESTRATÉGICAS:** periodos más largos.
- **DECISIONES TÁCTICAS U OPERACIONALES**: periodos de impacto más cortos.

# 6. Ventajas de los Modelos de Investigación de Operaciones

Estos modelos son un **método de determinación de la mejor manera de lograr un objetivo**, de cómo asignar los recursos escasos con los que disponemos.

Así es que es una forma de **evaluar el impacto** **de un cambio propuesto** o un nuevo sistema sin el costo y tiempo de llevarlo a cabo primero. Siempre es mejor modelar, dado que si hacemos un cambio en el modelo nos afecta únicamente en nuestro ordenador, pero si se aplicara directamente en la planta esto ocasionaría muchos gastos imprevistos, entre otras problemáticas.

Una forma de evaluar la fortaleza de la solución óptima al hacer **_preguntas de sensibilidad_**. Por ej. _¿qué pasa si …?_

A su vez, es un procedimiento para lograr un objetivo que beneficie a la organización global al incluir en el modelo consideraciones correspondientes a muchas partes de la organización.
