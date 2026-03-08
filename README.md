# telecom-analisis
# 📊 Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (*Churn*) en una empresa de telecomunicaciones mediante técnicas de análisis exploratorio de datos (EDA).  

La evasión de clientes representa un problema importante para las empresas, ya que implica pérdida de ingresos y mayores costos para adquirir nuevos usuarios. Comprender los factores que influyen en la cancelación del servicio permite diseñar estrategias efectivas de retención.

En este proyecto se analizan diferentes variables relacionadas con los clientes, como tipo de contrato, método de pago, tipo de servicio de internet, cargos mensuales y tiempo de permanencia, con el fin de identificar patrones asociados al abandono del servicio.

---

# 🎯 Objetivos

- Analizar la distribución de clientes que cancelan el servicio.
- Identificar patrones asociados con la evasión.
- Explorar la relación entre variables categóricas y churn.
- Analizar variables numéricas que influyen en la cancelación.
- Generar recomendaciones estratégicas basadas en los datos.

---

# 🗂️ Estructura del Proyecto

```
📁 churn-analysis
│
├── 📄 TelecomX_Churn_Analysis.ipynb
├── 📄 README.md
├── 📄 dataset.csv
```

**Archivos principales**

- `TelecomX_Churn_Analysis.ipynb` → Notebook con todo el análisis
- `dataset.csv` → Conjunto de datos utilizado
- `README.md` → Documentación del proyecto

---

# 📊 Dataset

El dataset contiene información sobre clientes de telecomunicaciones y sus características.

### Variables principales

| Variable | Descripción |
|--------|--------|
| customerID | Identificador del cliente |
| gender | Género del cliente |
| SeniorCitizen | Indica si el cliente es adulto mayor |
| Partner | Si tiene pareja |
| Dependents | Si tiene dependientes |
| tenure | Tiempo como cliente (meses) |
| PhoneService | Servicio telefónico |
| InternetService | Tipo de servicio de internet |
| Contract | Tipo de contrato |
| PaymentMethod | Método de pago |
| MonthlyCharges | Cargo mensual |
| TotalCharges | Cargo total acumulado |
| Churn | Indica si el cliente canceló el servicio |

---

# 🔎 Análisis Exploratorio de Datos

El análisis exploratorio permitió identificar patrones importantes relacionados con la evasión.

### Distribución de Churn

- **73.4 %** de los clientes permanecen en el servicio
- **26.6 %** de los clientes cancelaron

Esto indica que aproximadamente **1 de cada 4 clientes abandona la empresa**.

---

### Tipo de contrato

| Contrato | Tasa de Churn |
|--------|--------|
| Month-to-month | 42.7 % |
| One year | 11.3 % |
| Two year | 2.8 % |

Los contratos mensuales presentan **mayor probabilidad de cancelación**.

---

### Método de pago

El método con mayor evasión es:

- **Electronic check → 45.3 %**

Los métodos automáticos presentan menor churn.

---

### Servicio de Internet

| Servicio | Tasa de Churn |
|--------|--------|
| Fiber optic | 41.9 % |
| DSL | 19 % |
| No internet | 7.4 % |

Los clientes con **fibra óptica presentan mayor tasa de cancelación**.

---

### Variables Numéricas

| Estado del cliente | Tenure | Cargo mensual | Cargo total |
|---|---|---|---|
Clientes activos | 37.65 | 61.30 | 2555 |
Clientes que cancelaron | 17.98 | 74.44 | 1531 |

Esto indica que:

- Los clientes que cancelan permanecen **menos tiempo en la empresa**
- Pagan **mayores cargos mensuales**
- Cancelan **antes de acumular gasto significativo**

---

# 💡 Principales Insights

1️⃣ Los **contratos mensuales** presentan la mayor tasa de evasión.

2️⃣ Los clientes con **electronic check** cancelan con mayor frecuencia.

3️⃣ El servicio de **fibra óptica** presenta mayor churn.

4️⃣ Los clientes que abandonan el servicio suelen hacerlo **durante los primeros meses**.

---

# 📈 Recomendaciones

Basado en el análisis, se sugieren las siguientes estrategias:

- Incentivar **contratos de largo plazo**
- Mejorar la experiencia de **clientes nuevos**
- Analizar la **calidad o precio del servicio de fibra óptica**
- Promover **métodos de pago automáticos**
- Implementar **modelos predictivos de churn**

---

# 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook / Google Colab

---

# 🚀 Trabajo Futuro

Como extensión de este proyecto se podría desarrollar:

- Modelos de **Machine Learning para predicción de churn**
- Segmentación de clientes
- Sistemas de alerta temprana de abandono

---

# 👨‍💻 Autor

Proyecto desarrollado como parte de un análisis de datos para comprender los factores asociados con la evasión de clientes en telecomunicaciones.
