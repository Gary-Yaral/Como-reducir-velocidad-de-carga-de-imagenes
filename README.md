# Como reducir la velocidad de carga de imagenes
  - Primero: Reduce el tamaño de tus imagenes, pero conservando la relación de aspecto, o sea que debe mantenerse el aspecto de ancho y alto.
  - Segundo: Comprime el peso de las imagenes, puedes usar tyPNG https://tinypng.com/
  - Tercero: Activa la propiedad loading de la etiqueta img donde estas cargando tu imagen y pasale el valor lazy, tal y como te muestro en la parte de abajo
  
  ``` html 
    <img alt="" src="your-image.jpg" loading="lazy">
  
  ```
