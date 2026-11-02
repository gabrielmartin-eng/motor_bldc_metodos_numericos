# Caracterización y Modelamiento Numérico de un Motor BLDC
**Banco de Pruebas basado en Arduino Nano**

## 👥 Integrantes
- Martin Cravero, Gabriel
- Estefany Paima
- Tu Nombre (Documentación y Métodos Numéricos)

---

## 📌 Descripción del Proyecto
## 📌 Descripción del Proyecto
El sistema consiste en un banco de caracterización electromecánica experimental para un motor Brushless DC (BLDC) trifásico gobernado por un ESC de 40A. 

La adquisición de datos en tiempo real se ejecuta mediante un microcontrolador (Arduino Nano / ESP32) vinculado a:
- **Módulo INA219 (I2C):** Medición de tensión y corriente DC de entrada.
- **Sonda DS18B20:** Monitoreo térmico sumergible del motor.
- **Sensor Hall 3144E:** Lectura de pulsos mediante interrupción externa para el cálculo de velocidad angular (RPM).

Los datos recolectados se procesan mediante métodos numéricos para el modelamiento de curvas de rendimiento, ajuste de parámetros y análisis electromecánico.
---

## 🧮 Métodos Numéricos Aplicados
- **Interpolación (Lagrange / Splines):** Modelamiento de la curva torque-velocidad.
- **Ajuste por Mínimos Cuadrados:** Estimación de constantes eléctricas y mecánicas.
- **Diferenciación e Integración Numérica:** Cálculo de velocidad angular y aceleración a partir de lecturas de sensores.

---

## 📁 Estructura del Repositorio
- `/codigo_arduino`: Código cargado en el Arduino Nano para adquisición de datos.
- `/mediciones`: Archivos CSV con los datos crudos tomados en el banco de pruebas.
- `/metodos_numericos`: Scripts (Python / MATLAB / Octave) con los algoritmos numéricos.

---

## 📊 Resultados
*(En esta sección se añadirán las gráficas y comparativas de los métodos numéricos)*
