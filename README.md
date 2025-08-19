# Análisis sobre la otorgación de créditos en Alemania

## Grupo
Grupo 2 — Equidad en Aprendizaje Automático  
Integrantes: Lucas Barreiro, Luca Gaziglia y Agustín Viullet

## Descripción del proyecto
Análisis en Python enfocado en equidad de modelos de clasificación para la concesión de créditos. Se realizó un análisis exploratorio (EDA) profundo con evaluación de metrics de equidad y se aplicaron técnicas de mitigación de sesgos.

## Contenido del repositorio
- **`notebook.ipynb`**  
  Notebook con todo el flujo: carga de datos, EDA, entrenamiento de modelos, evaluación de equidad, aplicación de técnicas de mitigación y resultados comparativos.

- **`german_credit_data.xlsx`**  
  Dataset con información crediticia de individuos en Alemania, usado como base para el análisis.

- **`data/`**  
  Carpeta con datos auxiliares o datasets parciales utilizados dentro del análisis (podría incluir por ejemplo subsets, datos preprocesados o archivos derivados).

## Tecnologías utilizadas
- Python (Jupyter Notebook)
- Bibliotecas: `pandas`, `numpy`, `scikit-learn`, `aif360` (para fairness metrics), entre otras

## Metodología y flujo de trabajo
1. Carga y preprocesamiento de datos desde `german_credit_data.xlsx`.
2. Análisis exploratorio (distribuciones, correlaciones, etc.).
3. Entrenamiento de modelos de clasificación.
4. Evaluación de equidad usando métricas como:
   - *Disparate Impact*
   - *Equal Opportunity Difference*
   - *Equalized Odds*
5. Aplicación de técnicas de mitigación como *Reweighing* y *Adversarial Debiasing*.
6. Comparación de resultados antes y después de la mitigación, interpretando impacto sobre precisión y equidad.

## Cómo correr el análisis
1. Clonar el repositorio.
2. Instalar dependencias necesarias (por ejemplo, con un entorno virtual).
3. Abrir `notebook.ipynb` en Jupyter y ejecutar las celdas en orden para reproducir el análisis completo.

## Conclusiones potenciales
- Evaluación del compromiso entre precisión y equidad en modelos crediticios.
- Eficacia de técnicas de mitigación sobre los sesgos detectados.
- Recomendaciones para prácticas más justas en sistemas de decisión automatizada.

## Extensiones posibles
- Evaluar métricas adicionales (por ejemplo, false positive rate parity).
- Probar otras técnicas de mitigación (como *Prejudice Remover* o *Equalized Odds Postprocessing*).
- Automatizar pipelines de fairness con herramientas como Fairlearn.


