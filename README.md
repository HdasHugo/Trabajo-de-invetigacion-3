# Trabajo-de-invetigacion-3
## 1. TEMA: INTRODUCCIÓN A LA PROGRAMACIÓN POR BLOQUES DE ARDUINO EN TINKERCAD
## 2. PLANTEAMIENTO DEL PROBLEMA
La utilización de Arduino hoy en día es muy demandada en proyectos de electrónica, ya que al ser una plataforma libre y de código abierto, los usuarios pueden modificar los requerimientos a sus necesidades, debido a que incorpora un microcontrolador y un entorno de desarrollo que permiten que todo esto sea posible.
En nuestro caso, al ser un entorno virtual en el cual vamos a trabajar, utilizaremos el Arduino UNO que incorpora Tinkercad, realizando la programación de un circuito mediante un entorno de desarrollo gráfico (Programación por bloques). El propósito de este trabajo de investigación es analizar los aspectos de hardware que ofrece un Arduino, haciendo énfasis en la entrada (sensores) y salida de información (indicadores LEDs,- alarmas). Esto se determinará a partir de la fundamentación correspondiente a los componentes que conforma un Arduino, su funcionalidad y aplicándolo a diferentes circuitos, en los que se presente la operatividad y funcionamiento de algunos sensores que incorpora Tinkercad, tales como, el sensor de luz ambiental, sensor PIR, sensor de distancia, sensor de inclinación, sensor de temperatura y un sensor de gas.  
## 3. OBJETIVOS
### 3.1 OBJETIVO GENERAL
Implementar y analizar en base a la información de datos de entrada y salida de un Arduino, diferentes circuitos en los cuales se muestre el funcionamiento de los mismos, a través de la programación en un entorno gráfico y uso del Arduino en tinkercad, con el fin de entender el comportamiento del sistema de hardware que ofrece esta plataforma, junto con los sensores que serán utilizados para cada circuito.
### 3.2 OBJETIVOS ESPECÍFICOS
-	Investigar la funcionalidad y la composición del hardware de un Arduino y el funcionamiento de cada sensor que lo conforma, haciendo énfasis principalmente en las entradas y salidas de información.
-	Desarrollar la programación, mediante un entorno gráfico en Tinkercad (Diagrama de bloques) para los circuitos a implementar (Con sensores) observando su funcionalidad y la manera de aplicarlos en base a las características que ofrecen.
-	Entender el funcionamiento de la entrada y salida de datos que nos ofrece el uso del Arduino aplicado en el uso de sensores. Todo esto con el apoyo de la investigación que se habrá realizado y de los artículos de diferentes autores que permitan tener una idea mucho más clara y significativa de lo que está por realizarse, relacionándolos a su vez, con nuestro circuito/programa.
## 4. ESTADO DEL ARTE
### Evaluación de un algoritmo de ubicación basado en RSSI para redes de sensores inalámbricos
Realizado por Pereira Pires, R., Gracioli, G., Wanner, L. y Augusto Medeiros Frohlich, A. Evaluación de un algoritmo de ubicación basado en RSSI para redes de sensores inalámbricos el 16 de junio de 2011

La conciencia de posición es una característica deseable para muchas aplicaciones de redes de sensores inalámbricos. La indicación de intensidad de la señal recibida de un canal de radio proporciona una forma viable de estimar la distancia entre los nodos porque su uso no requiere ningún hardware adicional sino un transceptor de radio. El principal inconveniente de utilizar RSSI es su inestabilidad y susceptibilidad a interferencias que se advierte en entornos reales. Este trabajo muestra una evaluación de una implementación de un algoritmo de ubicación para redes de sensores inalámbricos y presenta mejoras que mejoran sustancialmente la confiabilidad en sus resultados. Los resultados muestran que las mediciones RSSI ajustadas adecuadamente se pueden utilizar con éxito para la localización en redes de sensores inalámbricos.

Otra aplicación de sensores pero esta vez aplicado hacia nuestra carrera como podemos ver va dirigido a redes y aquí va de forma más avanzada puesto que será un sensor inalámbrico 
### Comparación de rendimiento de un detector de semiconductores CZT de gran volumen y un detector de centelleo

Realizado por González, R., Pérez, JM, Vela, O. y De Burgos, E.Comparación de rendimiento de un detector de semiconductores CZT de gran volumen y un detector de centelleo 28 de agosto de 2006,

