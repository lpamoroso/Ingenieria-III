# Práctica 3 - Gestión de Proyectos y Costos

## Parte I: Conceptos generales

1. Explique con sus palabras en qué consiste un proyecto.

    Un proyecto es una secuencia de actividades única, complejas y conectadas que tienen un objetivo o propósito y que deben ser completadas en un tiempo específico, dentro del presupuesto y de acuerdo a las especificaciones. Es cualquier actividad que dé como resultado un producto o un entregable. Es una organización temporal creada con el propósito de entregar uno o más producto empresariales dentro de las restricciones de costo, calidad y recursos.

2. Indique cuál es el trabajo de un líder de proyecto. Nombre al menos cinco tareas del mismo.

    Es el responsable de detectar las necesidades de los usuarios y gestionar los recursos económicos, materiales y humanos, para obtener los resultados esperados en los plazos previstos y con la calidad necesaria. Es el que coordina el trabjo de técnicos y especialistas y la cominicación con los interesados. Son jugadores de equipo que motivan al personal usando sus conocimientos y habilidades. Son aquellos que realizan una planificación detallada para administrar la entrega de productos y servicios. Sus tareas suelen ser:
    * Desarrollar el plan del proyecto.
    * Identificar requerimientos y el alcance del proyecto.
    * Comunicar y reportar a interesados.
    * Administrar recursos humanos y materiales.
    * Controlar tiempos.

3. Enumere y explique cuáles son los parámetros o restricciones que afectan a los proyectos.

    Existen cinco restricciones que operan sobre un proyecto:
    * Alcance: es decir, los límites del proyecto. Dice lo que se va a hacer, e, implícitamente, también lo que no se va a hacer. Es crítico que el alcance sea correcto y también es posible que cambie, por lo que, cuando ello ocurra, el líder del proyecto debe detectar tal cambio, acomodar el plan conforme a ello.
    * Calidad: en particular, dos a tener en cuenta: la del producto y la del proceso.
    * Recursos: esto es, los activos, tales como personas, equipos, facilidades físicas, o artefactos necesarios para la realización del proyecto. Su disponibilidad es limitada, puede planificarse su uso o puede ser contratado a terceros. También pueden ser fijos o variables y son centrales para la planificación de las actividades del proyecto y la finalización ordenada del mismo. En particular, las personas son el recurso más importante.
    * Costo: es el presupuesto disponible para completar el proyecto.
    * Tiempo: es la ventana de tiempo en la cual el proyecto debe terminarse.

4. ¿En qué consiste el "Triángulo de alcance"? Explique el concepto.

    Es un triángulo que muestra la relación entre las tres variables de las que depende la calidad: el alcance, los costos y el tiempo.
    ![triangulo](imgs/triangulo.png)

    Ejemplos de su funcionamiento:
    * Si se reducen las personas que se dedican al proyecto, dada una calidad determinada, será necesario reducir el alcance del proyecto y/o aumentar su fecha de entrega.
    * Si se reduce la fecha en la cual se debe entregar el proyecto, dada una calidad determinada, será necesario reducir el alcance del proyecto y/o aumentar los recursos que se dedicarán a él.

5. Identifique las etapas que forman parte de un proyecto y describa en pocas palabras en qué consiste cada una.

    * Análisis de requisitos: es decir, extraer los requisitos de un producto de software.
    * Diseño y arquitectura: esto es, determinar cómo funcionará el sistema de forma general sin entrar en detalles.
    * Programación: en otras palabras, reducir el diseño a un código específico.
    * Pruebas: en otros términos, comprobar que el software realice correctamente las tareas indicadas en la especificación.
    * Documentación: dicho de otra forma, lo concerniente a la documentación(valga la redundancia) del propio desarrollo del software y de la gestión del proyecto.
    * Mantenimiento: dicho de otro modo, el soporte y las mejoras al sistema para enfrentar errores descubiertos y nuevos requisitos, respectivamente.

