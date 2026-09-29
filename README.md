# Modelo de Ising en dos dimensiones

[English version](README.en.md)

Trabajo práctico de Mecánica Estadística sobre redes de Ising bidimensionales, implementado en Python mediante el algoritmo de Metropolis.

## Contenido

El notebook desarrolla simulaciones para redes cuadradas y hexagonales con condiciones de contorno periódicas. Calcula y analiza observables termodinámicos, entre ellos la energía, la magnetización, la susceptibilidad y el calor específico, en función de la temperatura y del tamaño de la red. También explora la termalización y el comportamiento de los estados de espín a distintas temperaturas.

El desarrollo y las visualizaciones están en [`modelo_ising_2d.ipynb`](modelo_ising_2d.ipynb).

## Requisitos

- Python 3
- NumPy
- Matplotlib
- Numba
- SciPy
- tqdm

## Ejecución

Instalá las dependencias:

```bash
python -m pip install -r requirements.txt
```

Abrí `modelo_ising_2d.ipynb` en Jupyter o Google Colab y ejecutá las celdas en orden. Algunas simulaciones usan redes grandes y muchas iteraciones, por lo que pueden requerir bastante tiempo y memoria.

## Equipo

Grupo 15, Mecánica Estadística,  2025 2C.

- *Sammy Vallejo*
- Eugenio Andrés Della Valle
- Abraham Machicado

