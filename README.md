# Bot Length

Este bot fué creado con el propósito de probar el ambiente de desarrollo, se utilizó el Microsoft Bot Framework para C# y el  Bot Builder SDK para .NET . 

## Set up del ambiente de desarrollo
Para hacer funcionar el bot debes seguir la siguiente guía:
[Guía para montar y probar el bot](Guide.pdf)

## Capturas

Al compilar el código, el bot se ejecutará en la siguiente dirección

![Dirección URL BOT](capturas/url.jpg)    **El puerto puede variar**

La API funciona bajo el método HTTP POST, por lo que encontraremos el siguiente error
![Resultado API método GET](capturas/resultado.png)

Para probar el bot se puede utilizar el BOT Framework Emulator
![Image of Yaktocat](capturas/botfm.png)

En mi caso la conexión es la siguiente

![Image of Yaktocat](capturas/botfmbar.png)

Probando el bot con el mensaje 'Hola!', el BOT responde correctamente

![Image of Yaktocat](capturas/botfmhola.png)

El mensaje que retorna el BOT es JSON que el BOT Framework emulator se encarga de procesar.

![Image of Yaktocat](capturas/botfmhola2.png)

![Image of Yaktocat](capturas/botfmhola3.png)



