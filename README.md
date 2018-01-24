# fotoprep


## Purpose

Quickly prepare photos individually or in batches for use on social media sites, your own website, tablets, phones, etc.
The images can be resized and a watermark or an annotation bar can be added. Sharpening can be applied and additionally the metadata will be cleaned and a copyright notice will be added in the EXIF, IPTC and XMP tags.


## Features

- Convert images, including xcf and raw files, to jpg, png or tif.
- Resize images with presets.
- Resize images with one time custom sizes.
- Add a watermark.
- Add an annotation bar with a logo and a copyright notice.
- Add an extra comment to the annotation bar, taken from the comment metadata tag.
- Choose a font for the copyright notice and comment on the annotation bar.
- Sharpen the images.
- Customize the features by running fotoprep -s


## Usage

    fotoprep filename(s) -> Prepare photos for use on the Internet,
                            tablets, phones, etc.
    fotoprep -s          -> Run the setup program to set and/or
                            change options.
    fotoprep -v          -> Print the version number of fotoprep.
    fotoprep             -> Print this help.


## Notes

- ExifTool, GIMP, RawTherapee and ImageMagick must be installed.
- This will only work in Bash >= 4.0.
