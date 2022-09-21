# FGU-Theme-GM-Icon-Replacer
 This extension for Fantasy Grounds Unity (FGU) enables the user to exchange their GM Icon within Fantasy Grounds Unity with a custom graphic.

 In oder to do so, you must open up the extension file and replace the GM_Icon.png withing the PNGs folder with your custom asset.
 Keep in mind, that the asset you choose is best used with a resolution not larger than 42x42px. I recommend using 32x32px if you're using my [Dark Theme](https://github.com/SirMotte/FGU-Theme-Hearth). 
 If you would like to use the folden frame that the standard icon uses, I've included templates for you to make use of within your favourite image editing  software.

## Installation & Cusomization

- [Download](https://github.com/SirMotte/FGU-Theme-GM-Icon-Replacer/releases/tag/v1.0) the Extension from Github.

 If you're not using advanced file managers like [Total Commander](https://www.ghisler.com/) or [Directory Opus](https://www.gpsoft.com.au/index.html), that    handle opening up zipped files on the fly, you will need to follow these steps, follow step 4,5,6 and 10,11:

1. Rename the *GM_Icon_Replacer.**ext*** to *GM_Icon_Replacer.**zip***.
2. Unpack the zip file with an unpacer of your choice like winrar or 7zip.
3. Open up the unpacked folder. There you will find xml files and two folders.
4. If you want to, navigate to the templates folder and use the provided graphics and .svgs to create your own GM Icon on top.
5. Otherwise use whatever icon you like and rename it to *GM_Icon.png* and place it into the PNGs Folder.
6. When asked to overwrite, click yes.
7. Repack the GM_Icon_Replacer Folder again to GM_Icon_Replacer.zip.
8. Rename the *GM_Icon_Replacer.**zip*** file to *GM_Icon_Replacer**.ext** again.
10.Move the file named "GM_Icon_Replacer.ext" into the "Extensions" Folder found inside your Fantasy Grounds "Data" folder.
11. Activate the Extension listed as "Theme: GM Icon Replacer" in your campaign details page in the "Extensions" section and launch the campaign.
12. Done, I hope you like it!

## Advanced customization
 In case you want to make the extension file unique, to eg have several options to choose from when launching your campaign, follow these steps:
 1. Rename the GM_Icon_Replacer.ext file to something uniqe, for example GM_Icon_Replacer_YourName.ext.
 2. Within the .ext file, open up the extension.xml with a text editor of your choice.
 3. Modify this line `<name>Theme: GM Icon Replacer</name>` to, for example `<name>Theme: GM Icon Replacer - YourName</name>`
    - This will make sure, that if more than one Replacer Extension is present, Fantasy Grounds can pick up on this and show them as diferent extensions. Otherwise online the last one loaded will shop up.
 
 If you want to incluse additional icon replacements, you can include them in the override.xml.
 
Enjoy!
Sir Motte
