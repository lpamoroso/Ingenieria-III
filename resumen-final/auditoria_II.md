# Auditoría II

## Glosario

+ SCI: Sistema de Control Interno.

## Controles

Son necesarios para implementar los SCI. El control es un sistema que **previene**, **detecta** o **corrige** eventos ilegales.
+ **Es un sistema**: una contraseña, por ejemplo. El control comprende todos los aspectos de la misma, desdela seguridad y la correcta validación de la misma hasta el almacenamiento seguro o usos indebidos.
+ **Control de eventos ilegales**: el evento ilegal se da cuando se ingresan inputs no autorizados/incompletos o cuando ese input es transformado de alguna manera no autorizada/incompleta.

## Tipos de controles

+ **Preventivo**: reducen las **probabilidades** de que ocurra un **evento ilegal**. Instrucciones de cómo completar un formulario.
+ **Detectivo**: reducen la **cantidad de pérdidas** cuando los **eventos ilegales ocurren**. Un programa que valida datos de input, rechazando los erróneos.
+ **Correctivo**: reducen la **cantidad de pérdidas** cuando los **eventos ilegales ocurren**. Un programa que detecta el ruido en comunicaciones y permite corregir datos corruptos.

## Objetivo de la auditoría

Determinar si los **controles** están **bien ubicados** y **previenen** los **eventos ilegales**.

## Administrando el mostro (SCI)

Cuando la cosa se pone peluda hay dos caminos:
+ **Factorizar**: crear más subsistemas. La idea acá es dividir en tareas más **simples** de modo que todo se vuelva más **manejable**. Se necesita un criterio para particionar, como la función del subsistema. Primero se parte de funciones principales, y se va dividiendo hasta obtener unidades fácilmente comprensibles y manejables. También se puede usar de criterio el acoplamiento (independencia de otros subsistemas) o la cohesión (todas las tareas apuntan a cumplir la función principal del sistema). Hay dos formas de factorizar:
    - **Funciones gerenciales**: tareas que apuntan al desarrollo, implementación y mantenimiento de los SI.
        * **Alta gerencia**: asegurar que las funciones de los SI estén bien administradas. Decide políticas a largo plazo de uso de los SI.
        * **Gerencia de SI**: planificar y controlar actividades de SI. Aconseja a la alta gerencia y traduce las decisiones en objetivos y metas de corto plazo.
        * **Gerencia de desarrollo de sistemas**: diseño, implementación y mantenimiento de SI.
        * **Gerencia de programación**: programación de los SI.
        * **Administración de datos**: lograr objetivos de planificación y control en cuanto a datos.
        * **Gerencia de aseguramiento de calidad**: estándares de calidad de los SI.
        * **Administración de seguridad**: controles de acceso y seguridad física de los SI.
        * **Gerencia de operaciones**: planificación y control de operaciones diarias.
    - **Funciones de aplicación**: tareas que se focalizan en generar información confiable. Los SI de una organización se dividen en ciclos, los cuales dependen de la actividad de la organización. Ej de ciclos: compras y pagos, ventas y cobranza, tesorería, etc. La idea es factorizar cada ciclo. Ej: ventas podría dividirse en administración de clientes, captura de pedidos y facturación. Conjuntos de subsistemas incluye:
        * **Limítrofe**: componentes que establecen las interfaces entre el sistema y el usuario.
        * **_Input_**: componentes que capturan e ingresan comandos al sistema.
        * **Comunicaciones**: componentes que transmiten datos de sistemas a subsistemas.
        * **Procesamiento**: componentes que realizan tareas de decisiones y cálculo en el sistema. 
        * **Base de datos**: componentes que acceden, modifican o eliminan datos.
        * **_Output_**: componentes que muestran datos al usuario.
+ **Determinar confiabilidad de subsistemas**: ver si los subsistemas actuales son **confiables**. Para esto es necesario partir del subsistema de menor nivel y de ahí ir evaluando la confiabilidad por **niveles**. Para esto es que se debe determinar, por cada nivel, los posibles eventos a ocurrir partiendo de las funciones de cada subsistema. Se debe saber qué debería hacer cada función y si efectivamente eso se realiza.

  Luego, se determinan eventos legales e ilegales. Para esto es preciso entender que el sistema cambia de estado a través de transacciones generadas por eventos. Para saber todos los eventos que pueden surgir por una transacción, es necesario entender cómo el sistema la procesa. Un mecanismo para este fin es el de walthrough, que consiste en:

  1. Considerar una transacción individual.
  2. Identificar los componentes asociados a esa transacción.
  3. Entender qué rol tiene cada componente en el procesamiento de esa transacción.
  4. Considerar errores o irregularidades que pueden darse en el camino.

