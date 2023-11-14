# Descripcion

Aplicación simple del modelo GARCH a la serie temporal del paris index del periodo 2016 al 2023.

El modelo se implementó mediante la librería ***pyflux***, para utilizarlo se deben instalar las dependencias del archivo **requirements.txt** y solo funcionan con una versión **Python <= 3.11**. 

# Resultados

El modelo captura el comportamiento general de los datos (máximos y mínimos coinciden) pero el forecasting no es bueno. Una de las posibles justificaciones puede ser la forma en la que se implementa GARCH en pyflux, se debe hacer un análisis más cuidadoso y comparar con otras librerías.
