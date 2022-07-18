# Administración de proyectos III

## Glosario

+ **RRHH**: recursos humanos.
+ **PROD**: _productivity_ o productividad.
+ **KLOC**: _K-Lines Of Code_ o miles de líneas de código.
+ **NPO**: _New Point Object_ o nuevo punto objeto.
+ **PM**: _People Monthly_ o personas mes.

## Estimación de costos

**Predicciones** de cuánto **tiempo**, **esfuerzo** y **perfiles de RRHH** son requeridos para **construir un software**. El costo principal son los RRHH. Suelen ser inexactas por lo siguiente:
+ Dominio de la aplicación.
+ Hardware.
+ Herramientas.
+ Técnicas.
+ Personal.
+ Creadores y no constructor.
+ Problemas politicos: se estima para un presupuesto, luego este se ajusta y se pretende mantener el mismo tiempo.
+ Problemas técnicos: no existe un precedente histórico para estimar.

//NECESITO AHONDAR EN ESTO UN POCO MÁS

Las estimaciones de costos tienen dos usos:
+ **Planificación**: se necesita saber **cuántos recursos se va a insumir**.
+ **En control**: se necesita sabe **cuánto se hizo** y **cuánto falta**.

Se requieren métodos que estimen la complejidad del software **antes** de que sea desarrollado.

## Técnicas de estimación

+ **Lluvia de ideas**: sirve para generar **muchas ideas** en un grupo. Requiere la **participación espontánea** de todos. Permite obtener ideas **innovadoras** y **creativas**. Asegura la **calidad** ya que el clima de participación y motivación genera un sentimiento de **compromiso** y **responsabilidad** con el proyecto.
+ **Opinión experta**: **experiencia** de un personal de desarrollo senior. Se plantean los parámetros del proyecto y el experto da sus predicciones.
+ **Analogía**: **comparar** el proyecto actual con otros anteriores. Se analizan diferencias y similitudes claves.
+ **Descomposición**: se **descompone** el producto en **componentes** y las actividades en tareas basándose en experiencias pasadas.
+ **Modelos**: identifican contribuyentes claves al esfuerzo, generando fórmulas matemáticas que relacionan todos esos items al esfuerzo. Se clasifican en:
    - **_Bottom up_**: comienza con las partes más **pequeñas** y provee estimaciones para cada una de ellas.
    - **_Top down_**: estima el **producto o proceso completo**. Las estimaciones para cada componente se aprecian como porciones de un todo.
    
## Cálculo del esfuerzo

+ PM inicial = c KLOC ^k
+ PM = esfuerzo en Personas Mes.
+ c y k = constantes dadas por el modelo. k < 1.
+ KLOC = Thousands(K de Kilo) of Lines Of Code.

Se corrige usando **constructores de costos**.

### Constructores de costos

Hay 4 atributos:
+ **Del producto**: confiabilidad requerida, complejidad del producto, tamaño de la base de datos.
+ **Computacionales**: restricciones de almacenamiento y tiempo de ejecución, volatilidad de la máquina, optimización y experiencia en la máquina virtual.
+ **Del personal**: capacidad de análisis y programación y experiencia en la aplicación y en el lenguaje de programación.
+ **Del proceso**: uso de prácticas de programación modernas, uso de herramientas de software y planificación requerida.

## Pasos básicos de estimación

1. **Estimar el tamaño del software** y usar la fórmula del modelo para estimar el esfuerzo inicial.
2. **Revisar la estimación** usando constructores de costos.
3. **Aplicar las herramientas del modelo a la estimación del paso 2** para determinar el esfuerzo total.

**IMPORTANTE**: no confiar ciegamente en el resultado del modelo. Esto tampoco significa no usarlo.

## COCOMO

Significa _COnstructive COst MOdel_ (Modelo de construcción de costos). Hay tres modelos:
+ **Básico**: aplicable cuando se **conoce poco** del proyecto.
+ **Intermedio**: aplicable luego de la **especificación de requerimientos**.
+ **Avanzado**: aplicable cuando se **termina el diseño**. Es aplicar el intermedio a nivel de componentes para así poder construir una estimación para el proyecto completo.

Siempre calibrar el modelo al propio entorno de programación. Por lo general, en proyectos medios COCOMO básico e intermedio coinciden. Usar COCOMO avanzado cuando se identificaron los módulos del sistema.

Los tres modelos utilizan la siguiente fórmula: ```E = a S^b F```. Donde:
+ E = esfuerzo en personas mes.
+ S = tamaño medido en KDSI (_K-Delivered Source Instructions_, como KLOC pero más viejo).
+ F: factor de ajuste (1 en el modelo básico).
+ a, b: se obtienen de tablas del modelo en función del tipo de sistema.

### Fases de desarrollo de COCOMO

