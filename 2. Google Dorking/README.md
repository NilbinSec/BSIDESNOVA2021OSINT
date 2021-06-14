# Google Dorking Flags

The Google Dorking Flags were focused on leveraging google searches to identify specific pieces of information. Overall these were a mix of easy and more difficult.

# Mac Lab
**Point Value:** 25

**Prompt**
_Remember that web cam we saw during class? Where is it?_

_Flag will be the place, using the complete name._

Flag: **REDACTED**

**Attached Items** [Screenshot](https://github.com/NilbinSec/BSIDESNOVA2021OSINT/blob/main/2.%20Google%20Dorking/Screen_Shot_2021-03-21_at_1.33.12_PM.png)

During the google dorking portion of the CTF we discussed using google to find unsecured webcams. The below image is the screenshot with an inlay of the specific webcam in question:

![alt text](https://github.com/NilbinSec/BSIDESNOVA2021OSINT/blob/main/2.%20Google%20Dorking/Webcam.PNG "Logo Title Text 1")

**Methodology** This was a very quick and simple one for me. After entering the google search from the workshop and confirming the first result was still the one we saw earlier in the day I focused on the piece of data staring straight out at me from the screenshot, the IP address of the webcam. Anytime I have an IP address I would like to know more about I at the very least make a quick check on Shodan.

Shodan provided sufficient information to identify the flag and move on.

# Old Phone
**Point Value:** 50

**Prompt**
_What was Brian's previous work (desk) phone number?_
_Flag will be the 10-digit number. Example: 2028675309_

Flag: **REDACTED**

This was one of the more challenging flags because you had to identify a period in time or job to target. It was actually the second to last flag I found. With proper sock puppets backstopped, there are several sites available that allow you to trade your industry contact info for other industry member contact info as a form of business intelligence for generating sales leads. Because this *active* type of collection was not encouraged during the workshop I did not pursue it.

**Methodology** Initially I thought Brian's old number may still be associated with his current job. A little bit of targeted googling of his current job did not identify anything relevant. From that point I began googling some of the positions that were highlighted on his intro slide about himself from the start of the workshop. Biographic data regarding his recent period as an employee at George Washington University provided an excellent target for possible investigation because sites like [Crunchbase](https://www.crunchbase.com/person/brian-markham) were still 'fresh' enough in my mind that they had not updated his new job. This led me to the following google search:

>site:gwu.edu "Brian LASTNAME"

This search returned a large number of results related to Brian's time at the University, and a sequential review of results with liberal use of Ctrl-F to speed up searching garnered me the flag within 5 minutes of finding the proper search string.
