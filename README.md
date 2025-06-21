# 📊 Análisis de Evasión de Clientes (Churn) — TelecomX

Bienvenido al repositorio del proyecto de análisis de evasión de clientes en una empresa de telecomunicaciones.  
Este trabajo fue desarrollado en **Google Colab** utilizando Python, Pandas, NumPy, Matplotlib y Seaborn.

---

## 📌 Objetivo del Proyecto
El objetivo principal es **identificar patrones de comportamiento asociados a la evasión de clientes (Churn)** para ayudar a la empresa a:
- Reducir la pérdida de clientes.
- Mejorar la retención.
- Desarrollar estrategias basadas en datos.

---

## 🛠️ Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📂 Estructura del Proyecto
- `TelecomX_Data.json` → Base de datos original.
- `TelecomX_Analysis.ipynb` → Notebook con el desarrollo completo del análisis.
- `README.md` → Este archivo.

---

## 🔍 Resumen del Análisis

### 📊 Limpieza y Tratamiento de Datos
Se realizaron los siguientes pasos:
- Normalización de archivos JSON anidados.
- Conversión de tipos de datos.
- Eliminación de duplicados.
- Limpieza de celdas vacías en la columna `Churn`.
- Creación de una nueva variable: **Cuentas Diarias** (costo mensual dividido por 30).

---

### 📈 Análisis Exploratorio de Datos

#### Distribución de Evasión
Se analizó la proporción de clientes que permanecen y los que abandonan.

![Distribución de Churn](C:/Users/erosd/Desktop/PROYECTOS/Telecom X/TelecomX_Data)

---

#### Evasión por Variables Categóricas
Se estudiaron variables como tipo de contrato, método de pago y tipo de internet.

![Churn por Variables Categóricas](ruta/a/tu/grafico_categoricas.png)

---

#### Evasión por Variables Numéricas
Se analizaron:
- Antigüedad del cliente.
- Cargo mensual.
- Total gastado.
- Cuentas diarias.

![Churn por Variables Numéricas](ruta/a/tu/grafico_numericas.png)

---

## ✅ Principales Conclusiones
- Los **clientes con contratos mensuales** tienen mayor tasa de cancelación.
- Los clientes con **poca antigüedad** son más propensos a abandonar.
- Los clientes que utilizan **pagos automáticos** tienen menor probabilidad de churn.
- El servicio de **fibra óptica presenta mayor evasión** en comparación con otros tipos de internet.

---

## 💡 Recomendaciones
- Incentivar **contratos anuales o bianuales**.
- Implementar programas de fidelización para **clientes nuevos**.
- Ofrecer **beneficios exclusivos para pagos automáticos**.
- Revisar calidad y competitividad del servicio de **fibra óptica**.
- Crear **alertas tempranas** para detectar clientes en riesgo.

---

## 🚀 Resultado Final
El análisis permite a la empresa comprender el comportamiento de sus clientes y tomar decisiones estratégicas para mejorar la retención y la satisfacción.

---

## 📂 Cómo Ver el Proyecto
Podés explorar el notebook completo en Google Colab:  
🔗 [Enlace al Notebook](link-a-tu-colab)

---

## 🙌 Autor
**Eros Díaz**  
📫 [LinkedIn](https://www.linkedin.com/in/eros-diaz)

---

## ✨ Vista previa recomendada
> ⚙️ Si subís tus gráficos a GitHub, usá esta estructura para que se vean:
```markdown
![Título descriptivo](carpeta/grafico.png)