+ **Requerimientos/planificación**: analizar requerimientos, mostrar plan de producto y generar una especificación completa del producto. 6% al 8% del esfuerzo nominal PM.
+ **Diseño**: determinación de arquitectura del producto y de las especificaciones de los subsistemas. 16% al 18% del esfuerzo nominal PM.
+ **Programación**: diseño detallado y prueba del código. 48% al 68% del esfuerzo nominal PM.
+ **Prueba/integración**: unir las diferentes unidades ya probadas. 16% al 34% del esfuerzo nominal PM.

### Clasificación de sistemas de COCOMO

+ **Orgánicos**: involucra procesamiento de datos, uso de base de datos y se focaliza en transacciones y recuperación de datos. Ej: sistema de facturación.
+ **Embebidos**: contiene software de tiempo real que es una parte integral de un sistema mayor basado en hardware. Ej: control de ascensores.
+ **Semi-embebidos**: entre orgánico y embebido. Presenta mayor procesamiento de transacciones. Ej: monitoreo de una red.

El modelo básico aplica las siguientes fórmulas y valores:

Sistema|A|B|C|D
:---:|:---:|:---:|:---:|:---:|
Orgánico|2.40|1.05|2.50|0.38
Embebido|3.00|1.12|2.50|0.35
Semi-embebido|3.60|1.20|2.50|0.32

```
Personas Mes (PM) = a*(KDSI^b)
Tiempo de Desarrollo (TD) = c*(PM^d)
PM = Personas necesarias para hacer el proyecto en 1 mes
KDSI = Miles de líneas de código entregables
```

### Aplicación de COCOMO

Si se **sabe poco**, **COCOMO básico**. Si se **conoce un poco más** como el **lenguaje** o las **herramientas** a utilizar, el **COCOMO intermedio**. Luego se eligen los conductores de costos de una tabla que presenta 15. La importancia de cada conductor de costo es clasificada en una escala ordinal con seis puntos: Muy Baja, Baja, Nominal, Alta, Muy Alta, Extra Alta.

### Factores de ajuste/Atributos de costo/Conductores de costo para COCOMO

Tratan de capturar el **impacto** del entorno del proyecto en el costo del desarrollo. 4 categorías:
+ Atributos del **producto**
    - **RELY** (_reliability_ o fiabilidad): posibles **consecuencias** para el usuario en caso de que existan defectos en el producto.
        * **Muy Baja**: el efecto de un fallo del software simplemente trae como consecuencia la inconveniencia de **corregir el fallo**.
        * **Baja**: el efecto de un fallo software es una **pérdida fácilmente recuperable** para los usuarios.
        * **Nominal**: el efecto es una **moderada pérdida** para los usuarios, pero es una situación de la que **se puede salir sin excesiva dificultad**.
        * **Alta**: el efecto es una **gran pérdida financiera** o una **inconveniencia masiva humana**.
        * **Muy Alta**: el efecto es una **pérdida de vidas humanas**.
    - **DATA**: **tamaño de la base de datos** a desarrollar en relación con el **tamaño del programa**. Se define por el cociente D/P siendo D (database) tamaño de la base de datos en bytes y P (program), tamaño del programa en DSI. El cociente se mide en escalas de 0 a 10, de 10 a 100, de 100 a 1000 y de más de 1000 para bajo, nominal, alto y muy alto, respectivamente.
    - **CPLX** (_complexity_ o complejidad): complejidad de los módulos y del sistema en sí mismo. La puntuación puede variar de Muy Baja si el módulo está compuesto de expresiones matemáticas simples a Extra Alta para módulos que utilizan muchos recursos de planificación.
+ Atributos del **hardware**
    - **TIME**: limitaciones en el porcentaje de uso de la CPU. Mientras más chico el margen de tiempo de ejecución disponible del programa, más alta la restricción y más alto el costo. Es Nominal cuando el porcentaje es el 50%, y Extra Alta cuando la restricción es del 95%.
    - **STOR**: limitaciones en el porcentaje del uso de la memoria. Mientras más chico el margen de memoria disponible para ejecución, más esfuerzo y más costo. Nominal cuando la reducción del almacenamiento principal es del 50% a Extra Alta cuando la reducción es del 95%.
    - **VIRT**: cambios que puede sufrir la máquina virtual (hardware mas software) durante el desarrollo del software. Refleja la probabilidad de que ocurran los cambios desde Baja a Muy Alta.
    - **TURN**: tiempo de respuesta del ordenador desde el punto de vista del programador. Cuanto mayor sea el tiempo de respuesta, más alto será el esfuerzo humano. Puede variar desde Baja para un sistema interactivo; a Muy Alta, cuando el tiempo medio de respuesta es de más de 12 horas.
