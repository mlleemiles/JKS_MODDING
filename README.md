# Basic Modding Guide For Samurai Maiden
## Tools and scripts you need
[UABEAvalonia](https://github.com/nesrak1/UABEA)

[Update Catalog Script To Allow You To Edit Game Files](https://cdn.discordapp.com/attachments/862035809795964969/927372959746768996/updatecatalog.py)
## Modding
- **Update Catalog File**

First of all you need to run the script in the StreamingAssets/aa folder (next to catalog.json) and it should make a catalog_new.json file with CRCs disabled. Just replace the old one with the new one. (To run .py file, get [Python](https://www.python.org/downloads/) here)


<p align="center"><img src="https://cdn.discordapp.com/attachments/536983241979068422/1051676125434220554/image.png" width="75%" height="75%"/></p>

- **Modifying .bundle Files**

Next up open a bundle file with UABEAvalonia. The program will ask you where to decompress the file, choose whichever you like.

<p align="center"><img src="https://cdn.discordapp.com/attachments/536983241979068422/1051678723037999104/image.png" width="75%" height="75%"/></p>

Click on info to check the file's content:

For text files, you can export dump and reimport dump for your edits. For textures, use **Plugins** function to import your new texture!

<p align="center"><img src="https://cdn.discordapp.com/attachments/536983241979068422/1051680372582264862/image.png" width="75%" height="75%"/></p>

- **Saving Your Changes**

In the `asset info` window, select Save in the File menu. To complete changes, exit the `asset info` window and File->Save in bundle window.

And finally, replace the original .bundle file with your newly saved .bundle file and its done.

Example of an edited text file in game:

<p align="center"><img src="https://cdn.discordapp.com/attachments/536983241979068422/1051475609970278400/image.png" width="75%" height="75%"/></p>

## Credits
[UABEAvalonia](https://github.com/nesrak1/UABEA)

