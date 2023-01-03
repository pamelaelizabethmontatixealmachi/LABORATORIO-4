# LABORATORIO-4
LB4


Integrantes:

Jose Joaquin Silva Escobar


Pamela Elizabeth Montatixe Almachi


Mauricio Joseph Taco Cabrera

OBJETIVO


Implementar el teorema de Superposición en un ejercicio práctico.
Entender el teorema de superposición de manera experimental a través del simulador Tinkercad


MARCO TEÓRICO


TEOREMA DE SUPERPOSICIÓN

El teorema de superposición establece que en un circuito lineal con varias fuentes, la corriente y el voltaje para cualquier elemento en el circuito es la suma de las corrientes y voltajes producidos por cada fuente que actúa de manera independiente.

Para calcular la contribución de cada fuente de forma independiente, todas las demás fuentes deben eliminarse y reemplazarse sin afectar el resultado final. Al eliminar una fuente de voltaje, su voltaje debe establecerse en cero, lo que equivale a reemplazar la fuente de voltaje con un cortocircuito. Al eliminar una fuente de corriente, su corriente debe establecerse en cero, lo que equivale a reemplazar la fuente de corriente con un circuito abierto. Cuando suma las contribuciones de las fuentes, debe tener cuidado de tener en cuenta sus signos. Es mejor asignar una dirección de referencia a cada cantidad desconocida, si aún no se ha dado.

El voltaje o corriente total se calcula como la suma algebraica de las contribuciones de las fuentes. Si una contribución de una fuente tiene la misma dirección que la dirección de referencia, tiene un signo positivo en la suma; si tiene la dirección opuesta, entonces un signo negativo. Tenga en cuenta que si las fuentes de voltaje o corriente tienen resistencia interna, debe permanecer en el circuito y aún debe considerarse. En TINA, puede asignar una resistencia interna al voltaje de CC y las fuentes de corriente, mientras usa el mismo símbolo esquemático. Por lo tanto, si desea ilustrar el teorema de superposición y al mismo tiempo utilizar fuentes con resistencia interna, solo debe establecer el voltaje (o corriente) de la fuente en cero, lo que deja intacta la resistencia interna de la fuente. Alternativamente, puede reemplazar la fuente con una resistencia igual a su resistencia interna. Para usar el teorema de superposición con corrientes y voltajes de circuito, todos los componentes deben ser lineales; es decir, para todos los componentes resistivos, la corriente debe ser proporcional al voltaje aplicado (satisfaciendo la ley de Ohm). Tenga en cuenta que el teorema de superposición no es aplicable a la potencia, ya que la potencia no es una cantidad lineal. La potencia total entregada a un componente resistivo debe determinarse utilizando la corriente total o el voltaje total a través del componente y no puede determinarse mediante una simple suma de las potencias producidas por las fuentes de forma independiente.

Corto circuito

Se denomina cortocircuito al fallo en un aparato o línea eléctrica por el cual la corriente eléctrica pasa directamente del conductor activo a la fase neutro o tierra, entre dos fases en el caso de sistemas polifásicos en corriente alterna o entre polos opuestos en el caso de corriente continua.

El cortocircuito de produce normalmente por fallos en el aislante de los conductores, cuando estos quedan sumergidos en in medio conductor como el agua por contacto accidental entre conductores aéreos por fuertes vientos o rotura de los apoyos

EXPLICACIÓN DEL PROCEDIMIENTO
3.1 MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/116780506/210407904-85d7db86-9131-4b59-b1ba-4685a259754c.png)


3.2 Arme el circuito que se muestra en la figura 4.1.

![image](https://user-images.githubusercontent.com/116780506/210407993-883311c2-9602-4731-bfcb-2a3ab16f9d3a.png)


3.3 Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/116780506/210408033-63616588-3864-40af-b75f-9b5d0b3a593b.png)


3.4 Haga “cero” la fuente de voltaje de 3 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/116780506/210408082-e1b48ced-515d-4384-925b-da3bd215e053.png)




3.5 Haga “cero” la fuente de voltaje de 10 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/116780506/210408141-7d6739a0-2190-43ec-87e0-4c4dd025af8a.png)


RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR


4.1. Medición de voltaje aplicando superposición

![image](https://user-images.githubusercontent.com/116780506/210408185-d070d9fc-b5f1-4796-957b-3456f552fae8.png)
 
 
4.2. Medición de corriente aplicando superposición

![image](https://user-images.githubusercontent.com/116780506/210408225-38068a6a-ff8a-4b00-a5dd-e221473a2db5.png)




4.3 Calcular errores de las mediciones

![image](https://user-images.githubusercontent.com/116780506/210408271-73564912-f2cc-47b1-8215-70beedf9392c.png)


VIDEO
5.1 Calculos

https://drive.google.com/file/d/1xprbNgkmxy9d7ilNZ2S2OvpFzzpXu-Dq/view?usp=sharing

5.2 Circuito armado en thinkercard

https://drive.google.com/file/d/10VzfwMNfGud2X6F1dh8xxfxFGUCOALH6/view?usp=sharing

CONCLUSIONES
• El método o teorema de superposición es de gran utilidad para analizar circuitos que tengan dos o más fuentes de suministro ya que al analizarlo fuente por fuente el análisis resultará mucho más sencillo de realizar.

• Se comprobó que los resultados obtenidos mediante el método de superposición son similares a los datos obtenidos en la simulación del circuito considerando también la pérdida de decimales lo cual causará que los resultados calculados varían de forma mínima con los obtenidos en simulación.

• Los circuitos lineales cumplen la propiedad de superposición. Esto es, en un circuito con varias fuentes (de tensión / corriente), la respuesta se puede hallar sumando la respuesta del circuito a cada una de las fuentes (independientes) por separado

• En la aplicación el teorema de superposición permite un cálculo veloz, eficaz y fácil para el análisis de circuitos electrónicos de una rama, componente o línea de componentes

BIBLIOGRAFÍA
Floyd, T. L., Salas, R. N., González, L. M. O., & López, G. P. (2007). Principios de circuitos eléctricos. Pearson Educación.

Vass, H. (2007). Circuitos eléctricos III.
