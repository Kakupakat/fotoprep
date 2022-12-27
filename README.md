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

    fotoprep -s          -> Run the setup program to set and/or
                            change options.
                            You should do this before the first use!
    fotoprep filename(s) -> Prepare photos for use on the Internet,
                            tablets, phones, etc."
    fotoprep -v          -> Show the version number of fotoprep.
    fotoprep -h          -> Show this help.

    The images you pass to fotoprep can be of different types,
    even GIMP and RAW files (using RawTherapee and its .pp3
    sidecar files). The files can come from several different
    directories in your file system at the same time.
    Don't worry, your images will not be changed.
    All operations are performed on copies of the files.
    The results will be placed in a new directory called:
    fotoprep-<PID> inside the directory where fotoprep was started.

## Notes

- ExifTool, GIMP, RawTherapee and ImageMagick must be installed.
- This will only work in Bash >= 4.0.