6. Explique cómo se pueden clasificar los proyectos de software.

    Pueden clasificarse según duración, riesgo, complejidad, valor comercial y costo. De ahí, se desprende la siguiente tabla:

    Tipo | Duración | Riesgo | Complejidad | Tecnología | Problemas
    :---:|:--------:|:------:|:-----------:|:----------:|:---------:
    A | > 18 meses | Alto | Alta | De avanzada | Seguros 
    B | 9-18 meses | Medio | Media | Actual | Muy probables
    C | 3-9 meses | Bajo | Baja | Mejor del tipo | Algunos
    D | < 3 meses | Muy bajo | Muy baja | Práctica | Ninguno

7. Enumere y ejemplifique causas de fracaso de proyectos.

    * No prestar la suficiente atención a...
        + casos de negocio: es decir, puede que al analista se le haya escapado el detalle de que el sistema que se estaba construyendo tuviera soporte para tarjeta de crédito. O puede que el analista no se lo hubiera preguntado pero el cliente "lo daba por sentado".
        + calidad: por ejemplo, si el sistema es funcional pero la interfaz es fea o poco intuitiva.
        + definición y medida de los entregables: en otras palabras, entregables demorados o que, simplemente, no funcionen del todo bien.

    * Inadecuada...
        + definición de responsabilidades: por ejemplo, si nadie o algunos no tienen del todo claro los alcances de su rol(no saben o no tienen claro del todo de qué son responsables).
        + planificación y coordinación de recursos: por ejemplo, cuando se asigna más personal del requerido a una tarea y se descuidan otras.

    * Pobre estimación de...
        + duración: por ejemplo, que se calculen mal los tiempos a una funcionalidad y que se atrace todo.
        + costos: por ejemplo, que se despilfarre con una funcionalidad y que se ahorre de forma extrema en funcionalidades en las que debería dedicarse mayor presupuesto, como consecuencia de tal despilfarro.

    * Falta de...
        + comunicación con los interesados: por ejemplo, que un desarrollador no comunique sus problemas con la gerencia y esto impacte notoriamente en la calidad del producto.
        + compromiso de los interesados: por ejemplo, que uno de los desarrolladores no termine con lo que se comprometió a tiempo.
        + control de calidad: por ejemplo, cuando se hace énfasis en que se vea bien o sea intuitivo, pero las funcionalidades no terminan de funcionar(valga la redundancia) bien.
        + control de avance: por ejemplo, cuando se le dedica mucho tiempo a una funcionalidad y, como consecuencia de eso, se le dedica menos tiempo a otra. Esto puede desembocar en funcionalidades incompletas o inacabadas e impactar fuertemente en la calidad del producto, además de que también impacta en los costos.
8. Revise y compare las definiciones de administración de proyectos vistas en clase y otras disponibles en la Web(debe citar las definiciones utilizadas). En base a esas definiciones, se pide:

    Definición provista por la cátedra:

    > Es la planificación, la delegación, el seguimiento y el control de todos los aspectos del proyecto y la motivación de los participantes para alcanzar los objetivos del proyecto dentro de los objetivos de rendimiento esperados en términos de tiempo, costo, calidad, alcance, beneficios y riesgos.

    Definición provista por wikipedia.org:

    > Metodología utilizada a nivel mundial para alcanzar objetivos en un tiempo determinado llevando una gestión equilibrada y separando las urgencias de las tareas que realmente son importantes para el cliente

    Definición provista por monografias.com:

    > Es la disciplina de gestionar proyectos exitosamente, la cual puede y debe aplicarse durante el ciclo de vida de cualquier proyecto. Es la forma de planear, organizar, dirigir y controlar una serie de actividades realizadas por un grupo de personas que tienen un objetivo específico.

    1. Identificar aspectos comunes.

        En todas las definiciones se habla de objetivos, de gestión, de planificación. Se habla de alcanzar objetivos controlando ciertos aspectos.

    2. Identificar aspectos mencionados que considere importantes y justificar.

        * Es la planificación, la delegación, el seguimiento y el control...: no solo es importante planificar, sino controlar que lo planificado se lleve exitosamente a cabo delegando cada tarea sobre quien debe delegarse.
        * en términos de tiempo, costo, calidad, alcance, beneficios y riesgos: no solo es importante alcanzar los objetivos, sino que la idea es alcanzarlos a tiempo, construyendo un producto de calidad, que no se esté descuidando ningún aspecto importante de las funcionalidades, que no se esté gastando plata en problemas que pudieran haberse evitado, que se hayan prevenido todos los riesgos posibles y que se hayan maximizado los beneficios.

    3. Enumerar ventajas de una buena administración de proyectos.

        La principal ventaja con respecto a una mala administración es que si la administración es muy buena, es muy probable que las metas del proyecto se alcancen. La administración de proyectos garantiza que se alcancen los objetivos cumpliendo los estándares en términos de tiempo, calidad, beneficios, riesgos, costo y alcance.

