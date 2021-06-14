# EXIF

Both these flags focused on interpreting the EXIF data of images to find the flag.

# Agnes
**Point Value:** 25

**Prompt**
_Who's the artist of this photo? Agnes will never tell._

_Flag will be the complete string._

Flag: **REDACTED**

Included with the prompt was a link to the image below: ![alt-text](https://github.com/NilbinSec/BSIDESNOVA2021OSINT/blob/main/4.%20EXIF/agnes2.jpeg) 

**Methodology** As a low point value flag I went with my gut and ran the jpg through [ExifTool](https://github.com/exiftool/exiftool) which worked great. One of the available metadata tags available for jpg is the Artist tag which ExifTool found successfully. The entire string in the tag was the flag as expected. 

# Vacation Photos
**Point Value:** 50

**Prompt**
_I had the best time on my vacation but I can't remember where I took this picture. Can you help me?_

_Flag should be entered with no spaces. State not required._

Flag: **REDACTED**

Included with the prompt was a link to an [HEIC File](https://github.com/NilbinSec/BSIDESNOVA2021OSINT/blob/main/4.%20EXIF/IMG_2199.HEIC) 

**Methodology** HEIC is a raw image format that most image viewers cannot correctly interpret, but [ExifTool](https://github.com/exiftool/exiftool) is also compatible with them. In this case, ExifTool revealed quite a few tags, but the ones of note were the GPS coordinates. In this case I did need to plot the coordinates with [gps-coordinates](https://gps-coordinates.org/) and not google maps but the flag was the first attempt I had when I saw the location.
