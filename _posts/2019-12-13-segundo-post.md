---
title: I.-Proceso de la Ingeniería en Software
author: JP
layout: post
---

**Factores de Calidad del Software:** 
 
Es el grado con el que un sistema, componente o proceso cumple los requerimientos especificados y las necesidades o expectativas del cliente o usuario.

Se pueden clasificar en dos grandes grupos (Pressman):

**Medidas Directas** : La medida o medición decimos que es directa, cuando disponemos de un instrumento de medida que nos muestra un resultado (generalmente numérico).
**Medidas Indirectas** : Cuando hablamos de sistemas informáticos no siempre es posible realizar una medida directa, porque no disponemos del instrumento adecuado que nos permita realizar esa medición

**Metricas del Software**

Son las que están relacionadas con el desarrollo del software como funcionalidad, complejidad, eficiencia.

Entre las métricas del software tenemos las siguientes:

1. **Métricas técnicas:**  Se centran en las características del software. Aquí medimos la complejidad lógica y el grado de modularidad del sistema. Mide la estructura del sistema, el cómo está hecho.
2. **Métricas de calidad:**  Son todas las métricas de software que definen de una u otra forma la calidad del software; tales como corrección, exactitud, integridad, facilidad de uso, estructuración o modularidad, pruebas, facilidad de mantenimiento, reusabilidad, cohesión del módulo, acoplamiento del módulo, etc.

    * **Corrección:**  es el grado en que el software desempeña la función para la que fue creado y se mide en defectos por KLDC.
    * **Facilidad de Mantenimiento:**  es la sencillez con que un programa puede corregirse si se encuentra un error, al adaptarse si su entorno cambio o mejorar si el cliente cambia los requisitos y se mide en forma indirecta en TMC (Tiempo Medio de Cambio).
    * **Integridad:**  es la habilidad de un sistema para resistir ataques que requiere la definición de amenaza y seguridad y se calcula: integridad = 1 – (amenaza \* (1 – seguridad)).
    * **Facilidad de uso:** Es el intento por cuantificar la sencillez de una aplicación al utilizarla.

3. **Métricas de Productividad** : Se centran en el rendimiento del proceso de la ingeniería del software. Es decir qué tan productivo va a ser el software que voy a diseñar. Se refiere a las características del software.

4. **Métricas de costo** : se centra en el costo total del sistema informático.

5. **Métricas orientadas al tamaño** : Esta nos permite conocer el tiempo en el que se terminará el software y cuántas personas se necesitan para su desarrollo, aquí medimos las variables con las que desarrollamos el software.

6. **Métricas orientadas a la función o puntos de función:** Son medidas indirectas del software y del proceso por el cual se desarrolla. En lugar de calcular las líneas de código (LDC), las métricas de función se centran en la funcionalidad o utilidad del programa. Los puntos de función nos indican la medida de la productividad.