9. Cite los desafíos de la administración de proyectos. Indique qué puede hacerse para cumplirlos.

    * Alto nivel de innovación: se puede resolver aplicando mayores cursos de capacitación o contratando más personal capacitado.
    * Complejidad: dividiendo las tareas en módulos simples fáciles de completar.
    * Requerimientos ambiguos: es necesario disponer de analistas altamente capacitados que sepan detectar ese problema.
    * Falta de competencias necesarias.//preguntar
    * Herramientas y técnicas inmaduras: utilizando estándares y técnicas que se comprobaron funcionan bien y siguiéndolas a raja tabla.
    * Cumplir con regulaciones de gobierno: es necesario disponer de alguien especializado en materia gubernamental que alerte desde el principio si el proyecto puede violar una regulación gubernamental o que sepa como solucionar ese percance cuando surja.
    * Cumplir con plazos: motivar al personal para mantener el compromiso.
    * Tratar con proveedores.//preguntar
    * Reportar a altas autoridades: es necesario que se aliente a los empleados a tales prácticas y que cuando surja una queja o un reporte se lleve a cabo una investigación para probar lo que el empleado dice.
    * Retener personal calificado: se podría establecerles metas y que cada meta valga una cantidad determinada de dinero. Proporcionar beneficios.
    * Administrar personal con diferentes niveles de productividad: debe haber personal especializado en esa tarea que se encargue de repartir equitativamente las tareas.
    * Administrar equipos distribuidos en diferentes ubicaciones.//preguntar.
    * Administrar entornos multiculturales y multilingua: es necesario que se disponga de personal poliglota que entienda las necesidades del cliente o empleados y que se especialice en la cultura de ellos para mantener un buen trato.

10. Mencione y explique con sus palabras cómo es el ciclo de vida de un proyecto.

    1. Definir el proyecto: esto es, definir el alcance de éste, los costos, el tiempo que va a llevar.
    2. Desarrollar un plan detallado: es decir, detallar qué se va a hacer y cómo se va a hacer.
    3. Ejecución del proyecto: en otras palabras, poner en en marcha lo ya planificado.
    4. Monitorear/Controlar: en otros términos, monitorear que el plan se lleve a cabo, corregir problemas que afecten a la ejecución de éste.
    5. Terminación/Cierre: ya sea porque se han alcanzado los objetivos o no, en algún momento debe concluir el plan.

11. Explique qué es un programa. Mencione diferencias entre programas y proyectos.

    Un programa es un grupo de proyectos relacionados que se gestionan de manera coordinada para obtener beneficios. Integra los proyectos de modo que se pueda alcanzar un resultado mayor que la suma de sus partes.  
    Los proyectos y los programas tienen varias diferencias, la principal, que un programa es un conjunto de proyectos. Además, el proyecto tienen un alcance limitado a un producto en concreto; los programas tienen un espectro más amplio que puede cambiar dependiendo la expectativa de beneficios. Otra duferencia es acerca de los cambios: los proyectos intentan mantenerlos al mínimo y los programas es algo que deben esperar e incluso aceptar. En los proyectos, los líderes se centran en la entrega de las tareas y a cumplir los criterios de éxito; en los programas, éstos se centran más en la resolución de comflictos y gestión de relaciones.

