# 🌀 Random Walk in Stochastic Processes  

This repository focuses on **Random Walk** a specific type of stochastic process.
The goal is to provide theoretical and practical examples to understand, simulate, and visualize this probabilistic model and explore its various applications. 

---

## 📖 Repository content  

```bash
random-walk/
├── README.md               # 📄 Welcome file.
├── notebooks/              # 📚 Jupyter notebooks for interactive simulations.
│   ├── random_walk_1d.ipynb
│   ├── random_walk_2d.ipynb
│   └── random_walk_multidimensional.ipynb
├── src/                    # 🐍 Python source code, with reusable functions.
│   ├── random_walk.py
│   └── visualizacion.py
├── docs/                   # 📝 Theoretical documentation and detailed explanations.
│   ├── introduccion.md
│   ├── aplicaciones.md
│   └── referencias.md
└── requirements.txt        # 📦 Dependencies needed to run the project.
```

---

## 🧮 ¿What is a random walk?  

A **Random Walk** is a stochastic process in which a value evolves in succesive random steps.  

📊 It is used in :  
- **Finance** (model asset prices).  
- **Physics** (Brownian motion).  
- **Biology** (particle scattering).  
- **IA / Machine Learning** (simulating random environments).  

---

## ⚡ Ejemplos visuales  

### 🔹 Random Walk 1D  
![Random Walk 1D](notebooks/plots/00_RandomWalk1D.png)  

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
```

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

## Results and Conclusions

- 1D random walk simulations were performed with up to N user-defined steps.
- The results show that the final position can vary widely due to randomness.
- These simulations allow for the introduction of concepts of stochastic processes and probability theory.