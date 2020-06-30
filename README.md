# LABORATORIO # 04

TEMA: TEOREMA DE SUPERPOSICIÓN
## 1. OBJETIVOS

**1,1.- GENERAL** 

* Comprobar experimentalmente el Teorema de Superposición.

**1,2.-ESPECÍFICOS**

* Examinar el funcionamiento de un circuito mixto con 2 fuentes de voltaje.

* Comparar los valores medidos con los valores calculados en el circuito y establecer el porcentaje de error resultante.

* Aplicar el uso de las leyes de voltaje de Kirchhoff  para el análisis de mallas.


## 2. PLANTEAMIENTO DEL PROBLEMA

Este proyecto consistió en la implementación de un circuito electrónico virtual en un programa online denominado Tinkercad con la finalidad de experimentar una simulación del circuito donde es posible aplicar el Análisis de Malla. Se procede a realizar ensamblaje   del circuito con resistencias en serie y paralelo de diferentes valores para que estas formen mallas con el fin de poder realizar su análisis midiendo las corrientes de cada malla del circuito.


## 3. MARCO TEÓRICO 



## 4. DIAGRAMAS

Se simula un circuito lineal, es un circuito mixto con cuatro resistencias en paralelo y corriente conectadas a dos fuentes de voltaje de corriente directa.

![](https://github.com/BriandaLema/Laboratorio4/blob/master/img/Diagrama.png)

## 5. LISTA DE COMPONENTES

| CANTIDAD| ELEMENTO |
| ------- | -------------|
| 2       | Fuente de Voltaje C.D.  |
| 1       | Multímetro digital  |
| 1       | Resistor de 1 kΩ   |
| 1       | Resistor de 2.2 kΩ   |
| 1       | Resistor de 820 Ω  |
| 1       | Resistor de 470 Ω|
| 1       | Protoboard                    |

## 6. MAPA DE VARIABLES 

Variables eléctricas: 
* Corriente 
* Resistores

## 7. EXPLICACIÓN CÓDIGO DE FUENTE

Para este laboratorio utilizamos el simulador de Tinkercad , el cual es un sofware de diseño de circuitos, en este dispositivo encontramos una gama alta de componentes electrónicos que se utilizan para la creación de circuitos y simular su funcionamiento.
Tinkercad funciona directamente en un navegador web moderno por lo cual una conexión a internet es fundamental para la utilización de esta fuente. 
El mismo programa nos guía y asesora acerca de lo que realizamos, por lo cual la utilizacion de esta fuente es muy práctica si tienes un conocimiento básico sobre circuitos eléctricos.Una herramienta característica de Tinkercad es quemientras la simulación está en marcha podemos ir modificando las variables de cada elemento y ver los cambios en el momento. También podemos obtener una lista con los materiales empleado  que nos sirvio para realizar las fichas técnicas.



## 8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Fundamentalmente los prerrequisitos que requiere este laboratorio sería: un dispositivo tegnológico (sea un teléfono, una pc, un tableta, entre otras); pues trabajamos en un simulador online, nuestro segundo requisito es acceso a internet y finalmente tener conocimientos básicos sobre las leyes aplicadas, los componentes, elementos y variables que se utiliza para la creación del circuito.


## 9.APORTACIONES

Para complementar la correcta cuantificacion de valores calculados y valores medidos se utilizo una aplicación más denominada Multisim, que es un programa que se debe instalar en un sistema inteligente para poder hacer una grafica y simulación de un circuito.

## 10. CONCLUSIONES

**ANÁLISIS DE RESULTADOS Y CÁLCULO DEL ERROR**

MEDICIÓN DE VOLTAJE APLICANDO SUPERPOSICIÓN

* **VOLTAJE TOTAL (VA)**

| CALCULADO | MEDIDO  | 
|----------|------|
| 0.952 V | 0.94 V |

* **VOLTAJE (VA) CUANDO V2=0**

| CALCULADO | MEDIDO  | 
|----------|------|
| 7.48 V | 7.47 V |

* **VOLTAJE (VA) CUANDO V1=0**

| CALCULADO | MEDIDO  | 
|----------|------|
| -6.53 V | -6.53 V |

* **CORRIENTE TOTAL (Ix)**

| CALCULADO | MEDIDO  | 
|----------|------|
| 0.0255 A | 0.0255 A |

* **CORRIENTE (Ix) CUANDO V2=0**

| CALCULADO | MEDIDO  | 
|----------|------|
|  ∞  | 0 A |

* **CORRIENTE (Ix) CUANDO V1=0**

| CALCULADO | MEDIDO  | 
|----------|------|
| -0.0255 A | -0.0255 A |

- **CÁLCULO DEL ERROR DE LA CORRIENTE**

Corriente total calculado= 0.0255 A

Corriente total medido= 0.0255 A

%error=((Valor teórico-Valor medido)/Valor teórico)* 100

%error=((0.0255 A - 0.0255 A)/ 0.0255 A)* 100

%error= 0 % 

- **CÁLCULO DEL ERROR DEL VOLTAJE**

Voltaje total calculado= 0.952 V

Voltaje medido= 0.94 V

%error=((Valor teórico-Valor medido)/Valor teórico)* 100

%error=((0.952 V - 0.94 V)/ 0.952 )* 100

%error= 0.0126 % 

Como podemos observar los valores de cada corriente medida en las tres mallas con analisís de mallas son muy parecidos a los valores cálculados con el Tinkercad, ya que el porcentaje de error de la corriente es menor al 1%.

Habiendo simulado y creado el circuito, se observa que las corrientes con valores teóricos y los prácticos son semejantes, dando a conocer el funcionamiento del método de análisis de malla.

Conluimos generalmente que hay una pequeña diferencia entre los valores medidos y calculados, se podría dar por dos razones : al momento de calcular con el multímetro los valores, intervienen las tolerancias de las resistencias, y esto podría afectar a los valores obtenidos; mientras que en los valores medidos intervien la falta de utilización de todos los decimales,  lo cual afecta los valores obtenemos. 



## 11. RECOMENDACIONES

Recomendamos el asegurarse del correcto cálculo de los valores de manera clara y ordenada, de lo contrario, tendríamos un % de error excesivo. Es muy importante asignar una corriente de malla a cada malla (sentido cualquiera) y asignar una polarización a cada elemento del circuito.

Así mismo se recomienda cerciorarse de que la implementación de circuito este correctamente elaborado tal como está planteado.
Para terminar podemos sugerir utilizar de manera adecuada en serie el uso del multímetro para el cálculo de las corrientes.


## 12. CRONOGRAMA

![](https://github.com/BriandaLema/Laboratorio4/blob/master/img/Cronograma4.png)

https://trello.com/b/CRvRVdmQ/cronograma

## 13. BIBLIOGRAFÍA

* Antony, G. G. (26 de Julio de 2013). PANAMAHITEK. Obtenido de http://panamahitek.com/ley-de-los-voltajes-de-kirchhoff-metodo-de-mallas/#:~:text=En%20un%20circuito%20el%C3%A9ctrico%2C%20una,formadas%20por%204%20caminos%20cerrados.&text=Si%20multiplicamos%20las%20corrientes%20de,el%20total%20debe%20ser%20cero.

* Willi, M. (s.f.). KHAN ACADEMY. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-superposition



## 14.- ANEXOS
https://github.com/BriandaLema/Laboratorio4/blob/master/Anexos/ANEXOS4.pdf






