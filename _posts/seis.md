---
title: II.-Modelos de desarrollos; tradicionales vs alternativos
author: JP
layout: post
---
**MODELO GENERAL DEL PROCESO DE DESARROLLO DE SOFTWARE**

Los modelos de proceso de desarrollo de software incluyen los requisitos del sistema como entrada y un producto entregado como salida

- **Especificación**

Formulación de los requisitos y restricciones del sistema

- **Diseño**

Elaboración de un documento con el modelo del sistema

- **Fabricación**

Construcción del sistema

- **Prueba**

Comprobación de que el sistema cumple las especificaciones requeridas

- **Instalación**

Entrega del sistema al cliente y garantía de que es operativo

- **Mantenimiento**

Reparación de los fallos que aparecen en el sistema

En el proceso de construcción de sistemas informáticos se pueden distinguir tres fases genéricas:

- **Fase de definición**
  - Se identifican los requisitos claves del sistema y del software
  - Se desarrolla
    - Un Análisis de Sistemas
      - Se define el papel de cada elemento en el sistema automatizado de información, incluyendo el que jugará el software
    - Un Análisis de Requisitos
      - Se especifican todos los requisitos de usuario que el sistema tiene que satisfacer
      - Esta fase está orientada al **QUÉ**
        - Qué información ha de ser procesada, qué función y rendimiento se desea, qué interfaces han de establecerse, qué ligaduras de diseño existen y qué criterios de validación se necesitan para definir un sistema correcto
  - Existe un paso complementario: la planificación del proyecto software:
    - Se asignan los recursos
    - Se estiman los costos
    - Se planifican las tareas y el trabajo
- **Fase de desarrollo**
  - Fase orientada al **CÓMO**
  - El primer paso de esta fase corresponde al Diseño del Software
    - Se trasladan los requisitos del software a un conjunto de representaciones que describen la estructura de datos, arquitectura del software y procedimientos algorítmicos que permiten la construcción física de dicho software.
  - Los otros dos pasos de la fase de desarrollo corresponden a la **Codificación** y a la **Prueba del Software**
- **Fase de mantenimiento**
  - Mantenimiento correctivo
    - Corrección de errores
  - Mantenimiento adaptativo
    - Adaptaciones requeridas por la evolución del entorno del software
  - Mantenimiento perfectivo
    - Las modificaciones debidas a los cambios de requisitos del usuario para mejorar el sistema
  - Mantenimiento preventivo
    - Mejora de las características internas del producto para hacer más mantenible

**MODELOS DE PROCESOS**

El modelo de cascada
  - Modelo de Plan-impulsado. Fases separadas y distintas de especificación y desarrollo.

Las fases están identificadas por separado:

  - El análisis  y definición de requerimientos
  - Diseño del sistema y software.
  - Pruebas de implementación de unidades
  - Integración y pruebas del sistema
  - Operación y mantenimiento

El principal inconveniente del modelo de la cascada es la dificultad de acomodar el cambio después de que está en marcha el proceso. En principio, una fase tiene que ser completada antes de pasar a la siguiente fase.

**Problemas del Modelo de Cascada:**

  - Inflexible división del proyecto en fases distintas hace que sea difícil responder a las necesidades cambiantes de los clientes.
  - Por lo tanto, este modelo sólo es apropiado cuando los requisitos son bien entendidos y los cambios serán bastante limitados durante el proceso de diseño.
  - Pocos sistemas tienen requisitos estables.
  - El modelo de cascada se utiliza sobre todo para los grandes proyectos de ingeniería de sistemas en que un sistema se desarrolla en varios lugares

**El desarrollo incremental**

Especificación, desarrollo y validación se intercalan. Puede ser el plan impulsado o ágil.

- **Beneficios:**
  - El costo de atender las necesidades cambiantes de los clientes se reduce.
    - La cantidad de análisis y la documentación que tiene que ser hecho de nuevo es mucho menor que la que se requiere con el modelo de cascada.
  - Es más fácil obtener retroalimentación de los clientes en el trabajo de desarrollo que se ha hecho.
    - Los clientes pueden hacer comentarios sobre las manifestaciones del software y ver cuánto se ha implementado.
  - Más rápida entrega y despliegue de software de utilidad para el cliente es posible.
    - Los clientes pueden usar y obtener valor a partir del software anterior que es posible con un proceso de cascada.
