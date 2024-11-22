# Explicación

Se consideraron 4 partículas confinadas en un cuadrado de $L\times L$, sujetas al potencial de Lennard-Jones. Todas con la misma masa y radio, con condiciones de frontera reflectantes.

Para las condiciones iniciales se consideraron cuatro casos, haciendo una simulación por cada uno con base en el método de Verlet.

* **Caso 1**. Para el tiempo $t=0$: la posición inicial de cada partícula en la esquina del cuadrado y velocidades iniciales nulas.
* **Caso 2**. Para el tiempo $t=0$: la posición inicial de cada partícula en la esquina del cuadrado y velocidades iniciales aleatorias según la distribución de Maxwell-Boltzmann.
* **Caso 3**. Para el tiempo $t=0$: la posición inicial de cada partícula aleatoria dentro del cuadrado y velocidades iniciales nulas.
* **Caso 4**. Para el tiempo $t=0$: la posición inicial de cada partícula aleatoria dentro del cuadrado y velocidades iniciales aleatorias según la distribución de Maxwell-Boltzmann.

Cada programa imprime las posiciones iniciales y las posiciones finales (después de un tiempo dado por el intervalo utilizado en el método de Verlet y el número de paso) de cada partícula. Muestra también de forma gráfica la posición inicial y final de cada partícula dentro del cuadrado, haciendo más intuitivo el análisis de este sistema.
