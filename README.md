# Proyecto: Ayudando a Amancio a repartir su legado

Este es un proyecto de **Aprendizaje No Supervisado** realizado para el módulo de Sistemas de Aprendizaje Automático (IES de Teis). 

Amancio Ortega cumple 89 años y quiere decidir dónde invertir su legado. Nos ha pedido ayuda para identificar qué países están en una situación más crítica a nivel socioeconómico y de salud para que su fundación pueda construir hospitales, escuelas y comedores sociales.

El dataset contiene datos de **167 países** con 10 variables clave como mortalidad infantil, esperanza de vida, ingresos, inflación y PIB.

### ¿Qué hemos hecho?
El trabajo se divide en los pasos lógicos de un análisis de datos real:

1.  **Limpieza y Análisis (EDA):** Ver cómo se distribuyen los datos y si hay valores nulos (spoiler: el dataset está bastante limpio).
2.  **Preprocesamiento:** Como no puedes comparar "mortalidad infantil" con "PIB" directamente (las escalas son mundos distintos), hemos normalizado los datos.
3.  **Clustering (K-Means / Jerárquico):** Hemos agrupado los países por "parecido". Aquí es donde buscamos el número óptimo de grupos para ver cuáles son los que realmente necesitan la ayuda.
4.  **PCA (Reducción de Dimensionalidad):** Analizamos si podíamos simplificar las 10 variables en unas pocas "super-variables" sin perder información.
5.  **Conclusiones:** La lista final de países que Amancio debería tener en su radar.

### Stack Tecnológico
* **Python** (Pandas, Numpy)
* **Scikit-Learn** (para los modelos de ML)
* **Matplotlib & Seaborn** (para que las gráficas se entiendan)
* **Jupyter Notebook**

### Cómo usarlo
Si quieres echarle un ojo al análisis:
1. Clona el repositorio.
2. Asegúrate de tener instalado `sklearn`, `pandas` y `seaborn`.
3. Abre el archivo `.ipynb` y ejecuta las celdas.

---
