# Administración de proyectos II

## Glosario

+ WBS: _Work Breakdown Structure_.

## WBS (Work Breakdown Structure o Estructura de descomposición del trabajo) 

Es una **descripción jerárquica** del trabajo que se debe realizar para completar el proyecto. El trabajo se divide en **actividades** y las actividades en **tareas**. El líder de proyecto es el encargado de construirlo de la manera que el considere conveniente para poder administrar el proyecto correctamente.

```
                                 Meta
           |                      |             |
      Actividad 1              Actividad 2  Actividad 3  NIVEL 1
   |              |
Actividad 1.1  Actividad 1.2                             NIVEL 2

Actividad 1.1
Tarea 1  Tarea 2  Tarea 3  ...  Tarea N
```

El WBS permite:
1. **Diseñar y planificar el trabajo**, es decir, visualizar cómo puede definirse y administrarse el trabajo del proyecto.
2. **Diseñar la arquitectura**, esto es, mostrar la relación entre los distintos items del trabajo.
3. **Planificar**, estimar tiempos, esfuerzo y recursos hasta el último nivel.
4. **Informar** el estado de avance.

## Formas de construcción

+ **Top down con equipo completo**: todos los miembros del equipo participan de la descomposición, por lo que este enfoque brinda la oportunidad de que todos presten atención al WBS. Se comienza del nivel 0 (la meta) y se va descomponiendo sucesivamente hasta que los participantes consideren que el trabajo está correctamente definido. Dado que las actividades se definen más en detalle, las estimaciones de costo, tiempo y recursos son más **exactas**. Una vez definidas las actividades, se debe secuenciar. Se debe analizar, además, qué tareas pueden hacerse concurrentemente. 
+ **Top down con subequipos**: es una variante del enfoque anterior en el que el equipo completo SOLO acuerda la partición de primer nivel, requiriendo esto menos tiempo. De esta forma, se crearán tantos subequipos como actividades haya en el nivel 1 y cada grupo particionará una actividad. La idea es que a cada subequipo se le asigne la actividad en la que **más experiencia tenga** y que, si fuera necesario, éste solicitara ayuda externa.
+ **Bottom Up**: al igual que en el enfoque anterior, en este también el equipo completo acuerda la partición de primer nivel y se crean subequipos, en los que a cada uno se le asignará la actividad en la que tenga **más experiencia**. Luego, los integrantes de cada subequipo presentarán **ideas** sobre las tareas que involucra la actividad y clasificarán las que parecieran relacionarse. Por último, se reúne el equipo completo, se presentan los resultados y se discute en conjunto. Esta aproximación tiene la **desventaja** de no definir las tareas con el suficiente grado de **granularidad**.

## ¿Cómo sé que completé una actividad de WBS?

Cada actividad debe poseer 6 características para considerarse completa:
1. **Estado medible**: en cualquier momento se puede determinar el **estado** en que se encuentra.
2. **Acotada**: debe tener un **principio** (evento/fecha inicio) y **fin** (evento/fecha fin).
3. **Producir un entregable**: esto es, algo **tangible** de que la actividad se completó (un documento, una autorización, un producto, etc).
4. **Tiempo y costo estimable**: el tiempo y el costo debe ser fácil de estimar. Cuanto más simple la tarea, más simple de estimar.
5. **Duración aceptable**: no puede durar más de 10 días.
6. **Independiente**: la idea es que una vez que la actividad **empieza** se pueda **continuar razonablemente sin interrupciones** y sin inputs adicionales. El esfuerzo dedicado a la actividad ha de ser continuo.

## ¿Qué tener en cuenta para definir actividades?

Si bien no hay reglas al respecto, el criterio a utilizar puede ser:
+ **Por sustantivos**: en función del entregable. Ejemplo: si ha de construirse un sistema de alumnos, las actividades podrían ser Definición, análisis y diseño.
+ **Por verbos**: en función de las acciones requeridas para producir el entregable. Ejemplo: si ha de construirse un sistema de alumnos, las actividades podrían ser definir alcance, analizar requerimientos y diseñar arquitectura.
+ **Organizacional**: en función de las unidades organizativas que trabajarán en el proyecto. Ejemplo: si ha de construirse un sistema de alumnos, las actividades podrían ser Departamento de alumnos y estudio, Secretaría académica y Departamentos académicos.

## ¿Cómo estimar duración y esfuerzo de actividades?

- **Duración**: tiempo transcurrido en días laborales para finalizar el proyecto. Los feriados, días no laborables o fines de semana NO CUENTAN.
- **Esfuerzo de trabajo**: labor requerida para completar una actividad. La labor puede realizarse en horas consecutivas o no.

La duración es diferente del esfuerzo de trabajo, ya que algo que llevó 10 días (duración), fue realizado en 20 horas laborables (esfuerzo de trabajo). El tiempo transcurrido es diferente del tiempo de trabajo ya que en medio de este último surgen imprevistos, interrupciones, etc.

La duración de una actividad está influenciada por los **recursos** asignados a ésta. Se dice que está influenciada ya que la relación **NO ES LINEAL** entre la cantidad de recursos asignados y la duración de ésta. De hecho, puede llegar un punto, el _crashpoint_ de la actividad, en el que **agregar más recursos aumente la duración de la actividad**. Por lo tanto, si han de asignarse más recursos a un actividad primero debe considerarse que se agregará:
+ N canales de comunicación más a los existentes.
+ El trabajo de coordinar a todas las personas implicadas.
+ Nuevas tareas (capacitación, supervisión, coordinación, etc).
Todo esto podría acarrear nuevos **riesgos**, ya que podría pasar, entre otras cosas, que los recursos no se adaptaran exitosamente a la nueva tarea.

### Variación de la duración

Existen varias causas:
1. **Variación en los perfiles**: dado que la estimación de la duración de una actividad se suele basar en personas con un determinado perfil para ésta, si el perfil es diferente esto afecta a la duración. 
2. **Eventos inesperados**: demoras de proveedores, fallas de energías, enfermedades, etc.
3. **Eficiencia del tiempo de trabajo**: cada vez que un trabajador es **interrumpido**, **le demanda más tiempo volver al nivel de productividad previo al momento de la interrupción**. La idea es, entonces, lograr eficiencia al trabajar de manera focalizada.
4. **Errores e interpretaciones erróneas**: si se entiende mal lo que hay que hacer, esto implica muchas veces perder tiempo en rehacer trabajo ya hecho.

### Métodos de estimación de duración

1. **Similitud con otras actividades**: estimar en base a actividades similares de otros proyectos. Los datos están en la memoria de las personas.
2. **Datos históricos**: idem anterior, pero con una base de datos además de la memoria de las personas.
3. **Juicio experto**: estimar utilizando consultores externos o vendedores con experiencia en la metodología/tecnología. Si el juicio externo se basa en la estimación de vendedores, las estimaciones pueden no ser muy objetivas.
4. **Técnica Delphi**: //PREGUNTAR PROFE
5. **Técnica de 3 puntos**: para esta estimación se utilizan 3 estimaciones:
   + **Optimista**: duración más corta suponiendo que todo ocurre de acuerdo a lo planificado.
   + **Neutra**: duración normal de la actividad.
   + **Pesimista**: duración de la actividad suponiendo que falle todo lo que se previó que puede fallar.

   Aplicar formula: (Optimista + 4 * Media + Pesimista) / 6
6. **Técnica Delphi de banda ancha**: //PREGUNTAR PROFE
