# ProyectoParteIII-RINGELING
Proyecto Final Data Science I, comisión 74225

# Link Colab:
https://colab.research.google.com/drive/1bu8PwQvtsAEaMhAT_yNYW_-xJ4xuU0mm?usp=sharing

# Objetivo: Detección talentos en FIFA 21
Este proyecto utiliza un dataset de jugadores del juego FIFA 21 para construir un modelo de clasificación que predice la categoría sobre l calidad de cada jugador (Elite, muy bueno...) en función de las caracteristicas técnicas, físicas y mentales. El objetivo final es identificar jugadores que están subvalorados o sobrevalorados, lo que podría ser útil al momento de tomar decisiones de scouting o análisis del mercado

# Metodología:
# 1. Limpieza y preparación de datos
- Conversión de valores monetarios existentes y unidades físicas
- Eliminación de columnas que no agregan valor (URLs, imágenes)
- Codificación de variables categóricas

# 2. Clasificación jugadores
- Se definieron categorías (Elite, Muy Bueno, etc) según evaluación llamada ↓OVA<<
- Se aplicó modelo Random Forest Classifier

# 3. Evaluación:
- Se utilizaron métricas como Precisión, Recall, F1-Score
- Se analizaron las predicciones correctas, subvaloradas y se generó un ranking

# Resultados:
- El modelo alcanzó un alto nivel de precisión
- Se generaron visualizaciones que ayudan a comprender la distribución de calidad entre los jugadores.
- Se identificaron posibles talentos ocultos y jugadores sobrevalorados en el dataset

#Conclusión:
Con este proyecto queda demostrado que es posible aplicar técnicas de Machine Learning, como Random Forest y selección de características para detectar discrepancias entre la percepción, el cual es el rating oficial del juego y el rendimiento potencial de los jugadores en FIFA 21.  
Gracias a la combinación de análisis de datos, gráficas y evaluación de métricas se logró identificar talentos ocultos y jugadores sobrevalorados con fundamentos técnicos.
El modelo alcanzó un rendimiento eficaz y balanceado entre clases, lo que lo convierte en una herramienta útil para complementar procesos de scouting, desarrollo de videojuegos o análisis deportivo.  
A futuro, el modelo podría mejorar incluyendo datos de rendimiento real (goles, asistencias), expandiendo a otras ligas y utilizando algoritmos más avanzados.

Este enfoque de clasificación basado en datos puede trasladarse fácilmente a escenarios reales en el deporte o la industria del entretenimiento.



