# Support Library y Google Play Services

## Parte 2
Integra Google Play Services en tu aplicación para que haga uso del servicio de Maps.
### Requisitos
Para esta parte, vas a necesitar correr sobre un dispositivo que tenga Google Play Services instalado. Si estarás corriendo la aplicación en un emulador de Genymotion, deberás instalar las aplicaciones de Google. La guía de cómo hacerlo está [acá](http://forum.xda-developers.com/showthread.php?t=2528952).
## Instrucciones
- Implementa la función <code>goToMapsActivity()</code> de <code>MainFragment</code> para que vaya a un <code>ExampleMapActivity</code>
- El layout de <code>ExampleMapActivity</code> consiste de un Mapa que te lleve a una coordenada de tu preferencia

### Extra Parte 2
Ahora que lograste incluir un mapa en tu aplicación, intenta interactuar con él. Agrega en <code>ExampleMapActivity</code> un layout con 2 <code>EditText</code>s y un botón en el menú de la Activity (el botón debería aparecer en el ActionBar de la Activity; puede estar sin ícono). Cada <code>EditText</code> indicara la latitud o longitud de la coordenada que quieres que se vea en el mapa. Al presionar el botón del menú, centra el mapa según las coordenadas que el usuario coloca.
