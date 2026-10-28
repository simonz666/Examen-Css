
#Mock ups. Prototipos o bocetos iniciales de la pagina de eco market.
![alt text](<img/mock up/contacto mock up.jpg>)![alt text](<img/mock up/descripcion mock up.jpg>)![alt text](<img/mock up/menu mock up.jpg>)![alt text](<img/mock up/productos mock up.jpg>)

#evidencia celular, si alguna parte se ve entre cortada facilmente se puede scrolear las para poder verlas.
<img width="1303" height="918" alt="image" src="https://github.com/user-attachments/assets/3a0b1ee5-8d6c-4123-9206-d97518d0ae32" />,<img width="429" height="859" alt="image" src="https://github.com/user-attachments/assets/721841ba-3d83-4c07-ade5-2555433d2ca8" />,<img width="386" height="856" alt="image" src="https://github.com/user-attachments/assets/9aef2baf-dc25-43a9-923d-adb31bce5611" />,<img width="388" height="852" alt="image" src="https://github.com/user-attachments/assets/812f1410-e735-41ac-b430-1189a91b43a3" />
#evidencia computadores.
<img width="1871" height="1030" alt="image" src="https://github.com/user-attachments/assets/818d1576-d08c-4184-acd7-6700cd8e7ad7" />,<img width="1871" height="1027" alt="image" src="https://github.com/user-attachments/assets/6e7f3995-98e8-490b-9338-80d6ad9127fe" />,<img width="1874" height="1033" alt="image" src="https://github.com/user-attachments/assets/be405f3c-6f09-44dd-8dfb-1f22c037a901" />,<img width="1873" height="1033" alt="image" src="https://github.com/user-attachments/assets/9735fb14-64fe-44a1-aa92-b35595639b91" />






#Arquitectura y Desarrollo del Sitio

pagina del proyecto: https://simonz666.github.io/Ecomarket_SimonRangel/
El desarrollo de *EcoMarket se estructuró bajo un enfoque modular, escalable y puramente nativo, diseñado para separar claramente la estructura, el estilo y la interactividad sin depender de librerías o frameworks externos:

- *Estructura Multi-página: El sitio web se divide en un archivo principal (`index.html` en la raíz) y vistas secundarias ubicadas en la carpeta de soporte (como `productos.html`, `contacto.html` y `sobre-nosotros.html`). Se implementó HTML semántico para asegurar una correcta accesibilidad y estructuración del documento.
- *Maquetación con CSS Grid: Las secciones clave (catálogos, banners y la sección de historia) utilizan **CSS Grid** para la distribución de grillas complejas y **Flexbox** para la alineación flexible de elementos como la barra de navegación y las tarjetas, garantizando una adaptabilidad fluida en diversas resoluciones.
- *Organización Modular de Hojas de Estilo: Los estilos están distribuidos de manera modular para optimizar el mantenimiento y evitar conflictos visuales:
- `main.css`: Variables globales, reseteo de estilos y tipografías base del sitio.
-  `layout.css`: Contenedores generales, grillas estructurales y puntos de quiebre (*media queries*) para adaptabilidad responsiva.
-   `components.css`: Estilos específicos para elementos reutilizables como tarjetas de productos, botones, la barra de navegación y el pie de página (*footer*).
-     animations.css`: Transiciones y efectos visuales fluidos que mejoran la experiencia visual del usuario.
- *Validación de Formularios: La retroalimentación visual en los formularios de contacto se gestionó de forma avanzada mediante selectores de estado nativos de CSS (tales como `:invalid` y `:not(:placeholder-shown)`), permitiendo mostrar alertas y estados de error/éxito dinámicos sin necesidad de lógica adicional.
- *Despliegue y Control de Entorno**: Configurado para su integración continua en **GitHub Pages**, asegurando el uso de rutas relativas correctas y respetando la sensibilidad a mayúsculas y minúsculas propia de los entornos de producción en Linux.

#Tecnologias usadas
Html:5 y Css para la estructuracion de la pagina.
Git y Github para el control de versiones y despliege usando la función de github pages.
