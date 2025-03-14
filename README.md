# Estrategia de Trading con Aprendizaje No Supervisado

## Descripción
Este proyecto explora una estrategia de trading basada en aprendizaje no supervisado, aplicando clustering para la selección de activos en el S&P 500 y optimización de cartera mediante el ratio de Sharpe.

## Objetivos
- Descargar y procesar datos de precios de acciones del S&P 500.
- Calcular indicadores y características relevantes para cada acción.
- Filtrar las 150 acciones más líquidas y calcular retornos mensuales.
- Obtener factores Fama-French y calcular betas con ventana móvil.
- Aplicar clustering con K-Means para agrupar activos similares.
- Construir una cartera basada en la Frontera Eficiente con máximo ratio de Sharpe.
- Visualizar los retornos de la cartera y compararlos con el S&P 500.

## Tecnologías y Librerías Utilizadas
- Python (`pandas`, `numpy`, `matplotlib`, `statsmodels`, `sklearn`, `yfinance`, `PyPortfolioOpt`)

## Estructura del Proyecto
1. **Descarga y carga de datos**: Obtención de precios de acciones con `yfinance` y `pandas_datareader`.
2. **Cálculo de características**: Generación de indicadores técnicos y fundamentales.
3. **Filtrado de activos**: Selección de las acciones más líquidas.
4. **Clustering**: Aplicación de K-Means para segmentar acciones en grupos similares.
5. **Optimización de cartera**: Uso de `PyPortfolioOpt` para construir una cartera eficiente.
6. **Evaluación**: Comparación de los retornos de la cartera frente al S&P 500.

## Resultados Esperados
- Una cartera optimizada que supere al mercado en términos de ratio de Sharpe.
- Insights sobre la agrupación de activos en base a características cuantitativas.
- Visualizaciones de la evolución de la cartera y su comparación con el benchmark.

## Instalación y Uso
### Requisitos
- Python 3.8+
- Instalar dependencias:
  ```bash
  pip install pandas numpy matplotlib statsmodels pandas_datareader yfinance scikit-learn PyPortfolioOpt
  ```

### Ejecución
1. Ejecutar el script de descarga de datos.
2. Procesar los datos y calcular indicadores.
3. Aplicar clustering y seleccionar activos.
4. Optimizar la cartera y evaluar los resultados.

# Unsupervised_Learning-Trading
