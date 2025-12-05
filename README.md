# 📈 Análisis Estratégico de Rentabilidad de Tarifas en Telecom (Megaline)

## 📌 Contexto y Problema de Negocio
Trabajando como analista para el operador de telecomunicaciones Megaline, el objetivo fue determinar **cuál de sus dos planes de prepago, Surf o Ultimate, genera mayor ingreso promedio** para optimizar la estrategia de publicidad de la empresa.

El análisis se basó en una muestra de 500 clientes durante el año 2018.

## 🎯 Objetivos Clave del Análisis

1.  **Preprocesamiento de Datos:** Aplicar reglas de negocio estrictas (ej. redondeo de llamadas y datos) y consolidar la actividad mensual (llamadas, mensajes, internet) de cada usuario.
2.  **Métrica de Ingresos:** Desarrollar una función para calcular el ingreso mensual total por usuario, considerando la cuota fija y el **cobro por exceso de límite (*overage*)** por cada plan.
3.  **Análisis de Consumo:** Calcular y visualizar la media, varianza y desviación estándar del consumo (minutos, SMS, GB) para cada plan.
4.  **Pruebas de Hipótesis:**
    * Evaluar si existe una **diferencia estadísticamente significativa** en el ingreso promedio de los usuarios de los planes Surf y Ultimate.
    * Evaluar si el ingreso promedio de los usuarios en el área **Nueva York-Nueva Jersey** difiere del de otras regiones.

## 💡 Insights Estratégicos (Clave para tu Portafolio)

| Métrica | Plan Surf | Plan Ultimate | Impacto en el Negocio |
| :--- | :--- | :--- | :--- |
| **Ingreso Promedio Mensual** | **[Ingreso Promedio de Surf]** | **[Ingreso Promedio de Ultimate]** | **El plan Ultimate genera un ingreso promedio significativamente mayor.** *Necesitas poner el valor numérico obtenido en tu análisis.* |
| **Varianza de Ingresos** | **Alta** | **Baja** | La alta varianza de **Surf** indica que una parte de sus usuarios genera ingresos adicionales considerables al exceder los límites, principalmente por **uso excesivo de datos (GB)**. El plan Ultimate es más predecible en su flujo de caja. |
| **Consumo Promedio de Minutos** | Cerca de su límite (500) | Muy por debajo de su límite (3000) | Los usuarios de Surf están más cerca de agotar sus límites, lo que confirma la vulnerabilidad al *overage*. |

### Resultados de Pruebas de Hipótesis:
* **Plan Más Rentable:** El análisis estadístico (t-test) confirma que **el ingreso promedio del plan Ultimate es mayor** y la diferencia es estadísticamente significativa.
* **Impacto Regional:** No se encontró evidencia estadística significativa para afirmar que la ubicación geográfica (NY/NJ vs. resto) impacte el ingreso promedio del cliente.

## 🛠️ Tecnologías
* `Python`
* `Pandas` (Manipulación y agregación de datos)
* `NumPy` (Cálculos numéricos, en particular el redondeo hacia arriba)
* `SciPy.stats` (Pruebas de hipótesis T-Test)
* `Matplotlib` & `Seaborn` (Visualización de distribuciones)

