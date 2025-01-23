# Proyecto 9 - Betabank: ¿Quienes se van? 

Los clientes de Beta Bank se están yendo, cada mes, poco a poco. Es más barato salvar a los clientes existentes que atraer nuevos. 
Necesitamos predecir si un cliente dejará el banco pronto. Realizamos un modelo predictivo de bosque aleatorio, usando datos bancarios. Debido a las diferencias en las proporciones de las clases se intentaron difernetes métodos de equilibrio de las mismas.

## Contenido del archivo
El notebook consta de:
- **79 celdas en total:**
  - **50 celdas de markdown:** Documentación y explicaciones detalladas.
  - **29 celdas de código:** Implementación del modelo y análisis de datos.

### Bibliotecas principales utilizadas
El proyecto hace uso de varias bibliotecas de Python para procesamiento y aprendizaje automático, incluidas:
- **Manipulación de datos:** `pandas`, `numpy`.
- **Preprocesamiento:** `OrdinalEncoder`, `StandardScaler`.
- **Modelado:** `RandomForestClassifier` (de `sklearn.ensemble`).
- **Evaluación de modelos:** Métricas como `accuracy_score`, `f1_score`, `roc_auc_score`, entre otras.

## Estructura principal
1. **Carga de datos:**
   - Lectura y exploración inicial de los datos.
   - Limpieza y preprocesamiento.

2. **Análisis exploratorio de datos (EDA):**
   - Análisis descriptivo y visualización de patrones clave.

3. **División de datos:**
   - División en conjuntos de entrenamiento y prueba usando `train_test_split`.

4. **Modelado:**
   - Entrenamiento de un modelo de clasificación con `RandomForestClassifier`.

5. **Evaluación:**
   - Cálculo de métricas de desempeño como F1-score, matriz de confusión, y curvas ROC.

## Requisitos del sistema
Para ejecutar este notebook, necesitarás:
- Python 3.7 o superior
- Dependencias listadas en `requirements.txt`

## Ejecución del proyecto
1. Clona este repositorio:
   ```bash
   git clone <URL-del-repositorio>
   ```

2. Cambia al directorio del proyecto:
   ```bash
   cd <nombre-del-directorio>
   ```

3. Ejecuta el notebook:
   ```bash
   jupyter notebook proyecto_9.ipynb