12. ¿Cuál es la relación entre la administración de programas y la administración de proyectos?

    Un programa vincula proyectos de varias maneras:
    * Interdependencias de tareas entre proyectos.
    * Limitaciones de recursos a través de múltiples proyectos.
    * Actividades de mitigación del riesgo.
    * Escalamientos de problemas, cambios de alcance, calidad, gestión de comunicaciones, riesgos, etc.

## Parte II: Actividades y tareas de proyectos

13. Explique qué es Work Breakdown Structure(WBS) y cómo se construye.

    Es una descripción jerárquica del trabajo que se debe realizar para completar el proyecto. Es algo así como una descomposición funcional: el trabajo se divide en actividades y las actividades en tareas. Hay dos formas de construirlo: usando top-down o bottom-up. Si se utiliza top-down, puede realizarse usando el equipo completo o en sub-equipos. Si se utiliza el equipo completo, todos los miembros del equipo participan en la descomposición y se va descomponiendo hasta que los participantes estén satisfechos de que el trabajo ha sido suficientemente definido. Sus ventajas es que, debido al suficiente nivel de detalle, las estimaciones de costo, tiempo y recursos son más exactas. Además, brinda la oportunidad de que todos presten atención al WBS y se discuta en el momento. Si, en cambio, se opta por sub-equipos entonces el equipo completo acuerda la partición de primer nivel y se crean tantos sub-equipos como actividades hayan en tal nivel. Luego, a cada sub-equipo se le asigna la actividad para la cual tenga más experiencia y éste particiona tal actividad. Si así lo requiera, un sub-equipo puede solicitar ayuda externa. La ventaja de este enfoque es que lleva menos tiempo que el anterior.

14. Mencione los distintos usos del WBS en la administración de proyectos.

    Sirve para:
    * Diseñar y planificar el trabajo.
    * Diseñar la arquitectura.
    * Planificar.
    * Informar el estado del proyecto.

15. Indique cuáles son las características que deben tener las actividades para considerarse completas. Explique.

    Deben considerarse 6 características:
    1. Estado medible: es decir, puede medirse el estado en que se encuentra.
    2. Acotada: esto es, una fecha de inicio y otra de fin.
    3. Producir un entregable: en otras palabras, debe producir algún signo visible de que se completó, puede ser un documento, un producto, la autorización para continuar con la próxima tarea, etc.
    4. Tiempo y costo estimable: en otros términos, que el tiempo y el costo sean fácilmente medibles. Si todas las tareas son fácilmente estimables, entonces las mediciones de tiempo y el costo serán más exactas.
    5. Duración aceptable: dicho de otra manera, que la duración de la actividad sea admisible: que no se le asigne un mes(hay excepciones), pero tampoco 3 días.
    6. Independiente: dicho de otro modo, que una vez iniciada no dependa de otra actividad. El esfuerzo dedicado a una actividad debe ser contínuo.

16. Explique qué es la duración de una actividad. Indique cuál es la diferencia con el esfuerzo de trabajo.

    La duración es el tiempo transcurrido en días laborables para finalizar el proyecto(feriados, fines de semana y días no laborables no cuentan). El esfuerzo de trabajo es la labor requerida para completar una actividad. La labor puede realizarse en horas consecutivas o no. Ejemplo: una tarea pudo haber sido completado en 10 días pero el esfuerzo de trabajo fue solo de 20 horas.

17. ¿Cuáles son las causas de variación en la duración de una actividad?

    Existen varias:
    * Cantidad de recursos planificados para trabajar en ella.
    * Variación en los perfiles.
    * Eventos inesperados.
    * Eficiencia del tiempo de trabajo.
    * Errores e interpretaciones erróneas.
    * Errores y malentendidos.

18. Mencione las distintas técnicas para estimar esfuerzo.

    Existen varias:
    * Similitud con otras actividades.
    * Datos históricos.
    * Juicio experto.
    * Técnica Delphi.
    * Técnica de tres puntos.
    * Técnica Delphi de banda ancha.

## Parte III: Costos

