# Presentación
¡Saludos!, mi nombre es Maximiliano Garcia Giron (sin acentos), soy Ingeniero en Mecatrónica egresado de la Universidad Nacional de Cuyo y este es mi portafolio profesional. Como podrá observarse al revisar mis proyectos estudiantiles y laborales, la característica que más me representa es la curiosidad, unida a unos grandes deseos de continuar aprendiendo, experimentando y desarrollando la creatividad de forma constante, me encuentro interesado en investigación y desarrollo, quedando tambien abierto a trabajos de mantenimiento y de campo.

Tambien puedes visitarme en [Linkedin](https://www.linkedin.com/in/maximiliano-garcia-giron-01a9251ba/) y ver mi [Curriculum Vitae](https://github.com/MaximilianoGarcia716/Portafolio/blob/main/Curriculum%20Vitae/CURRICULUM%20VITAE%20Garcia%20Maximiliano.pdf).

Además de ser hispanohablante nativo tengo certificado el nivel [C2 de inglés](https://efset.org/cert/wq7khc).

A continuación se presenta un resumen de los proyectos que he desarrollado sea en solitario o en conjunto, cada uno con tiene a su vez su propio repositorio donde pueden verse en más detalle, incluyendo código.

# Robot holonómico diferencial de exploración para busqueda y rescate

Este proyecto consiste en un robot de tipo holonómico diferencial de tres motores.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/03.jpg)

El robot posee una inteligencia artificial de tipo Tensorflow entrenada para reconocer 5 señales de peligro.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/01.jpg)

Además posee un sistema de navegación odométrico/inercial utilizando filtro de Kalman para integrar ambos sensores. Finalmente la interfaz muestra el estado del robot, la cámara con la identificación de Tensorflow y un mapa donde se muestra el recorrido del robot y además pueden colocarse señales en dicho mapa para ubicar ciertos puntos de interés. Dicha interfaz está diseñada para tomar la consigna de un mando tipo Xbox para controlar el movimiento del robot y las funciones de la interfaz.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/02.jpg)

El repositorio completo puede verse [aquí](https://github.com/MaximilianoGarcia716/Proyecto-Final-de-Estudios).

# Automata de grúa portuaria

Ese proyecto fué desarrollado en conjunto con otro [alumno de la facultad](https://github.com/jonathan-obredor), consiste en un autómata de control para una grúa de tipo pórtico implementado en una simulación de PLC utilizando grafos y texto estructurado según al estándar de programación IEC61131, posee un control de tres niveles, siendo estos seguridad, control supervisor y control de movimiento para el actuador de izaje y movimiento del carro, además se agregó un control de balanceo para la carga y se realiza una simulación en el propio PLC del sistema físico. Los resultados de dicha simulación son enviados por OPC UA a la terminal de Matlab donde se muestra en la interfaz.

![Image](https://raw.githubusercontent.com/MaximilianoGarcia716/Portafolio/main/Imagenes/04.jpg)

El repositorio completo puede verse [aquí](https://github.com/MaximilianoGarcia716/Automata-de-grua-portuaria).
