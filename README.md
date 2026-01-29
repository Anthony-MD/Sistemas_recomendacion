# Neural-Movie-Recommender-Pytorch
Este proyecto implementa un sistema de recomendación híbrido basado en Deep Learning. Utiliza una arquitectura de **Filtrado Colaborativo Neuronal** para predecir las preferencias de los usuarios sobre películas, superando las limitaciones de los modelos lineales tradicionales mediante el uso de embeddings y redes neuronales densas.

# Movie Recommendation System: Neural Collaborative Filtering with PyTorch

## Descripción
Este proyecto implementa un sistema de recomendación híbrido basado en Deep Learning. Utiliza una arquitectura de **Filtrado Colaborativo Neuronal** para predecir las preferencias de los usuarios sobre películas, superando las limitaciones de los modelos lineales tradicionales mediante el uso de embeddings y redes neuronales densas.

## Stack Tecnológico
* **Framework:** PyTorch (elegido por su flexibilidad y control granular sobre los tensores).
* **Data Science:** Pandas, NumPy, Scikit-learn.
* **Visualización:** Matplotlib, Seaborn.

## Innovaciones Técnicas
* **Arquitectura MLP (Multi-Layer Perceptron):** Implementación de capas densas para capturar relaciones complejas y no lineales entre usuarios e ítems.
* **Ingeniería de Embeddings:** Creación de vectores latentes optimizados para representar perfiles de usuario y características de películas.
* **Normalización de Similitud:** Uso de similitud de coseno normalizada (con scores estables entre 50 y 70) para garantizar recomendaciones consistentes y evitar sesgos en los pesos de los embeddings.


## Análisis de Resultados
El sistema fue evaluado mediante la métrica de **Similitud de Coseno**, obteniendo resultados clave para la validación del modelo:
* **Puntuaciones entre 50 y 70:** Estos valores indican una separación clara entre categorías de películas y una captura precisa de las preferencias del usuario.
* **Consistencia:** El modelo logra agrupar ítems similares de manera efectiva, garantizando recomendaciones coherentes con el historial del usuario.


## Resultados y Conclusiones
* **Rendimiento Robusto:** El modelo demuestra una separación clara en los espacios latentes, permitiendo agrupar preferencias de usuario de forma efectiva.
* **Resolución de Problemas:** El proyecto fue migrado estratégicamente de TensorFlow a PyTorch para resolver conflictos de dependencias y optimizar la arquitectura del modelo, demostrando capacidad de adaptación técnica.
  
<img width="1414" height="125" alt="image" src="https://github.com/user-attachments/assets/9856b9e0-d0d1-4f29-b722-126c5949cb61" />


## Cómo ejecutar
1. Clonar el repositorio.
2. Instalar dependencias: `pip install torch pandas numpy scikit-learn matplotlib`.
3. Ejecutar el notebook `Practica_Final_SRV.ipynb`.
