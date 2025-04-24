# Análisis de Tiendas - Proyecto de Ciencia de Datos

Este repositorio contiene un análisis comparativo de cuatro tiendas distintas basado en datos proporcionados por **Alura LATAM** como parte del reto *"Fundamentos para la nube en la industria 4.0 con tecnologías Microsoft"*.

A través de gráficos y código en Python, se extraen conclusiones para recomendar al Sr. Juan la mejor tienda en la cual invertir.

---

## 📊 Objetivo
Analizar información clave de cada tienda, como ingresos, productos vendidos, satisfacción del cliente y costos de envío, para tomar una decisión fundamentada sobre cuál es la opción de inversión más estable y rentable.

---

## 📂 Contenido del análisis

El notebook incluye:

- Carga y lectura de datos desde CSV (GitHub)
- Cálculo de **ingresos totales por tienda**
- Identificación de la **categoría más vendida**
- Análisis de la **satisfacción del cliente** (calificaciones promedio)
- Determinación de **productos más y menos vendidos**
- Comparación de la diferencia entre el producto más y menos vendido
- Evaluación del **costo promedio de envío** por tienda

---

## 🔹 Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib
- NumPy
- Google Colab (entorno sugerido para ejecución)

---

## 🔧 Estructura del Código

El análisis está dividido en funciones reutilizables para:
- Calcular promedios generales (`getAverageGeneralGraphics`)
- Obtener ingresos totales por tienda (`sumaPorTienda`)
- Analizar la categoría más popular (`getProductoMasPopularPorTienda`)
- Calcular la calificación promedio por tienda (`getAverageStore`)
- Identificar productos más y menos vendidos (`getProductoMasVendido`, `getProductoMenosVendido`)
- Calcular el costo de envío promedio (`getAverageShippin`)

---

## ▶️ Cómo ejecutar el código

1. Abre el archivo en un entorno como Google Colab o Jupyter Notebook.
2. Ejecuta las celdas de importación de librerías y carga de datos.
3. Llama a las funciones en el orden sugerido o personalízalas para tus propios análisis.
4. Asegúrate de tener conexión a internet para acceder a los archivos CSV alojados en GitHub.
5. Los gráficos se generan automáticamente al ejecutar cada bloque, proporcionando visualizaciones útiles para el análisis.

---

## 🌟 Conclusiones principales
- La **Tienda 3** resulta la más adecuada para invertir gracias a:
  - Buen rendimiento en categorías clave como muebles
  - Alta satisfacción del cliente
  - Costos de envío más bajos
  - Ventas distribuidas de manera uniforme entre productos

---

## 📄 Referencias
- Datos proporcionados por Alura LATAM
- Curso: Challenge Alura Store Practicando Python para Data Science: Challenge Alura Store

---

## 🤝 Autor
**Javier Alvarado Márquez**  
Estudiante de Ingeniería en Sistemas Computacionales
