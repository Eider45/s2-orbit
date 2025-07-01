Este proyecto implementa un modelo numérico para describir la órbita de la estrella S2 alrededor del agujero negro supermasivo Sagitario A* (Sgr A*), ubicado en el centro de la Vía Láctea. Utilizamos la métrica de Schwarzschild e integramos numéricamente las ecuaciones geodésicas utilizando la librería PyGRO, incorporando efectos relativistas como la precesión del periastro, el corrimiento gravitacional al rojo, y realizando un ajuste bayesiano de los parámetros orbitales mediante técnicas de Monte Carlo vía cadenas de Markov (MCMC).

Los datos observacionales utilizados provienen de: Gillessen et al. (2017) — https://arxiv.org/abs/1611.09144

Posiciones angulares:

- SHARP/NTT (1992–2002)

- NACO/VLT (2002–2016)

Velocidades radiales:

- NIRC2/Keck (antes de 2003)

- SINFONI/VLT (después de 2003)

Los archivos están disponibles en la carpeta datos/.


Este trabajo se basa en el ejemplo de la estrella S2 desarrollado por R. Dellamonica, disponible en el repositorio oficial de PyGRO:

https://github.com/rdellamonica/pygro

Documentación del ejemplo: https://rdellamonica.github.io/pygro


