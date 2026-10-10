# Taller Redes Neuronales II — Backpropagation, funciones de activación y clasificación multiclase (MNIST sin CNN)

**Universidad de Cundinamarca · Especialización en Inteligencia Artificial · Deep Learning – Conceptos (2026)**
**Autor:** Juan Pablo Cristancho Tula

Actividad R1-A2-S4 *Redes Neuronales II*.

## Contenido

| Notebook | Tema | Colab |
|---|---|---|
| `01_perceptron_binaria_numpy` | Perceptrón de Rosenblatt vs. neurona sigmoide (NumPy) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Juanpatula2361/Taller-Redes-Neuronales-II/blob/main/notebooks/01_perceptron_binaria_numpy.ipynb) |
| `02_red_una_capa_oculta_numpy` | Red con una capa oculta: sigmoide vs. ReLU (NumPy) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Juanpatula2361/Taller-Redes-Neuronales-II/blob/main/notebooks/02_red_una_capa_oculta_numpy.ipynb) |
| `03_mlp_backpropagation_numpy` | MLP modular con backpropagation y gradient checking (NumPy) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Juanpatula2361/Taller-Redes-Neuronales-II/blob/main/notebooks/03_mlp_backpropagation_numpy.ipynb) |
| `04_mnist_mlp_keras` | MNIST con MLP en TensorFlow/Keras | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Juanpatula2361/Taller-Redes-Neuronales-II/blob/main/notebooks/04_mnist_mlp_keras.ipynb) |
| `05_mnist_mlp_pytorch` | MNIST con MLP en PyTorch | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Juanpatula2361/Taller-Redes-Neuronales-II/blob/main/notebooks/05_mnist_mlp_pytorch.ipynb) |

## Estructura

```
notebooks/   Cuadernos .ipynb de la actividad
results/     Figuras y métricas generadas (metricas_keras.json, metricas_pytorch.json, PNG)
scripts/     Scripts auxiliares
requirements.txt
```

## Ejecución

```bash
pip install -r requirements.txt
jupyter notebook notebooks/
```

Cada notebook también se puede abrir en Google Colab con el botón de la tabla.
