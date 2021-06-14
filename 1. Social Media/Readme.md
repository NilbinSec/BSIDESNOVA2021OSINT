# Social Media Flags

The Social Media flags were focused on finding thigs out about Brian's (the workshop instructor) life. Both flags were comparatively difficult compared to most of the other sections.

# If it pleases the court
**Point Value:** 50

**Prompt**
_Where did Brian's wife attend law school?_

Flag: **REDACTED**

This was the first flag I clicked on and it looked fairly simple at first glance but actually took me a significant amount of time. In the future, unless a flag is clearly <60 seconds to complete I plan to review all the questions before diving headfirst into a flag.

**Methodology** Brian had leaked a fair amount of personal information during the workshop; this was likely on purpose to give the participants a little bit of a headstart in conducting their research during the CTF. Normally my first stop would be the [Melissa Personator](https://www.melissa.com/) because I have had serious success correlating names, locations, and other biographical data in the past. Instead, I attempted to use [FamilyTreeNow](https://familytreenow.com/) because it was the source specifically taught during the workshop. Unfortunately I had serious troubles identifying the name of Brian's wife based on the general location I knew he lived (DMV Area). Following some frustrating setbacks looking for women of a similar age linked to a Brian Markham on FamilyTreeNow as possible answers I switched over to Melissa but was similarly frustrated.
At this point I switched over to some basic google searches such as 
>Brian LASTNAME Virginia

>Brian LASTNAME Washington D.C.

>Brian LASTNAME Maryland

One of these rapidly turned up a review Brian and his wife wrote which gave me a probable name for his wife. A quick search on LinkedIn for her name quickly returned the flag.

# Good Luck
**Point Value** 50

**Prompt**
_Brian has an Instagram account. Can you find it and find the flag?_

Flag: **REDACTED** (I am also redacting Brian's username because it is google dorked a fair amount during the CTF, it will be labled as USERNAME)

**Methodology**This was by far the most difficult flag to find in the CTF. We knew from the workshop that USERNAME was his most common handle online, but he made it a point to show that other people (including on Instagram) used the name. Because there was no clear answer I began datamining every source I could think of in an attempt to locate a link to other social media pages. I went through every [PeekYou](http://peekyou.com/) account for USERNAME hoping to find a link but was unfortunately largely unsuccessful. For some of the more unmanageable sites I was able to quickly mine some of the data using some simple google searches with targeted operators such as:
>site:reddit.com USERNAME instagram

Unfortunately none of these were very successful. I did find other associates of Brian but none of their accounts were followed or following a probable Brian instagram account. 

After PeekYou failed to return fruitful results I tried out my preferred replacement for PeekYou, [Maigret](https://github.com/soxoj/maigret). Maigret is an amazing tool for datamining social media and old school forum accounts online. The Github has a pre-populated Google shell to run it. While Maigret failed to find me what I was hoping for, it *did* reveal quite a few more accounts that were clearly associated with Brian under the USERNAME handle and not other personas dating back over a decade.

Thoroughly frustrated at this point--with more time invested than any of the other flags--I turned back towards Brian's wife who I discovered in the previous flag. Using some of the previously identified information on her I identified a feed of photos from her instagram. With access to her instagram, I was able to locate Brian's account and the immediately obvious flag.
