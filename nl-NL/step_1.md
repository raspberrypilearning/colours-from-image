Klik met de rechtermuisknop op de afbeelding op jouw webpagina en selecteer `Copy image address` of `Copy Image Link`:

![Het uitvoergebied in Trinket met een grote keverafbeelding. In het rechtermuisknopmenu is de optie 'Copy image address' geselecteerd.](images/copy-image-address.png)

Ga in een nieuw browservenster naar [coolors.co](https://coolors.co){:target="_blank"}. Selecteer het menu 'Tools' en dan 'Image picker'.

![De coolors.co website met tools geselecteerd in de rechterbovenhoek. De tool 'Image picker' is gemarkeerd in het drop-down menu.](images/image-picker-menu.png)

Klik op de knop 'Browse image'.

![De knop Browse image.](images/browse-image-button.png)

Klik op 'URL' en plak het gekopieerde afbeeldingsadres in het vak 'Image URL'. Klik op 'OK'.

![Het Select image vak met geselecteerde URL en het afbeeldingsadres voor de keverafbeelding erin gekopieerd.](images/select-image-box.png)

Er worden voorbeeldpaletten gemaakt op basis van jouw afbeelding. Je kunt de schuifregelaar 'Picked palettes' gebruiken om te selecteren welk kleurenschema je wilt gebruiken.

![De picked paletschuifregelaar staat op een derde van de breedte. De afbeelding wordt weergegeven met hotspots die laten zien waarvan de kleuren zijn geselecteerd.](images/generated-image-palettes.png)

Als je tevreden bent met het palet, klik dan op de dropdown-pijl van de 'Export palette' knop en selecteer 'Open in the generator'.

![Het Export palette menu met het bovenste item 'open in the generator' geselecteerd.](images/generate-palette-menu.png)

Het uiteindelijke palet wordt getoond. De gecodeerde letters en cijfers zijn de hexadecimale codes van de door jou gekozen kleuren. Update de variabelewaarden in je `default.css` bestand om deze nieuwe kleuren te gebruiken.

![Gekleurde vierkanten met de hexadecimale codes erop geschreven.](images/final-image-palette.png)


--- code ---
---
language: html
filename: default.css
line_numbers: true
line_number_start: 4
line_highlights: 5-14
---

:root {
  --primary: #08586B;
  --onprimary:#4f4e4e;
  --secondary: #E0DB54;
  --onsecondary:#ffffff;
  --tertiary:#AF5C08;
  --ontertiary: #ffffff;
  --page:#ffffff;
  --onpage:#000000;
  --detail: #AB7C1C;
  --detail2: #38640D;
}

--- /code ---
