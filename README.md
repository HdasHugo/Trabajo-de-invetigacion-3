# Trabajo-de-invetigacion-3
## 1. TEMA: SENSORES CON ARDUINO EN TINKERCAD
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
## 5. DIAGRAMAS
### 5.1. DIAGRAMAS DE BLOQUES
![Diagrama 1 1](https://user-images.githubusercontent.com/68835261/91748961-6fad6100-eb86-11ea-89b5-8a01531a5967.JPG)

![Diagrama 1 2](https://user-images.githubusercontent.com/68835261/91748963-7045f780-eb86-11ea-8d61-d1feed6ecb0e.JPG)

![Diagrama 1 3](https://user-images.githubusercontent.com/68835261/91748971-73d97e80-eb86-11ea-808d-904950519ed0.JPG)

![Diagrama 1 4](https://user-images.githubusercontent.com/68835261/91748978-776d0580-eb86-11ea-8214-191d78467b29.JPG)

![Diagrama 1 5](https://user-images.githubusercontent.com/68835261/91748981-7936c900-eb86-11ea-95ba-6b353ca88434.JPG)

![Diagrama 1 6](https://user-images.githubusercontent.com/68835261/91748993-7d62e680-eb86-11ea-80fd-e37b2cce1e07.JPG)

### 5.2. DIAGRAMAS ELÉCTRICOS
![Diagrama 1 7](https://user-images.githubusercontent.com/68835261/91748998-7fc54080-eb86-11ea-9214-282cdaaacfb5.JPG)

![Diagrama 1 8](https://user-images.githubusercontent.com/68835261/91749020-8489f480-eb86-11ea-9a1f-0138ab2d8591.JPG)

![Diagrama 1 9](https://user-images.githubusercontent.com/68835261/91749031-86ec4e80-eb86-11ea-8127-2af0da6540dd.JPG)

![Diagrama 2 1](https://user-images.githubusercontent.com/68835261/91749406-09750e00-eb87-11ea-90ee-b9ecf31ff58d.JPG)

![Diagrama 2 2](https://user-images.githubusercontent.com/68835261/91749062-8d7ac600-eb86-11ea-9342-19085d17a310.JPG)

![Diagrama 2 3](https://user-images.githubusercontent.com/68835261/91749071-9075b680-eb86-11ea-96ce-5943295123ca.JPG)

## 6. LISTA DE COMPONENTES
![Tabla 1 1](https://user-images.githubusercontent.com/68835261/91750083-1b0ae580-eb88-11ea-8408-c9daa48cf5df.jpg)

## 7. MAPA DE VARIABLES
### DETECTOR DE LUZ AMBIENTAL
### - Variables utilizadas para el funcionamiento del circuito
![Figura 1 1](https://user-images.githubusercontent.com/68835261/91749160-b0a57580-eb86-11ea-82cd-24eda2634664.JPG)

### - Interfaz de usuario
![Figura 1 2](https://user-images.githubusercontent.com/68835261/91749169-b438fc80-eb86-11ea-87be-cf539222b898.JPG)

Donde:
- Led Blanco --> Representa altas cantidades de luz.
- Led Naranja --> Representa medianas cantidades de luz.
- Led Azul --> Representa bajas cantidades de luz.

### - Tabla - resumen de variables
![Tabla 1 2](https://user-images.githubusercontent.com/68835261/91750086-1d6d3f80-eb88-11ea-847b-2dcf33235e98.JPG)

### DETECTOR DE MOVIMIENTO
### - Variables utilizadas para el funcionamiento del circuito
![Figura 1 3](https://user-images.githubusercontent.com/68835261/91749187-ba2edd80-eb86-11ea-9cc4-cf144c06dfdb.JPG)

### - Interfaz de usuario
![Figura 1 4](https://user-images.githubusercontent.com/68835261/91749196-bc913780-eb86-11ea-9fa8-8aec37aad8ca.JPG)

Donde:
- Transductor piezoeléctrico --> Representa a una alarma.

### - Tabla - resumen de variables
![Tabla 1 3](https://user-images.githubusercontent.com/68835261/91750095-2100c680-eb88-11ea-80fa-bc6104b22c59.JPG)

### DETECTOR DE DISTANCIA
### - Variables utilizadas para el funcionamiento del circuito
![Figura 1 5](https://user-images.githubusercontent.com/68835261/91749209-c2871880-eb86-11ea-913e-2848950dd525.JPG)

### - Interfaz de usuario
![Figura 1 6](https://user-images.githubusercontent.com/68835261/91749220-c87cf980-eb86-11ea-8317-5c13d31e2d9b.JPG)

Donde:
- Led Rojo --> Representa corta distancia entre un objeto y el sensor (Estado de alarma).
- Led Naranja -->Representa mediana distancia de un objeto con respecto al sensor.
- Led Rojo --> Representa larga distancia de un objeto con respecto al sensor.

### - Tabla - resumen de variables
![Tabla 1 4](https://user-images.githubusercontent.com/68835261/91750104-252ce400-eb88-11ea-8e3c-1671c2b6b339.JPG)

### DETECTOR DE DISTANCIA
### - Variables utilizadas para el funcionamiento del circuito
![Figura 1 7](https://user-images.githubusercontent.com/68835261/91749377-011cd300-eb87-11ea-9001-0726bc4472cf.JPG)

### - Interfaz de usuario
![Figura 1 8](https://user-images.githubusercontent.com/68835261/91749611-5953d500-eb87-11ea-9e08-db4ed4171f23.JPG)

### - Tabla - resumen de variables
![Tabla 1 5](https://user-images.githubusercontent.com/68835261/91750109-278f3e00-eb88-11ea-84b0-a9a8e321ccca.JPG)

### DETECTOR DE TEMPERATURA
### - Variables utilizadas para el funcionamiento del circuito
![Figura 1 9](https://user-images.githubusercontent.com/68835261/91749621-5ce75c00-eb87-11ea-948e-d052142a174a.JPG)

### - Interfaz de usuario
![Figura 2 1](https://user-images.githubusercontent.com/68835261/91749631-61ac1000-eb87-11ea-8224-9a659ef37cc5.JPG)

Donde:
- Led Rojo --> Representa altos niveles de temperatura
- Led Azul --> Representa bajos niveles de temperatura

### - Tabla - resumen de variables
![Tabla 1 6](https://user-images.githubusercontent.com/68835261/91750118-2a8a2e80-eb88-11ea-8e9a-9ae307951179.JPG)

### DETECTOR DE GAS
### - Variables utilizadas para el funcionamiento del circuito
![Figura 2 2](https://user-images.githubusercontent.com/68835261/91749641-653f9700-eb87-11ea-867d-3c936cbdf0b2.JPG)

### - Interfaz de usuario
![Figura 2 3](https://user-images.githubusercontent.com/68835261/91749649-68d31e00-eb87-11ea-8235-c5ba0968b4a1.JPG)

Donde:
- Led Rojo --> Representa altas cantidades de gas.
- Led Azul --> Representa bajas cantidades de gas.
- Transductor piezoeléctrico --> Representa a una alarma.

### - Tabla - resumen de variables
![Tabla 1 7](https://user-images.githubusercontent.com/68835261/91750131-30800f80-eb88-11ea-861b-f282fd7155c8.JPG)

## 8. EXPLICACIÓN DEL CÓDIGO FUENTE
### DETECTOR DE LUZ AMBIENTAL 
El funcionamiento del programa básicamente consiste de estructuras condicionales “If-Else” anidadas, en las que se postulan las diferentes condiciones para que los LEDs funcionen como indicadores de la existencia de bajas, medianas y altas cantidades de luz. (Figura 2.4).
Por otro lado, la primera línea de código (expresada en bloques), nos permite asignar el pin analógico A0 a la variable creada “BrilloLuz”.
La segunda línea de código, nos permite imprimir en un monitor, los valores o niveles de luminosidad que el sensor capta.
![Figura 2 4](https://user-images.githubusercontent.com/68835261/91749654-6c66a500-eb87-11ea-815a-14f0c2fa3f09.JPG)

### - Alta luminosidad
La primera estructura condicional nos estipula que, si la variable BrilloLuz se encuentra en el rango de 13 y 17, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.4 – Llave de color rojo), en la que únicamente el pin digital 2 (LED blanco) se encontrará en estado lógico ALTO. Esto quiere decir que existen altos niveles de luz captados por el sensor de luz ambiental en un determinado lugar.

### - Mediana luminosidad
La segunda estructura condicional nos estipula que, si la variable BrilloLuz se encuentra en el rango de 17 y 26, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.4 – Llave de color azul), en la que únicamente el pin digital 3 (LED naranja) se encontrará en estado lógico ALTO. Esto quiere decir que existen medianos niveles de luz captados por el sensor de luz ambiental en un determinado lugar.

### - Baja luminosidad
Si no se cumple con ninguna de las dos estructuras condicionales anteriores, se asume que la variable BrilloLuz se encontrará en el rango de 26 en adelante, entonces el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.4 – Llave de color naranja), en la que únicamente el pin digital 4 (LED azul) se encontrará en estado lógico ALTO. Esto quiere decir que existen bajos niveles de luz captados por el sensor de luz ambiental en un determinado lugar.

### DETECTOR DE MOVIMIENTO
![Figura 2 5](https://user-images.githubusercontent.com/68835261/91749668-725c8600-eb87-11ea-9a82-b27c1b6fb0bd.JPG)

### - Existencia de Movimiento
La primera estructura condicional (Ilustrada en la figura 2.5 – Llave de color rojo) nos estipula que, si la variable Sensor se encuentra en estado lógico ALTO, el programa ejecutará la secuencia de bloques, en la que el pin digital 3 (LED) y el pin digital 4 (Transductor piezoeléctrico) se encontrarán en estado lógico ALTO. Esto quiere decir que el sensor recibió niveles de radiación infrarroja, lo cual implica que existió movimiento en un área específica. Para indicar dicho suceso, hemos considerado encender el LED y el transductor piezoeléctrico en señal de alarma.

### - No existe Movimiento
Si no se cumple dicha condición se ejecutará la secuencia de bloques (Ilustrada en la figura 2.5 – Llave de color azul), en la que el pin digital 3 (LED) y el pin digital 4 (Transductor piezoeléctrico) se encontrarán en estado lógico BAJO. Esto quiere decir que el sensor no recibió niveles de radiación infrarroja, lo cual implica que no existió movimiento en un área específica. 

### DETECTOR DE DISTANCIA
![Figura 2 6](https://user-images.githubusercontent.com/68835261/91749673-75f00d00-eb87-11ea-86a2-a23287b1485b.JPG)

### - Corta Distancia
La primera estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de distancia entre 0 y 100 cm, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.6 – Llave de color rojo), en la que únicamente el pin digital 2 (LED rojo) se encontrará en estado lógico ALTO. Esto quiere decir que la distancia entre el objeto y el sensor ultrasónico es corta. Para lo cual hemos encendido un LED rojo en señal de alarma.

### - Mediana Distancia
La segunda estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de distancia entre 100 y 200 cm, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.6 – Llave de color azul), en la que únicamente el pin digital 3 (LED naranja) se encontrará en estado lógico ALTO. Esto quiere decir que la distancia entre el objeto y el sensor ultrasónico es mediana. Para lo cual hemos encendido un LED naranja para indicar dicha distancia.

### - Larga Distancia
Si no se cumple con ninguna de las dos estructuras condicionales anteriores, se asume que la variable Sensor se encontrará en el rango de 200 cm. en adelante, entonces el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.6 – Llave de color naranja), en la que únicamente el pin digital 4 (LED azul) se encontrará en estado lógico ALTO. Esto quiere decir que la distancia entre el objeto y el sensor ultrasónico es lejana. Para lo cual hemos encendido un LED azul para indicar dicha distancia.

### DETECTOR DE INCLINACIÓN
![Figura 2 7](https://user-images.githubusercontent.com/68835261/91749675-7688a380-eb87-11ea-9c9e-ab478729a895.JPG)

### - Existencia de inclinación
La estructura condicional (Ilustrada en la figura 2.7 – Llave de color rojo) nos estipula que, si la variable Sensor se encuentra en estado lógico ALTO, el programa ejecutará la secuencia de bloques, en la que el pin digital 3 (LED) se encontrará en estado lógico ALTO. Esto quiere decir que existió inclinación de un objeto y esto fue captado por el sensor, expresándolo como una señal digital equivalente a 1 lógico. Para indicar dicho suceso, hemos considerado encender un LED.

### - No existe inclinación
Si no se cumple dicha condición se ejecutará la secuencia de bloques (Ilustrada en la figura 2.5 – Llave de color azul), en la que el pin digital 3 (LED se encontrarán en estado lógico BAJO. Esto quiere decir que no existió inclinación alguna del objeto y esto fue captado por el sensor, expresándolo como una señal digital equivalente a 0 lógico. Para indicar dicho suceso, hemos considerado apagar el LED.

### DETECTOR DE TEMPERATURA
![Figura 2 8](https://user-images.githubusercontent.com/68835261/91749690-7dafb180-eb87-11ea-915e-d0d893368eff.jpg)

### - Temperaturas entre -40°C y -10°C
La primera estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de temperatura entre -40 y -10°C, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.8 – Llave de color azul), en la que únicamente el pin digital 6 (LED azul) se encontrará en estado lógico ALTO. Esto quiere decir que la temperatura captada por el sensor es baja. Para lo cual hemos encendido un LED azul para representar dicha característica.

### -	Temperaturas entre -10 °C y 20°C
La segunda estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de temperatura entre -10 y 20°C, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.8 – Llave de color verde), en la que los pines digitales 6 y 5 (LED azul y verde respectivamente) se encontrarán en estado lógico ALTO. Esto quiere decir que la temperatura captada por el sensor aumentó en relación al caso anterior. Para lo cual hemos encendido los LEDs azul y verde para representar dicha característica.

### -	Temperaturas entre 20 °C y 50°C
La tercera estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de temperatura entre -20 y 50°C, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.8 – Llave de color amarillo), en la que los pines digitales 6, 5 y 4 (LEDs azul, verde y amarillo respectivamente) se encontrarán en estado lógico ALTO. Esto quiere decir que la temperatura captada por el sensor aumentó en relación a los dos casos anteriores. Para lo cual hemos encendido los LEDs azul, verde y amarillo para representar dicha característica.

### -	Temperaturas entre 50 °C y 90°C
La cuarta estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de temperatura entre 50 y 90°C, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.8 – Llave de color naranja), en la que los pines digitales 6, 5, 4 y 3 (LEDs azul, verde, amarillo y naranja respectivamente) se encontrarán en estado lógico ALTO. Esto quiere decir que la temperatura captada por el sensor aumentó en relación a los tres casos anteriores. Para lo cual hemos encendido los LEDs azul, verde, amarillo y naranja para representar dicha característica.

### -	Temperaturas mayores a 90 °C 
Si no se cumple ninguna de las estructuras condicionales anteriores, se asume que la temperatura estará con valores mayores a 90°C, entonces el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.8 – Llave de color rojo), en la que los pines digitales 6, 5, 4, 3 y 2 (LEDs azul, verde, amarillo, naranja y rojo respectivamente) se encontrarán en estado lógico ALTO. Esto quiere decir que la temperatura captada por el sensor aumentó en relación a los cuatro casos anteriores, siendo los niveles más altos de temperatura. Para lo cual hemos encendido todos los LEDs y así representar dicha característica. En otras palabras, los Leds indican de manera gráfica la escala de temperatura que es captada por el sensor. 

### DETECTOR DE GAS
![Figura 2 9](https://user-images.githubusercontent.com/68835261/91749697-80aaa200-eb87-11ea-8ea7-64e439319acc.jpg)

### -	Nivel de gas entre 306 y 346
La primera estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de nivel de gas entre 306 y 346, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.9 – Llave de color azul), en la que únicamente el pin digital 6 (LED azul) se encontrará en estado lógico ALTO. Esto quiere decir que los niveles de gas captados por el sensor son bajos. Para lo cual hemos encendido un LED azul, representando así dicha característica.

### -	Nivel de gas entre 346 y 386
La segunda estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de nivel de gas entre 346 y 386, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.9 – Llave de color verde), en la que los pines digitales 6 y 5 (LEDs azul y verde respectivamente) se encontrarán en estado lógico ALTO. Esto quiere decir que los niveles de gas captados por el sensor aumentaron en relación al caso anterior. Para lo cual hemos encendido los LEDs azul y verde, representando así dicha característica.

### -	Nivel de gas entre 386 y 456
La tercera estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de nivel de gas entre 386 y 456, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.9 – Llave de color amarillo), en la que los pines digitales 6, 5 y 4 (LEDs azul, verde y amarillo respectivamente) se encontrarán en estado lógico ALTO. Esto quiere decir que los niveles de gas captados por el sensor aumentaron en relación a los dos casos anteriores. Para lo cual hemos encendido los LEDs azul, verde y amarillo, representando así dicha característica.

### -	Nivel de gas entre 456 y 560
La cuarta estructura condicional nos estipula que, si la variable Sensor se encuentra en el rango de nivel de gas entre 456 y 560, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.9 – Llave de color naranja), en la que los pines digitales 6, 5, 4 y 3 (LEDs azul, verde, amarillo y naranja respectivamente) se encontrarán en estado lógico ALTO. Esto quiere decir que los niveles de gas captados por el sensor aumentaron en relación a los tres casos anteriores. Para lo cual hemos encendido los LEDs azul, verde, amarillo y naranja, representando así dicha característica.

### -	Niveles de gas mayores a 560
Si no se cumple ninguna de las estructuras condicionales anteriores, se asume que los niveles de gas están por encima de 560, entonces el programa ejecutará la secuencia de bloques (Ilustrada en la figura 2.9 – Llave de color rojo), en la que los pines digitales 6, 5, 4 , 3 y 2 (LEDs azul, verde, amarillo, naranja y rojo respectivamente) se encontrarán en estado lógico ALTO, al igual que el pin digital 7 (Transductor piezoeléctrico). Esto quiere decir que los niveles de gas captados por el sensor aumentaron en relación a los cuatro casos anteriores, siendo niveles altos de gas captados por el sensor. Para lo cual hemos encendido todos los LEDs y el transductor piezoeléctrico que representa una señal de alerta o alarma por altas cantidades de gas situadas en un lugar determinado.

## 9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN
En lo que corresponde a la utilización de aplicaciones secundarias para que el programa funcione correctamente, podemos decir que no se ha necesitado de ninguna que influya directamente sobre su programación, ya que Tinkercad ofrece formatos de programación tanto en un entorno textual como gráfico. 

Ahora bien, necesitamos saber cuales son los pasos para poder programar un Arduino en una interfaz gráfica (mediante bloques) en Tinkercad. Para lo cual, debemos:

1.	Seleccionar en la sección de componentes, todos los elementos que se utilizarán en el circuito, entre ellos, el Arduino UNO R3 que incorpora Tinkercad.
![DP1](https://user-images.githubusercontent.com/68835261/91749085-953a6a80-eb86-11ea-93e4-128cd287f088.JPG)

2.	Conectar todos los componentes electrónicos de entrada y salida en los pines digitales del Arduino, se recomienda utilizar un protoboard para mayor facilidad al momento de realizar las conexiones.
![DP2](https://user-images.githubusercontent.com/68835261/91749106-9bc8e200-eb86-11ea-8d51-2caa83876604.JPG)

3.	Dirigirse a la barra de control y seleccionar la opción “Código”
![DP3](https://user-images.githubusercontent.com/68835261/91749113-a08d9600-eb86-11ea-860a-b715ccafcd2e.JPG)

4.	Nos encontraremos con la siguiente interfaz y seleccionaremos la opción de programación mediante “Bloques”. Por default el programa incorpora 4 bloques de código con instrucciones variadas. Entonces procedemos a borrar y a programar nuestro circuito
![DP4](https://user-images.githubusercontent.com/68835261/91749118-a2eff000-eb86-11ea-8744-9d73a232ed14.JPG)

5.	En la siguiente figura se encuentran todos los bloques categorizados (bloques de salida, entrada, notación, control, matemáticas, variables). Entonces seleccionamos, los que sean necesarios y de esta manera dar las instrucciones para que nuestro circuito funcione a nuestra necesidad. En este caso un sistema de semáforos controlados por dos switch de entrada.
![DP5](https://user-images.githubusercontent.com/68835261/91749134-a84d3a80-eb86-11ea-9d37-8efe71522183.JPG)

6.	Una vez que ya se ha realizado la programación (ilustrada en la sección 8. Explicación del código fuente) procedemos a dar clic en “Iniciar simulación” y verificar que el circuito funcione correctamente (Sección 10. Aportaciones)
![DP6](https://user-images.githubusercontent.com/68835261/91749148-ac795800-eb86-11ea-95a4-2736ddd31a32.JPG)

Por otro lado, para el correcto funcionamiento de cada circuito, hay que tener en cuenta varios puntos específicos. Los cuales son indispensables para entender los rangos de operación de cada sensor. 

### •	Detector de luz ambiental
-	Nivel de luz alta (LED blanco encendido) cuando el sensor capte un rango de valores entre 13 y 17.
-	Nivel de luz mediano (LED naranja encendido) cuando el sensor capte un rango de valores entre 17 y 26.
-	Nivel de luz baja (LED azul encendido) cuando el sensor capte un rango de valores mayores a 26. 

### •	Detector de movimiento
-	Encendido del LED y del transductor piezoeléctrico en señal de alarma por detectar movimiento de un objeto con el sensor PIR.

### •	Detector de distancia
-	Distancia cercana entre el objeto y el sensor ultrasónico, cuando este último capte una distancia que se encuentre entre 0 y 100 cm. (LED rojo encendido).
-	Distancia mediana entre el objeto y el sensor ultrasónico, cuando este último capte una distancia que se encuentre entre 100 y 200 cm. (LED naranja encendido).
-	Distancia mediana entre el objeto y el sensor ultrasónico, cuando este último capte una distancia que se encuentre entre 100 y 200 cm. (LED azul encendido).

### •	Detector de inclinación
-	Encendido del LED cuando el sensor detecte inclinación.
-	Apagado del LED cuando el sensor no detecte inclinación.

### •	Detector de temperatura
-	Temperaturas entre -40°C y -10°C  Encendido del LED azul (Temperaturas bajas).
-	Temperaturas entre -10°C y 20°C  Encendido del LED azul y verde.
-	Temperaturas entre 20°C y 50°C  Encendido del LED azul, verde y amarillo.
-	Temperaturas entre 50°C y 90°C  Encendido del LED azul, verde, amarillo y naranja.
-	Temperaturas mayores a 90°C  Encendido del LED azul, verde, amarillo, naranja, rojo.

### •	Detector de gas
-	Niveles de gas entre 306 y 346  Encendido del LED azul (bajos niveles de gas).
-	Niveles de gas entre 346 y 386  Encendido del LED azul, y verde
-	Niveles de gas entre 386 y 456  Encendido del LED azul, verde y amarillo
-	Niveles de gas entre 456 y 560  Encendido del LED azul, verde, amarillo y naranja
-	Niveles de gas mayores a 560  Encendido del LED azul, verde, amarillo, naranja y rojo y del transductor piezoeléctrico en señal de alarma (altos niveles de gas).

Nota: Para programar en Arduino mediante Tinkercad, se requiere de la familiarización con fundamentos básicos de programación (Principalmente sobre estructuras condicionales, lógica booleana) y conocimientos sobre el funcionamiento de los sensores, además de la constitución, funcionalidad y partes de un Arduino.

## 10. APORTACIONES
### Características principales del Arduino UNO
-	Microcontrolador: ATmega328 
-	Voltaje de operación: 5V 
-	Voltaje de entrada (recomendado): 7-12V 
-	Voltaje de entrada (límites): 6-20V 
-	Pines de E/S digitales: 14 (de los cuales 6 proporcionan salida PWM) 
-	Pines de entrada analógica: 6 
-	Corriente DC por pin de E/S: 40 mA 
-	Corriente DC para 3.3V Pin: 50 mA 
-	Memoria Flash: 32 KB de los cuales 0,5 KB utilizados por el bootloader 
-	SRAM: 2 KB (ATmega328) 
-	EEPROM: 1 KB (ATmega328) Velocidad de reloj: 16 MHz

### Analog IN
Si se requiere de la utilización de señales análogas y utilizarlas como datos de información de entrada, debemos conocer, lo siguiente:
-	La placa Arduino Uno tiene 6 pines analógicos, que utilizan ADC (Convertidor de Analógico a Digital). Estos pines sirven como entradas analógicas, pero también pueden funcionar como entradas o salidas digitales.
 
-	El ADC es un circuito electrónico utilizado para convertir señales analógicas en señales digitales. Esta representación digital de señales analógicas permite al procesador, que es un dispositivo digital, medir la señal analógica y utilizarla durante su funcionamiento.
-	Los pines Arduino A0-A5 son capaces de leer tensiones analógicas. En Arduino el ADC tiene una resolución de 10 bits, lo que significa que puede representar una tensión analógica de 1.024 niveles digitales. El ADC convierte el voltaje en bits que el microprocesador puede entender.

### Ejemplo del funcionamiento del circuito detector de luz ambiental 
### -	Niveles de luz mayores a 26
![Figura 3 1](https://user-images.githubusercontent.com/68835261/91749703-843e2900-eb87-11ea-8126-7ab0de9d56bf.JPG)

### -	Niveles de luz entre 17 y 26
![Figura 3 2](https://user-images.githubusercontent.com/68835261/91749714-899b7380-eb87-11ea-8353-9362b8683c71.JPG)

### -	Niveles de luz entre 13 y 17
![Figura 3 3](https://user-images.githubusercontent.com/68835261/91749729-8e602780-eb87-11ea-8e0c-2d3d552f1da7.JPG)

### Ejemplo del funcionamiento del circuito detector de movimiento 
### -	Existencia de movimiento
![Figura 3 4](https://user-images.githubusercontent.com/68835261/91749749-94560880-eb87-11ea-93f4-87742104f366.JPG)

### -	Inexistencia de movimiento
![Figura 3 5](https://user-images.githubusercontent.com/68835261/91749767-991abc80-eb87-11ea-9d66-99dd241575c1.JPG)

### Ejemplo del funcionamiento del circuito detector de distancia
### -	Distancia entre 0 y 100 cm.
![Figura 3 6](https://user-images.githubusercontent.com/68835261/91749775-9cae4380-eb87-11ea-9dfc-18fcc85d8be4.JPG)

### -	Distancia entre 100 y 200 cm.
![Figura 3 7](https://user-images.githubusercontent.com/68835261/91749785-a172f780-eb87-11ea-8bf8-889aaf0bcb24.JPG)

### -	Distancias mayores a 200 cm.
![Figura 3 8](https://user-images.githubusercontent.com/68835261/91749798-a637ab80-eb87-11ea-8459-d28197865585.JPG)

### Ejemplo del funcionamiento del circuito detector de inclinación
### -	Inexistencia de inclinación.
![Figura 3 9](https://user-images.githubusercontent.com/68835261/91749815-adf75000-eb87-11ea-964b-22d3db97ed05.JPG)

### -	Existencia de inclinación.
![Figura 4 1](https://user-images.githubusercontent.com/68835261/91749822-b0f24080-eb87-11ea-8c21-0a9da48bf846.JPG)

### Ejemplo del funcionamiento del circuito detector de temperatura
### -	Temperatura entre -40°C y -10 °C.
![Figura 4 2](https://user-images.githubusercontent.com/68835261/91749831-b3ed3100-eb87-11ea-93cf-881d8b05db57.JPG)

### -	Temperatura entre -10°C y 20 °C.
![Figura 4 3](https://user-images.githubusercontent.com/68835261/91749847-b9e31200-eb87-11ea-878a-22169779f64e.JPG)

### -	Temperatura entre 20°C y 50 °C.
![Figura 4 4](https://user-images.githubusercontent.com/68835261/91749854-bfd8f300-eb87-11ea-901c-eb51cc7d3c4a.JPG)

### -	Temperatura entre 50°C y 90 °C.
![Figura 4 5](https://user-images.githubusercontent.com/68835261/91749865-c4051080-eb87-11ea-8371-ed8fd94364e2.JPG)

### -	Temperaturas mayores a 90 °C.
![Figura 4 6](https://user-images.githubusercontent.com/68835261/91749877-c7989780-eb87-11ea-8d2e-a4d822e3887a.JPG)

### Ejemplo del funcionamiento del circuito detector de gas
### -	Niveles de gas entre 306 y 346.
![Figura 4 7](https://user-images.githubusercontent.com/68835261/91749890-cbc4b500-eb87-11ea-8c02-a4f877748934.JPG)

### -	Niveles de gas entre 346 y 386.
![Figura 4 8](https://user-images.githubusercontent.com/68835261/91749898-d0896900-eb87-11ea-9b8c-54c94f34fc60.JPG)

### -	Niveles de gas entre 386 y 456.
![Figura 4 9](https://user-images.githubusercontent.com/68835261/91749907-d54e1d00-eb87-11ea-9c4d-bb65e930adba.JPG)

### -	Niveles de gas entre 456 y 560.
![Figura 5 1](https://user-images.githubusercontent.com/68835261/91749925-daab6780-eb87-11ea-97d1-b5d3a120fcc0.JPG)

### -	Niveles de gas mayores a 560.
![Figura 5 2](https://user-images.githubusercontent.com/68835261/91749934-de3eee80-eb87-11ea-99e0-2631a0633cd8.JPG)

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

## 14. Bibliografía

## 15. Anexos
### 15.1 Manual de usuario
El presente manual está diseñado para facilitar el uso de los 6 circuitos que nos permiten simular el funcionamiento de detección de luz ambiental, movimiento, distancia, inclinación, temperatura y detección de gas. 

1.	Cuenta en Tinkercad
Si no se ha registrado en Tinkercad, lo primero que debe hacer es crearse una cuenta introduciendo sus datos personales, correo electrónico y contraseña. Tal como se muestra, a continuación:
![MU 1](https://user-images.githubusercontent.com/68835261/91749970-ec8d0a80-eb87-11ea-83ea-469a1a7d89d2.JPG)

2.	Una vez creada la cuenta, lo que debe realizar es proceder a ingresar al siguiente enlace: 
https://www.tinkercad.com/things/9oqJvGw5adi

3.	El enlace le llevará a la dirección web en el que podrá ejecutar y simular los 6 circuitos en una interfaz de laboratorio virtual que ofrece Tinkercad. Le aparecerá una pestaña en la que tendrá que presionar el botón Iniciar Simulación, tal como se muestra a continuación. 
![MU 2](https://user-images.githubusercontent.com/68835261/91749978-edbe3780-eb87-11ea-825b-372d3094a526.JPG)

4.	Escoja un circuito
En este punto tendrá que activar uno de los seis circuitos, cada uno está implementado con diferentes sensores.
-	Circuito detector de luz ambiental
![MU 3](https://user-images.githubusercontent.com/68835261/91749991-f151be80-eb87-11ea-833b-e623966b3a55.JPG)

-	Circuito detector de movimiento
![MU 4](https://user-images.githubusercontent.com/68835261/91749999-f6af0900-eb87-11ea-85d4-489078feaef3.JPG)

-	Circuito detector de distancia
![MU 5](https://user-images.githubusercontent.com/68835261/91750018-fd3d8080-eb87-11ea-998e-d031ccc9d8de.JPG)

-	Circuito detector de inclinación
![MU 6](https://user-images.githubusercontent.com/68835261/91750026-01699e00-eb88-11ea-8005-5bea67f3626e.JPG)

Circuito detector de temperatura
![MU 7](https://user-images.githubusercontent.com/68835261/91750042-075f7f00-eb88-11ea-842a-e3f28d29f6bd.JPG)

-	Circuito detector de gas
![MU 8](https://user-images.githubusercontent.com/68835261/91750056-0cbcc980-eb88-11ea-845d-12b110e990a5.JPG)

### 15.2 Hojas Técnicas
![HT 1](https://user-images.githubusercontent.com/68835261/91749963-ea2ab080-eb87-11ea-86e1-556c40a1e4fd.JPG)