- **Problemas** :
  - El proceso no es visible.
    - Los gerentes necesitan entregas regulares para medir el progreso. Si se desarrollan rápidamente los sistemas, no es rentable para producir documentos que reflejen todas las versiones del sistema.
  - Estructura del sistema tiende a degradarse a medida que se añaden nuevos incrementos.
    - A menos tiempo y dinero que se gasta en la refactorización para mejorar el software, cambio regular tiende a corromper su estructura. La incorporación de nuevos cambios de software se vuelve cada vez más difícil y costoso.

ESPIRAL

Es un modelo de ciclo de vida desarrollado por Barry Boehm en 1988.

  - Las actividades de este modelo son una espiral, cada bucle es una actividad.
  - Las actividades no están fijadas a prioridad, sino que las siguientes se eligen en función del análisis de riesgo, comenzando por el bucle interior.
  - En este modelo, el esfuerzo de desarrollo es iterativo. Tan pronto como uno completa un esfuerzo de desarrollo, otro comienza. Además, en cada desarrollo ejecutado, puedes seguir estos cuatros pasos.

  1. Determinar qué quieres lograr.
  2. Determinar las rutas alternativas que puedes tomar para lograr estas metas. Por cada una, analizar los riesgos y resultados finales, y seleccionar la mejor.
  3. Seguir la alternativa seleccionada en el paso 2.
  4. Establecer qué tienes terminado.

El Modelo Espiral mejora el Modelo de Cascada enfatizando la naturaleza iterativa del proceso de diseño. Eso introduce un ciclo de prototipo iterativo. En cada iteración, las nuevas expresiones que son obtenidas transformando otras dadas son examinadas para ver si representan progresos hacia el objetivo.

**Actividades principales:**

  - **Primer Paso**. Identificación de:
    - Los objetivos de la parte del producto que está siendo elaborada (rendimientos, funcionalidad, adaptación al cambio, etc.).
    - Las alternativas principales de la implementación de esta porción del producto (usar el diseño A, usar el diseño B, reutilizar el módulo X de la aplicación Z, comprar a un proveedor externo, etc.).
    - Las restricciones impuestas para cada alternativa (costes, planificaciones, interfaces, etc.).
  - **Segundo paso**.
    - Evaluar las diferentes alternativas que se plantean teniendo en cuenta los objetivos a conseguir y las restricciones impuestas. Frecuentemente, este paso identifica las áreas de incertidumbre del proyecto con sus correspondientes riesgos.
    - Si existen riesgos, lo siguiente es la formulación de una estrategia efectiva en coste (utilizando prototipos, simulación, bancos de prueba, cuestionario para los usuarios, modelización analítica o combinaciones de éstas y otras técnicas de resolución de riesgos) para resolver dichos riesgos.
  - **Tercer paso**. Consiste en desarrollar, verificar y validar (probar):
    - Tareas de la actividad propia y de prueba.
    - Análisis de alternativas e identificación resolución de riesgos.
    - Dependiendo del resultado de la evaluación de los riesgos, se elige un modelo para el desarrollo, el que puede ser cualquiera de los otros existentes, como formal, evolutivo, cascada, etc.
  - **Cuarto paso.** Revisar todo lo hecho, evaluándolo, y con ello decidir si se continúa con las fases siguientes y planificar la próxima actividad.

**Características:**

  - En cada giro se construye un nuevo modelo del sistema completo.
  - Este modelo puede combinarse con otros modelos de proceso de desarrollo (cascada, evolutivo).
  - Mejor modelo para el desarrollo de grandes sistemas.
  - El análisis de riesgo requiere la participación de personal  altamente calificado.

DESARROLLO RAPIDO DE APLICACIONES

Es un modelo de proceso del ciclo de vida clásico que enfatiza un ciclo de vida de desarrollo extremadamente corto.