En este artículo nos muestra sobre  el desarrollo de la instrumentación nuclear portátil exige detectores compactos de alta sensibilidad operados a temperatura ambiente. La sensibilidad de estos detectores depende principalmente de dos parámetros: eficiencia absoluta y resolución energética. Para proporcionar una alta eficiencia, se necesitan grandes volúmenes. Para los detectores de semiconductores capaces de operar a temperatura ambiente, los mayores volúmenes efectivos con una resolución aceptable se logran con detectores de píxeles y cuadrícula coplanares CdZnTe. Por otro lado, recientemente se desarrollaron nuevos materiales de centelleo con capacidades espectrométricas solo alcanzables hace algunos años con semiconductores. En este trabajo comparamos el rendimiento de dos detectores de última generación de diferentes tecnologías con un volumen relativamente grande: un detector de CdZnTe de rejilla coplanar con dimensiones de 15 mm x 15 mm x 10 mm y un detector LaBr Cristal 3 (Ce) con un volumen de 18 mm x 18 mm x 30 mm. El cristal CdZnTe fue fabricado por Yinnel Tech (EE. UU.) Y el detector fue fabricado por BSI (Letonia). El centelleador LaBr 3 (Ce) se cultivó y encapsuló en Saint-Gobain (Francia). La resolución de energía para el detector CZT es 2.05% FWHM a 662 keV. La resolución del centelleador a esta energía fue cercana al 3%. La eficiencia total se estudió en una configuración con fuentes puntuales calibradas. Los espectros experimentales se compararon con simulaciones Monte-Carlo realizadas con Geant4. Las implicaciones de los resultados de esta comparación se discuten en el contexto del uso práctico de estas unidades.

En este vemos otra forma aplicada a los sensores y otro tipo de funcionalidades junto con otras aplicaciones como detectores y su comparación entre los dos que nos presentan aquí y cuál es el mejor para ser de su uso 


### Sensores de humedad basados en nanovarillas de óxido de zinc integrados de bajo costo para la plataforma Arduino

En este articulo se nos  demuestra la realización de un sencillo sistema integrado y de bajo costo de modulación de intensidad y la  detección directa basada en humedad y detección de vapor que utiliza nano-barras de óxido de zinc (ZnO) como material activo este dispositivo de detección consta de nano-barras de ZnO cultivadas de manera óptima en un sustrato de vidrio y montadas en una plataforma impresa en 3D para la alineación con una configuración de diodo emisor de luz verde para una excitación de borde. 
Se utilizó una plataforma Arduino para el procesamiento de señales de detección de la luz transmitida. Tanto la dispersión hacia adelante como hacia atrás se ven afectadas debido a la fuga de luz mientras se propaga a través del sustrato de vidrio, que se atenúa aún más en presencia de humedad. En este artículo, se encontró que la dispersión hacia atrás era dominante y, por lo tanto, con el aumento de la humedad, se controló una reducción en la luz transmitida. Cuando se probó el sensor en un ambiente con humedad controlada, se encontró que el voltaje de salida cae en aproximadamente 750 mV al cambiar el nivel de humedad relativa (RH) del 35% al 90% de una manera no lineal. Se observó que la sensibilidad media del sensor era de -12 mV /% en todos los niveles de HR probados. Se encontró que la sensibilidad era más alta a -24,6 mV /% para RH superiores al 70%. Se obtuvo un tiempo de respuesta promedio de 3.8 s para niveles de HR de 85% con respecto a las condiciones de humedad ambiental estándar (HR 50%), que mostró un tiempo de recuperación más rápido de 2.2 

Aquí se nos indica una aplicación del arduino no aplicada a sensores lo que nos da una idea de su variedad  de su usos no solo se van aun solo tema además de eso de su bajo costo que le hace que sea accesible para casi cualquier persona 


## 4. MARCO TEÓRICO
### Arduino
Arduino es una plataforma de creación de electrónica de código abierto, la cual está basada en hardware y software libre, flexible y fácil de utilizar para los creadores y desarrolladores. (F, 2018).

En este caso nos enfocaremos en el Arduino UNO, una placa electrónica basada en el chip de Atmel ATmega328 que tiene 14 pines digitales de entrada / salida, es el Arduino Pinout de los cuales 6 los puede utilizar como salidas PWM, 6 entradas analógicas, un oscilador de cristal de 16 MHz, una conexión USB, un conector de alimentación, una cabecera ICSP y un botón de reset. (Anónimo, 2016).

