# ProyectoParteIII-RINGELING
Proyecto Final Data Science I, comisión 74225

# Objetivo: Detector talentos en FIFA 21
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
