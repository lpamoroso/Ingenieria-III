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
11. Explique qué es un programa. Mencione diferencias entre programas y proyectos.
12. ¿Cuál es la relación entre la administración de programas y la administración de proyectos?

## Parte II: Actividades y tareasde proyectos

13. Explique qué es Work Breakdown Structure(WBS) y cómo se construye.
14. Mencione los distintos usos del WBS en la administración de proyectos.
15. Indique cuáles son las características que deben tener las actividades para considerarse completas. Explique.
16. Explique qué es la duración de una actividad. Indique cuál es la diferencia con el esfuerzode trabajo.
17. ¿Cuáles son las causas de variación en la duración de una actividad?
18. Mencione las distintas técnicaspara estimar esfuerzo.

## Parte III: Costos

19. Explique a qué se hace referencia con el término "Estimación de costos".
20. ¿Cuáles son las técnicas de estimación y para qué se utilizan?
21. El modelo COCOMO original es una colección de tres modelos:
    1. Básico.
    2. Intermedio.
    3. Avanzado o detallado.

Explique las diferencias entre estos modelos.
22. Los modelos calculan el esfuerzo requerido E a través de una fórmula de la forma: E = a x Sbx F, y la duración estimada a través de la fórmula: D = c x Ed
    1. ¿Qué valor toma F para el modelo básico?
    2. Describir brevemente en función de qué tipos de variables se calcula el factor de ajuste F en los otros dos modelos.
    3. Indicar cómo varían los valores de a y b, y c y d en ambas fórmulas de acuerdo al modo utilizado.
    4. Describir las características generales de sistemas que apliquen a cada uno de estos modos:
        1. Orgánico
        2. Semi-embebido
        3. Embebido

    Dar ejemplos.
23. ¿Cuáles son los principales objetivos considerados en el desarrollo del modelo COCOMO 2.0? Explique diferencias con la versión original.
24. Explique qué es la economía de escala. De al menos dos ejemplos.

## Parte IV: Gestión de proyectos

25. Explicar qué es la gestión de los beneficios y en qué consiste su enfoque.
26. ¿Cuáles son las características principales de la gestión de los interesados?
27. Indicar cuáles son los objetivos de la gestión de los interesados y a qué preguntas responde.
28. ¿De qué forma se representa la identificación de los interesados y sus intereses? Ejemplifique.
29. Indique qué datos se incluyen al momento de crearuna matriz de impacto y qué aporta el análisis de los mismos.
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