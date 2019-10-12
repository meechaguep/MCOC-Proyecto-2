# MCOC-Proyecto-2



En este proyecto se busca poder simular el transporte de sedimento minero.

Integrantes:

Piedad Bull: https://github.com/piedadbull .

Matias Echagüe: https://github.com/meechaguep .

Pedro Naretto: https://github.com/PedroNaretto .

Catalina Solano: https://github.com/cpsolano .



## Entrega 4

En este proyecto se busca poder simular el transporte de sedimento minero de fondo de ríos. Esto se realizará en base a métodos langrangianos, es decir, que estudia el movimiento de cada partícula de forma individual.

Se tomarán como supuestos las siguientes condiciones:

Diámetros de la partícula (d)= 15 mm

Densidad de la partícula (rho_particula) = 2650 kg/(m^3)

Densidad del agua (rho_agua) = 1000 kg/(m^3)

Constante de drag (Cd) = 0.47

Constante de lifting (Cl) = 0.2

Constante de peso (Cm) = 0.5

Velocidad del flujo en x (vfx) = 5.0 m/s

Velocidad del flujo en y (vfy) = 0.1 m/s

El intervalo de tiempo en los que grafica la posición de la partícula fue de (dt) = 0.001 s, con un tiempo máximo de simulación (tmax) de 1 s. Esto fué igual para las tres pruebas mostradas en los resultados.

## Validación

Al comparar los datos que se obtuvieron a partir del código con los del profesor, se puede ver una similitud para 2 particulas, con una diferencia de un decimal, lo cual se puede justificar por temas de unidades, pero se logra hacer una validación por los resultados obtenidos que se mueven en un rango parecido haciendo la excepción del decimal.

![alt text](https://github.com/cpsolano/MCOC-Proyecto-2/blob/master/Gr%C3%A1ficos/2%20p.png)

![alt text](https://github.com/cpsolano/MCOC-Proyecto-2/blob/master/Gr%C3%A1ficos/particle_positions%202.png)

Por otro lado, no se logra hacer una validación para una mayor cantidad de particular con respecto al movimiento que se espera entre ellas, pero se logran valores parecidos igual. El tener un movimiento distinto se puede deber a una modelación distinta del choque entre particulas.

![alt text](https://github.com/cpsolano/MCOC-Proyecto-2/blob/master/Gráficos/5%20p.png)
![alt text](https://github.com/cpsolano/MCOC-Proyecto-2/blob/master/Gr%C3%A1ficos/10%20p.png)

Comparación para 20 particulas

![alt text](https://github.com/cpsolano/MCOC-Proyecto-2/blob/master/Gr%C3%A1ficos/20.1%20p.png)

![alt text](https://github.com/cpsolano/MCOC-Proyecto-2/blob/master/Gr%C3%A1ficos/particle_positions%201.png)

## Características del computador:

Fabricante: ASUSTek Computer Inc.

Procesador: Intel(R)Core(TM)i7-7700HQ CPU @ 2.80GHz 2.81GHz

Memoria instalada (RAM) : 16.0 GB (15.9 GB utilizable)

## Graficos y tiempos 
En este computador se corrió para 3 cantidades de partículas, obteniendo así los siguientes gráficos y tiempos. Para 4 particulas, el tiempo transcurrido en procesar el código fue de 13.30s, para 11 fue de 154.24s, y para el de 20 partículas el tiempo fue de 409.97s. 

![alt text](https://github.com/meechaguep/MCOC-Proyecto-2/blob/master/Grafico_4_particulas_2.png)
![alt text](https://github.com/meechaguep/MCOC-Proyecto-2/blob/master/Grafico_11_particulas.png)
![alt text](https://github.com/meechaguep/MCOC-Proyecto-2/blob/master/Grafico_20_particulas.png)
