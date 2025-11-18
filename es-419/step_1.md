Haga clic derecho en la imagen en su página web y seleccione `Copy image address` o `Copy image address`:

![El área de salida en Trinket con una imagen grande de un escarabajo. El menú del clic derecho tiene una opción para 'Copy image address'.](images/copy-image-address.png)

En una nueva ventana del navegador, vaya a [coolors.co](https://coolors.co){:target="_blank"}. Seleccione el menu 'Tools' despues 'Image picker'.

![El sitio web coolors.co con tarifas seleccionados en la esquina superior derecha. La herramienta 'Image picker' está resaltada en el menú desplegable.](images/image-picker-menu.png)

Haga clic en el botón 'Browse image'.

![El botón para buscar la imagen.](images/browse-image-button.png)

Haga clic en 'URL' y después copie la dirección de la imagen dentro del cuadro de 'Image URL'. Hega clic en 'OK'.

![El cuadro de selección de imagen con la URL seleccionada y la dirección de imagen para la imagen del escarabajo copiada en.](images/select-image-box.png)

Se han creado paletas de muestra de tu imagen. Puedes usar el deslizador de 'Picked palettes' para seleccionar cual paleta de colores desea usar.

![El deslizador de la paleta escogida es un tercio del camino a través. La imagen se muestra con circulos llamativos resaltando donde se han seleccionado los colores.](images/generated-image-palettes.png)

Cuando esté contento con su paleta, haga clic en el botón con la flecha hacia abajo al lado del botón 'Export palette' y seleccione 'Open in the generator'.

![El menú para exportar una paleta con el elemento superior 'open in the generator' seleccionado.](images/generate-palette-menu.png)

Se muestra la paleta final. Las letras y números codificados son los códigos hexadecimales para los colores que has elegido. Actualiza los valores de las variables en tu archivo `default.css` para usar estos nuevos colores.

![Cuadros de color con los códigos hexadecimales escritos en ellos.](images/final-image-palette.png)

## --- code ---

language: html
filename: default.css
line_numbers: true
line_number_start: 4
line_highlights: 5-14
----------------------------------------------------------

:root {
\--primary: #08586B;
\--onprimary:#4f4e4e;
\--secondary: #E0DB54;
\--onsecondary:#ffffff;
\--tertiary:#AF5C08;
\--ontertiary: #ffffff;
\--page:#ffffff;
\--onpage:#000000;
\--detail: #AB7C1C;
\--detail2: #38640D;
}

\--- /code ---
