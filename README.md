# 📊 Extracción de Conocimiento en Bases de Datos

**Proyecto académico de Ingeniería en Desarrollo de Software**

## 🎯 Objetivo del Proyecto

Comprender y aplicar técnicas de procesamiento de datos para implementar almacenes útiles en la extracción de conocimiento, incluyendo:

- **Análisis Supervisado**: Algoritmos de predicción y clasificación
- **Análisis No Supervisado**: Extracción de características y patrones ocultos
- **Dashboard Interactivo**: Visualización avanzada de resultados

## 🗂️ Estructura del Proyecto

```
📁 extraccion-conocimiento-bd/
├── 📄 README.md
├── 📁 datos/
│   └── online_retail_dataset.xlsx
├── 📁 notebooks/
│   ├── 📓 main.ipynb (configuración inicial)
│   ├── 📓 01_analisis_exploratorio.ipynb
│   ├── 📓 02_modelo_regresion.ipynb
│   ├── 📓 03_modelo_clustering.ipynb
│   ├── 📓 04_modelo_clasificacion.ipynb
│   ├── 📓 05_modelo_asociacion.ipynb
│   └── 📓 06_dashboard.ipynb
├── 📁 modelos/
│   ├── 🤖 modelo_regresion.pkl
│   ├── 🤖 modelo_clustering.pkl
│   ├── 🤖 modelo_clasificacion.pkl
│   └── 🤖 modelo_asociacion.pkl
├── 📁 visualizaciones/
│   └── 📊 (gráficas generadas)
└── 📁 documentos/
    └── 📑 reporte_final.pdf
```

## 🔧 Tecnologías Utilizadas

- **Python 3.11+**
- **Google Colab** - Entorno de desarrollo
- **GitHub** - Control de versiones
- **Pandas & NumPy** - Manipulación de datos
- **Scikit-learn** - Machine Learning
- **Plotly & Dash** - Visualización y Dashboard
- **MLxtend** - Análisis de asociación

## 📊 Dataset: Online Retail

**Fuente**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

**Descripción**: Datos transaccionales de una tienda online incluyendo:
- Información de clientes y productos
- Cantidades y precios
- Fechas de transacciones
- Países de origen

## 🤖 Modelos Implementados

### 🎯 Aprendizaje Supervisado
1. **Regresión**: Predicción del monto total de compra
2. **Clasificación**: Categorización de clientes (frecuentes vs ocasionales)

### 🔍 Aprendizaje No Supervisado
1. **Clustering**: Segmentación de clientes por comportamiento
2. **Asociación**: Análisis de productos frecuentemente comprados juntos

## 📈 Dashboard Interactivo

Dashboard desarrollado con **Dash** que incluye:
- Filtros dinámicos por país, fecha y producto
- Visualizaciones interactivas de todos los modelos
- Métricas de rendimiento en tiempo real

## 🚀 Cómo Ejecutar el Proyecto

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/[tu-usuario]/extraccion-conocimiento-bd.git
   ```

2. **Abrir en Google Colab**:
   - Subir los notebooks a Google Colab
   - Ejecutar `main.ipynb` para configurar el entorno

3. **Ejecutar notebooks en orden**:
   - 01_analisis_exploratorio.ipynb
   - 02_modelo_regresion.ipynb
   - 03_modelo_clustering.ipynb
   - 04_modelo_clasificacion.ipynb
   - 05_modelo_asociacion.ipynb
   - 06_dashboard.ipynb

## 📋 Criterios de Evaluación

### ✅ Criterio SA (Satisfactorio)
- [x] Modelo de regresión con justificación
- [x] Modelo de agrupación con análisis
- [x] Repositorio con código organizado

### ✅ Criterio DE (Destacado)
- [x] Todos los puntos de SA
- [x] Modelo de clasificación
- [x] Modelo de asociación

### ✅ Criterio AU (Autónomo)
- [x] Todos los puntos de DE
- [x] Dashboard interactivo avanzado

## 👨‍💻 Autor

**Diego Antonio Martínez Balderas**
- 🎓 Estudiante de Ingeniería en Desarrollo de Software
- 📧 [2022371075@uteq.edu.mx]

## 📝 Licencia

Este proyecto es de uso académico para la materia de Extracción de Conocimiento en Bases de Datos.

---

⭐ **¡Dale una estrella si este proyecto te fue útil!** ⭐