El modelo DRA es una adaptación a alta velocidad del ciclo de vida clásico en el que se logra el desarrollo rápido utilizando un enfoque de construcción basado en componentes. Si se comprenden bien los requisitos y se limita el ámbito del proyecto, el proceso DRA permite al equipo de desarrollo crear un sistema completamente funcional dentro de períodos cortos de tiempo.

Cuando se utiliza principalmente para aplicaciones de sistemas de información, el enfoque DRA comprende las siguientes fases:

- **Modelado de gestión:** El flujo de información entre las funciones de gestión se modela de forma que responda a las siguientes preguntas: ¿Qué información conduce el proceso de gestión? ¿Qué información se genera? ¿Quién la genera? ¿A dónde va la información? ¿Quién la procesa?
- **Modelado de datos:** El flujo de información definido como parte de la fase de modelado de gestión refina como un conjunto de objetos de datos necesarios para apoyar la empresa. Se definen las características de cada uno de los objetos y relaciones entre estos objetos.
- **Modelado de procesos:** Los objetos de datos definidos en la fase de modelado de datos quedan transformados para lograr el flujo de información necesario para implementar una función de gestión. Las descripciones se crean para añadir, modificar, suprimir, o recuperar un objeto de datos.
- **Generación de aplicaciones:** El DRA asume la utilización de técnicas de cuarta generación. En lugar de crear software con lenguajes de programación de tercera generación, el proceso DRA trabaja para volver a utilizar componentes de programas ya existentes (cuando es posible) o a crear componentes reutilizables (cuando sea necesario). En todos los casos se utilizan herramientas automáticas para facilitar la construcción del software.
- **Prueba y entrega:** Como el proceso DRA enfatiza la reutilización, ya se han comprobado muchos de los componentes de los programas. Esto reduce tiempo de pruebas. Sin embargo, se deben probar todos los componentes nuevos y se deben ejercitar todas las interfaces a fondo.

**Problemas (i)**:

-
  - Para proyectos grandes aunque por escalas, el DRA requiere recursos humanos suficientes como para crear el número correcto de equipos DRA.
  - DRA requiere clientes y desarrolladores comprometidos en las rápidas actividades necesarias para completar un sistema en un marco de tiempo abreviado. Si no hay compromiso, por ninguna de las partes constituyentes, los proyectos DRA fracasarán.
  - No todos los tipos de aplicaciones son apropiados para DRA.
  - Si un sistema no puede modularizarse adecuadamente, la construcción de los componentes necesarios para DRA será problemático.
  - Si está en juego el alto rendimiento, y se va a conseguir el rendimiento convirtiendo interfaces en componentes de sistemas, el modelo DRA puede que no funcione.

**ORIENTADOS A LA REUTILIZACION**

Esta aproximación se basa en la existencia de un número significativo de elementos reutilizables. El proceso de desarrollo, se centra en la integración de estos elementos en un sistema, en lugar de desarrollarlo desde cero.

Incorpora muchas características del modelo en espiral. Es evolutivo por naturaleza.

El proceso tiende a estructurarse en dos subprocesos distintos y separados:

- **El desarrollo para reutilización:** construcción de elementos reutilizables dentro de un dominio concreto.
- **El desarrollo con reutilización:** construcción de aplicaciones utilizando elementos reutilizables.
- Etapas del proceso

- Análisis de los componentes;
- Requisitos de modificación;
- Configuración del sistema con la reutilización;
- Desarrollo e integración.

- La reutilización es ahora el enfoque estándar para la construcción de muchos tipos de sistemas de negocio

**ORIENTADO A OBJETOS**

El modelo orientado a objetos utiliza el paradigma de la orientación a objetos para el desarrollo de software.

Este enfoque realiza la construcción de modelos de un sistema por medio de la identificación y la especificación de un conjunto de objetos relacionados, que colaboran entre si de acuerdo a los requerimientos establecidos para el sistema de objetos.

La definición del modelado orientado a objetos puede claramente dividir el enfoque en tres dimensiones:

- La dimensión estructural.
- La dimensión dinámica.
- La dimisión funcional.

Este tipo de modelado implica la realización de las siguientes actividades:


