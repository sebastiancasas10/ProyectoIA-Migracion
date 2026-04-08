# ProyectoIA-Migracion
El presente repositorio contendra todo lo relacionado con nuestro proyecto 
# Determinantes económicos, sociales y demográficos de la migración en Colombia:

## Un enfoque probabilístico y machine learning (2022-2025)

**Autores:**\
Alan Steven Ríos Munar\
Juan Esteban Samaniego Poveda\
Sebastián Casas Poloche

**Universidad Externado de Colombia**\
IA con aplicaciones en economía\
Lina María Castro\
2026

------------------------------------------------------------------------

## Objetivo

Determinar qué factores económicos, demográficos y sociales son
causantes de la migración interna del país y cuál es la probabilidad de
migración de los ciudadanos colombianos, tanto entre departamentos como
municipios.

Identificar:

-   Regiones con mayor concentración de flujos de entrada y salida.
-   Causas del desplazamiento.
-   Probabilidad de migración hacia otra región.

------------------------------------------------------------------------

## Descripción

Desarrollar un modelo que permita caracterizar las principales variables
que producen migración en el territorio nacional y la probabilidad de
que una persona migre a otra región del país, mediante el análisis y
comparación de diferentes modelos probabilísticos.

Se utilizará:

-   KNN para agrupar personas que compartan características similares.
-   Mapas de calor para visualizar el flujo de migrantes a nivel
    departamental y municipal.

Clasificando los departamentos y municipios con mayor movilidad de
personas y con mayor probabilidad de migración.

------------------------------------------------------------------------

## Desafíos

Unir en una sola base de datos la GEIH (Gran Encuesta Integrada de
Hogares) realizada por el DANE de los años 2023, 2024 y 2025.

Considerando que:

-   La información está dada por meses.
-   Cada encuesta representa un año específico.

Con el fin de aumentar la efectividad en la predicción de la
probabilidad de migración y sus causas.

------------------------------------------------------------------------

## Entrega de Valor

El proyecto aporta una innovación metodológica y aplicada al estudio de
la migración interna en Colombia al integrar:

-   Modelos probabilísticos.
-   Machine learning.
-   Análisis espacial.
-   Unificación de la GEIH 2023-2025.

A diferencia de estudios de causalidad, la investigación:

-   Estima la probabilidad individual de migración interna.
-   Identifica perfiles migratorios mediante KNN.
-   Compara distintos modelos probabilísticos según capacidad
    predictiva.
-   Incorpora análisis territorial con mapas de calor y flujos
    interregionales.

------------------------------------------------------------------------

## Stakeholders

-   Ministerio de Trabajo
-   Planeación Nacional
-   Gobernaciones
-   Alcaldías
-   Programas de desarrollo regional
-   Planeación urbana

------------------------------------------------------------------------

## Técnicas que se utilizarán

-   Análisis exploratorio de datos
-   Clustering
-   Machine learning
-   Modelos probabilísticos
-   Análisis espacial
-   Integración y transformación de datos

------------------------------------------------------------------------

## Fuentes de Datos

### Gran Encuesta Integrada de Hogares (GEIH) 2023-2025

### Banco de la República

-   Indicadores regionales de actividad económica
-   Desempleo regional
-   Informes económicos departamentales

### Departamento Administrativo Nacional de Estadística (DANE)

-   PIB departamental
-   Tasa de desempleo por ciudad
-   Índice de pobreza monetaria
-   Índice de pobreza multidimensional

------------------------------------------------------------------------

## Variables

### Demográficas

-   Edad
-   Sexo
-   Tamaño del hogar
-   Estado civil

### Socioeconómicas

-   Ingresos
-   Condición laboral
-   Tipo de ocupación
-   Formalidad / informalidad
-   Nivel educativo

### Territoriales

-   Cambio de municipio de residencia
-   Municipio de residencia anterior

### Migración

-   Migración reciente (últimos 12 meses)
-   Motivo de migración

### Violencia

-   Desplazamiento por violencia asociada al conflicto armado
-   Desplazamiento por violencia no asociada al conflicto armado
-   Motivo de migración por inseguridad o amenazas
