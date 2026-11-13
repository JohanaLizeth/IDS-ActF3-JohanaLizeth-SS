# Actividad Formativa 3: Implementación y Evaluación de Filtros Digitales

Este repositorio contiene el código desarrollado en Python (Google Colab) para el diseño, simulación y análisis de filtros digitales en el dominio del tiempo y de la frecuencia.

## Objetivo
Diseñar e implementar filtros digitales **Pasa Bajos**, **Pasa Altos** y **Pasa Bandas** utilizando métodos IIR y FIR, evaluando su efectividad sobre una señal compuesta contaminada con ruido blanco.

## Contenido del Código (`Actividad3_Filtros_Digitales.ipynb`)
1. **Generación de señal de entrada:** Creación de una señal compuesta por tres frecuencias (15 Hz, 120 Hz y 350 Hz) más ruido blanco gaussiano.
2. **Análisis espectral (FFT):** Visualización del espectro de frecuencia antes del filtrado.
3. **Filtro Pasa Bajos (IIR Butterworth):** Frecuencia de corte en 40 Hz para aislar la componente de 15 Hz.
4. **Filtro Pasa Altos (IIR Chebyshev Tipo I):** Frecuencia de corte en 250 Hz para aislar la componente de 350 Hz.
5. **Filtro Pasa Bandas (FIR con ventana Hamming):** Banda de paso de 80 Hz a 160 Hz para aislar la componente intermedia de 120 Hz.
6. **Respuesta en frecuencia:** Evaluación comparativa de la ganancia y atenuación de los tres filtros diseñados.

## Librerías Utilizadas
* `numpy`
* `scipy.signal`
* `matplotlib`
