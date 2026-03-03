# 📊 Telecom X: Análisis de Evasión de Clientes (Churn)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luisoroz1/9-TelecomX_LATAM_Challenge/blob/principal/TelecomX_LATAM.ipynb)

![Status](https://img.shields.io/badge/Status-V1--Completa-green)
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.24+-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-ffffff?logo=matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-444444?logo=seaborn&logoColor=white)

## 📝 Descripción del Proyecto
Este proyecto desarrolla un análisis integral sobre la deserción de clientes en la compañía **Telecom X**. El objetivo es transformar datos crudos obtenidos de una API jerárquica en información accionable para identificar patrones de comportamiento y factores de riesgo.

> **Proyecto desarrollado como parte del desafío de análisis de datos para ORACLE y ALURA LATAM.**

## 🔍 Diccionario de Datos
* **Identificación**: `customerID`, `Churn` (Variable Objetivo).
* **Perfil**: Género, Senior Citizen, Socio, Dependientes y Antigüedad (`tenure`).
* **Servicios**: Telefonía, Internet (DSL/Fibra), Seguridad Online, Soporte Técnico, etc.
* **Cuenta**: Contrato, Método de Pago, Cargos Mensuales y Totales.

## 🏗️ Metodología (Pipeline de Datos)
1. **Ingesta**: Conexión a API JSON y aplanado de datos.
2. **Limpieza**: Eliminación de 224 registros vacíos en `Churn` y casting de tipos.
3. **Ingeniería**: Creación de `cuentas_diarias` y `Segmento_Tenure`.
4. **EDA**: Análisis Univariado, Bivariado y Multivariado.

## 🚀 Instrucciones de Uso
1. **Abrir en Colab**: Usa el botón superior para ejecutar el cuaderno en la nube.
2. **Orden**: Ejecuta las celdas secuencialmente para asegurar la integridad de las variables.
3. **Persistencia**: Ejecuta `drive.mount()` si deseas guardar resultados en tu Drive personal.

## 📈 Hallazgos Clave
* **Tasa General de Churn**: **26.54%**.
* **Periodo Crítico**: Los clientes 'Rookie' (0-12 meses) tienen una tasa de fuga del **47%**.
* **Servicio Crítico**: La Fibra Óptica muestra un Churn del **42%**.
* **Valor Acumulado**: Correlación de **0.83** entre antigüedad y cargos totales.

## 💡 Ideas y Próximos Pasos (V2)
* Retención proactiva para nuevos clientes.
* Auditoría de calidad técnica en servicios de Fibra.
* Modelado predictivo con Machine Learning.

## 📄 Licencia
Este proyecto está bajo la Licencia MIT - mira el archivo [LICENCIA](LICENCIA) para más detalles.

---
**Desarrollado por: Luis Orozco**
