# 🚀 Fundamentos de Python - Control y Funciones

¡Bienvenido(a) a este repositorio! Aquí encontrarás las soluciones a tres retos prácticos de programación en **Python**. El objetivo principal de estos ejercicios es afianzar conceptos clave de programación estructurada, tales como:
- **Funciones y modularidad.**
- **Estructuras condicionales (`if`, `elif`, `else`).**
- **Estructuras iterativas (ciclos `for` y `while`).**
- **Estructuras de datos básicas (Listas y Diccionarios).**

Este proyecto fue desarrollado en colaboración con **Juan Pablo Serna Arboleda**.

---

## 🛠️ Requisitos
Para poder ejecutar los scripts, asegúrate de tener instalado:
- [Python 3.x](https://www.python.org/downloads/) en tu sistema operativo.

---

## 📁 Estructura del Proyecto
El proyecto está organizado en la carpeta `src/`, dividida por las temáticas de cada reto:
```text
├── src/
│   ├── funciones/
│   │   └── reto1.py
│   ├── condicionales/
│   │   └── reto2.py
│   └── iterativas/
│       └── reto3.py
└── README.md
```

---

## 💻 Descripción de los Retos

### 🔹 Reto 1: Reporte de Horas (Funciones y Ciclos)
**Ubicación:** `src/funciones/reto1.py`

**Descripción:**  
Este script está diseñado para gestionar el tiempo de un programador. Interactúa con el usuario solicitando su nombre y cuántos proyectos tiene asignados. Utilizando un ciclo `while`, pide las horas dedicadas a cada proyecto de forma secuencial. Al finalizar, genera un reporte detallado con el total de horas, el promedio y el porcentaje de tiempo dedicado a cada proyecto específico.

**Conceptos aplicados:** Listas, ciclos `while`, cálculos de promedios y porcentajes, prevención de división por cero.

**Ejecución:**
```bash
python src/funciones/reto1.py
```

### 🔹 Reto 2: Gestión de Inventario (Condicionales)
**Ubicación:** `src/condicionales/reto2.py`

**Descripción:**  
Este script simula un sistema de control de stock de un inventario a partir de una lista predefinida de cantidades. Utiliza estructuras condicionales `if-elif-else` para clasificar cada producto y emitir una alerta:
- **Agotado (0):** Requiere reorden inmediata.
- **Crítico (1 a 5):** Se sugiere reposición.
- **Adecuado (> 5):** Nivel de stock saludable.
Al final, entrega un resumen ejecutivo mostrando los índices de los productos agotados, las cantidades críticas y el porcentaje de disponibilidad total del inventario.

**Conceptos aplicados:** Listas, iteraciones con `for`, condicionales anidados, funciones nativas (`len()`).

**Ejecución:**
```bash
python src/condicionales/reto2.py
```

### 🔹 Reto 3: Analizador de Texto (Iterativas y Diccionarios)
**Ubicación:** `src/iterativas/reto3.py`

**Descripción:**  
Este programa actúa como un contador de frecuencias de palabras. Se le pide al usuario ingresar una frase o párrafo largo; el código se encarga de "limpiar" el texto pasándolo a minúsculas y removiendo signos de puntuación comunes. Posteriormente, separa las palabras y utiliza un **diccionario** para almacenar y contar cuántas veces se repite cada una. Finalmente, determina e imprime cuál fue la palabra más frecuente en todo el texto.

**Conceptos aplicados:** Manipulación de strings (`.lower()`, `.replace()`, `.split()`), uso avanzado de Diccionarios y búsqueda de máximos.

**Ejecución:**
```bash
python src/iterativas/reto3.py
```

---

¡Gracias por visitar este repositorio! Si tienes alguna sugerencia o quieres probar los códigos, siéntete libre de clonarlo.
