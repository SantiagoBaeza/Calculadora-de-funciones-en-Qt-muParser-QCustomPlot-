[⬅️ Volver a "Proyectos con Qt"](https://github.com/SantiagoBaeza/proyectos-con-Qt/tree/main)

# Calculadora de funciones en Qt

Este proyecto implementa una calculadora gráfica en **Qt** que permite graficar dos funciones matemáticas, calcular áreas bajo curvas y realizar operaciones entre funciones (suma, resta, multiplicación y división).  
Se integraron las librerías externas **muParser** y **QCustomPlot** mediante DLL, logrando una interfaz interactiva y funcional.

---

## Contexto

Este ejercicio fue desarrollado en un **recuperatorio académico**, donde el objetivo principal era entregar una solución funcional en tiempo limitado.  
Por esa razón el código contiene funciones similares repetidas, aunque cumple plenamente con su propósito y demuestra integración de librerías externas y manejo de gráficos en Qt.

---

## Capturas

- **Captura 01**: Interfaz mostrando dos funciones graficadas y operaciones realizadas entre ellas.  
  ![Interfaz](screenshot.png)

---

## Funcionalidad

- Graficar dos funciones matemáticas en un rango definido.  
- Calcular el área bajo una curva mediante el método del trapecio.  
- Realizar operaciones entre funciones: suma, resta, multiplicación y división.  
- Validación de entradas con mensajes de advertencia.  
- Visualización de resultados en displays LCD dentro de la interfaz.

---

## Tecnologías utilizadas

- Qt (C++), señales y slots.  
- Librería externa: **muParser** (DLL).  
- Librería externa: **QCustomPlot** (DLL).  
- Widgets: QPushButton, QLineEdit, QLCDNumber, QCustomPlot.  
- Algoritmos de integración numérica implementados en C++.

---

## Comentarios finales

Los archivos del proyecto están incluidos en este repositorio para que cualquier persona pueda descargarlos y compilarlos localmente en **Qt** con las librerías **muParser** y **QCustomPlot**.  
De esta manera, es posible revisar el código, ejecutar la aplicación y comprobar tanto la evaluación de funciones como la representación gráfica y las operaciones entre ellas.

---

> 🧩 Estos espacios están en construcción y se actualizan de forma frecuente.
