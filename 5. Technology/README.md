# Technology

The final two flags of the CTF were more Google dorking and determining what to do with the information.

# Emergency 911
**Point Value:** 25

**Prompt**
_What E911 system does the University of Maryland use?_

_Flag will be the company name._

Flag: **REDACTED**

**Methodology** I initially had a fair amount of difficulty figuring this one out. I don't think I was googling quite correctly, I was looking for IT pages instead of going for the obvious. Eventually I switched to just the following search
>site:umd.edu E911

That search was exactly what I needed to find the flag after reading the directions for setting the system up on a student's phone.

# My Pillow
**Point Value:** 50

**Prompt**
_Which company hosts Mike Lindell's social media platform?_

_Flag will be the entire name of the company_

Flag: **REDACTED**

**Methodology** Mike Lindell is a conservative CEO who established a new social media company named [Frank](https://frankspeech.com/) after Parler went offline. I reached this point by googling Lindell's name and reading up on his Wikipedia entry. I briefly looked at Frank's wikipedia page which said it had hosting with AWS which seemed really strange after Amazon stopped hosting Parler but gave a few variations of Amazon and AWS as attempts without success.

Moving on from that I searched for the Frank website on Shodan which highlighted the flag as the service provider for the website.
