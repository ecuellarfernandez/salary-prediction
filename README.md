# Predicción de Salarios con RandomForest
Este proyecto tiene como objetivo predecir los salarios utilizando un modelo de RandomForestRegressor basado en un conjunto de datos que incluye información sobre educación, experiencia, ubicación, título del trabajo, edad y género.

## Requisitos
Para ejecutar este proyecto, necesitas tener instalados los siguientes paquetes de Python:

- pandas
- scikit-learn
- numpy
- matplotlib
  
```
 pip install pandas scikit-learn numpy matplotlib
```

## Dataset
El dataset utilizado en este proyecto debe estar en formato CSV y contener las siguientes columnas:

- Education: Nivel educativo (por ejemplo, High School, Bachelor, PhD)
- Experience: Años de experiencia
- Location: Ubicación (por ejemplo, Urban, Suburban, Rural)
- Job_Title: Título del trabajo (por ejemplo, Manager, Director, - Analyst)
- Age: Edad del individuo
- Gender: Género (por ejemplo, Male, Female)
- Salary: Salario (variable objetivo)

## Ejercicio para los compañeros

`ejercicio_companeros.ipynb`

### Objetivo del Ejercicio

El objetivo del ejercicio es que los compañeros completen un notebook con un ejemplo de predicción de salarios utilizando el modelo de RandomForestRegressor. A través de este ejercicio, los compañeros aprenderán a preparar los datos, entrenar el modelo y validar su rendimiento.

### Instrucciones

1. **Cargar el Dataset**: Los compañeros deberán cargar el dataset proporcionado en el notebook.
2. **Revisar Datos Nulos**: Comprobar la existencia de valores nulos en el dataset y manejarlos adecuadamente.
3. **Codificar Variables Categóricas**: Convertir las variables categóricas en valores numéricos utilizando LabelEncoder.
4. **Dividir los Datos**: Separar el dataset en características (X) y variable objetivo (y), y luego dividirlo en conjuntos de entrenamiento y prueba.
5. **Crear y Entrenar el Modelo**: Crear una instancia del modelo RandomForestRegressor y entrenarlo con los datos de entrenamiento.
6. **Predecir y Validar**: Utilizar el modelo entrenado para hacer predicciones en el conjunto de prueba y calcular el error cuadrático medio (MSE) y la raíz cuadrada del MSE (RMSE).
7. **Visualización**: Crear un gráfico de dispersión para comparar los valores reales y predichos.
