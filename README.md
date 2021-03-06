# Práctica 1


## *PLANTEAMIENTO DEL PROBLEMA*

Durante las últimas semanas hemos sido participes de conocer una nueva rama de la carrera de Ingeniería Mecatrónica, los circuitos eléctricos, se ha analizado y resuelto una variedad de circuitos eléctricos. Para la resolución de los mismos tenemos que recurrir a diferentes leyes, sin embargo, es necesario demostrarlas para su mejorar comprensión, en este caso es de sumo interés comprobar que las leyes de Voltaje y Corriente de Kirchhoff se cumplen dentro del análisis de nuestros circuitos.

## *OBJETIVO:*

-Demostrar experimentalmente la Leyes de Voltaje y de Corriente de Kirchhoff mediante el uso de simuladores para comprender de mejor manera los conomimiento previamente adquiridos.

-Familiarizar al estudiante en el uso de instrumentos del laboratorio.

## *LISTA DE MATERIALES:*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Fuente de voltaje de C.D |
| 2  | Multímetros digitales |
|  1 | Resistor de 1k  |
|  2 | Resistores de 2,2K  |
| 1 | Resistor de 1,8k  |
| 1  | Resistor de 3,9k  |
| 1  | Protoboard          |

## *MARCO TEÓRICO*

La Ley de Ohm establece que el voltaje entre los extremos de muchos tipos de materiales conductores es directamente proporcional a la corriente que fluye a través del material.      V = IxR. Por otro lado las Leyes de Kirchhoff constituyen la base para el análisis de los circuitos eléctricos. Sus conceptos básicos son tan amplios, que pueden aplicarse a cualquier circuito, desde el circuito más sencillo, hasta la red más compleja.

Primera Ley de Kirchhoff: La suma algebraica de las corrientes que entran (o salen de) a una unión de dos o más elementos es igual a cero. Esto significa que la suma de las corrientes que entran a la unión es igual a la suma de las corrientes que salen de ella, como se aprecia en la figura 1.


![PrimeraLey](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%201.png)

Fig. 1. Primera Ley de Kirchhoff


Segunda Ley de Kirchhoff: La suma algebraica de las diferencias de potencial alrededor de cualquier trayectoria cerrada en un circuito es cero. Esto significa que, en un circuito cerrado, la suma de las elevaciones de tensión es igual a la suma de las caídas de tensión. La figura 2 muestra dos resistencias en serie, en cada una hay una caída de potencial, la suma de esas dos caídas de potencial es igual al voltaje suministrado por la fuente. 

![SegundaLey](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%202.png)

Fig. 2. Segunda Ley de Kirchhoff


## *PROCEDIMIENTO*

1.	Construir en el Protoboard el circuito de la figura 3.

![CircuitoPropuesto](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%203.png)

Fig. 3. Circuito resistivo mixto

2.	Medir y registrar en la tabla la caída de voltaje y corriente en cada uno de los elementos del circuito.

## *TABULACIÓN DE DATOS*

| Variable | Valor Calculado | Valor Medido |
| ----- | ----- | ----- |
| VR1 (V) | 2,053 | 2,046 |
| IR1(mA) | 2,053 | 2,056 |
| VR2(V) | 4,251 | 4,223 |
| IR2(mA) | 1,09 |1,088|
| VR3(V) | 2,1255 | 2,115 |
| IR3 (mA) | 0,963 | 0,964 |
| VR4(V) | 2,1255 | 2,115|
| IR4(mA) |  0,963 | 0,964 |
| VR5(V) | 3,696 | 3,73|
| IR5(mA) | 2,053 | 2,046|

Tabla  I. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Tabla%202.png)

Tabla II. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Tabla%203.png)

Tabla III. Verificación de LCK

## *ECUACIONES*
Las unidades que se representan con la ley de Kirchoff son las mismas con las que se trabajan en la ley de Ohm. Para poder analizar las mismas, es necesario saber de dónde se obtienen:

Las unidades respectivas sobre la ley de ohm son: 

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Ecuaciones.jpg)


Su fórmula es I=V/R

Intensidad=Amperio (A

Voltaje=Voltio (V)

Resistencia= Ohmio (omega)


Una vez obtenido este modelo matemático podemos afirmar que se cumple la siguiente ley: 


V1+V2+V3+V4+...Vn=0


Esta ecuación se cumple siempre y cuando sea de solamente una malla, es decir la sumatoria de voltajes dentro de una malla es igual a cero, afirmando eso se cumple otra ley que nos habla sobres las corrientes:


I(salida)=I(entrada)


## *DIAGRAMA*
![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%203.png)

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%206.png)


## *EXPLICACIÓN DEL CIRCUITO*