Dado que lo anterior es costoso por existir muchas transacciones, es que se agrupa por clases de transacciones y se procede de la siguiente manera:
1. Agrupar transacciones con **procesamiento similar**.
2. **Entender las transacciones** y determinar los eventos que puedan surgir como grupo.
3. Tratar aquellas transacciones que serían relevantes para la auditoría.

Si bien esto último no identifica todos los eventos, lo cierto es que llega a cubrir lo más importante. Luego los auditores determinarán si los controles están bien ubicados y si funcionan correctamente. Es así que con la evidencia recolectada se procede a determinar si las pérdidas por eventos ilegales son aceptables. Por cada evento ilegal ha de considerarse los controles que lo cubren, si estos son confiables y si pudiera ocurrir algún error o irregularidad. Para esto se publican listas de errores que muestran y exponen las irregularidades.

## Estimar confiabilidad de controles

La evaluación siempre se da desde abajo hacia arriba, puesto que los subsistemas inferiores son componentes de los superiores. Es así que analizando el nivel más bajo se puede ver el impacto, la naturaleza y la frecuencia de eventos ilegales en niveles más altos. En cualquier nivel de la estructura, los pasos se resumen en:
1. Identificar transacciones que ingresan al sistema.
2. Considerar eventos legales e ilegales que puedan ocurrir.
3. Asegurar la confiabilidad de los controles que detectan los eventos ilegales.

## Más controles

A medida que se sube de nivel, suelen aparecer más controles porque:
+ Los controles de bajo nivel andan mal.
+ Es más efectivo en costos implementar el control en un nivel más alto.
+ Algunos eventos no son ilegales excepto en los niveles más altos.

## Riesgos de la auditoría

El riesgo de auditoría se mide como el riesgo de que un auditor fracase al detectar las pérdidas materiales reales o potenciales, o que los registros sean incorrectos. Es decir:

```RDA = RI * RC * RD```

Siendo:
+ **Riesgo deseado** (RDA): esto es, el riesgo que se desea correr.
+ **Riesgo inherente** (RI): es decir, la probabilidad de que haya una pérdida material o imputación errónea, antes de determinar la confiabilidad de los controles.
+ **Riesgo de control** (RC): en otras palabras, la probabilidad de que los controles internos fallen en evitar pérdidas materiales o imputaciones erróneas. 
+ **Riesgo de detección**(RD): o sea, la probabilidad de que no se detecten las pérdidas materiales o imputaciones erróneas.

## Pasos para calcular el riesgo de auditoría

1. **Calcular el nivel RDA**: se evaluán las consecuencias de fracasar en detectar las pérdidas materiales reales o potenciales.
2. **Se calcula RI** a partir de varios factores como:
   + Naturaleza de la organización.
   + Industria en la que opera.
   + Características del gerenciamiento.
   + Intereses contables y de auditoría (si se usan técnicas, entre otras cosas...).

   Luego se calcula el RI para **diferentes segmentos de la auditoría** (ciclos, sistemas de aplicación, etc). Para cada parte, se analizan factores como:
   + **Sistemas financieros**: los controles financieros sobre los principales activos de la organización. Principal blanco de acciones delictivas y fraudes. Alto RI.
   + **Sistemas estratégicos**: las ventajas competitivas de la organización (clientes, secretos de marca, etc). Son blanco de espionaje industrial o acciones indebidas de la competencia. Alto RI.
   + **Sistemas de operación crítica**: aquellos sistemas que podrían paralizar toda la organización si fallasen. Alto RI por lo gral.
   + **Sistemas de tecnología avanzada**: sistemas que usan tecnología de punta. Alto RI por falta de experiencia en su uso.
3. Se calcula el RC asociado a cada segmento de la auditoría considerando la confiabilidad de los controles gerenciales y de aplicación. Los controles gerenciales se suelen identificar y evaluar primero. Estos actúan en forma de capas de cebolla por encima de los controles de aplicación, por lo que el buen nivel de controles externos garantizarán el nivel de los internos. Suelen evaluarse en general y no para cada aplicación.//PREGUNTAR AL PROFE CÓMO FUNCIONA ESTE RIESGO
4. Se calcula **el nivel de RD necesario** para cumplir el RDA. Para esto se diseñan procedimientos de recolleción de evidencia para alcanzar el RD. Dado que lo auditores no suelen poder recolectar toda la evidencia que quisieran, deben ser astutos para determinar en donde aplicar los procedimientos y cómo analizar la evidencia obtenida.
