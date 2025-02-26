# Proyecto M7 UDD - Gianluca Contenla

## Descripción del Proyecto

Este proyecto tiene como objetivo aplicar técnicas avanzadas de ciencia de datos y aprendizaje automático para la detección de neumonía a partir de imágenes de rayos X de tórax. El proyecto incluye un análisis exploratorio de datos, limpieza, entrenamiento de un modelo de red neuronal, y la creación de una API REST para realizar predicciones.

## Tecnologías Utilizadas

### Lenguaje de Programación
- Python

### Librerías Principales
- TensorFlow/Keras
- NumPy
- Matplotlib/Seaborn
- Scikit-learn
- Flask

### Herramientas
- Google Colab (usado como IDE)
- GitHub (para subir el proyecto)

## Resultados del Modelo

El modelo alcanzó las siguientes métricas:

| Métrica  | Valor  |
|----------|--------|
| Accuracy | 90.5%  |
| Precision | 93.2%  |
| Recall  | 89.0%  |
| F1-score | 91.0%  |

### Matriz de Confusión
![image](https://github.com/user-attachments/assets/a2feba65-0e92-4337-a85f-71acaf0a5330)

### Gráficas de Entrenamiento

#### Evolución de la pérdida y el accuracy durante el entrenamiento
![image](https://github.com/user-attachments/assets/b4ddb3c8-0133-4524-9a91-d226543c8940)

#### Evolución del F1-score
![image](https://github.com/user-attachments/assets/98f291ed-758b-4c7b-b820-b558c982d650)

### Prueba del modelo prediciendo imágenes

![image](https://github.com/user-attachments/assets/c26063ae-c41c-40f3-a132-7684eb3f3153)

Se logró predecir 10/10 imágenes.

## API REST

El proyecto incluye una API REST construida con Flask que permite realizar predicciones en tiempo real.

- **Diagnóstico:** "Normal" o "Neumonía".
- **Confianza:** 91% aproximadamente.

## Contacto

**Nombre:** Gianluca Contenla  
**Email:** gianluca.contenla@gmail.com  
**GitHub:** [GianlucaCL](https://github.com/GianlucaCL)

---
Muchas gracias por ver mi proyecto para la UDD, cualquier feedback es bienvenido.