Nuestro circuito está conformado por 6 elementos, que serán 5 resistencias y nuestra fuente de voltaje, colocadas como se lo puede ver en nuestro circuito. 

La fuente de voltaje proporcionará energía al circuito, llegando a nuestra primera resistencia que será nuestra resistencia de 1000 ohmios. De dicha resistencia nuestra corriente que fluye por dicha resistencia, se dividirá en dos nuevas resistencias. Nuestra primera resistencia es la de 3900 ohmios, que saldrá por nuestro nodo que se conectará a nuestra última resistencia. Nuestra segunda resistencia, obtenida de nuestra resistencia de 1000 ohmios, es la de 2200 ohmios, que estará conectada en serie con otra resistencia de 2200 ohmios y saldrá a nuestra última -resistencia. Dicha resistencia es una resistencia de 1800 ohmios, que será la que cierre nuestro circuito al conectarse con nuestro polo negativo de la batería, permitiendo así, que exista un flujo de corriente.


## *ANÁLISIS DE RESULTADOS*
 Ahora compararemos los resultados obtenidos tanto teoricamente como en la simulación a su vez calculando su error.
 
 
 Con la siguiente fórmula:
 
 %Error= (Valor teorico - Valor medido)/(Valor teorico) * 100
 
 Entonces calculamos los errores de cada elemento, obteniendo.
 
 | Variable | Valor Calculado | Valor Medido | %Error |
| ----- | ----- | ----- | -----|
| VR1 (V) | 2,053 | 2,046 | 0,34% |
| IR1(mA) | 2,053 | 2,056 | 0,15% |
| VR2(V) | 4,251 | 4,223 |  0,66% |
| IR2(mA) | 1,09 |1,088|   0,18%  |
| VR3(V) | 2,1255 | 2,115 |  0,49% |
| IR3 (mA) | 0,963 | 0,964 | 0,10% |
| VR4(V) | 2,1255 | 2,115|  0,49% |
| IR4(mA) |  0,963 | 0,964 | 0,10% |
| VR5(V) | 3,696 | 3,73|   0,92% |
| IR5(mA) | 2,053 | 2,046| 0,34% |

IV. Error obtenido en las mediciones

 Como podemos ver, se manifiestan ciertos errores a la hora de hacer mediciones, que pueden ser por equivocación humana o por el error que puede cometer el instrumento. Como se puede observar ningún error llega al 1%, esto principalmente se ve reflejado en la comprobación de las leyes de Kirchhoff (véase en Tabla III). Donde se obtienen pequeñas diferencias; en cuanto a corriente en los dos nodos tenemos una diferencia con el valor calculado de 0.004mA y respecto a corriente tenemos una diferencia de 0.004 y 0.007 voltios. Aun así, la ley se cumple si tomamos como aceptables los errores cometidos.


## *CONCLUSIONES*

-	Al realizar la suma de los voltajes en cada malla damos por hecho que La ley de Voltaje de Kirchoff se cumple, ya que los datos que obtuvimos dos reflejan una diferencia de solamente 0.004 y 0.005 voltios.

-	Se ha comprobado la Ley de corriente de Kirchoff mediante el cálculo en cada nodo de las corrientes que entran con las corrientes que salen. Donde se ha obtenido un error absoluto de 0.004 mA en cada nodo, esto se debe principalmente a que los valores que nos arroja el instrumento, de cierta forma puede variar en un pequeño intervalo.

-	Se obtuvo errores entre los valores medidos y los valores calculados, pero están dentro del rango de error que puede cometer el instrumento, por tanto, se considera que es aceptable.

## *RECOMENDACIONES*

-	Es necesario asegurar los valores que asignamos tanto a las fuentes de voltaje como a las resistencias, ya que se suele cometer errores con las unidades de medida, de igual forma que la conexión esté bien hecha para que las mediciones sean lo más exactas posibles.

-	Tener en cuenta claros los conceptos y a qué se refiere cada ley para comprender de mejor manera la práctica realizada.

-	Tener mucho cuidado con las fuentes de voltaje manejadas, ya que pueden ser peligrosas. También estar al tanto de las capacidades de las resistencias, ya que cuando se realice un circuito real podemos dañar algunos elementos si no los colocamos adecuadamente.


## *CRONOGRAMA*

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Cronograma/Cronograma_Informe1.jpg)

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*
![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%206.png)

Fig. 4. Circuito en TinkerCad

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%207.jpeg)

Fig. 5. Medición de corriente

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%208.jpeg)

Fig. 6. Medición de voltaje

![alt text](https://github.com/Kevi7k/Practica1./blob/master/Img/Diagrama%204.jpeg)

Fig. 7. Comprobación teórica de Leyes


