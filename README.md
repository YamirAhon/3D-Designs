# Introducción
En el presente repositorio se encuentra una recopilación de mis diferentes diseños 3D de los projectos en los que he participado a lo largo de mi trayectoria académica y profesional. Estos diseños muestran mis habilidades en modelado 3D, diseño mecánico y desarrollo de productos utilizando principalmente el software Autodesk Inventor.

# Planta de empacadora de bloques
Como parte de un proyecto colaborativo con la Universidad Nacional Autónoma de México (UNAM) se realizó la creación de una planta empacadora de bloques de colores en miniatura. El presente modelo fue diseñado teniendo en mente su fabricación mediante el uso de MDF 3mm y equipos de corte láser.

![Ensamblaje total de la empacadora](Empacadora/Empacadora.png)

Para la realización de este proyecto se escogió utilizar una metología de diseño modular, dividiendo la planta en diferentes módulos montables: 
- Rack de actuadores
- Faja transportadora 1
- Faja transportadora 2
- Torre de sensado

### Rack de actuadores
El primer módulo diseñado fue un rack vertical por el cual caerían y se acumularían productos destinados a ser empujados hacia una faja transportadora mediante el uso de actuadores lineales. Para lograr esto, se requirió diseñar una estructura montable que permita contener y guiar a los productos en su caída y ubicarlos en una posición específica consistentemente tal que los actuadores puedan empujarlos sin impedir la caída de los siguientes productos. Además, se tuvo que diseñar una caja de actuadores, para la cual se tuvo que adaptar diseños ya existentes de actuadores lineales para que puedan satisfacer los requerimientos de tamaño y distancia de actuación del rack y puedan ser fijados a la estructura. Para el acceso a los actuadores para su mantenimiento se integraron aletas con huecos para pernos como método de fijación de una tapa trasera.

![Ensamblaje total del rack de actuadores](Empacadora/Rack_de_actuadores/Rack_de_actuadores.png)

### Faja transportadora 1
Luego, se diseñó la estructura de una faja transportadora que permita desplazar los productos haciendolos pasar por una estación de sensado de color, sensores de proximidad infrarrojos y servomotores con de guías para el reposicionamiento de productos. Para el funcionamiento de la faja se fabricaron mediante impresión 3D rodillos dentro de los cuales se fijaron rodamientos en sus extremos, y dentro de estos se fijaron otras piezas que permitirían fijar los rodillos a la estructura y establecer un enlace con el eje giratorio del motor encargado del movimiento de la faja. Se decidió aprovechar la altura de esta faja para utilizar el espacio interno para almacenamiento de los cables y controladores de la planta, por lo que se agregaron huecos en diferentes puntos de la estructura para pasar cables. Además,para asegurar el centrado de las piezas en la faja para su entrada a la torre de sensado y el guiado de los productos en caso sean rechazados por la planta se diseñaron guías de dirección colocadas en ambos lados de la estructura y una guía de rechazo con huecos para su enlace con el eje rotatorio del servomotor de rechazo.

![Ensamblaje total del rack de actuadores](Empacadora/Faja_transportadora_1/Faja_transportadora_1.png)


### Faja transportadora 2




### Torre de sensado
Para el sensado de colores de lo productos se decidió diseñar una torre de sensado que permita cubrir el producto y mantener en oscuridad el sensor de colores para minimizar la interferencia en las mediciones ocasionada por la variación de la intensidad de luz exterior. Se fijó el sensor de colores a una distancia de 5mm con respecto al producto a medir para reducir el error del sensado debido a la distancia. Para el acceso a al sensor para su mantenimiento se integraron aletas con huecos para pernos como método de fijación de una tapa superior.

![Ensamblaje total del rack de actuadores](Empacadora/Torre_de_sensado/Torre_de_sensado.png)
