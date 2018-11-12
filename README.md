# Fontawesome Icons for Pencil

Generate a Stencil (collection) of all Fontawesome icons for [Pencil](http://pencil.evolus.vn/)

Based on the 24px version of the icons, however everything is in vector format, so can be scaled to any size.

## Installation

- Download the [latest release] zip file.
- Install the collection in Pencil by going to *Tools > Install new collection* and selecting the zip.

## Generating the Collection

- Clone this repo
- Download Fontawesome
- Run the `generate-xml.py` script (tested with Python 3.4).

This will generate the stencil definition XML and png thumbnails and place them in the `gen/` folder.

Everything **inside** the `gen/` folder can then be zip'd and installed in Pencil.


## License

This project is a clone of [nathanielw/Material-Icons-for-Pencil](https://github.com/nathanielw/Material-Icons-for-Pencil).
Fontawesome is *not* included

All source code/scripts used to generate the Pencil stencil are released under the [MIT License](http://opensource.org/licenses/mit-license.php).
