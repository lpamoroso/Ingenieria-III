# Práctica 1 - Calidad de Software (Parte A)

## Parte I: Conceptos generales

1. Describir con sus palabras qué entiende por Calidad.

    La calidad puede definirse como el grado de satisfacción producida o percibida por un elemento (tangible o intangible) a través de distintas características que lo definen, componen o los efectos que este produce mediante su uso u obtención.

2. Cada uno de los denominados gurús(o padres) de la calidad han creado o instaurado algún programa, término o proceso que los ha colocado en ese lugar. Investigue y explique con sus palabras el aporte realizado por cada uno de los gurús mencionados en la teoría.
3. Explique con sus palabras qué es la Calidad del software y cómo se divide.

    Es el valor que los usuarios o clientes dan a un producto de software, según este satisfaga sus necesidades. Este producto a su vez es el resultado de un proceso de desarrollo, el cual condiciona la calidad del software. Se divide en:
    - Calidad del producto obtenido.
    - Calidad del proceso de desarrollo: es decir, que el proceso produzca los resultados esperados en base al producto que se desea lograr, siendo los procesos, basados en una correcta definición y que estos sean mejorados en función de los objetivos de negocio.

4. ¿Cómo se diferencian los términos Norma y Estándar? Explique.

    La diferencia es que se denomina norma a una regla que se debe seguir o a que se deben ajustar las conductas, tareas o actividades. La norma es un término fuerte, define las pautas a seguir. Un estándar es un modelo, patrón o referencia a tomar. Más que una regla, es una sugerencia.

## Parte II: Calidad de Producto

5. Describa el concepto de Calidad de Producto de software.

    Si bien la calidad es un concepto vago y subjetivo, a priori puede definirse como la capacidad de un producto de software para servir satisfactoriamente a los propósitos del usuario mediante su utilización, conformando completamente los requisitos explícitos e implícitos del cliente, manteniendo la ausencia de defectos e imperfecciones.

6. Explique cuáles son los pasos a seguir para realizar una evaluación siguiendo el proceso de evaluación definido en la norma ISO/IEC 14598.
7. Describa el Modelo de Calidad de la ISO/IEC 9126.

    * Funcionalidad

        + Aplicabilidad: la capacidad del software para proveer un conjunto apropiado de funciones para las tareas y objetivos especificados por el usuario.
        + Precisión: capacidad del software de proveer los resultados correctos o convenidos con el grado de precisión necesarios.
        + Interoperabilidad: capacidad del software para interactuar con uno o mas sistemas especificados.
        + Seguridad: capacidad del software para proteger la información y los datos de modo que las personas o los sistemas no autorizados no puedan leerlos o modificarlos y a las personas o sistemas autorizados no se les denegará el acceso.
        + Conformidad de funcionalidad: capacidad de adherir a estándares, convenciones o regulaciones legales y prescripciones similares referente a la funcionalidad.

    * Fiabilidad

        + Madurez: capacidad del software para evitar fallas como resultado de errores en el software.
        + Recuperabilidad: capacidad del software de reestablecer un nivel de rendimiento y recuperar datos directamente afectados en el caso de una falla.
        + Tolerancia a fallas: capacidad del software de mantener un nivel especificado de rendimiento en casos de fallas del software.
        + Conformidad de fiabilidad: capacidad del software para adherirse a las normas, convenciones o regulaciones relativas a la fiabilidad.

    * Usabilidad

        + Comprensibilidad: capacidad del software para permitir al usuario entender si el software es aplicable, y cómo puede ser utilizado para las tareas y las condiciones particulares de la aplicación.
        + Capacidad de aprendizaje: la capacidad del software para permitir al usuario aprender su aplicación.
        + Operabilidad: capacidad del software para permitir al usuario operarlo y controlarlo.
        + Atractividad: capacidad del software de ser atractivo al usuario.
        + Conformidad de usabilidad: capacidad del producto software para adherirse a las normas, convenciones, guías de estilo o regulaciones relacionadas a su usabilidad.

    * Eficiencia

        + Comportamiento en el tiempo: capacidad del software para proveer tiempos apropiados de respuesta y procesamiento, y ratios de rendimiento cuando realiza su función bajo las condiciones establecidas.
        + Utilización de recursos: capacidad del producto software para utilizar apropiadas cantidades y tipos de recursos cuando éste funciona bajo las condiciones establecidas.
        + Conformidad de eficiencia: capacidad del producto software para adherirse a normas o convenciones relacionadas a la eficiencia.

    * Facilidad de Mantenimiento

        + Analizabilidad: capacidad del software para ser diagnosticado por deficiencias o causas de fallas en el software o la identificación de las partes a ser modificadas.
        + Cambiabilidad: capacidad del software para permitir que una determinada modificación sea implementada.
        + Estabilidad: capacidad del software para evitar efectos inesperados debido a modificaciones del software.
        + Testeabilidad: capacidad del software para permitir que las modificaciones puedan ser validadas.
        + Conformidad de facilidad de mantenimiento: capacidad del software para adherirse a estándares o convenciones relativas a la facilidad de mantenimiento.

    * Portabilidad

        + Adaptabilidad: capacidad del software para ser adaptado a diferentes entornos definidos sin aplicar acciones o medios diferentes de los previstos para el propósito del software considerado.
        + Instalabilidad: capacidad del software para ser instalado en un entorno definido.
        + Co-existencia: capacidad del software para co-existir con otro producto software independiente dentro de un mismo entorno compartiendo recursos comunes.
        + Reemplazabilidad: capacidad del software para ser utilizado en lugar de otro producto software, para el mismo propósito y en el mismo entorno.
        + Conformidad de portabilidad: capacidad del software para adherirse a estándares o convenciones relacionados a la portabilidad.

