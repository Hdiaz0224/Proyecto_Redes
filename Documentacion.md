# Proyecto_Redes
# SDN: Que son y como se diferencian
Para empezar el escrito se dará una breve introducción a lo que se explicará en todo este, que fuentes de información encontramos y finalmente se dará respuesta a las preguntas a resolver. Primero que todo el fin de este ensayo es buscar 5 diferentes fuentes de información únicamente artículos científicos y literatura gris que hablen sobre las SDN (Software Defined Networks) tema central del ensayo.

Las fuentes de información relevantes encontradas incluyen un artículo científico de la revista Universidad Alas Peruanas sobre los protocolos de comunicación en SDN, otro artículo de la Universidad Estatal Península de Santa Elena que explica las SDN en general, un artículo de la revista Visión Electrónica sobre la gestión centralizada de redes, un artículo de la Revista Ibérica de Sistemas e Tecnologías de Informaçã que compara la red tradicional con la SDN, y un trabajo de diploma de la Universidad Central “Marta Abreu” de las Villas que evalúa el rendimiento de las redes SDN.
Teniendo en cuenta la información anterior, las preguntas a resolver eran las siguientes ¿Qué es SDN? ¿Por qué es importante? ¿Cómo funciona? ¿Qué tipos existen? ¿Cuáles son las ventajas y limitaciones comparado al paradigma tradicional de redes? Primero que todo SDN significa Redes definidas por software y estas son un enfoque de las redes en la cual lo principal es desprender el control del Hardware y que este control se le dé a una aplicación de software llamada controlador. Esto lo hace para tener un nuevo enfoque que permita inicializar, controlar, cambiar y gestionar el comportamiento de reenvío del trafico de una red mediante APIs. Para resumir el que es SDN se podría decir que son una arquitectura de red que separa el plano de control y el plano de datos, esto con el fin de que exista una mayor flexibilidad y programabilidad en la gestión de red como se observa en la Figura 1.


                         Figura 1:Arquitecutra de red clásica y Arquitectura de red SDN

 ![image](https://github.com/Hdiaz0224/Proyecto_Redes/assets/93561095/bc7e9823-ea21-41ee-97e1-3ce62fe83959)

                                                          Fuente [2]

La segunda pregunta es ¿Por qué son importantes las redes SDN? Según fuentes de información, las redes SDN ofrecen flexibilidad y programabilidad en la gestión de red. Al separar el control y los datos, permiten una programación más eficiente y automatización de tareas antes tediosas. Son escalables y se adaptan a diferentes necesidades, como entornos empresariales o de centros de datos. Además, ayudan a los administradores a tomar decisiones rápidas y precisas en el enrutamiento del tráfico, reduciendo errores humanos y costos. 

La tercera pregunta es ¿Cómo funciona? De acuerdo con las fuentes de información, en las redes administradas por software se separan físicamente el plano de control y el plano de datos. El primero se encarga de tomar decisiones sobre cómo manejar los paquetes de datos que fluyen a través de la red, mientras que el segundo se encarga de su transmisión. En el centro del plano de control se encuentra el controlador SDN, el cual es responsable de tomar decisiones sobre cómo se deben manejar los paquetes en la red. Para ello, el controlador se comunica con los dispositivos de red mediante el protocolo OpenFlow, el cual le permite programar las tablas de flujo en los dispositivos para determinar cómo deben ser manejados los paquetes. Cada vez que un dispositivo SDN recibe un paquete, busca una coincidencia en su tabla de flujo para saber cómo debe ser manejado. Si no hay una coincidencia, el dispositivo solicita al controlador instrucciones sobre cómo manejar el paquete. El controlador, a su vez, programa la tabla de flujo del dispositivo para manejar futuros paquetes similares. De esta manera, el uso de las SDN permite una mayor flexibilidad y programabilidad en la gestión de redes, lo que se traduce en una mayor eficiencia y una reducción de costos.

La cuarta pregunta es ¿Qué tipos existen? Según las fuentes de información, existen tres tipos de SDN: centralizada, distribuida e híbrida. En el caso de la SDN centralizada, un único controlador centralizado es el encargado de tomar decisiones sobre cómo enrutar el tráfico en la red. Los dispositivos de red programables se comunican con el controlador a través de protocolos como OpenFlow. Por otro lado, la SDN distribuida cuenta con múltiples controladores distribuidos en la red, cada uno de ellos responsable de tomar decisiones sobre una parte específica de la red. Los dispositivos de red programables se comunican con los controladores locales en lugar de hacerlo con un controlador centralizado. Finalmente, en la SDN híbrida se combinan elementos de la SDN centralizada y distribuida. Existe un controlador centralizado que toma decisiones globales sobre cómo enrutar el tráfico en la red, pero también hay controladores locales que se encargan de tomar decisiones sobre partes específicas de la red. Cada uno de estos tipos de SDN tiene sus propias ventajas y desventajas, y es importante seleccionar el tipo adecuado según las necesidades y características de la red en cuestión.

La última pregunta es: ¿Cuáles son las ventajas y limitaciones de las redes definidas por software en comparación con el paradigma tradicional de redes? En cuanto a las ventajas, SDN presenta varias:
-	Mayor flexibilidad y escalabilidad: SDN permite una mayor flexibilidad en la configuración de la red, lo que puede mejorar el rendimiento y reducir los costos. También puede simplificar la gestión de la red al proporcionar una vista centralizada y unificada de toda la infraestructura de red.
-	Mayor eficiencia: SDN permite una gestión más eficiente y dinámica de la red al separar el plano de control del plano de datos. Los administradores de red pueden tomar decisiones más rápidas y precisas sobre cómo enrutar el tráfico en la red.
-	Mejor seguridad: SDN permite una mayor visibilidad y control sobre el tráfico en la red, lo que puede mejorar la seguridad.

Sin embargo, también hay limitaciones para tener en cuenta:
-	Mayor complejidad: La implementación de SDN puede ser más compleja que las redes tradicionales debido a su arquitectura centralizada o distribuida.
-	Dependencia del software: La dependencia del software para gestionar las redes puede ser un riesgo si hay problemas con el software o si se produce un ataque cibernético.
-	Costo inicial: La implementación inicial de SDN puede ser costosa debido a los requisitos adicionales para dispositivos programables y controladores.

                      Figura 2: Comparación de SDN vs Red Tradicional.

 ![image](https://github.com/Hdiaz0224/Proyecto_Redes/assets/93561095/51918a57-211c-4215-9b7e-38c0ee3bfd65)

                               Fuente [2]

En conclusión, aunque las redes definidas por software presentan muchas ventajas, también es importante tener en cuenta sus limitaciones antes de tomar la decisión de implementarlas en una red.

Referencias

G. Mocha Guacho y J. Celleri Pacheco, "Análisis Comparativo de Protocolos de Comunicación para Redes definidas por Software", HAMUT'AY, vol. 7, n.º 3, p. 39, enero de 2021. Accedido el 08 de mayo de 2023. [En línea]. Disponible: https://doi.org/10.21503/hamu.v7i3.2190

L. M. Amaya Fariño, J. F. Arroyo Pizarro, M. Jaramillo Infante, A. R. Tumbaco Reyes y B. M. Mendoza Morán, "SDN Redes definidas por Software usando MiniNet", Revista Científica y Tecnológica UPSE, vol. 9, n.º 1, pp. 48–56, junio de 2022. Accedido el 08 de mayo de 2023. [En línea]. Disponible: https://doi.org/10.26423/rctu.v9i1.489

M. Á. Barrera Pérez, N. Y. Serrato Losada, E. Rojas Sánchez y G. Mancilla Gaona, "State of the art in software defined networking (SDN)", Visión electrónica, vol. 13, n.º 1, pp. 178–194, enero de 2019. Accedido el 08 de mayo de 2023. [En línea]. Disponible: https://doi.org/10.14483/22484728.14424

E. R. Pérez Tardío, "Evaluación de desempeño de las redes SDN mediante la aplicación de mecanismos de calidad de servicio definidos para redes IP", Tesis de grado, Universidad Central "Marta Abreu" de Las Villas, Villa Clara, 2019.

P. Alcivar y M. Navia, "Comparativa entre red tradicional y red definida por software: Caso de estudio ESPAM MFL", Revista Ibérica de Sist. e Tecnologias de Informação Iberian J. Inf. Syst. Technol., pp. 79–90, febrero de 2020.

## Introduccion
Para el desarrollo de este proyecto se nos dividio en 2 partes, la primera parte era realizar una revision bibliografica en la cual se iba a buscar informacion acerca de las SDN y a resolver las siguientes preguntas ¿Qué es SDN?¿Por qué es importante?¿Cómo funciona?¿Qué tipos existen? ¿Cuáles son las ventajas y limitaciones comparadoal paradigma tradicional de redes?.

La segunda parte del proyecto es plantear una red empresarial utilizando el paradigma de SDN, implementarla y emularla en la herramienta de SDN Mininet. Para finalmente, validar  el  funcionamiento  de  la  red empresarial utilizando comandos tales como iperf y pingall
## Desarrollo
Proceso de Mininet:
1. Instalación
La instalación de mininet se inicia teniendo en cuenta es el software de virtualización que se va a utilizar siendo en este caso el Oracle VM VirtualBox que es el software que ofrece Oracle para arquitecturas x86/amd64, siguiendo la instalación se ubica en donde esta ubicado la imagen de Mininet en Linux Ubuntu para luego realizar la instalación de manera automatica por parte de la VM.
2. Uso
Para usar la VM se realiza todo con comandos dentro del CLI, al ser Linux no hay una interfaz grafica como la de windows para un manejo sencillo, pero si se quiesiera se podria instalar, con el comando de cd (change directory) que se utiliza para cambiar el directorio especificando una ruta absoluta, siendo asi que se ubica dentro de la carpeta de mininet y luego la carpeta de examples para poder utilizar la herramienda de Miniedit y en donde adedmas se guardan las versiones del proyecto en .py y en .mn, siendo en .mn para poder editarlo en Miniedit y en .py para poder usarlo dentro del cli de mininet. Ademas se utilizó el comando de ls (Listar Archivos) para verificar que documentos estan dentro de las carpetas.
3. Instalación PuTTY y XMING
Como dentro de mininet no hay un software que soporte una interfaz grafica de edición como lo es Miniedit, se opto por usar dos aplicaciones externas las cuales son PuTTY que es un clientede SSH, Telnet, rlogin y TCP raw de licencia libre para poder comunicar Xming que es una implementación portatil del sistema de ventanas X para Windows y Mininet, la coneccion entre estos dos se hizo por medio del SSH permitiendo el uso de X11 y luego ingresando la direccion IPv4 de la VM para que asi PuTTY pudiese ejecutar sin problemas Miniedit.
4. Implementación 
Para realizar la topoliga del proyecto en principio se usó la herramienta de Miniedit, que los permite usar una interfaz grafica para realizar una topologia con diferentes dispositivos para realizar una red, usando el comando de sudo python miniedit.py donde sudo es el comando que se realiza para ejecutar programas y python para especificar el lenguaje que se esta utilizando dentro de la herramienta. Dentro de la topologia se tuvo en cuenta el proyecto 2 de un curso de la Universidad de Washington para realizar una red empresarial, la cual esta dividida en diferentes subredes y se comunican por un router que es manejado por un POX controller. Esta topologia se guarda en dos formatos, siendo el formato de .mn y .py, los comentados anteriormente para su libre edicion y ejecucion.
5. Resultados
Dentro del proyecto se realizaron 2 comandos principalmente, el comando pingall para verificar que todo este conectado y el comando iperf para verificar la velocidad entre 2 dispositivos resultando de manera exitosa la utilización de ambos comandos, como se puede evidenciar en las siguientes capturas:

![image](https://github.com/Hdiaz0224/Proyecto_Redes/assets/93561095/f4f55323-ac37-4a78-98ec-3cd95671dc75)
![image](https://github.com/Hdiaz0224/Proyecto_Redes/assets/93561095/83ebed65-9fe4-4a73-8640-6ea0e5495d5d)
![image](https://github.com/Hdiaz0224/Proyecto_Redes/assets/93561095/64e20d3a-6fff-487f-a128-bf9e555d4a5e)
![image](https://github.com/Hdiaz0224/Proyecto_Redes/assets/93561095/ff5e9623-f3cb-42c4-b47f-0037fbca7ce8)


## Conclusiones
Pudimos concluir que tanto el manejo y configuracion de Mininet y Miniedit son complicados pero realmente dejan ver la practica de como es una SDN, asi como, lo esencial de una SDN y como se diferencia del paradigma tradicional de redes
## Retos
Los principales retos de este proyecto fueron encontrar fuentes de informacion en Ingles o en Español ya que al momento de buscar muchas de estas aparecian en Portugues, idioma que ninguno del grupo maneja, y tambien toda la configuracion de Mininet.

## Referencias
https://www.youtube.com/watch?v=3VY7KMPmEVo&list=PLbu9W4c-C0iDdltGXLGKv8KvfJQg1c8_7&index=3
