Fais un clic droit sur l'image de ta page web et sélectionne « Copier l'adresse de l'image » ou « Copier le lien de l'image » :

![La zone de sortie dans Trinket avec une grande image de scarabée. Le menu du clic droit comporte une option "Copier l'adresse de l'image"'.](images/copy-image-address.png)

Dans une nouvelle fenêtre de ton navigateur, va sur [coolors.co](https://coolors.co){:target="_blank"}. Sélectionne le menu « Tools » puis « Image picker ».

![Le site web coolors.co avec les outils sélectionnés dans le coin supérieur droit. L'outil "Image picker" est mis en évidence dans le menu déroulant.](images/image-picker-menu.png)

Clique sur le bouton « Browse image ».

![Le bouton Browse image.](images/browse-image-button.png)

Clique sur « URL » puis colle l'adresse de l'image copiée dans la case « Image URL ». Clique sur « OK ».

![La boîte de sélection de l'image avec l'URL sélectionnée et l'adresse de l'image du scarabée copiée.](images/select-image-box.png)

Des échantillons de palettes sont créés à partir de ton image. Tu peux utiliser le curseur « Picked palettes » pour sélectionner le schéma de couleurs que tu veux utiliser.

![Le curseur de la palette choisie se trouve à un tiers de sa hauteur. L'image est présentée avec des zones indiquant où les couleurs ont été sélectionnées.](images/generated-image-palettes.png)

Lorsque tu es satisfait de la palette, clique sur la flèche déroulante du bouton « Export palette » et sélectionne « Open in the generator ».

![Le menu de la palette d'exportation avec l'élément supérieur "Open in the generator" sélectionné.](images/generate-palette-menu.png)

La palette finale est affichée. Les lettres et les chiffres codés sont les codes hexadécimaux des couleurs que tu as choisies. Mets à jour les valeurs des variables dans ton fichier `default.css` pour utiliser ces nouvelles couleurs.

![Des carrés de couleur sur lesquels sont inscrits les codes hexagonaux.](images/final-image-palette.png)

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
