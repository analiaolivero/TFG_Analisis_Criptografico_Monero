# Análisis criptográfico de la criptomoneda Monero

Este repositorio contiene los cuadernos de python (Jupyter Notebooks) desarrollados como material práctico y visual para el Trabajo de Fin de Grado (TFG) en la Universidad Politécnica de Madrid (UPM). 

El objetivo de este código es ilustrar los conceptos matemáticos y algorítmicos que fundamentan la privacidad de la criptomoneda Monero.

* **Autora:** Analía Olivero Betancor
* **Institución:** Universidad Politécnica de Madrid (UPM)

## Estructura del repositorio

El código está dividido en dos cuadernos independientes correspondientes a los capítulos de la memoria del TFG:

* **`Capitulo_1_Fundamentos.ipynb`** (análisis de las curvas elípticas). Incluye la representación de la ley de grupo mediante el método de la cuerda y tangente en curvas de Weierstrass, y la construcción geométrica mediante hipérbolas en curvas de Edwards retorcidas.
* **`Capitulo_4_Firma_Anillos.ipynb`** (simulación del protocolo de Monero mediante grafos acíclicos dirigidos bipartitos). Simulación del ataque de deducción por cero señuelos (reacción en cadena) para ilustrar la vulnerabilidad histórica de la red cuando permitía el uso de firmas de anillo de distinta longitud, evaluando la pérdida de privacidad colectiva a través de la matriz de probabilidades $W$.

## Requisitos y ejecución

Para reproducir las simulaciones y generar las gráficas exactas que aparecen en la memoria del TFG, es necesario tener instaladas las siguientes librerías de Python:

```bash
pip install numpy matplotlib networkx jupyter
```
