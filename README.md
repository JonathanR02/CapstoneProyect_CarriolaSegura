Titulo del Proyecto : Carriola Segura.

Introducción.

Actualmente vivimos en un país de mucha inseguridad, por lo que es importante resguardar la seguridad de los bebes y evitar que sean separados de sus familias. La mayoría de las ocasiones los bebes son sustraídos de las carriolas y muchas veces a los padres no se les es posible percatarse de la situación al instante. 

Aunque existen carriolas inteligentes con increíbles funcionalidades, no existen carriolas que mantenga un monitoreo del bebe, por ejemplo de cuando es levantado de la misma o que verifique que pasa en su alrededor. 

Este proyecto busca mantener la seguridad del bebe mediante múltiples funcionalidades, se considera que la carriola tenga incluido 2 brazaletes para la madre y el padre que son las personas que podrían levantar al bebe de la carriola, estos estarían vinculados a un brazalete más que tendría él bebe, en el caso de que los padres levanten al bebe de su carriola, al estar vinculados los brazaletes no sonaría ninguna alarma, en el caso de que alguna otra persona lo haga, sí se activaría una alarma, aunado a estas funcionalidades se desea que la carriola tenga incluida una cámara que registre los movimientos en los alrededores y mediante GPS se plantea tener el registro de la ubicación de la carriola.


Alcances

Este proyecto busca tener múltiples funcionalidades de seguridad en la carriola y mediante estos evitar la sustracción del menor de su carriola. Se desea que los usuarios estén seguros de que su bebe no será sustraído por cualquier extraño y que de suceder esto exista la posibilidad de que inmediatamente se active la alerta y  se puedan percatar al instante de la situación y así evitar el robo del menor. 



Justificación
 	El proyecto se realizará entorno a Internet de las cosas ya que entre sus múltiples ventajas permite automatizar los procesos, aumenta la seguridad que es uno de los puntos importantes que se busca con este proyecto,  aumentar la seguridad del bebe en la carriola. Mediante los diferentes dispositivos electrónicos se podrá mantener un monitoreo de las actividades alrededor de la carriola y lanzar alertas en cuanto él bebe sea levantado por alguna persona que no cuente con el brazalete.  Todas estas funcionalidades se realizarán de forma inmediata y en tiempo real que es otra de las características de realizar proyectos en torno a Internet de las cosas. 


Objetivo.

    • Crear el prototipo de una carriola inteligente con múltiples funcionalidades de seguridad para él bebe. 


Material necesario.

Para ensamblar el circuito se requiere contar con el siguiente material:

    • Esp32 								2	$208.00
    • Cámara Esp32-cam						2 	$227.00	
    • Sensor de proximidad E18d80nk				1 	$125.00
    • Sensor de fuerza resistivo					1 	$290.00	
    • Altavoz para alarma						1	$200.00	
    • Sensor inductivo de proximidad npn				1 	$273.00
    • Raspberry pi 							1	$2479.00
	
*Posiblemente sean necesarios más materiales, pero esto se tomara en cuenta sobre el avance del aprendizaje del diplomado.
Circuito propuesto.

Se conectarán a los Esp32 las respectivas cámaras, las cuales permitirán tener monitoreado los alrededores de la carriola, también a uno de los Esp32 se conectará el sensor de presión, los datos de estos tres dispositivos serán enviados a través del lenguaje Mqtt para ser capturados en el Esp32 y que se puedan enviar a una bases de datos creada en MySQL. Por otra parte la  Raspberry será la encargada de analizar constantemente que los datos de presión no varíen en gran medida, ya que si esto llegara a suceder, significa que alguien ha tomado al bebe. Para el caso en el que él bebe sea levantado de la carriola la Raspberry enviará una señal para que la luz se encienda y la alarma se active. El sensor de proximidad estará conectado directamente a la Raspberry la cual realizará un análisis por si alguien se acerca, mantendrá monitoreado así como como los datos de quien se acerca.
Todos los dispositivos funcionarán en conjunto para brindarle la mejor seguridad al bebe que está en la carriola.
