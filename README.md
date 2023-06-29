# Tesis-CIIS
Códigos principales empleados para obtener los resultados mostrados en la tesis de maestría "Cuantificación de la incertidumbre en la inversión del deslizamiento sísmico", elaborada por Isaac Valverde 

En este repositorio se encuentran 8 notebooks de Jupyter, el primero llamado "Programa1.ipynb" contiene la resolución de un problema de inversión mediante inferencia bayesiana.

Dicho problema consiste en ajustar el modelo de una recta a una serie de datos sintéticos generados a partir perturbaciones aleatorias a una serie de datos obtenidos de la evaluación de la función de una recta con una pendiente y ordenada al origen dadas.

El segundo es nombrado "Programa2.ipynb" y resuelve el caso sintético presentado por Nocquet (2018) mediante dos metodologías, la primera utilizando la estrategia semianalítica que él mismo propone y la segunda simulando muestras de la posterior mediante MCMC.

El tercer notebook llamado "Programa3.ipynb" resuelve el problema de aplicación real correspondiente al sismo de Acapulco del 7 de septiembre de 2021, a partir de la estrategia semianalítica con una simplificación para evitar el cálculo de integrales multivariadas.

El notebook llamado "Programa4_1.ipynb" fue escrito con la ayuda del M.C. Isaias Manuel Ramirez Bañales. Este simula muestras de la TMVN posterior de forma eficiente.

El notebook nombrado "Programa4_2.ipynb" carga las muestras generadas con "Programa4_1.ipynb" y despliega una gráfica para determinar el quemado y el IAT como referencia para determinar el lag. Posteriormente se obtiene una muestra efectiva que se utiliza para calcular los coeficientes de variación de cada parámetro.

Los notebooks "Programa5_1.ipynb" y "Programa5_2.ipynb" fueron escritos con el propósito de explorar los valores de alpha y discretización respectivamente, involucrados en la resolución de la estrategia semianalítica de Nocquet (2018) utilizando QMC para el problema de aplicación.

El notebook nombrado "Programa6.ipynb" calcula los coeficientes de variación del problema de aplicación usando la estrategia semianalítica de Nocquet (2018) para obtener las marginales, utilizando QMC para resolver las integrales involucradas.
