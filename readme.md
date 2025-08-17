# TelecomX - Análisis de Datos para la Prevención de Churn en LATAM

## 📌 Descripción del Proyecto
Análisis de datos de clientes de TelecomX en Latinoamérica para identificar patrones de abandono (churn) y generar insights accionables.

## 🛠️ Tecnologías
- **Python 3** + **Jupyter Notebook**
- **Librerías principales**:
  - Pandas (manipulación de datos)
  - NumPy (cálculos numéricos)
  - Requests (descarga de datos)

## 📊 Estructura del Análisis

### 1. Extracción de Datos
- Carga desde JSON remoto (`TelecomX_Data.json`)
- Validación inicial de estructura
- Diccionario de datos incorporado

### 2. Transformación
- Limpieza de datos:
  - Estandarización de formatos
  - Manejo de valores nulos
  - Conversión de tipos
- Desanidado de diccionarios embebidos
- Feature engineering:
  - Cálculo de cargos diarios
  - Codificación de variables categóricas

### 3. Análisis
- Estadísticos descriptivos
- Correlaciones entre variables
- Segmentación por estado de churn
- Identificación de factores clave

## 📈 Hallazgos Clave

**Distribución de Churn**:
```python
Baja
0    5398 (74.3%)
1    1869 (25.7%)
