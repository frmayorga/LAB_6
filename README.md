# LAB_6

# OBJETIVOS

## OBJETIVO GENERAL 
 
- Demostrar experimentalmente el teorema de la maxima transferencia de potencia con la ayuda del simulador DCACLab, en el problema dado, para indicar las corrientes, voltajes y potencias corespondidnetes, al modificar un resistor(Rl) en el circuito indicado.   

## OBJETIVO ESPECIFICO

- Hallar los valores correspondientes de voltaje, corriente y potencia en el simulador, al cambiar el dato de Rl.
- Determinar con los calculos la potencia en cada caso y comparar con el valor del simulador.
- Buscar el error porcentual que exiten en las potencias de los diferentes datos del Rl. 

# MARCO TEORICO

![teorema de potencia](https://user-images.githubusercontent.com/93361435/148871802-5b3d6a8b-b4f9-4f48-a644-7f0e7d0f9d33.jpg)

**CODIGO DE COLORES PARA RESISTORES DE 4 BANDAS** 

| DIGITO | COLOR |
|--------|------------|
| 0 | Negro |
| 1 | Café |
| 2 | Rojo |
| 3 | Naranja |
| 4 | Amarillo |
| 5 | Verde |
| 6 | Azul |
| 7 | Violeta |
| 8 | Gris |
| 9 | Blanco |

TOLERANCIA : Oro +- 5%; Plata +- 10%.


# PROCEDIMIENTO

Se procedio al armado del circuito en los simuladores tinkercad y DCACLab presente en la figura: 

![image](https://user-images.githubusercontent.com/93361435/148960620-a8784434-38d4-41aa-b48c-a9642f0e8ee4.png)

Se midio el voltaje y corriente de los resistores en tinkercad despues se procedio al calculo teórico de la potencia en cada uno de los resistores con el fin de demostrar el teorema de máxima potencia. Se ordeno estos datos en la tabla 6.1

# RESPUESTA DE INTERROGANTES Y CALCULO DE ERROR

**Tabla 6.1**

| RL (Ohmios) | Corriente Medida (mA) | Voltaje Medido (V) | Potencia Calculada Experimentalmente (W) | Potencia Calculada Teóricamente (W) | 
|-------------|-----------------------|--------------------|------------------------------------------|-------------------------------------|
| 220 Ohmios | 10.6 mA | 2.32 V | 26 mW | 24.54 mW |
| 470 Ohmios | 8.98 mA | 4.22 V | 38 mW | 37.92 mW |
| 680 Ohmios | 7.98 mA | 5.43 V | 44 mW | 43.28 mW |
| 820 Ohmios | 7.21 mA | 6.09 V | 43 mW| 42.63 mW |
| 1000 Ohmios | 6.82 mA | 6.82 V | 48 mW| 46.51 mW |
| 1500 Ohmios | 5.56 mA | 8.33 V | 50 mW| 46.37 mW |
| 1800 Ohmios |  5.00 mA |  9.00 V |  45 mW  |  45 mW |
| 2200 Ohmios |  4.41 mA |  9.71 V |  39 mW  |  42.8 mW |
| 3900 Ohmios |  2.94 mA |  11.50 V |  34 mW  |  33.71 mW |
| 4700 Ohmios |  2.54 mA |  11.90 V |  36 mW  |  30.32 mW |


#### 6.5.4. ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.

- Si, ya que como se observo al momento del que el valor de RL se acerca al valor de R1 la potencia aumenta, sin embargo cuando este valor aumenta la potencia no hace mas que disminuir, demostrando que para tener la potencia máxima R1 = RL  

#### 6.5.5 ¿Cuál fue la potencia máxima en RL?

- La potencia maxima en la parte medida fue de 50 mW cuando el resistor es de 1500 ohmios, pero la maxima medidada fue de 46.51 mW cuando el resistor es de 1000 ohmios.

#### 6.5.6. ¿Para qué valor de RL se obtiene la MTP?

- la maxima transferencia de potencia se obtiene cuando RL es igual a 1000 Ohms para los resistores proporcionados en este trabajo, sin embargo, la verdadera potencia maxima se alcanza cuando Rl es 1200 Ohms.


## CÁLCULO DE ERROR

Calculo de error de la potencia en los distintos resistores: 

![image](https://user-images.githubusercontent.com/93361435/149404872-9701c2a5-5936-4c94-a775-aad7472dbd80.png)  

![image](https://user-images.githubusercontent.com/93561706/149441021-31ff949e-d294-4b84-aac4-8a53515f236d.png)

![image](https://user-images.githubusercontent.com/93398718/149416869-a25012bf-45b8-4be9-bb2a-ddd638ed80b4.png)  


# VIDEO

https://youtu.be/V3VHKAaO3Pw

# CONCLUSIONES
- el teorema de maxima transferencia de potencia se cumple pues pudimos notar que una vez pasada la zona en la cual se encontraba el valor del resisitor que causa este efecto la potencia empezaba a disminuir sin importar que el valor de la resistencia aumentara.
- las potencias obtenidas de manera teorica no alcanzaban en ocasiones las potencias medidas con el simulador por este motivo llegamos a la conclusion de que quiza el simulador no era lo suficientemente confiable.

# BIBLIOGRAFIA

- Floyd, T. (2007). *Principios de circuitos eléctricos*. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) *Analisis de circuitos Teoria y Practica*. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
