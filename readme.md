# Churn prediction Beta Bank - Supervised Learning

## Descripción del proyecto

Este proyecto tiene como objetivo predecir si los clientes de Beta Bank abandonarán el banco en el corto plazo. Dado que es más rentable retener a los clientes existentes que atraer nuevos, el banco busca identificar comportamientos clave asociados con la fuga de clientes. Para ello, se construyó un modelo de predicción utilizando datos históricos del comportamiento de los clientes y sus contratos bancarios. 


## Funcionalidades principales

- **Carga y preparación de datos**: se procesan los datos de clientes para su análisis y modelado.
- **Análisis exploratorio**: se examinan los datos para identificar patrones y detectar desequilibrios en las clases.
- **Entrenamiento de modelos de clasificación**: se entrenan modelos tanto sin corrección como con técnicas de ajuste para corregir el desequilibrio de clases.
- **Evaluación de modelos**: se evalúan los modelos utilizando las métricas *F1* y *AUC-ROC* para medir su desempeño.
- **Mejora del modelo**: se aplican técnicas como el sobremuestreo y el submuestreo para optimizar el rendimiento en función del equilibrio de clases.


## Tecnologías Utilizadas
- **Python**: Lenguaje principal utilizado para la manipulación y análisis de datos.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **Numpy**: Librería fundamental para operaciones numéricas y manejo de arrays.
- **Scikit-learn**:  Biblioteca para implementar algoritmos de Machine Learning.
- **Jupyter Notebook**: Entorno de desarrollo interactivo.

## Instrucciones de Uso

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/kelvin-lab/Churn-prediction-Beta-Bank-Supervised-Learning.git
   ```

2. **Instalar dependencias:**

   Asegúrate de tener un entorno virtual configurado, luego instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. **Abrir el notebook en Jupyter:**

   Ejecuta Jupyter Notebook desde la terminal o utiliza una plataforma como Google Colab para abrir el archivo `.ipynb`:

   ```bash
   jupyter notebook
   ```

4. **Ejecutar las celdas:**

   Sigue el flujo de trabajo desde la limpieza de datos hasta el análisis y la visualización de los resultados.

## Contribuciones
Las contribuciones para mejorar el análisis o agregar nuevas funcionalidades son bienvenidas. Sigue estos pasos para contribuir:
1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request para revisión.

## Autores
Este proyecto fue desarrollado por **Kelvin Trujillo**.

## Licencia
Este proyecto está bajo la Licencia MIT. Para más información, revisa el archivo [LICENSE](./LICENSE).

## Conclusiones

Este proyecto demuestra cómo los modelos de aprendizaje supervisado pueden ser utilizados para abordar problemas de fuga de clientes en el sector bancario. Se exploraron diferentes enfoques para equilibrar las clases en los datos, y el modelo final logró superar el umbral mínimo de rendimiento definido por la métrica *F1*. La implementación de técnicas de sobremuestreo y submuestreo resultó ser efectiva para mejorar la capacidad predictiva del modelo en un conjunto de datos con desequilibrio de clases.