19. Explique a qué se hace referencia con el término "Estimación de costos".

    Estimación de costos implica realizar predicciones de cuánto tiempo, esfuerzo y perfiles de RRHH son requeridos para construir un sistema de software. No debe confundirse estimación de costos con estimación de esfuerzo.

20. ¿Cuáles son las técnicas de estimación y para qué se utilizan?

    * Brainstorming: es una técnica para generar muchas ideas en un grupo y requiere la participación espontánea de todos. La técnica permite obtener nuevas ideas y soluciones creativas e innovadoras. El clima de participación y motivación asegura mayor calidad en las decisiones tomadas por el grupo, más compromkiso por la actividad y un sentimiento de responsabilidad compartido por todos.
    * Opinión experta: utiliza la experiencia de un personal de desarrollo senior. El desarrollador describe los parámetros del proyecto y el experto hace predicciones basadas en experiencias previas. Se identifican similitudes y diferencias.
    * Descomposición: el análisis se focaliza en el producto o en las tareas requeridas para construirlo. La idea es descomponer el producto en componentes y las actividades en tareas. Se basan en casos promedios o experiencias pasadas.
    * Modelos: son técnicas que identifican contribuyentes claves al esfuerzo, generando fórmulas matemáticas que relacionan estos items al esfuerzo. Hay dos enfoques: bottom-up y top-down.

21. El modelo COCOMO original es una colección de tres modelos:
    1. Básico.
    2. Intermedio.
    3. Avanzado o detallado.

    Explique las diferencias entre estos modelos.

    * Básico: aplicable cuando se conoce muy poco del proyecto.
    * Intermedio: aplicable luego de la especificación de requerimientos.
    * Avanzado: aplicable cuando se termina el diseño.

22. Los modelos calculan el esfuerzo requerido E a través de una fórmula de la forma: E = a x Sᵇ x F, y la duración estimada a través de la fórmula: D = c x Eᵈ
    1. ¿Qué valor toma F para el modelo básico?

        1.

    2. Describir brevemente en función de qué tipos de variables se calcula el factor de ajuste F en los otros dos modelos.

        Los factores de ajuste son quince agrupados en cuatro categorías:
        * Atributos del producto
            + RELY(reliability): indica las posibles consecuencias para el usuario en el caso que todavía existan defectos en el producto(qué tan confiable-reliable- es el producto).
            + DATA: tamaño de la base de datos a desarrollar en relación con el tamaño del programa.
            + CPLX(complexity): complejidad de los módulos y el producto en general.
        * Atributos del hardware
            + TIME: limitaciones en el porcentaje del uso de la CPU.
            + STOR: limitaciones en el uso de la memoria.
            + VIRT: volatilidad de la máquina virtual(hardware + software) durante el desarrollo de software.
            + TURN(computer turnaround): cuantifica el tiempo de respuesta de la computadora desde el punto de vista del programador. Cuando mayor sea el tiempo de respuesta, más alto será el esfuerzo humano.
        * Atributos del personal
            + ACAP(analyst capability): capacidad de los analistas en términos de habilidad de análisis, eficiencia, y capacidad para cooperar.
            + AEXP(applications experience): experiencia del personal en aplicaciones similares.
            + PCAP(programmer capability): capacidad de los programadores en términos de habilidad de programción, eficiencia y capacidad para cooperar.
            + VEXP: experiencia de los programadores en la máquina virtual.
            + LEXP: experiencia de los programadores en el lenguaje de programación a utilizar.
        * Atributos del proyecto
            + MODP: uso de prácticas modernas de programación(programación estructura, desarrollo top-dpwn, etc).
            + TOOL: uso de herramientas de desarrollo de software.
            + SCED(required development schedule): indica el esfuerzo necesario para cumplir con la planificación.

    3. Indicar cómo varían los valores de a y b, y c y d en ambas fórmulas de acuerdo al modo utilizado.

    Tipo de sistema | a | b | c | d
    :--------------:|:-----:|:-----:|:-----:|:-----:
    Orgánico | 2.40 | 1.05 | 2.50 | 0.38
    Embebido | 3.00 | 1.12 | 2.50 | 0.35
    Semi-embebido | 3.60 | 1.20 | 2.50 | 0.32

    4. Describir las características generales de sistemas que apliquen a cada uno de estos modos:
        1. Orgánico
        2. Semi-embebido
        3. Embebido

    Dar ejemplos.

    * Orgánicos: involucra procesamiento de datos, uso de bases de datos y se focaliza en transacciones y recuperación de datos. Ejemplo: sistema de facturación. 
    * Embebido: contienen software de tiempo real que es una parte integral de un sistema mayor basado en hardware. Ejemplo: control de ascensores.
    * Semi-embebido: entre orgánico y embebido. Presenta mayor procesamiento de transacciones. Ejemplo: monitorio de una red.

