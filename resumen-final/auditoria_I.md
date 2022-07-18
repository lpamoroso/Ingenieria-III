# Auditoría I

## Glosario

+ **SI**: sistema de información.

## Razones para realizar una auditoría

+ **Costos por pérdida de datos**: cuanto más exactos los datos, más posibilidades de que la organización se adapte y sobreviva a un entorno cambiante.
+ **Costos por toma de decisiones incorrectas**: la calidad en la toma de decisiones depende de calidad en los datos y en las reglas de decisión. La exactitud en los datos depende del tipo de decisión a tomar: decisiones de planeamiento estratégico tomadas por la alta gerencia probablemente puedan aceptar errores en los datos; sin embargo, las decisiones de control administrativo y de control operativo requieren más exactitud.
+ **Costos por abusos computacionales**: incidente en el cual un víctima sufre o podría haber sufrido pérdida, y un perpetador con intención logra o podría haber logrado ganancia. Hacking, virus, etc. Las consecuencias son muchas: destrucción/sustracción/modificación/uso no autorizado de activos, daño físico a personas, pérdida de privacidad, etc.
+ **Costos por errores de computación**: se refiere a cuando la pérdida es considerable como pérdida de vidas humanas, privación de libertad o daño al medio ambiente.
+ **Valor de datos, hardware, software y personal**:
    - **Datos**: qué pasa si la competencia obtiene información privilegiada.
    - **Hardware**: qué pasa si un componente crítico deja de funcionar.
    - **Software**: qué pasa si se destruye.
    - **Personal**: qué pasa cuando un profesional calificado deja la empresa.
+ **Mantenimiento de privacidad**: se recolecta mucha información de un individuo y con un sistema automatizado podría integrarse y buscar información, a modo de usarla en contra de una persona.
+ **Evolución controlada de IT**: evitar un posible Skynet.

## Definición de auditoría

Recolectar y evaluar evidencia para determinar si:
+ **El sistema preserva los activos**: siendo activos el hardware, software, facilidades, personas, archivos, domuentación e insumos.
+ **Mantiene la integridad de los datos**: debe mantener la completitud, consistencia, veracidad y correctitud de los datos. Sin esto, la organización pierde ventaja competitiva.
+ **Permite alcanzar los objetivos de la organización**: formas de evaluar la efectividad de los sistemas:
    - **Monitoreo durante el desarrollo** que garantiza que se satisfacen los requerimientos del usuario.
    - **Post-Auditoría**.
    Formas de evaluar la efectividad de un SI:
    - **Características de los usuarios**.
    - **Entorno de toma de decisiones**.
+ **Usa los recursos eficientemente**: utiliza los recursos mínimos para satisfacer sus objetivos.
+ Otros objetivos: asegurar que la organización cumple con determinadas regulaciones/estándares ya sea involuntaria o voluntariamente. Ej: normas ISO.

## Logro de objetivos: implementando un SCI(Sistema de Control Interno)

Los objetivos de la auditoría sólo se pueden lograr si la alta gerencia implementa un sistema de control interno. Este incluye:
+ **Separación de obligaciones**: dado que el sistema automático realiza todas las funciones se debe separar la capacidad de ejecutar el programa, de la de modificarlo. En los sistemas manuales, diferentes personas realizan cada tarea.
+ **Delegación clara de autoridad y responsabilidades**: tanto en sistemas manuales como automáticos es complejo y las consecuencias son indeseables. Dado que muchos usuarios desarrollan, modifican y operan sus propias aplicaciones esto complejiza el control aunque el usuario tenga importantes beneficios.
+ **Reclutamiento y entrenamiento de personal calificado**: esto se refiere al poder que tiene cada operario. El personal responsable del sistema automatizado tiene delegado mayor poder que los operarios manuales. Esto hace que sea complejo elegir alguien confiable y competente para tanta responsbilidad. A lo anterior hay que sumar que la gerencia tiene poco tiempo para evaluar al personal.
+ **Sistema de autorizaciones**: están embebidas en los programas. Se debe controlar las autorizaciones definidas en el procedimiento y la veracidad del procesamiento de los programas. Hay dos tipos:
    - **Generales**: políticas que la organización debe seguir.
    - **Específicas**: transacciones individuales.
+ **Documentos y registros adecuados**: si bien esto no es tan necesario en los sistemas automatizados, deben haber facilidades de acceso que aseguren que los rastros de auditoría son exactos y completos.
+ **Control físico y documentación sobre los activos**: en los sistemas automáticos toda la información está centralizada, lo que aumenta el riesgo de pérdida por desastre o abuso. En los sistemas manuales, la información suele estar dispersa.
+ **Chequeos independientes de performance**: es decir, que el sistema automático ejecute un algoritmo para detectar irregularidades o errores. Los auditores deben evaluar los controles establecidos para desarrollar, modificar, operar y mantener programas. En los sistemas manuales, hay una persona que detecta las irregularidades.
+ **Comparación periódica de activos con registros contabilizados**: se debe establecer un programa en el sistema automático que verifique los datos que representan los activos con los activos reales a fin de determinar falta de completitud o inexactitud de los datos. En los sistemas manuales, hay una persona que detecta las irregularidades.

## La computación en una auditoría

A pesar de la **complejidad** que supone recolectar evidencia en un sistema automático, la función de la auditoría **no cambia**. Esto hace que sea complicado además determinar las consecuencias de fortalezas y debilidades de un sistema en pos de la fiabilidad de este. Los **errores** de los sistemas automáticos son **determinísticos**, **costosos** y **ocurren a mayor velocidad**. Esto hace que los **controles de calidad interna de un producto** sean **críticos**. Los errores en los sistemas manuales tienden a ser estocásticos, es decir, ocurren "cada tanto".

## Fundamentos de la auditoría

La auditoría de SI se fundamenta en:
+ **Auditoría tradicional**: aporta las bases, conocimiento, experiencia y filosofía de lo que una auditoría implica. Se basa en examinar los SI en base a los 3 preceptos antes nombrados.
+ **Auditoría de SI**: aporta técnicas de administración de proyectos y documentación, estándares y presupuestos. La parte más específica y focalizada.
+ **Ciencias de la computación**: los ingenieros de software deben colaborar con los objetivos de la auditoría. El conocimiento técnico y específico resulta provechoso para los auditores, aunque a veces también genere problemas.
    - **Beneficios**: es posible no preocuparse tanto por la confiabilidad de ciertas componentes.
    - **Problemas**: mayor dificultad para evitar abusos.
+ **Ciencias del comportamiento**: los objetivos de la auditoría podrían fallar si hay conflictos de comportamiento, como sabotaje del sistema.
