# Fundamentos de Python - Control y Funciones

Este repositorio contiene las soluciones a los retos prácticos de programación en Python. El objetivo principal es la aplicación de conceptos clave de programación estructurada, tales como:
- Funciones y modularidad.
- Estructuras condicionales (`if`, `elif`, `else`).
- Estructuras iterativas (ciclos `for` y `while`).
- Estructuras de datos básicas (Listas y Diccionarios).

**Desarrollado en colaboración con:** Juan Pablo Serna Arboleda.

---

## Requisitos
- Python 3.x instalado en el sistema.

---

## Estructura del Proyecto
El código fuente está organizado en la carpeta `src/`, separando cada reto según su temática:
```text
├── src/
│   ├── condicionales/
│   │   └── reto2.py
│   ├── funciones/
│   │   └── reto1.py
│   └── iterativas/
│       └── reto3.py
└── README.md
```

---

## Ejercicios y Descripción

### 1. Reto 1: Funciones (`src/funciones/reto1.py`)
Este script gestiona el tiempo de un programador. Interactúa con el usuario solicitando cuántos proyectos tiene asignados y utiliza un ciclo para pedir las horas dedicadas a cada proyecto. Al finalizar, genera un reporte detallado.

- **Conceptos aplicados:** Listas, ciclos `while`, cálculos de promedios y porcentajes.
- **Cómo ejecutarlo:**
```bash
python src/funciones/reto1.py
```

### 2. Reto 2: Condicionales (`src/condicionales/reto2.py`)
Este script simula un sistema de control de inventario a partir de una lista predefinida. Utiliza estructuras condicionales para clasificar cada producto y emite una alerta (Agotado, Crítico o Adecuado). Al final, entrega un resumen con índices de agotados, valores críticos y porcentaje de disponibilidad.

- **Conceptos aplicados:** Listas, iteraciones con `for`, condicionales anidados, función `len()`.
- **Cómo ejecutarlo:**
```bash
python src/condicionales/reto2.py
```

### 3. Reto 3: Iterativas (`src/iterativas/reto3.py`)
Este programa funciona como un contador de frecuencias de palabras. Se ingresa una frase larga; el código limpia el texto (minúsculas, sin signos de puntuación comunes), separa las palabras y utiliza un diccionario para almacenar y contar las repeticiones. Finalmente, determina la palabra más frecuente.

- **Conceptos aplicados:** Manipulación de strings (`lower`, `replace`, `split`), Diccionarios, búsqueda de valores máximos.
- **Cómo ejecutarlo:**
```bash
python src/iterativas/reto3.py
```