Los Arduino tienen puertos de entrada y salida y puertos de comunicación. 
-	Pines digitales: Se pueden configurar como entrada para leer o como salida. 
-	Pines analógicos de entrada: Usan un conversor analógico/digital y sirven para leer sensores analógicos como sondas de temperatura.
-	Pines analógicos de salida (PWM): La mayoría de Arduino no tienen conversor digital/analógico y para tener salidas analógicas se usa la técnica PWM. No todos los pines digitales soportan PWM.
-	La técnica PWN es: La modulación de ancho de pulso, o PWM, es una técnica para obtener resultados analógicos con medios digitales. 

El control digital se utiliza para crear una onda cuadrada, una señal conmutada entre encendido y apagado. Este patrón de encendido y apagado puede simular voltajes entre encendido y apagado al cambiar la parte del tiempo que la señal pasa en comparación con el tiempo que la señal pasa.

-	Puertos de comunicación: USB, serie, I2C y SPI.

### Tipos de memoria dentro del Arduino
- SRAM: Donde Arduino crea y manipula las variables cuando se ejecuta. Es un recurso limitado y debemos supervisar su uso para evitar agotarlo.
- EEPROM: Memoria no volátil para mantener datos después de un reset o apagado. Las EEPROMs tienen un número limitado de lecturas/escrituras, tener en cuenta a la hora de usarla.
- Flash: Memoria de programa. Usualmente desde 1 Kb a 4 Mb, donde se guarda el sketch (programa realizado).

