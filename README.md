# Basic Website Architecture

## Overview

Basic website file architecture demo showing how to use folders and index.html files to create pages and sub pages on a site. The pages feature a basic navigation bar to link the pages and 3 pages contain a style sheet to show how to handle linking files between folders of different depths.

This example relies on relative linking which uses the domain/location of a given file to orient links. Here is a summary of how relative linking functions:

>./(file name) --- stay here and, if provided, access (file name)

>../(file name) --- go up one folder and, if provided, access (file name)

>../../(file name) --- go up two folders and, if provided, access (file name)

>./assets/(file name) --- go to assets folder in this folder and, if provided, access (file name)

>../assets/(file name) --- go up one folder and then go into the assets folder there and, if provided, access (file name)

>../../assets/(file name) --- go up two folders and then go into the assets folder there and, if provided, access (file name)

NOTE: If no file name is given, the browser will look for an index.html file within the folder.

So, if we were on a site called https://www.linkexample.com/plants/flowers/ , the above items would take us to:

https://www.linkexample.com/plants/flowers/
https://www.linkexample.com/plants/
https://www.linkexample.com/
https://www.linkexample.com/plants/flowers/assets/
https://www.linkexample.com/plants/assets/
https://www.linkexample.com/assets/

