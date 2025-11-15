# Limpieza de datos en Notebook — Proyecto inicial (Kiva Crowdfunding)

## 📝 Descripción del proyecto

Este proyecto se centrará en aplicar las mejores prácticas de limpieza y preparación de datos utilizando Python en un entorno de notebook (Jupyter/Google Colab). El objetivo es transformar los datos brutos del dataset de Kiva Crowdfunding en un conjunto de datos estructurado, consistente y listo para análisis o modelado predictivo.

El proyecto sigue una metodología reproducible que abarca tres etapas fundamentales: **Importación y exploración inicial**, **Diagnóstico y limpieza de datos**, y **Validación y exportación del dataset limpio**. Se enfatiza la documentación clara de cada decisión tomada durante el proceso de limpieza, garantizando que cualquier miembro del equipo pueda replicar el trabajo y comprender el razonamiento detrás de cada transformación aplicada.

## 🎯 Objetivos concretos

- Entender la estructura y calidad raw del dataset.
- Corregir tipos, fechas y valores inconsistentes.
- Eliminar/gestionar duplicados y valores faltantes de forma documentada.
- Crear un artefacto final (CSV/Parquet) y un notebook reproducible con comentarios y celdas explicativas.

## 📊 Dataset Utilizado
Para este proyecto, trabajaremos con el dataset **"Data Science for Good: Kiva Crowdfunding"** que contiene información sobre préstamos de microfinanciación de Kiva, una organización sin fines de lucro.

- **Dataset principal**: [Descargar dataset Kiva](https://drive.google.com/file/d/1hY7KOuXNyY7WPw9cICXqrxmT8iRytmJk/view?usp=sharing)
- **Información detallada del dataset**: [Kaggle - Kiva Crowdfunding](https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding)
- **Organización**: [Kiva.org](https://www.kiva.org/)
  
## 🧰 Tecnologías y librerías

- **Python** (notebook Jupyter o Google Colab)
- **Librerías:** pandas, numpy, matplotlib / seaborn (opcional para exploración), pyarrow (si se exporta Parquet)
- **Control de versiones:** git (repositorio), README.md

### ⚠️ Nota sobre la elección del dataset
**Puedes utilizar cualquier dataset de tu interés** obtenido de otras fuentes de internet como Kaggle, data.gov, UCI Machine Learning Repository, o cualquier otra fuente de datos pública que sea de tu interés personal o profesional.

## 📦 Condiciones de entrega

El proyecto es **Individual**.

1. Será necesario entregar un **Notebook** (.ipynb) bien organizado y con comentarios explicativos.
2. Será necesario entregar el **Dataset limpio** exportado (CSV o Parquet).
3. Será necesario entregar un **README** con:
   - Pasos ejecutados
   - Cómo ejecutar el notebook
   - Resumen de decisiones de limpieza
4. **Repositorio** con todo lo anterior.

## ⏳ Plazo de Entrega

- 1 semana

## 🛠️ Tecnologías a usar

- Google Colab
- Github

## 🧭 Estructura recomendada del Notebook

1. **Importar datos** (mostrar primeros registros)
2. **Análisis exploratorio rápido** (shape, tipos, resumen estadístico)
3. **Diagnóstico de problemas** (missing, outliers, duplicados, formatos)
4. **Transformaciones y limpieza** (paso a paso, con celdas y comentarios)
5. **Validación post-limpieza** (checks, counts, sample)
6. **Exportar dataset limpio** y notas finales

## ✅ Checklist de limpieza (tareas y decisiones típicas)

- [ ] Revisar columnas, tipos de datos y convertir columnas de fecha a datetime
- [ ] Detectar y eliminar duplicados (documentar criterio)
- [ ] Analizar y tratar valores faltantes: imputación simple, eliminación o marca explícita
- [ ] Normalizar textos (país, moneda, categorías): trim, lower, mapeos
- [ ] Corregir formatos numéricos (coma/punto, tipos numéricos)
- [ ] Detectar y gestionar outliers razonables (documentar por qué se quitan o conservan)**
- [ ] Crear columnas derivadas útiles (ej.: año, mes, duración, ratio)
- [ ] Codificar variables categóricas si procede (labels / one-hot solo si es necesario)**
- [ ] Guardar snapshot del raw original y del dataset final**
- [ ] Añadir pruebas sencillas: conteos esperados, no-null en campos clave, unicidad**

## 📈 Buenas prácticas y criterios de calidad

- **Reproducibilidad:** todo cambio debe poder ejecutarse de nuevo desde el notebook
- **Trazabilidad:** explicar por qué se tomó cada decisión (notas/markdown)
- **Minimalismo en pérdida de información:** eliminar filas solo si hay justificación
- **Entregable usable:** dataset final con tipos correctos y documentación mínima

## 🧪 Criterios de evaluación

- Configurar y automatizar su entorno de trabajo.
- Gestionar equipos técnicos
- Evaluar Conjuntos de datos
- Desarrollar interfaces dinámicas**