8. Enumere las características que presenta la ISO/IEC 9126-1.

    Atributos de la calidad interna/externa:
    * Funcionalidad.
    * Fiabilidad.
    * Facilidad de uso.
    * Eficiencia.
    * Mantenibilidad.
    * Portabilidad.

    Atributos de la calidad de uso:
    * Efectividad.
    * Productividad.
    * Seguridad de acceso.
    * Satisfacción.

9. Las métricas de la ISO/IEC 9126-2 están definidas en forma de tabla. Explique cuáles son los componentes de esta tabla y qué criterios brinda la norma para la creación de nuevas métricas.

    * Nombre de métrica: las métricas correspondiente en la tabla de las métricas interna y externa tienen nombres similares.
    * Propósito de la métrica: están expresados como una pregunta a ser respondida por la aplicación de la métrica.
    * Método de aplicación: provee un contorno de la aplicación.
    * Medición, fórmula y cálculos de elementos de datos: provee la fórmula de medida y explica el significado de los elementos de dato usados.
    * Interpretación del valor medido: provee el rango y los valores preferidos.
    * Tipo de escala métrica: tipo de escala usada por la métrica. Los tipos de escalas usadas son; escala nominal, escala ordinal, escala de intervalo, escala de proporción y escala absoluta.
    * Tipo de Medida: los tipos usados son; tipo de tamaño(tamaño de la función o tamaño de la fuente, por ejemplo), tipo del tiempo(tiempo transcurrido o tiempo de usuario, por ejemplo) o tipo de cuenta(número de cambios o número de fallos, por ejemplo).

    //qué criterios brinda la norma para la creación de nuevas métricas

10. Mencione cuáles son los niveles de puntuación de las métricas.

    Si bien existen niveles de puntuación generales definidos por ISO, que suelen tomarse en cuenta, lo cierto es que no existe una escala general, dado que la calidad está asociada a necesidades dadas, las cuales varían de una evaluación a otra, por lo que debe establecerse una escala para cada evaluación. Un ejemplo podría ser inaceptable, mínimamente aceptable, rango al que se apunta y con requerimientos excedidos, donde inaceptable se considera como insatisfactorio y el resto de las escalas como satisfactorio.

11. Explique de qué forma se deben combinar los niveles de las métricas para establecer los niveles de las características y de evaluación.

    La forma en que se combinan es estableciendo cuál de los niveles de puntuación se considera satisfactorio o no, y definiendo qué características debe o debería proveer el software para considerarlo como tal o cual nivel. De esta manera, se puede llegar a medir qué se considera peor caso, a qué es a lo que se apunta y en dónde, en ese intervalo, el proyecto se encuentra.

12. Explique cómo se conforma la familia ISO/IEC 25000 (SQuaRE).
13. ¿Qué norma de la familia ISO/IEC 25000 reemplaza a la ISO/IEC 9126-1? Explique las diferencias.
14. ¿Qué norma de la familia ISO/IEC 25000 reemplaza a la ISO/IEC 14598? Explique las diferencias.

## Parte III: Calidad de Datos

15. Describa el concepto de Calidad de Datos IS0/IEC 25012.
16. Defina la clasificación propuesta por el modelo.