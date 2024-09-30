# App3

A new Flutter project.

## Getting Started

FlutterFlow projects are built to run on the Flutter _stable_ release.

///////////////////////////////////////////////////////////////////////////////////////////////////////

Nuestra aplicación es un dinamómetro diseñado utilizando FlutterFlow y exportado a Visual Studio Code para su desarrollo adicional. Se basa en el framework Flutter para la construcción de interfaces de usuario multiplataforma.
Para la comunicación con dispositivos externos, integramos la biblioteca flutter_bluetooth_serial que permite la comunicación Bluetooth en la aplicación. Esto nos permite establecer una conexión con un sensor de presión montado en un Arduino, a través del cual se transmiten datos en tiempo real.
La aplicación recibe datos de presión en un rango de 0 a 255 del sensor de presión conectado. Estos datos se muestran en una interfaz de usuario simple y receptiva, que permite a los usuarios visualizar la presión medida de manera clara y precisa en sus dispositivos móviles.
Además, hemos incorporado una entrada de texto que actúa como el display para los datos adquiridos a través de Bluetooth. Esto proporciona una forma conveniente para que los usuarios interactúen con la aplicación y vean los resultados de la medición de presión en tiempo real.
En resumen, nuestra aplicación aprovecha las capacidades de Flutter y la comunicación Bluetooth para ofrecer una solución técnica efectiva para la medición de presión en dispositivos móviles.