23. ¿Cuáles son los principales objetivos considerados en el desarrollo del modelo COCOMO 2.0? Explique diferencias con la versión original.

    Los objetivos de COCOMO 2.0 son:

    * Desarrollar modelos de costos y de estimación acordes a las prácticas actuales.
    * Desarrollar bases de datos de costos y herramientas que soporten una mejora contínua del modelo.
    * Proveer un framework analítico cuantitativo y un conjunto de herramientas y técnicas para evaluar los efectos de las mejoras en los costos de vida y en las planificaciones.

    Las principales diferencias entre COCOMO y COCOMO 2.0 son:

    * COCOMO: requiere software tamaño en KDSI como entrada, pero COCOMO 2.0 se basa en código KSLOC(lógico). La principal diferencia entre DSI y real es que una sola línea de código fuente puede tener varias líneas físicas.
    * COCOMO 2.0: aborda las siguiente tres fases del ciclo de vida en espiral: desarrollo de aplicaciones, principios de diseño y arquitectura post. COCOMO proporciona las estimaciones puntuales del esfuerzo y la programación, pero COCOMO 2.0 proporciona rangos probables de estimaciones que representan unadesviación estándar alrededor de la estimación más probable.

24. Explique qué es la economía de escala. De al menos dos ejemplos.

    Es el poder que tiene una empresa cuando alcanza un nivel óptimo de producción para ir produciendo más a menor coste, es decir, a medida que la producción en una empresa crece, sus costes por unidad producida se reducen. Cuanto más produce, menos le cuesta producir cada unidad. Ejemplos: uso de herramientas CASE, simulaciones, entornos de pruebas.

## Parte IV: Gestión de proyectos

25. Explicar qué es la gestión de los beneficios y en qué consiste su enfoque.

    La gestión de los beneficios consiste en obtener beneficios para sus clientes y para las partes interesadas. Su enfoque se divide en 5 partes:
    1. Desarrollo de una estrategia de gestión de beneficios: es decir, definir cómo el programa se encargará de la gestión de los beneficios.
    2. Perfiles de beneficios: esto es, identificar los beneficios en áreas como calidad de servicio(respuestas rápidas a las consultas de los ciudadanos, por ejemplo) o economía(si los beneficios contribuyen a reducir los costos de las agencias gubernamentales, por ejemplo).
    3. Plan de realización de beneficios: en otras palabras, una vista completa de todos los perfiles de beneficios en forma de un cronograma que define cuándo se realizará cada uno.
    4. Realización de beneficios: en otros términos, la entrega definitiva de los beneficios incrementales. A menudo, para implementar los beneficios en las organizaciones son necesarios cambios estructurales y/o de procesos, pero tales cambios son en pos de la inclusión de nuevas capasidades, productos y/o servicios.
    5. Revisión de beneficios: dicho de otro modo, validar el valor de los beneficios esperados y realizados a los ojos de los stakeholders. La idea es evaluar el nivel de los objetivos alcanzados y asegurar la alineación de los beneficios con los objetivos del programa. Además, es posible apreciar la efectividad de cómo son gestionados los beneficios e identificar, junto a los stakeholders, nuevos posibles beneficios.