1. Identificar las clases, modelos y objetos. (objetos y atributos).
2. Asociar estáticamente los objetos. (relaciones dependientes del dominio del problema).
3. Especificación del comportamiento de los objetos. (Definir como se comportaran los objetos).
4. Definir la jerarquía de herencia de las clases. (Definir la jerarquía de clases, para que el sistema quede lo más abstracto posible).

**Características** :

1. EL modelado Orientado a Objetos está basado en el paradigma orientado a objetos.
2. Trata el almacenamiento de objetos (persistencia de los objetos).
3. Define un lenguaje para le definición y manipulación de objetos.
4. Incluye mecanismos para optimizar el acceso (Indexación y Clustering), el control de la concurrencia, seguridad y gestión de usuarios, facilidad de consulta y recuperación ante fallos.
5. Debido a que es un esquema orientado a objetos incluye: Encapsulamiento, herencia, polimorfismo, etc.

**PROCESOS AGILES**

Cualquier proceso del software ágil se caracteriza por la forma en la que aborda cierto número de suposiciones clave [Fow02] acerca de la mayoría de proyectos de software:

1. Es difícil predecir qué requerimientos de software persistirán y cuáles cambiarán. También es difícil pronosticar cómo cambiarán las prioridades del cliente a medida que avanza el proyecto.
    2. Para muchos tipos de software, el diseño y la construcción están imbricados.
    3. El análisis, el diseño, la construcción y las pruebas no son tan predecibles como nos gustaría (desde un punto de vista de planeación).

Un proceso de software ágil debe adaptarse incrementalmente. Para lograr la adaptación incremental, un equipo ágil requiere retroalimentación con el cliente (de modo que sea posible hacer las adaptaciones apropiadas).

Un catalizador eficaz para la retroalimentación con el cliente es un prototipo operativo o una porción de un sistema operativo. – Qué estrategia se debe aplicar?

Este enfoque iterativo permite que el cliente evalúe en forma regular el incremento de software, dé la retroalimentación necesaria al equipo de software e influya en las adaptaciones del proceso que se realicen para aprovechar la retroalimentación.

**Factores Humanos**:

&quot;El desarrollo ágil se centra en los talentos y habilidades de los individuos, y adapta el proceso a personas y equipos específicos.&quot;

  - **Competencia**. En un contexto de desarrollo ágil (así como en la ingeniería de software), la &quot;competencia&quot; incluye el talento innato, las habilidades específicas relacionadas con el software y el conocimiento general del proceso que el equipo haya elegido aplicar.
  - **Enfoque común.** Aunque los miembros del equipo ágil realicen diferentes tareas y aporten habilidades distintas al proyecto, todos deben centrarse en una meta: entregar al cliente en la fecha prometida un incremento de software que funcione.
  - **Colaboración**. La ingeniería de software (sin importar el proceso) trata de evaluar, analizar y usar la información que se comunica al equipo de software; crear información que ayudará a todos los participantes a entender el trabajo del equipo; y generar información (software de cómputo y bases de datos relevantes) que aporten al cliente valor del negocio. Para efectuar estas tareas, los miembros del equipo deben colaborar, entre sí y con todos los participantes.
  - **Habilidad para tomar decisiones.** Cualquier equipo bueno de software (incluso los equipos ágiles) debe tener libertad para controlar su destino.
  - **Capacidad para resolver problemas difusos.** Los gerentes de software deben reconocer que el equipo ágil tendrá que tratar en forma continua con la ambigüedad y que será sacudido de manera permanente por el cambio.
  - Confianza y respeto mutuos. El equipo ágil debe convertirse en un equipo &quot;pegado&quot;. Un equipo pegado tiene la confianza y respeto que son necesarios para hacer &quot;su tejido tan fuerte que el todo es más que la suma de sus partes&quot; [DeM98].
  - **Organización propia.** En el contexto del desarrollo ágil, la organización propia implica tres cosas:
  1. El equipo ágil se organiza a sí mismo para hacer el trabajo,
  2. El equipo organiza el proceso que se adapte mejor a su ambiente local,
  3. El equipo organiza la programación del trabajo a fin de que se logre del mejor modo posible la entrega del incremento de software.