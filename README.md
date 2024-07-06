# Equipo: The members of tomorrow

## Nombre del proyecto: Notion AI Maker Presentation

### Descripción: El presente proyecto es una ayuda para el usuario, con el fin de ayudarle a realizar presentaciones

completas, con ayuda de IA por medio de una vinculación entre Notion y Chat GPT.

Problematica: Comunmente a los estudiantes les piden realizar presentaciones referentes a un tema,

en las que muchas veces invierten más tiempo en la elaboración de esta, que en el propio estudio del tema.

También la mayoría de los estudiantes que utilizan Notion, tienen la información dentro de este,

pero no saben cómo representarla de una manera más visual para una mejor comprensión.

### Solución de la problematica:

1. Obtener los datos de Notion por medio del workspace del usuario.
1. Procesamiento de los datos obtenidos por medio de Open AI para complementar la información y segmentarla

de forma que pueda ser integrada en slides, con una librería de Python (pptx).

1. Creación de slides por medio de Open AI.
1. Se descarga la presentación en PDF.

### Herramientas usadas:

Python para procesar la información recibida por el usuario y segmentarla en slides.

Servidor con DJANGO para almacenar la petición.

API de Open AI para complementar la información que fue recibida y para crear los slides.


Forma de obtener los datos: por medio del token de Notion, por lo que no se solicita correos, ni contraseñas del mismo.

Escalabilidad: Tener nuestra propia inteligencia artificial
