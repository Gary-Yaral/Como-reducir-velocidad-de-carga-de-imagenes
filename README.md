# Como reducir la velocidad de carga de imagenes
  * Primero: Reduce el tamaño de tus imagenes por lo minimo de 700px hasta 900px de ancho, pero conservando la relación de aspecto, o sea, debes mantener el aspecto de ancho y alto.
  * Segundo: Comprime el peso de las imagenes, puedes usar tinyPNG https://tinypng.com/
  * Tercero: Activa la propiedad loading de la etiqueta img donde estas cargando tu imagen y pasale el valor lazy, tal y como te muestro en la parte de abajo
  
  ``` html 
    <img alt="" src="your-image.jpg" loading="lazy">
  
  ```
