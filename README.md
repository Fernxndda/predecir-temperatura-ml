# Predicción de Temperatura — ESCOM IPN

Aplicación en Python que consulta la temperatura actual en la Escuela
Superior de Cómputo (ESCOM-IPN) y predice cómo va a cambiar en las
próximas 3 horas, usando un modelo de Machine Learning.

## ¿Cómo funciona?
- Obtiene la temperatura actual desde **WeatherAPI.com**
- Descarga el historial de 60 días desde **Open-Meteo**
- Entrena un modelo **Random Forest** con 23 variables
- Predice la temperatura cada 30 minutos por las próximas 3 horas

## Tecnologías
- Python 3
- scikit-learn, pandas, numpy
- APIs: WeatherAPI.com y Open-Meteo

## Cómo usarlo
1. Abre el notebook en Google Colab
2. Obtén una API key gratis en [weatherapi.com](https://www.weatherapi.com)
3. Reemplaza `TU_API_KEY_AQUI` con tu key
4. Ejecuta todas las celdas

## Resultado
El programa genera un reporte en consola con las condiciones
actuales y el pronóstico por intervalos de 30 minutos.**
