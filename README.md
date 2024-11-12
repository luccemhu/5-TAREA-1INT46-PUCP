# [5-TAREA-1INT46-PUCP](https://luccemhu.github.io/5-TAREA-1INT46-PUCP/)
Integrantes:

Joel B. Huamani Ccallocunto - 20196510
Luis E. Valverde Ramos - 20191930

Github Pages: https://luccemhu.github.io/5-TAREA-1INT46-PUCP/
Repositorio: https://github.com/luccemhu/5-TAREA-1INT46-PUCP

# Análisis de Eficiencia y Optimización en el Sector Público

Este repositorio presenta tres temas principales de análisis aplicados a problemas reales del sector público, utilizando diversas herramientas de optimización y evaluación de eficiencia. Los ejercicios incluyen problemas clásicos de optimización, toma de decisiones multicriterio y benchmarking de eficiencia en instituciones.

## Índice

1. [Parte 1: Maximización/Minimización](#parte-1-maximizaciónminimización)
    - [Ejercicio 1.1: El problema de la dieta](#ejercicio-11-el-problema-de-la-dieta)
    - [Ejercicio 1.2: El problema de la programación](#ejercicio-12-el-problema-de-la-programación)
2. [Parte 2: Toma de Decisiones Multicriterio](#parte-2-toma-de-decisiones-multicriterio)
    - [Ejercicio 2.1: Elegir un país para un programa de maestría](#ejercicio-21-elegir-un-país-para-un-programa-de-maestría)
3. [Parte 3: Benchmarking](#parte-3-benchmarking)

## Parte 1: Maximización/Minimización

Esta parte se enfoca en resolver dos problemas clásicos de optimización: **El problema de la dieta** y **El problema de la programación**. Ambos utilizan técnicas de programación lineal para maximizar o minimizar una función objetivo bajo ciertas restricciones.

### Ejercicio 1.1: El problema de la dieta

El **problema de la dieta** es un problema de optimización donde se busca minimizar el costo de los alimentos mientras se satisfacen los requisitos nutricionales necesarios. Este problema se puede resolver utilizando programación lineal, donde las variables son las cantidades de cada alimento que se deben consumir, y las restricciones son los requisitos nutricionales (calorías, vitaminas, minerales, etc.).

**Objetivos**:
- Minimizar el costo de la dieta.
- Satisfacer las necesidades nutricionales del consumidor.

### Ejercicio 1.2: El problema de la programación

El **problema de la programación** tiene como objetivo asignar tareas a un conjunto de trabajadores de manera eficiente. Este ejercicio busca minimizar el tiempo total de trabajo, considerando restricciones como las horas disponibles de los trabajadores y las duraciones de las tareas.

**Objetivos**:
- Minimizar el tiempo total necesario para completar todas las tareas.
- Asignar correctamente las tareas a los trabajadores.

## Parte 2: Toma de Decisiones Multicriterio

En esta parte, se exploran métodos de toma de decisiones multicriterio, donde se deben tomar decisiones considerando varios criterios, no solo uno.

### Ejercicio 2.1: Elegir un país para un programa de maestría

Este ejercicio aborda la selección de un país para estudiar un programa de maestría. Se utilizan criterios como el costo de vida, la calidad educativa, las oportunidades laborales post-graduación, y la calidad de vida en general. El objetivo es clasificar los países según estos criterios y tomar una decisión basada en la evaluación multicriterio.

**Criterios**:
- Costo de vida.
- Calidad educativa.
- Oportunidades laborales post-graduación.
- Calidad de vida.

## Parte 3: Benchmarking

La última parte de este repositorio se dedica a evaluar la **eficiencia de diversas entidades públicas** utilizando el concepto de benchmarking. El análisis se realiza sobre un conjunto de datos de municipios, donde se comparan indicadores de eficiencia, como la relación entre ingresos y gastos, y el número de residuos gestionados por personal de limpieza.

### Ejercicio 3.1: Evaluación de eficiencia en el sector público

Este ejercicio se centra en la evaluación de eficiencia en el sector público, aplicando el método de **Data Envelopment Analysis (DEA)**. Se usan indicadores como los ingresos, los gastos y el personal de limpieza para evaluar la eficiencia de diferentes municipios. Se utiliza el paquete `Pyfrontier` para realizar este análisis.

**Objetivos**:
- Calcular la eficiencia de los municipios.
- Visualizar los resultados en gráficos de frontera.
- Realizar un análisis de los municipios más eficientes en términos de gastos, ingresos y residuos gestionados.

## Cómo ejecutar los ejercicios

1. **Clonar este repositorio**:

   ```bash
   git clone https://github.com/tuusuario/analisis-eficiencia-publica.git
