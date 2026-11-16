# Recomendación de planes móviles para Megaline

## Descripción

Modelo de clasificación que recomienda el plan Smart o Ultra a partir del uso mensual de cada cliente (llamadas, minutos, mensajes y datos). La meta era superar 75 % de exactitud.

## Resultados principales

- Dividí los datos en entrenamiento, validación y prueba (60/20/20).
- Comparé árbol de decisión, bosque aleatorio y regresión logística, ajustando hiperparámetros con validación.
- El bosque aleatorio (50 árboles, profundidad 10) logró **79.9 %** de exactitud en prueba, frente a 75.9 % de la regresión logística.

## Herramientas

Python, pandas, scikit-learn

## Cómo ejecutarlo

```bash
pip install -r requirements.txt
jupyter notebook 04_recomendacion_planes_megaline.ipynb
```

Los datos provienen del programa de formación en ciencia de datos y no se incluyen en este repositorio. El notebook se puede revisar con todas sus salidas directamente en GitHub.

## Autor

Diego Parra · [LinkedIn](https://www.linkedin.com/in/diegoparragar)
