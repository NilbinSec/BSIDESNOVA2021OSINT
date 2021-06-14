# Maps and GPS Flags

The Maps and GPS flags were pretty simple and focused on correctly identifying locations and geocoordinates.

# Spot The Fed
**Point Value:** 25

**Prompt**
_My friend told me she'd be working at a secret government facility. All I have is the coordinates in this text file. Can you tell me at which government agency my friend is working?_

_Flag should be submitted as an acronym. Examples:DOJ FBI_

Flag: **REDACTED**

Included with the prompt was a link to a [txt file](https://github.com/NilbinSec/BSIDESNOVA2021OSINT/blob/main/3.%20Maps%20%26%20GPS/coordinates.txt) with the coordinates: 39.06481047910245, -77.88968192731699.

**Methodology** Just looking at the coordinates provided it was quickly clear that these were geocoordinates in degress-decimal degrees. People who are unfamilar with, or do not deal with geocoordinates in their day to day life may be confused why there are no cardinal directions for the lines of lattitude and longitude in the provided coordinates. All geocoordinates starts of 0 deg, 0 degs (or the intersection of the Prime Meridian with the Equator). If the first degree is positive, it is in the northern hemisphere, and if it is negative it is in the southern hemisphere. Similarly, when the second degree is positive it is eastern and when negative, western. 

While we discussed https://gps-coordinates.org/ during the workshop, past experience let me know that google maps does a great job with this form of geocoordinates so I used that instead to get a location on the map. Google Maps already is really good at identifing what is around a given location and the flag was readily visible.



# Heat on Feet
**Point Value:** 50

**Prompt**
_Where was this picture taken?_

_Flag will be the city and state._

Flag: **REDACTED**

Included with the prompt was the image included in the folder.

**Methodology** From the start we are being tossed a hint with the reddit banner along the bottom with user information. The provided image is pretty low res and I initially took a gamble and checked the metadata for the possibility of a quick win. As expected, there was no useful metadata. 

Following the lack of metadata, I switched over to reddit and searched for the user's profile and searched posts until I found the original image. The original image is much higher definition than the original making it easy to pickout the name of the train station. Googling the train station name along with "train station" identified two possibilities. I tried both and was awarded with the flag on my second attempt.
