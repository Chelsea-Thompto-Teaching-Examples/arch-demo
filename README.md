# Basic Website Architecture

## Overview

Basic website file architecture demo showing how to use folders and index.html files to create pages and sub pages on a site. The pages feature a basic navigation bar to link the pages and 3 pages contain a style sheet to show how to handle linking files between folders of different depths.

## File/Folder Structure

For every webpage in this example, there is a folder containing and index.html file. For pages that are supposed to be within or under another page, like the project pages being under/within the gallery page, the folders are placed within the gallery page folder. 

## Relative Linking

This example relies on relative linking which uses the domain/location of a given file to orient links. Here is a summary of how relative linking functions:

./(file name) --- stay here and, if provided, access (file name)

---

../(file name) --- go up one folder and, if provided, access (file name)

---

../../(file name) --- go up two folders and, if provided, access (file name)

---

./assets/(file name) --- go to assets folder in this folder and, if provided, access (file name)

---

../assets/(file name) --- go up one folder and then go into the assets folder there and, if provided, access (file name)

---

../../assets/(file name) --- go up two folders and then go into the assets folder there and, if provided, access (file name)

NOTE: If no file name is given, the browser will look for an index.html file within the folder.

So, if we were on a site called https://chelsea-thompto-teaching-examples.github.io/arch-demo/gallery/project-1/, the above items would take us to:

./

https://chelsea-thompto-teaching-examples.github.io/arch-demo/gallery/project-1/

---

../

https://chelsea-thompto-teaching-examples.github.io/arch-demo/gallery/

---

../../

https://chelsea-thompto-teaching-examples.github.io/arch-demo/

---

./assets/

https://chelsea-thompto-teaching-examples.github.io/arch-demo/gallery/project-1/assets/

---

../assets/

https://chelsea-thompto-teaching-examples.github.io/arch-demo/gallery/assets/

---

../../assets/

https://chelsea-thompto-teaching-examples.github.io/arch-demo/assets/