# 📊 Taller Práctico de Pandas y Operaciones Matemáticas

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange)
![Estado](https://img.shields.io/badge/Estado-Completado-success)

---

#  Introducción

## ¿Qué es Pandas?

Pandas es una biblioteca de código abierto para Python que facilita la gestión y el análisis de datos estructurados. Gracias a sus herramientas, es posible organizar grandes volúmenes de información en tablas, realizar consultas, transformar datos y obtener resultados de manera rápida y eficiente.

Algunas de sus aplicaciones más comunes son:

- Análisis de datos
- Limpieza de información
- Procesamiento de archivos Excel y CSV
- Creación de reportes
- Estadística descriptiva

---

## ¿Qué es NumPy?

NumPy (Numerical Python) es una biblioteca especializada en el manejo de arreglos y operaciones matemáticas de alto rendimiento. Permite realizar cálculos complejos de forma eficiente, siendo una herramienta fundamental para áreas como análisis de datos, inteligencia artificial y computación científica.

Entre sus principales características se encuentran:

- Manejo de vectores y matrices
- Operaciones matemáticas avanzadas
- Generación de datos numéricos
- Optimización de cálculos científicos
- Integración con Pandas y otras librerías

---

# 🎯 Objetivo del Taller

Aplicar conceptos fundamentales de análisis de datos utilizando la librería Pandas en Python, realizando operaciones matemáticas, estadísticas y manipulación de columnas sobre un conjunto de datos de productos tecnológicos y de oficina.

---

# 🛠️ Herramientas Utilizadas

- Pandas
- NumPy
- Jupyter Notebook
- Visual Studio Code
- GitHub

---

# 📑 Dataset Utilizado

El conjunto de datos utilizado contiene información relacionada con productos tecnológicos y artículos de oficina.

| Producto | Precio | Cantidad | Costo_Envio | Categoria |
|----------|---------|----------|-------------|------------|
| Laptop | 3500000 | 4 | 50000 | Tecnología |
| Mouse | 80000 | 15 | 10000 | Tecnología |
| Teclado | 120000 | 10 | 12000 | Tecnología |
| Silla | 450000 | 5 | 30000 | Oficina |
| Escritorio | 900000 | 3 | 40000 | Oficina |
| Monitor | 1100000 | 6 | 35000 | Tecnología |

Además, se agregaron 54 productos tecnológicos adicionales para ampliar el análisis de datos.

---

#  Desarrollo del Taller

## 🔹 Punto 1 – Creación y Exploración del DataFrame

En esta sección se realizó:

- Crear el DataFrame utilizando Pandas
- Mostrar las primeras 5 y las 10 últimas filas del DataFrame
- Identificar el tipo de dato de cada columna
- Mostrar el tamaño del DataFrame (filas y columnas)
- Generar una descripción estadística general del conjunto de datos

---

## 🔹 Punto 2 – Operaciones Matemáticas entre Columnas

En esta sección se realizó:

- Crear una nueva columna llamada Total_Venta = Precio × Cantidad
- Crear una nueva columna llamada Costo_Total = Total_Venta + Costo_Envio
- Calcular el promedio del Total_Venta
- Identificar el producto con mayor Total_Venta
- Identificar el producto con menor Total_Venta

---

## 🔹 Punto 3 – Porcentajes y Análisis

En esta sección se realizó:

- Crear una columna llamada IVA que represente el 19% del Total_Venta
- Crear una columna llamada Ganancia_Estimada correspondiente al 25% del Total_Venta
- Crear una columna llamada Perdida_Estimada correspondiente al 0.05% del Total_Venta
- Calcular qué porcentaje representa cada producto respecto al total general de ventas
- Mostrar únicamente los productos cuyo porcentaje de ventas sea superior al 15%

---

## 🔹 Punto 4 – Estadística Descriptiva

En esta sección se realizó:

- Calcular la media, mediana y moda de la columna Precio
- Calcular la desviación estándar de la columna Cantidad
- Calcular el valor máximo y mínimo de Total_Venta
- Explicar brevemente qué significa cada medida estadística obtenida

### Interpretación de las Medidas Estadísticas

- **Media:** representa el promedio general de los precios.
- **Mediana:** representa el valor central del conjunto de datos.
- **Moda:** representa el valor que más se repite.
- **Desviación estándar:** mide la dispersión de los datos respecto a la media.

---

## 🔹 Punto 5 – Filtrado y Ordenamiento

En esta sección se realizó:

- Mostrar únicamente los productos de la categoría Tecnología
- Ordenar los productos de mayor a menor según Total_Venta

---

#  Resultados Obtenidos

Durante el desarrollo del taller se logró:

- Manipular datos utilizando Pandas
- Aplicar operaciones matemáticas y estadísticas
- Realizar análisis porcentuales
- Filtrar y organizar información
- Exportar archivos Excel
- Comprender el funcionamiento de los DataFrames
- Mejorar la organización de proyectos en GitHub

---

#  Aprendizajes Adquiridos

- Uso de la librería Pandas
- Manipulación de DataFrames
- Aplicación de estadísticas descriptivas
- Operaciones matemáticas en Python
- Filtrado y ordenamiento de datos
- Exportación de información a Excel
- Documentación de proyectos en GitHub

---

#  Información Académica

| Campo | Información |
|--------|------------|
| Universidad | Universidad del Pacífico |
| Programa | Ingeniería de Sistemas |
| Asignatura | Inteligencia Artificial |
| Semestre | 8° |
| Corte | II |
| Fecha | 29/05/2026 |

---

#  Integrantes

- KAROL YISNEY CAICEDO MORENO
- ELKIN ANDRES CHALARCA TANGARIFE
- LUISA FERNANDA GONZALEZ DELGADO
- DAIRON VALENCIA CAMPAZ

---

#  Conclusión

El desarrollo de este taller permitió fortalecer los conocimientos relacionados con el análisis y procesamiento de datos mediante el uso de Pandas y NumPy. A través de diferentes ejercicios prácticos se aplicaron operaciones matemáticas, cálculos estadísticos y técnicas de organización de información que son ampliamente utilizadas en proyectos de ciencia de datos.

Además, se reforzó el manejo de herramientas de desarrollo como GitHub y Jupyter Notebook, contribuyendo a una mejor documentación y presentación de proyectos académicos y profesionales.
