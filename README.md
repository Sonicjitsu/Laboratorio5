# LABORATORIO # 04

TEMA: TEOREMA DE SUPERPOSICIÓN
## 1. OBJETIVOS

**1,1.- GENERAL** 

* Comprobar experimentalmente el Análisis de Mallas. 

**1,2.-ESPECÍFICOS**

* Examinar el funcionamiento de un circuito mixto con 2 fuentes de voltaje.

* Comparar los valores medidos con los valores calculados en el circuito y establecer el porcentaje de error resultante.

* Aplicar el uso de las leyes de voltaje de Kirchhoff  para el análisis de mallas.


## 2. PLANTEAMIENTO DEL PROBLEMA

Este proyecto consistió en la implementación de un circuito electrónico virtual en un programa online denominado Tinkercad con la finalidad de experimentar una simulación del circuito donde es posible aplicar el Análisis de Malla. Se procede a realizar ensamblaje   del circuito con resistencias en serie y paralelo de diferentes valores para que estas formen mallas con el fin de poder realizar su análisis midiendo las corrientes de cada malla del circuito.


## 3. MARCO TEÓRICO 


**MALLA EN UN CIRCUITO ELÉCTRICO**

Una malla es cualquier trayectoria cerrada de un circuito eléctrico, formado por elementos del mismo circuito.

![](https://github.com/BriandaLema/Laboratorio2/blob/master/img/Mallas%20en%20un%20circuito.jpg)

En la gráfica existen 4 mallas ,es decir 4 caminos cerrados dentro del circuito, donde intervienen resistencias y fuentes de voltaje.

**MÉTODO DE LA CORRIENTE DE MALLA**
 
El método de la corriente de malla se basa en la ley de voltaje de Kirchhoff , y según esta ley establece que la sumatoria de los voltajes en una malla es igual a cero.Es decir: si multiplicamos cada resistencia de en la malla por las corrientes de malla, al sumar los voltajes el total debe ser cero. Si no existe una fuente de corriente o voltaje en una malla , asumimos que la corriente fluye en sentido horario.

En el siguiente diagrama podemos representar las corrientes de la siguiente manera:

![](https://github.com/BriandaLema/Laboratorio2/blob/master/img/Sentido%20de%20las%20corrientes.jpg)

Observemos que en la malla 1 la corriente va en sentido horario ya que sale del positivo de la fuente, en las mallas 2 y 3 no existe fuente, así que se asume que va en sentido horario y en la malla 4 la corriente va en sentido anti horario ya que sale  del lado positivo de la fuente de voltaje.

Luego de establecer el sentido de las corrientes procedemos a colocar signos de polaridad a las resistencias por cada malla, para esto debemos tomar en cuenta que para todas las resistencias la terminal donde entra la corriente llevará un signo positivo y donde sale la corriente llevará un signo negativo, esto se realiza para facilitar la resolución del problema. Y quedaría de la siguiente manera: 

![](https://github.com/BriandaLema/Laboratorio2/blob/master/img/Polaridad%20de%20las%20resistencias.jpg)

Ya una vez colocado los signos procedemos  a establecer las ecuaciones para cada malla. Al final obtendremos un sistema de ecuaciones, que lo podremos resolver mediante matrices, así obteniendo cada uno de los valores de las corrientes requeridas.

## 4. DIAGRAMAS

Para este laboratorio se utilizó un circuito mixto en donde podemos diferenciar que se encuentra constituido por 3 mallas.

![](https://github.com/BriandaLema/Laboratorio2/blob/master/img/Circuito%20lab%202%20(2).png)

## 5. LISTA DE COMPONENTES

| CANTIDAD| ELEMENTO |
| ------- | -------------|
| 2       | Fuente de Voltaje C.D.  |
| 1       | Multímetro digital  |
| 1       | Resistor de 820 Ω   |
| 1       | Resistor de 390 Ω   |
| 1       | Resistor de 1 kΩ  |
| 1       | Resistor de 1.2 kΩ|
| 1       | Resistor de 2.2 kΩ|
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

ANÁLISIS DE MALLAS 

| CORRIENTE | MEDIDO | CALCULADO  |
|----------|------|-------|
| I1 (A) | 0.01145 A | 0.0115 A|
| I2 (A) | 0.00285 A| 0.00285 A|
| I3 (A) | 0.00049 A | 0.000488 A |



- CÁLCULO DEL ERROR DE LA CORRIENTE

∑(Corriente calculado)= (0.0115 + 0.00285 + 0.000488) A

∑(Corriente calculado)=  0.01484 A

∑(Corriente medido)= (0.01145 + 0.00285 + 0.00049) A

∑(Corriente medido)= 0.01479 A 

%error=((Valor teórico-Valor medido)/Valor teórico)* 100

%error=((0.01484 A - 0.01479 A)/ 0.01484 A)* 100

%error= 0.34 % 

Como podemos observar los valores de cada corriente medida en las tres mallas con analisís de mallas son muy parecidos a los valores cálculados con el Tinkercad, ya que el porcentaje de error de la corriente es menor al 1%.

Habiendo simulado y creado el circuito, se observa que las corrientes con valores teóricos y los prácticos son semejantes, dando a conocer el funcionamiento del método de análisis de malla.

Conluimos generalmente que hay una pequeña diferencia entre los valores medidos y calculados, se podría dar por dos razones : al momento de calcular con el multímetro los valores, intervienen las tolerancias de las resistencias, y esto podría afectar a los valores obtenidos; mientras que en los valores medidos intervien la falta de utilización de todos los decimales,  lo cual afecta los valores obtenemos. 



## 11. RECOMENDACIONES

Recomendamos el asegurarse del correcto cálculo de los valores de manera clara y ordenada, de lo contrario, tendríamos un % de error excesivo. Es muy importante asignar una corriente de malla a cada malla (sentido cualquiera) y asignar una polarización a cada elemento del circuito.

Así mismo se recomienda cerciorarse de que la implementación de circuito este correctamente elaborado tal como está planteado.
Para terminar podemos sugerir utilizar de manera adecuada en serie el uso del multímetro para el cálculo de las corrientes.


## 12. CRONOGRAMA

![](https://github.com/BriandaLema/Laboratorio2/blob/master/img/Cronograma.png)

https://trello.com/b/0MUzNNnz/lab-2

## 13. BIBLIOGRAFÍA

* Antony, G. G. (26 de Julio de 2013). PANAMAHITEK. Obtenido de http://panamahitek.com/ley-de-los-voltajes-de-kirchhoff-metodo-de-mallas/#:~:text=En%20un%20circuito%20el%C3%A9ctrico%2C%20una,formadas%20por%204%20caminos%20cerrados.&text=Si%20multiplicamos%20las%20corrientes%20de,el%20total%20debe%20ser%20cero.

* Willi, M. (s.f.). KHAN ACADEMY. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method



## 14.- ANEXOS
https://github.com/BriandaLema/Laboratorio2/blob/master/ANEXOS/ANEXOS.pdf