26. ¿Cuáles son las características principales de la gestión de los interesados?

    Ayuda a asegurar que las partes interesadas:
    * Estén comprometidas con los beneficios identificados y su realización.
    * Estén fomentando la propiedad.
    * Sean responsables de añadir valor a través del proceso de realización.

27. Indicar cuáles son los objetivos de la gestión de los interesados y a qué preguntas responde.

    El principal objetivo es asegurar que los beneficios:
    * Sean identificados.
    * Estén definidos claramente.
    * Estén vinculados a los resultados estratégicos.
    * Sean específicos, medibles, realizables, realistas y limitados con el tiempo.

28. ¿De qué forma se representa la identificación de los interesados y sus intereses? Ejemplifique.

    La principal forma es la comunicación. La comunicación es un factor crítico de éxito para cualquer proceso de transformación. La idea es concientizar a los stakeholders sobre los beneficios y el impacto y de esa manera obtener el compromiso del personal de las organizaciones con los cambios a ser introducidos. Es importante, además, mantener a todo el personal de las organizaciones informado sobre los progresos realizados antes, durante y después de la ejecución y entrega de resultados. Es de crítica importancia garantizar que las comunicaciones sean doble vía, alentando activamente a los stakeholders a proporcionar un feedback y asegurarse de que estén informados acerca del uso del mismo.

29. Indique qué datos se incluyen al momento de crear una matriz de impacto y qué aporta el análisis de los mismos.

//pedir explicación

30. ¿Qué datos tiene un plan de comunicación dentro de la gestión de los interesados? Mencione posibles canales de comunicación.

## Parte V: Ejercicios

31. Una empresa vende seguros para bienes inmuebles. Cuenta con 10 empleados de planta y 20 vendedores contratados. En base a requerimientos de los directivos, la Gerencia de Sistemas definió la ejecución de dos proyectos para el período 2017-2018:
    1. Comprar dispositivos móviles para ayudar a los 20 vendedores en sus tareas diarias.
    2. Proveer un sistema de sueldos y jornales. Para cada proyecto se pide:
        1. Clasificarlo y justificar dicha clasificación.
        2. Identificar al menos 3 tareas que sería necesario ejecutar en cada proyecto –analizar si están conectadas y en caso afirmativo, explicar cómo.
        3. Explicar dos situaciones que puedan hacer fracasar el proyecto.
32. Elegir una organización y describir a qué se dedica(cuál es su misión). Formular un objetivo estratégico para el cual se necesite la ejecución de un programa y luego:
    1. Identificar un programa para la implementación del objetivo estratégico que incluya al menos tres proyectos.
    2. Explicar por qué los proyectos forman parte del programa.
33. Una importante empresa de servicios de salud, con más de 20.000 empleados, tiene como proyecto proveer a sus empleados un sistema online que los ayude a mejorar y mantener su estado de salud. Hoy en día, la empresa paga un 20% más que el promedio del mercado en servicios de salud prepaga. Se cree que, con este sistema, se mejorará la salud de sus empleados y se podrán negociar mejores precios con la prepaga, ahorrando al menos $150 al año por empleado. Se busca terminar el proyecto en 6 meses con un presupuesto de $500.000. El sistema requiere:
    1. Permitir a los empleados registrarse a programas de recreación patrocinados por la compañía, tales como fútbol, básquet, ciclismo y otros deportes.
    2. Permitir a los empleados registrarse a programas y clases para ayudarlos a controlar su peso, reducir el stress, dejar de fumar, etc.
    3. Monitorear datos sobre los empleados que se involucran en esas actividades recreacionales y esos programas de salud.
    4. Ofrecer incentivos a los que se inscriben en los programas y tienen un buen desenvolvimiento en ellos (dejando de fumar, ganando competencias, etc.)
    
    Para este proyecto se busca formular una estrategia de gestión de los interesados con:
    
    1. Identificación de al menos tres grupos de interesados.
    2. Creación del mapa de partes interesadas.
    3. Creación de la matriz de impacto de las partes interesadas.
    4. Elaboración de un plan de comunicación.
    5. Definición de los canales de comunicación.