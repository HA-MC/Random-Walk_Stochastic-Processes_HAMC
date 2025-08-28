# 🌀 Random Walk in Stochastic Processes  

This repository focuses on **Random Walk** a specific type of stochastic process.
The goal is to provide theoretical and practical examples to understand, simulate, and visualize this probabilistic model and explore its various applications. 

---

## 📖 Contenido del repositorio  

random-walk/
│── README.md # Este archivo
│── notebooks/ # Notebooks con simulaciones
│ ├── random_walk_basico.ipynb
│ ├── random_walk_2d.ipynb
│ └── random_walk_multidimensional.ipynb
│── src/ # Código fuente en Python
│ ├── random_walk.py
│ └── visualizacion.py
│── docs/ # Explicaciones teóricas
│ ├── introduccion.md
│ ├── aplicaciones.md
│ └── referencias.md
│── requirements.txt # Dependencias del proyecto


---

## 🧮 ¿Qué es un Random Walk?  

Un **Random Walk** es un proceso estocástico en el cual un valor evoluciona en pasos sucesivos aleatorios.  
Ejemplo clásico:  
- Imagina a una persona que en cada paso decide ir **izquierda** o **derecha** con igual probabilidad.  
- Después de muchos pasos, su posición final depende de la secuencia de elecciones.  

📊 Se utiliza en:  
- **Finanzas** (modelar precios de activos).  
- **Física** (movimiento Browniano).  
- **Biología** (dispersión de partículas).  
- **IA / Machine Learning** (simulación de entornos aleatorios).  

---

## ⚡ Ejemplos visuales  

### 🔹 Caminata aleatoria 1D  
![Random Walk 1D](https://upload.wikimedia.org/wikipedia/commons/6/6a/Random_walk_5000.svg)  

### 🔹 Caminata aleatoria en 2D  
![Random Walk 2D](https://upload.wikimedia.org/wikipedia/commons/2/29/RandomWalk_1000.gif)  

---

## 🚀 Instalación y uso  

1. Clona el repositorio:  
```bash
git clone https://github.com/tuusuario/random-walk.git
cd random-walk

Instala las dependencias:

pip install -r requirements.txt

Abre los notebooks en Jupyter:

jupyter notebook

---

## 🚀 Inicio rápido

Para clonar el repositorio, instalar las dependencias y ejecutar los notebooks, sigue estos sencillos pasos:

1.  **Clona el repositorio**:
    ```bash
    git clone [https://github.com/tu-usuario/random-walk.git](https://github.com/tu-usuario/random-walk.git)
    cd random-walk
    ```

2.  **Instala las dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Abre los notebooks con Jupyter**:
    ```bash
    jupyter notebook
    ```
    Una vez en Jupyter, navega a la carpeta `notebooks/` y explora los ejemplos.

---

## 📊 Visualizaciones

Aquí tienes una muestra de lo que puedes simular y visualizar.

### 🔹 Caminata Aleatoria en 1D

Imagina a un punto que se mueve a la izquierda o a la derecha de forma aleatoria en una línea. Su posición final es el resultado de una serie de decisiones binarias.

![Random Walk 1D](https://upload.wikimedia.org/wikipedia/commons/6/6a/Random_walk_5000.svg)

### 🔹 Caminata Aleatoria en 2D

En dos dimensiones, el movimiento es similar a una partícula de polen en el agua (movimiento browniano). En cada paso, la partícula puede moverse en cualquier dirección, creando una trayectoria errática y fascinante.

![Random Walk 2D](https://upload.wikimedia.org/wikipedia/commons/2/29/RandomWalk_1000.gif)

---