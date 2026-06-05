# Anexo Metodológico - Auditoría de Clasificación Charcot

## 📋 Contenido de este Repositorio

Este repositorio contiene el **código fuente completo** y la **auditoría metodológica integral** de la investigación sobre clasificación de criterios Charcot en bases de datos bibliográficas.

---

## 🔑 ELEMENTO CRÍTICO CITADO EN MANUSCRITO

### **TABLA 4: Validación de Muestra - 60 Artículos Codificados** ⚠️
**Ubicación:** Al inicio del notebook `PIPELINE_CONSOLIDADO.ipynb` (primeras celdas de texto)

Contiene la **lista codificada de los 60 artículos de la muestra** con la clasificación manual de los evaluadores **E** y **T**, utilizada para la validación de confiabilidad interobservador (Cohen's Kappa = 0.314).

---

## 🚀 Acceso Rápido

### **Google Colab (Recomendado)**
Abre directamente en Colab sin instalar nada:

👉 **[https://colab.research.google.com/drive/1fkA8zNanziYqBQqOJy9AGbWMOx5WecZc?usp=sharing](https://colab.research.google.com/drive/1fkA8zNanziYqBQqOJy9AGbWMOx5WecZc?usp=sharing)**

*(Cualquier persona con el enlace puede visualizar)*

---

## 📁 Archivos de Entrada (Input Data)

El pipeline utiliza los siguientes archivos de datos:

| Archivo | Descripción |
|---------|------------|
| **Validación de muestra.xlsx** | Clasificación manual por evaluadores E y T |
| **pubmed-DiabeticFoNC-set.txt** | Base de datos PubMed principal |
| **pubmed-DiabeticFo-setCOMPLEMENTO.txt** | Base de datos PubMed complementaria |
| **scopus-DiabeticFoNC.csv** | Base de datos Scopus |
| **savedrecsCF.txt** | Base de datos Web of Science |
| **scimagojr 2024 Subject Category - Neurology.csv** | Referencia de impacto SJR (Neurología) |
| **scimagojr 2024 Subject Category - Neurology (clinical).csv** | Referencia de impacto SJR (Neurología clínica) |

---

## 🚀 Código Fuente

### **PIPELINE_CONSOLIDADO.ipynb**
Notebook Jupyter que contiene:
- Carga y procesamiento de todas las bases de datos
- Auditoría completa de clasificación Charcot
- **TABLA 4: Lista codificada de 60 artículos validados**
- Validación estadística de resultados
- Generación de análisis y visualizaciones
- Cálculo de métricas de confiabilidad

---

## 📖 Cómo Usar Este Código

### Opción 1: Ver en Google Colab (Recomendado - Sin instalación)
**👉 [Abrir en Colab](https://colab.research.google.com/drive/1fkA8zNanziYqBQqOJy9AGbWMOx5WecZc?usp=sharing)**

### Opción 2: Desde GitHub a Colab
1. Ve a https://colab.research.google.com/
2. Selecciona `Archivo` → `Abrir notebook`
3. Pega esta URL:
   ```
   https://github.com/eyberrospib-commits/Anexo_Metodologico_Auditoria_Clasificacion_Charcot/blob/main/PIPELINE_CONSOLIDADO.ipynb
   ```
4. ¡Colab lo abrirá automáticamente!

### Opción 3: Descargar y Ejecutar Localmente
1. Descarga `PIPELINE_CONSOLIDADO.ipynb` desde el repositorio
2. Descarga todos los archivos de datos
3. Coloca todo en la misma carpeta
4. Abre en Jupyter:
   ```bash
   jupyter notebook PIPELINE_CONSOLIDADO.ipynb
   ```

### Opción 4: Clonar el Repositorio Completo
```bash
git clone https://github.com/eyberrospib-commits/Anexo_Metodologico_Auditoria_Clasificacion_Charcot.git
cd Anexo_Metodologico_Auditoria_Clasificacion_Charcot
jupyter notebook PIPELINE_CONSOLIDADO.ipynb
```

---

## 📊 Estructura del Análisis

El notebook ejecuta:

1. **TABLA 4: Lista codificada de 60 artículos validados** (al inicio)
2. **Carga de datos** desde las 7 fuentes de entrada
3. **Procesamiento y limpieza** de bases de datos
4. **Auditoría de clasificación** aplicando criterios Charcot
5. **Validación cruzada** con clasificaciones manuales
6. **Cálculo de métricas** (Cohen's Kappa = 0.314, concordancia)
7. **Generación de reportes** y visualizaciones

---

## 💻 Requisitos Técnicos

### Para Colab (Recomendado)
- Solo necesitas una cuenta de Google
- ¡Nada que instalar!

### Para ejecución local:
```
Python 3.7+
pandas
numpy
scikit-learn
matplotlib
seaborn
openpyxl (para leer Excel)
```

Instalación:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

---

## 📌 Información para Revisores

✅ **Código auditado** - Sin secretos ni datos sensibles

✅ **Datos completos** - Todas las bases de datos incluidas

✅ **Reproducible** - El pipeline es completamente replicable

✅ **TABLA 4 disponible** - Al inicio del notebook con lista codificada de 60 artículos

✅ **Google Colab disponible** - Acceso directo sin instalación

⚠️ **Nota importante:** El archivo PIPELINE_CONSOLIDADO.ipynb es muy grande (1.2 MB). Si GitHub no lo renderiza en el navegador, puedes:
- Descargarlo directamente
- Abrirlo en Google Colab (opción recomendada)
- Clonar el repositorio

---

## 🔍 Métricas de Validación

- **Muestra validada:** 60 artículos codificados
- **Universo de datos:** N = 464
- **Métrica principal:** Cohen's Kappa = 0.314
- **Evaluadores:** E y T
- **Validación de muestra:** TABLA 4 (al inicio del notebook)

---

## 📖 Cómo Citar

Si utilizas este código o datos en tu investigación:

```
eyberrospib-commits. (2026). Anexo Metodológico - Auditoría de Clasificación Charcot. 
GitHub. https://github.com/eyberrospib-commits/Anexo_Metodologico_Auditoria_Clasificacion_Charcot
```

---

**Última actualización:** Junio 2026

---

## 💬 Soporte

Para preguntas sobre:
- **El código:** Abre un issue en este repositorio
- **Los datos:** Consulta el notebook con las descripciones de procesamiento
- **La metodología:** Refiere al manuscrito y este anexo complementario
