# trabajo-extra-amplificador-no-inversor-

1.-Objetivos

General

-Analizar el comportamiento de un amplificador sumador no inversor e identificar las aplicaciones para este tipo de circuitos.

Especificos

-Comparar las simulaciones con la practica para justificar los datos.


-Identificar las similitudes con el circuito con un amplificador no inversor.


2.-Marco teórico

![image](https://user-images.githubusercontent.com/93899720/156722624-9237ed2f-6865-43b1-8c56-1492a0ffaf1a.png)


3.-Procedimiento

Primero se realiza la simulacion utilizando el simulador DCAClab

![image](https://user-images.githubusercontent.com/93899720/156722981-a7c3914f-2ebf-4a33-b2b9-7a1ddb649f9f.png)

El circuito a implementar es el siguiente:

![image](https://user-images.githubusercontent.com/93899720/156722883-fa82973e-31f0-4405-b2db-1ae9059864da.png)

Primero sacamos todos los componentes que vamos a utilizar para armar el circuito.

![image](https://user-images.githubusercontent.com/93899720/156723396-12296fd0-4874-446d-9f7f-1ccfed1e7d27.png)

Luego procedemos a conectar todo el circuito como se presenta en el diagrama

![image](https://user-images.githubusercontent.com/93899720/156724225-817be870-ff64-449d-b549-ca48b15e1dbd.png)

Luego se ajustan los valores de cada componente

![image](https://user-images.githubusercontent.com/93899720/156724389-1fca292d-9381-4b8d-89b0-07d901f47c37.png)


![image](https://user-images.githubusercontent.com/93899720/156724456-4cd9e8b2-957e-4a8b-a16b-591913db30ea.png)


![image](https://user-images.githubusercontent.com/93899720/156724478-b44844fc-0976-4685-a852-3a20fcdfc780.png)


![image](https://user-images.githubusercontent.com/93899720/156724537-18b5d68a-a392-4de6-b985-cd4b0db376c6.png)


Luego con la ayuda del osiloscopio visualizamos la curva sinosoidal que nos confirma que el voltaje se amplifico hasta 10 voltios

![image](https://user-images.githubusercontent.com/93899720/156724913-9dcd917e-ab19-4073-876d-647eba77a077.png)


![image](https://user-images.githubusercontent.com/93899720/156724984-b3ab285b-8811-41f2-9243-1c416621f1b1.png)

Como se puede observar el voltaje se incremento ya que el dato que colocamos en la fuente de poder fue de 1V y la grafica nos presenta un voltaje pico de 10V lo que concuerda ya que la ganancia esta determinanda por la resistencia 2 sobre la resistencia 1 lo que nos da un valor de 10.


-Materiales:

-Potenciometro


-Resistencias(10 kΩ y 1 kΩ)


-Cables conductores


-Amplificador operacional (LM741CN)


-Fuente de voltaje (12 V)


Contruccion del circuito:

Primero se coloca el amplificador operacional en el protoboar con el seintido de la media luna mirando hacia la izquierda para poder identificar de mejor manera las entradas.


![WhatsApp Image 2022-03-06 at 11 20 12 PM](https://user-images.githubusercontent.com/93899720/156969561-4c2b1494-1e09-48e2-a400-e5d0fe0887ec.jpeg)


Luego se coloca el potenciometro para regular la cantidad de voltaje que entra a nuestro circuito.


![WhatsApp Image 2022-03-06 at 11 20 12 PM (1)](https://user-images.githubusercontent.com/93899720/156969637-77938d5e-a192-4b3b-b3db-a0e61b6b8065.jpeg)


Se procede a conectar el potenciometro a la entrada no inversora del amplificador que es el pin tres de este.


![WhatsApp Image 2022-03-06 at 11 20 14 PM](https://user-images.githubusercontent.com/93899720/156969735-721987b0-8e25-4a82-a92e-05c4fe7d8086.jpeg)


Se procede a colocar las resistencias de acuerdo al diagrama del amplificador, la resistencia de 10 kΩ se conecta a la entrada no inversora y a su ves a la salida del amplificador.

La segunda resistencia se conecta a la entrada no inversora y a su ves a tierra.

por ultimo la salida de voltaje positiva que es el pin 7 del amplificador se conecta a la corriente y la salida de voltaje negativa que es el pin 4 se conecta a tierra.


![WhatsApp Image 2022-03-06 at 11 20 18 PM](https://user-images.githubusercontent.com/93899720/156970068-6b2e20b7-6701-4153-bdee-774235e47878.jpeg)



Luego se coloca dos cables uno en la parte positiva y el otro en la parte negativa del protoboard para medir intensidad.


![WhatsApp Image 2022-03-06 at 11 20 17 PM](https://user-images.githubusercontent.com/93899720/156970188-8c1dfa21-f883-45c7-9690-0ff18a0fc326.jpeg)


Por ultimo se conecta todo el circuito a una fuente de poder que en este caso es de 12 V.


![WhatsApp Image 2022-03-06 at 11 20 19 PM](https://user-images.githubusercontent.com/93899720/156970248-dd14728e-f5f8-4d0f-8da1-2128e9769600.jpeg)
![WhatsApp Image 2022-03-06 at 11 20 20 PM](https://user-images.githubusercontent.com/93899720/156970268-81df63ce-4260-4bcb-9d2c-fa8988b7f5a9.jpeg)
![WhatsApp Image 2022-03-06 at 11 20 21 PM](https://user-images.githubusercontent.com/93899720/156970311-43d39fdd-155e-498b-9818-8fa699c52401.jpeg)



4.-Video

5.-Concluciones

-Se concluye que el amplificador sumador no inversor es muy útil para generar una onda resultante a partir de varias ondas lo que facilita tener el control sobre el voltaje.


-Se concluye que el amplificador sumador no inversor es simplemente el amplificador no inversor pero configurado para que potencie y sume voltajes.


-Se concluye que el amplificador sumador no inversor es muy útil a la vez que versátil ya que permite combinar señales a voluntad del usuario como por ejemplo en un mezclador de audio se pueden sumar varias señales de varias entradas.


6.-Bibliografia

-	Amplificador sumador No inversor - Amplificadores operacionales. (2015). Solución ingenieril. http://solucioningenieril.com/amplificadores_operacionales/amplificador_sumador_no_inversor


-	Op-amp Varieties. (2017). Aplicaciones: Amplificador Sumador. http://hyperphysics.phy-astr.gsu.edu/hbasees/Electronic/opampvar5.html#:%7E:text=El%20amplificador%20sumador%20es%20un,varias%20se%C3%B1ales%20con%20ganancias%20iguales.


-	Como funciona circuito sumador no inversor y aplicaciones con OPAMP (Clase 68). (2019, 30 octubre). YouTube. https://www.youtube.com/watch?v=ocIYmhMPYJ0