### Composición de la placa de Arduino
![Captura partes arduino](https://user-images.githubusercontent.com/68835261/88507070-312df080-cfa1-11ea-8c21-d2e615ba8267.JPG)
1. Botón de Reset: Sirve para inicializar nuevamente el programa cargado en el microcontrolador de la placa. Cuando deje de responder el Arduino Uno es el botón de encendido o apagado para que vuelva a restablecerse. 
2. Pines o puertos de entrada y salida: son los pines donde conectar los sensores, componentes y actuadores que necesiten de señales digitales.
3. Pines o puertos de entrada y salida: son los pines donde conectar los sensores, componentes y actuadores que necesiten de señales digitales
4. Puerto USB: Utilizado tanto para conectar con un ordenador y transferir o cargar los programas al microcontrolador como para dar electricidad al Arduino. También se usa como puerto de transferencia .
5. Chip de interface USB: es el encargado de controlar la comunicación con el puerto USB. 
6. Reloj oscilador: Es el elemento que hace que el Arduino vaya ejecutando las instrucciones. Es el encargado de marcar el ritmo al cual se debe ejecutar cada instrucción del programa.
7. Led de encendido. Es un pequeño LED que se ilumina cuando la placa esta correctamente alimentada. 
8. Microcontrolador. (ATMEGA 328) Este es el cerebro de cualquier placa Arduino. Es el procesador que se encarga de ejecutar las instrucciones de los programas. 
9. Regulador de tensión: Este sirve para controlar la cantidad de electricidad que se envía a los pines, con lo que asegura que no se estropee lo que conectemos a dichos pines. 
10. Puerto de corriente continua. Este puerto es el que se usa para darle electricidad a la placa si no se usa alimentación USB. 
11. Zócalo de tensión. Aquí estarán los pines con los que alimentaremos nuestro circuito. 
12. Entradas analógicas: Zócalo con distintos pines de entrada analógica que permiten leer entradas analógicas. (Anónimo, 2016).

### Entrada y salida, Comunicación
![Captura pines digitales](https://user-images.githubusercontent.com/68835261/88509037-d21eaa80-cfa5-11ea-83d0-26cd44f25c41.JPG)
-	Cada uno de los 14 pines digitales de la Uno puede utilizarse como entrada o salida, utilizando las funciones pinMode(), digitalWrite() y digitalRead(). (En nuestro caso esto último se lo realizaría mediante interfaz gráfica).
-	Funcionan a 5 voltios. 
-	Cada clavija puede proporcionar o recibir un máximo de 40 mA y tiene una resistencia pull-up interna de 20-50 kOhms.
-	El Arduino Uno tiene un buen número de opciones para comunicarse con un ordenador, otro Arduino, u otros microcontroladores. El ATmega328 proporciona comunicación serie UART TTL, que está disponible en los pines digitales 0 (RX) y 1 (TX).
### Sensor de Luz
Es un dispositivo electrónico que responde al cambio en la intensidad de la luz, permite sensar la presencia de luz. Los sensores de luz detectan la luz visible (La que el ser humano puede percibir) y tiene una respuesta de acuerdo a la intensidad.
Es utilizado para medir la iluminancia, en otras palabras para medir el nivel de iluminación. Al conocer el valor de iluminación podremos decir si es correcto o incorrecta lo iluminado que está un lugar y esto se deberá por la luz insuficiente para iluminar el área determinada o por el exceso de luz que haya.
 
#### Tipos de sensores de Luz:
- Fotodiodo.-Semiconductor construido con una unión PN, sensible a la incidencia de la luz visible o infrarroja.
- LDR.-El fotoresistor o LDR por sus siglas en inglés (Light Dependent Resistor) es una resistencia la cual varía su valor en función de la cantidad de luz que incide cobre su superficie.
- Fototransistor.-Tiene una union base collector p-n sensible a la luz.
- Célula fotoeléctrica.-Es un dispositivo electrónico que permite transformar la energía lumínica en energía eléctrica mediante el efecto fotoeléctrico, generando energía solar fotovoltaica.
###  Sensor PIR
Los detectores PIR (Passive Infrared) o Pasivo Infrarrojo, reaccionan sólo ante determinadas fuentes de energía tales como el calor del cuerpo humano o animales. Básicamente reciben la variación de las radiaciones infrarrojas del medio ambiente que cubre. Es llamado pasivo debido a que no emite radiaciones, sino que las recibe. Estos captan la presencia detectando la diferencia entre el calor emitido por el cuerpo humano y el espacio alrededor.
Su componente principal son los sensores piroeléctrico. Se trata de un componente electrónico diseñado para detectar cambios en la radiación infrarroja recibida. Generalmente dentro de su encapsulado incorporan un transistor de efecto de campo que amplifica la señal eléctrica que genera cuando se produce dicha variación de radiación recibida.
 
###  Sensor de Distancia 
Un sensor de distancia es un dispositivo que permite realizar la medida de distancia lineal, dependiendo de su configuración electrónica o por medio de programación estos normalmente pueden adaptarse para medir la distancia o ser utilizados como sensores de presencia (movimiento).
Tipos de sensor de distancia:
Sensor de distancia por infrarrojo.-Se basa en un sistema de emisión – receptor de radiación.
Sensor ultrasónico.-Consiste en enviar pulsos haciendo que las ondas reboten en la superficie.
 
###  Sensor de inclinación 
Un Tilt Switch o interruptor basculante es un tipo de interruptor o sensor de inclinación que cambia en un cierto ángulo en comparación con el horizonte (similar al antiguo interruptor de mercurio). Se trata de un inclinómetro con salida de conmutación. Dado que la gravedad sirve como referencia, se consigue la máxima libertad de montaje
#### Funcionalidad
La funcionalidad de los sensores de inclinación está influenciada por factores como la gravedad, la vibración, la temperatura, el desplazamiento del cero, la linealidad, la sensibilidad entre ejes, la aceleración/deceleración, el choque, la línea de visión clara entre el usuario y el punto medido, y la calibración de los sensores de inclinación. 
Las especificaciones clave de los sensores de inclinación incluyen:
-	 Número de ejes: El número de ejes es un factor importante, ya que varía de una aplicación a otra. En robótica, se utiliza un sensor de inclinación de dos ejes. En los mandos y joysticks de los videojuegos, se requiere un sensor de inclinación de tres ejes. En algunos smartphones, se utilizan sensores de cuatro ejes. 
-	Resolución: La inclinación mínima detectada por el sensor. 
-	Sensibilidad: La capacidad del sensor para reaccionar a pequeños cambios. 
-	Rango de medición: El rango de inclinación que puede ser manejado por el sensor. Algunos sensores son capaces de medir hasta 10° mientras que otros pueden cubrir un rango de hasta 60°. 
-	Tolerancia al ruido: El ruido tiende a causar distorsiones armónicas en el funcionamiento del sensor, lo que resulta en una variación de la salida y una reducción de la eficiencia del sistema. Deben respetarse las directrices del fabricante con respecto a los niveles de ruido. 
-	Vibración: Las vibraciones pueden interrumpir la funcionalidad del sensor y, por lo tanto, se requieren medidas de resistencia a las vibraciones, especialmente cuando los sensores se utilizan en condiciones difíciles, por ejemplo, en vehículos todo terreno o en obras de construcción.
 
###  Sensor de temperatura
Un sensor de temperatura es un sistema que detecta variaciones en la temperatura del aire o del agua y las transforma en una señal eléctrica que llega hasta un sistema electrónico. Esta señal conlleva determinados cambios en ese sistema electrónico para la regulación de la temperatura.
También conocido como sonda de temperatura, este sensor se compone principalmente de tres partes. Primeramente, y como es obvio, cuenta con un elemento sensor (cuyos tipos pasaremos a ver en este post). Además de este elemento, se compone de una vaina de material conductor en su interior y un cable que conecta al sistema electrónico en cuestión.
#### Sensores Termopares mas utilizados:
El termopar es el sensor más empleado en los sistemas de medición de temperatura. Estos sensores económicos, de sencilla instalación y con una precisión ajustada a distintos procesos. Aunque su funcionamiento cumple con suficiencia, su respuesta puede ser algo lenta en comparación con otros tipos de sensores de temperatura.
El funcionamiento de los termopares se basa en dos hilos metálicos de diferentes materiales unidos por un extremo, el cual se conoce como junta caliente o junta de medición. Cuenta con otro extremo separado, llamado junta fría. La diferencia de temperatura entre ambas juntas produce un diferencial de tensión, que será la señal enviada al dispositivo electrónico.
Dentro de estos sensores, se encuentran diferentes tipos de termopares según los materiales de los que estén compuestos. Los más comunes son los siguientes:
- Termopar Tipo J: Hecho de una combinación de hierro y constatan (aleación de cobre y niquel). De uso limitado en entornos oxidantes. Cuenta con un rango de temperatura entre los 0°C y los 750°C.
- Termopar Tipo T: Se compone de un alambre de cobre y otro de constatan. De uso recomendado en entornos de humedad. Su rango de temperatura se encuentra entre los -250°C y los 350°C.
- Termopar Tipo K: Compuesto de una junta de chromega (aleación de cromo y niquel) y alomega (aleación de aluminio y niquel), es el sistema de captación de temperatura más extendido. Y es que su rango de temperatura es muy amplio, situándose entre los -200°C y los 1250°C, aunque se recomienda para medidas entre 300 y 1100ºC.
- Termopar Tipo E: Su combinación de materiales incluyen chromega y constatan. Su rango de temperaturas se sitúa entre los -200°C y los 900°C.
 
### Sensor de Gas
Los sensores de gas son dispositivos que indican la presencia de algún gas específico, en algunos casos pueden configurarse o, en caso de tener sensores más precisos, miden la concentración de gas. Los sensores de gas son usados para prevenir la exposición a gases combustibles y gases tóxicos. Se recomienda usar estos sensores en espacios confinados y pequeños debido a que su eficiencia es mayor.
#### Tipos de sensores para gases:
- Sensores semiconductores.- Sensores con semiconductores de óxido metal. Funcionan con una película sensible al gas que está compuesta principalmente por cristales de oxido-metal del tipo n – normalmente es dióxido de estaño (SnO2), óxido de indio (InO3), óxido de wolframio (WO3), entre otros-. Estos sensores son muy eficientes ya que pueden operar en un rango amplio de ambientes húmedos. En estos sensores, una reacción química ocurre cuando el gas hace contacto con el sensor provocando que la resistencia eléctrica en el sensor decrezca. En los sensores que usan el dióxido de estaño, la sensibilidad para diferentes gases varía con la temperatura, por lo que hay un filamento que se calienta por medio de una corriente eléctrica.
- Sensores infrarrojos. Estos sensores funcionan con emisores y receptores de luz infrarroja. Si un gas se encuentra en el ambiente, éste interfiere con la potencia de transmisión entre el emisor y el receptor. Esta alteración determina qué tipo de gas se encuentra presente.
- Sensores ultrasónicos. Estos sensores usan emisiones ultrasónicas para detectar cambios en el ruido de fondo del ambiente en donde se encuentren, principalmente para detectar fugas en tuberías -la fuga de un gas genera un sonido ultrasónico en un rango promedio entre los 25 kHz y los 10 Mhz
- Sensores electroquímicos. Estos sensores tienen dos electrodos divididos por una capa de electrolitos, la cual puede ser líquida, sólida o en forma de gel. Cuando el gas entra en el sensor a través de una membrana y la tensión de polarización está aplicada a los electrodos, se presenta una reacción de reducción-oxidación que genera una corriente eléctrica directamente proporcional a la concentración de gas.
- Sensores catalíticos. A estos sensores también suelen llamarlos pellistores -palabra formada por la combinación de las palabras en inglés pellet y resistor-. Su funcionamiento es por la oxidación del gas vía catalítica. Dado que estos son los sensores de gas más asequibles para el publico en general, se ahondará un poco más en su configuración y en su funcionamiento.
## 11.Conclusiones
-	La implementación de los seis circuitos, cuya operatividad se basa en la función de cada sensor utilizado, se lo ha realizado de tal manera que los datos de entrada y salida que se utilizaron se relacionen entre sí por medio de las instrucciones que se establecieron en el programa elaborado en un entorno gráfico, en el cual se implementaron principalmente estructuras condicionales para cumplir el funcionamiento de dichos circuitos, dependiendo del estado lógico o el rango de valores en el que se encuentren las entradas (Sensores) para que sus salidas (LEDs y transductores piezoeléctricos) se comporten como señal de alarma o una escala que obedezca a los parámetros del nivel de luz, temperatura y gas existente en un determinado lugar, también la existencia o no de movimiento e inclinación de determinados objetos y la distancia existente entre un objeto con respecto al sensor. Claramente todo ello depende del sensor con el que se esté trabajando.
-	La familiarización con la funcionalidad de cada componente que conforma a un Arduino (Hardware), en este caso el Arduino UNO, fueron muy importantes para lograr realizar nuestro circuito y entender cómo interactúan, mediante el programa para con los componentes del circuito implementado. Básicamente el cerebro de esta plataforma electrónica es el microcontrolador ATMEGA 328, el cual contiene un total de 28 pines o puertos, y 14 de ellos (correspondientes a los pines digitales) hemos utilizado para la entrada y salida de información, es decir, los correspondientes a los sensores PIR, de distancia (ultrasónico), y de inclinación y LED´s respectivamente. Además de ello también se utilizaron los pines de entrada analógicos para leer los datos captados por los sensores de luz ambiental, temperatura y gas. Hay que tener en cuenta que el reloj oscilador del Arduino es fundamental, ya que gracias a él las instrucciones se realizan con respecto a los tiempos que, en este caso, se han impuesto por default en las instrucciones del programa. Y cuya información se guarda en cada una de las memorias que incorpora esta plataforma (SRAM, EEPROM, FLASH).
-	La realización del programa e implementación del circuito se la realizó en base a todo lo investigado, lo cual tiene que ver con las funcionalidades que ofrece el microcontrolador Arduino, principalmente con lo correspondiente a su Hardware y el funcionamiento de cada sensor utilizado para cada circuito que se ha implementado. Y es muy importante saber que la utilización de Arduino hoy en día es muy demandada en proyectos de electrónica, ya que tiene varias ventajas como, por ejemplo: su bajo coste, y su versatilidad, ya que los usuarios pueden modificar los requerimientos a sus necesidades, además que, en nuestro caso, la programación se la realizó en Tinkercad con un entorno de desarrollo gráfico, lo que implica que es muy intuitiva y fácil de utilizar para cualquier tipo de usuario, incluso para los aprendices. De hecho, al momento de realizar la investigación con los artículos de los autores investigados, podemos darnos cuenta de la gran cantidad de aplicaciones que tiene un Arduino, junto con varios sensores y que de cierta manera se relaciona con nuestra investigación en cuestión.
## 12.Recomendaciones
-	Se recomienda realizar la investigación única y exclusivamente de los temas a ser tratados durante la ejecución y realización del informe que a su vez sustenten los fundamentos para la elaboración del algoritmo y su programación. 
-	Implementar y declarar correctamente las variables necesarias del programa, de tal manera que permitan realizar el código de programación sin que exista ningún tipo de error al momento de ejecutar y compilar el programa.
-	Si no existe familiarización con la programación mediante interfaz textual, recomendamos realizar el algoritmo de programación en una interfaz gráfica, pues una de las ventajas que tiene Tinkercad es que podemos visualizar las dos interfaces al mismo tiempo. Y de esta manera comprender de manera intuitiva la realización del programa. Incluso, exportar el código generado, para implementarlo en un Arduino físico.
## 13.Cronograma

![Cronograma 3 Trabajo de investigacion](https://user-images.githubusercontent.com/66962449/91748631-e4cc6680-eb85-11ea-8590-29249957daae.png)

## 14. Aportaciones
