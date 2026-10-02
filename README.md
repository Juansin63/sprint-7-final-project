# sprint-7-final-project
#  Análisis Exploratorio de Datos (EDA) y Segmentación - ConnectaTel

##  Objetivo del proyecto
Realizar un Análisis Exploratorio de Datos (EDA) completo y un proceso caracterizacion sobre las tablas de usuarios y uso de ConnectaTel. 
El propósito principal es identificar patrones de comportamiento, detectar valores atípicos relevantes y generar segmentacion de clientes que sirvan de base para la toma de decisiones de negocio y estrategia comercial.

---

##  Datasets utilizados
El análisis se basa en tres fuentes principales de datos: 
* 'plans': catalogo de planes 
* 'users_latam': nformación de cada usuario (datos personales, plan, fecha de registro, churn).
* 'usage': Contiene  Actividad generada por los usuarios: llamadas, mensajes, duración, longitud.
 
---

## 🛠️ Etapas del análisis realizadas
1. **Limpieza y Exploración Inicial ('EDA')**: Revisión de la estructura de los datos, tipos de variables, estadísticas descriptivas y manejo de valores nulos.
2. **Detección de Outliers:** Uso de diagramas (boxplots) y cálculo del rango intercuartílico (IQR) para identificar consumos extremos, los cuales se decidió mantener por representar a clientes de alto valor (VIP).
3. **Caracterizacion y Segmentación:**
   * Creación de 'grupo_edad' para clasificar a los usuarios demográficamente (Joven, Adulto, Adulto Mayor).
   * Creación de 'grupo_uso' cruzando llamadas y mensajes (Bajo uso, Uso medio, Alto uso).
4. **Visualización y Generación de Insights:** Gráficos de distribución (histogramas y gráficos de barras) para analizar el comportamiento por tipo de plan.

---

##  Cómo ejecutar el notebook
1. Abrir el archivo .ipynb en GitHub
