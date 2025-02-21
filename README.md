# 🏠 Predicción de Vista al Mar de Casas con Algoritmos de Aprendizaje Automático Clásico

## Autores

[**Mariana Solano Pineda**](https://www.linkedin.com/in/mariana-solano-pineda/)
Estudiante de economía y administración de empresas Universidad de Los Andes

[**Helen Melissa Margfoy Contreras**](https://www.linkedin.com/in/helenmargfoy/)
Estudiante de Economía y Gobierno y asuntos Públicos Universidad de Los Andes

[**Cristian Oviedo**](https://www.linkedin.com/in/cristian-oviedo-78362524b/)
Estudiante de economía Universidad de Los Andes

[**Tomás Acevedo Echeverría**](https://www.linkedin.com/in/tom%C3%A1s-acevedo-echeverr%C3%ADa-913a35212?trk=contact-info)
Estudiante de economía Universidad de Los Andes

[**Darío Montoya Loor**](https://www.linkedin.com/in/dario-montoya-532071227/)
Estudiante de economía y gobierno Universidad de Los Andes

## 📚 Descripción

Este proyecto aplica algoritmos de **aprendizaje automático clásico** para predecir si una casa tendrá precio alto o bajo, basado en sus características. Se implementan y comparan varios modelos, incluidos **logit básico**, **lasso** y **ridge**. 🏡

## 🎯 Planteamiento del Problema

El problema que aborda este proyecto es predecir si una casa tendrá precio alto o bajo en función de sus características. Este es un **problema supervisado** de **clasificación binaria**, ya que la variable objetivo (`price_category`) es una variable categórica que toma dos valores: **1** si la casa tiene precio alto y **0** si tiene precio bajo. 🎯

El proyecto tiene como meta determinar qué modelo de aprendizaje automático predice mejor si una casa tiene precio alto, basado en sus características estructurales y de ubicación.

## 📂 Contenido del Repositorio

- **Main.ipynb**: El script principal para ejecutar todos los modelos y evaluar su rendimiento.
- **README.md**: Este archivo que estás leyendo. 😄

## 🤖 Algoritmos Implementados

A continuación, se describen los algoritmos implementados en este proyecto:

1. **Logit Básico (Regresión Logística)**: Es un modelo de clasificación binaria que se adapta para predecir si una casa tiene un precio alto o bajo, basado en las características proporcionadas. Utiliza una función sigmoide para transformar las predicciones en probabilidades, y en este caso, la salida es un valor entre 0 y 1 que indica la probabilidad de que una casa pertenezca a la categoría de precio alto.
2. **Lasso (Least Absolute Shrinkage and Selection Operator)**: Es un modelo de regresión lineal regularizada que agrega una penalización sobre los coeficientes del modelo. Esto ayuda a reducir la magnitud de los coeficientes de las variables menos relevantes, forzándolos incluso a cero en algunos casos, lo cual realiza una selección de características. En el contexto de este proyecto, Lasso permite identificar las características más importantes que afectan el precio de la casa, evitando el sobreajuste y mejorando la generalización del modelo.
3. **Ridge**: Similar a Lasso, Ridge es una técnica de regresión lineal regularizada. Sin embargo, a diferencia de Lasso, Ridge penaliza los coeficientes sin forzarlos a cero, lo que significa que todas las características contribuyen al modelo, pero con coeficientes más pequeños. Este enfoque es útil cuando se tienen muchas variables y se desea evitar el sobreajuste sin eliminar ninguna de las características.

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
19. **price_category**: Se añade a la base de datos creando una variable dummy a partir de la media del precio de las casas (1=precio alto, 0)=precio bajo)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

