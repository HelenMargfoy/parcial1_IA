# 🏠 Predicción de Vista al Mar de Casas con Algoritmos de Aprendizaje Automático Clásico

## Autores

[**Mariana Solano Pineda**](https://www.linkedin.com/in/mariana-solano-pineda/)
Estudiante de economía y administración de empresas Universidad de Los Andes

[**Helen Melissa Margfoy Contreras**](https://www.linkedin.com/in/helenmargfoy/)
Estudiante de Economía y Gobierno y asuntos Públicos  Universidad de Los Andes

[**Cristian Oviedo**](https://www.linkedin.com/in/cristian-oviedo-78362524b/)
Estudiante de economía Universidad de Los Andes

## 📚 Descripción

Este proyecto aplica algoritmos de **aprendizaje automático clásico** para predecir si una casa tendrá **vista al mar** o no, basado en sus características. Se implementan y comparan varios modelos, incluidos **regresión logística**, **SVM**, **K-means** y **algoritmos basados en árboles**. 🌊🏡

## 🎯 Planteamiento del Problema

El problema que aborda este proyecto es predecir si una casa tendrá **vista al mar** (sí o no) en función de sus características. Este es un **problema supervisado** de **clasificación binaria**, ya que la variable objetivo (`waterfront`) es una variable categórica que toma dos valores: **1** si la casa tiene vista al mar y **0** si no la tiene. 🎯

El proyecto tiene como meta determinar qué modelo de aprendizaje automático predice mejor si una casa tiene vista al mar, basado en sus características estructurales y de ubicación. 🌊

## 📂 Contenido del Repositorio

- **Main.ipynb**: El script principal para ejecutar todos los modelos y evaluar su rendimiento.
- **README.md**: Este archivo que estás leyendo. 😄

## 🤖 Algoritmos Implementados

A continuación, se describen los algoritmos implementados en este proyecto:

1. **Regresión Logística**: Aunque es un modelo de clasificación binaria, se adapta para predecir si una casa pertenece a la categoría de precio alto o bajo.
2. **Support Vector Machines (SVM)**: Algoritmo que busca encontrar el hiperplano óptimo que divide los datos en clases.
3. **K-Means**: Un algoritmo de agrupamiento no supervisado utilizado para agrupar las casas en clústeres según sus características. Este enfoque puede ayudar a identificar categorías de precios.
4. **Árboles de Decisión y Random Forest**: Algoritmos basados en árboles que aprenden a predecir el precio de una casa según reglas extraídas de los datos.

## 🔍 Variables de la base de datos
 
A continuación se describen las variables del conjunto de datos utilizado en este proyecto:

1. **date**: Fecha de venta de la casa (tipo de dato: cadena de texto).
2. **price**: Precio de la casa (tipo de dato: flotante).
3. **bedrooms**: Número de dormitorios de la casa (tipo de dato: entero).
4. **bathrooms**: Número de baños de la casa (tipo de dato: flotante).
5. **sqft_living**: Metros cuadrados de área habitable (tipo de dato: entero).
6. **sqft_lot**: Tamaño del lote en metros cuadrados (tipo de dato: entero).
7. **floors**: Número de pisos de la casa (tipo de dato: flotante).
8. **waterfront**: Si la casa tiene vista al mar (1 = sí, 0 = no; tipo de dato: entero).
9. **view**: Calificación de la vista (valor entero entre 0 y 4).
10. **condition**: Condición general de la casa (valor entero entre 1 y 5).
11. **sqft_above**: Área habitable sobre el nivel del suelo (tipo de dato: entero).
12. **sqft_basement**: Área del sótano (tipo de dato: entero).
13. **yr_built**: Año de construcción de la casa (tipo de dato: entero).
14. **yr_renovated**: Año de renovación de la casa (tipo de dato: entero).
15. **street**: Dirección de la calle (tipo de dato: texto).
16. **city**: Ciudad donde se encuentra la casa (tipo de dato: texto).
17. **statezip**: Código postal y estado (tipo de dato: texto).
18. **country**: País donde se encuentra la casa (valor fijo "USA"; tipo de dato: texto).

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