+ Atributos del **personal**:
    - **ACAP** (_Analyst Capability_): capacidad de cooperación de analistas. Cuanto más capaz sea el grupo, menos esfuerzo será necesario. Va desde Muy Baja a Muy Alta.
    - **AEXP** (_Analyst Experience_): experiencia del grupo en una aplicación similar.
        * **Muy Baja**: <= 4 meses de XP.
        * **Baja**: 1 año de XP.
        * **Nominal**: 3 años de XP.
        * **Alta**: 6 años de XP.
        * **Muy Alta**: >= 12 años de XP.
    - **PCAP** (_Programmer Capability_): idem ACAP pero con programadores.
    - **VEXP** (_Virtual Experience_): idem AEXP pero con programadores.
        * **Muy Baja**: <= 1 mes.
        * **Baja**: 4 meses.
        * **Nominal**: 1 año.
        * **Alta**: >= 3 años.
    - **LEXP** (_Language Experience_): experiencia de los programadores en el lenguaje de programación.
        * **Muy Baja**: <= 1 mes.
        * **Baja**: 4 meses.
        * **Nominal**: 1 año.
        * **Alta**: >= 3 años.
+ Atributos del **proyecto**:
    - **MODP** (_Modern Practices_): utilización de prácticas modernas de programación (Top-Down, programación estructurada, etc.).
        * **Muy Baja**: no se utilizan prácticas modernas de programación (MODP).
        * **Baja**: uso experimental MODP.
        * **Nominal**: experiencia razonable en algunas MODP.
        * **Alta**: experiencia razonable en gran parte de MODP.
        * **Muy Alta**: uso habitual de MODP.
    - **TOOL**: uso de herramientas de software. Va desde Muy Bajo, cuando solo se usan herramientas básicas; a Muy Alto, cuando se utilizan herramientas específicas.
    - **SCED**: esfuerzo necesario para cumplir con la planificación. Siendo el plazo definido en el modo básico el tiempo nominal de desarrollo, si ocurren apresuramientos será Muy Bajo y si ocurren retrazos, Muy Alto.
    
//PEDIR EXPLICACIÓN DE CÓMO FUNCIONA LA TABLA DE COCOMO

## COCOMO 2.0

**Actualización** de COCOMO para que se pueda adaptar a las nuevas tecnologías, enfoques de orientados a objetos, etc. Si bien COCOMO fue muy exitoso, su aplicación **ya no es práctica para entornos modernos de desarrollo**. COCOMO 2.0 tiene como objetivos:
+ Desarrollar modelos de costos y de estimación acordes a las prácticas actuales.
+ Desarrollar bases de datos de costos y herramientas que soporten una mejora continua del modelo.
+ Proveer un framework analítico cuantitativo, y un conjunto de herramientas y técnicas para evaluar los efectos de las mejoras en los costos de ciclos de vida y en las planificaciones.

Tres modelos:
+ **Modelo de la aplicación**: basado en prototipos y utiliza puntos objeto.
+ **Modelo de diseño**: obtener estimaciones de costo y duración antes de finalizar el diseño de la arquitectura. Utiliza puntos función.
+ **Modelo de post-arquitectura**: modelo muy detallado con más conductores de costo. Utiliza KDSI.

### Bases de estimación para COCOMO 2.0

KLOC: _K Lines Of Code_.

+ **Puntos Objeto** (PO):
    1. Estimar número de pantallas, reportes y componentes del lenguaje de programación.
    2. Clasificar la complejidad de esos objetos en simple, media o alta y determinar los pesos (no adjunto la tabla para hacerlo).
    3. Determinar PO: sumar los pesos obtenidos antes.
    4. Estimar el porcentaje de reuso esperado y re calcular los NPO usando la formula PO (100 - %reuso) /100.
    5. Determinar ratio de productividad (PROD) con NPO / PM.
    6. Estimar PM con NPO/PROD
+ **Puntos Función** (PF):
    1. Calcular los PF en base a requerimientos y documentos de diseño. Tener en cuenta inputs externos, outputs externos, consultas externas, archivos internos y archivos de interface externos.
    2. Clasificar cada punto función de acuerdo a su complejidad (no incluyo tabla).
    3. Aplicar pesos de complejidad de acuerdo a tabla (no adjunto tabla).
    4. Convertir PF a líneas de código en base a tabla (no adjunto tabla).
    
### Estimación del esfuerzo para COCOMO 2.0

Se usa la formula: PM nominal = A * (Tamaño) ^B

- Tamaño se expresa en KLOC.
- A intenta cuantificar los efectos multiplicativos en el esfuerzo de proyectos de tamaño creciente.
- B mide economía de escala:
    + B < 1.0: la productividad aumenta a medida que aumenta el tamaño del proyecto. Esto puede darse utilizando herramientas CASE específicas.
    + B = 1.0: no aplica (balance).
    + B > 1.0: a medida que aumenta el tamaño del proyecto, disminuye la productividad (problemas de comunicación, integración, etc).
    
