# Analyze a Phishing Email Sample.

**1.Obtain a sample phishing email (many free samples online).**

This is the link of sample

[**phishing_pot/email/sample-1009.eml at main · rf-peixoto/phishing_potA collection of phishing samples for researchers and detection developers. - phishing_pot/email/sample-1009.eml at main…**
github.com](https://github.com/rf-peixoto/phishing_pot/blob/main/email/sample-1009.eml?source=post_page-----ea539b6d11ed---------------------------------------)

**2.Examine sender’s email address for spoofing.**

First copy the header

In gmail click on … dots click on show originals and copy click boards go to the thsese website to check email spoofing website [**https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx?huid=9331f3c8-e3c9-4723-b961-c9abbfe5fe23**](https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx?huid=9331f3c8-e3c9-4723-b961-c9abbfe5fe23)

Copy paste the header in box click on the **analyze header**

![](https://miro.medium.com/v2/resize:fit:700/1*VBaV4s4h59tyiVjsGtDKrw.png)

if you go the below you can easily see clearly this email is spoofed

![](https://miro.medium.com/v2/resize:fit:1000/1*eWcC-kJRmOXnzk0ilngkHg.png)

**3.Check email headers for discrepancies (using online header analyzer).**

For email header analysis use same tool [**https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx?huid=9331f3c8-e3c9-4723-b961-c9abbfe5fe23**](https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx?huid=9331f3c8-e3c9-4723-b961-c9abbfe5fe23)

![](https://miro.medium.com/v2/resize:fit:700/1*VBaV4s4h59tyiVjsGtDKrw.png)

you can see this is blacklisted

![](https://miro.medium.com/v2/resize:fit:700/1*4j20KB4I6773IzM5LiIFkA.png)

**4.Identify suspicious links or attachments.**

for identify suspicious link first copy the link and go to the virus total and paste it

suspicious link is ; **http://ecs-49-0-248-79.compute.hwclouds-dns.com/**

![](https://miro.medium.com/v2/resize:fit:700/1*BppDykopYmFlgaWFcIVflQ.png)

you can easily identified suspicious link

![](https://miro.medium.com/v2/resize:fit:700/1*D8FxZ0NmodY1USqyepSqYA.png)

**5.Look for urgent or threatening language in the email body.**

if you read this email you can see this in below;

You
 are expected to call DHL office +1(318)901–5153 immediately you receive
 this message because Bank of America (BOA) has finally released your 
compensation fund of $6,400,000.00 million USD and it has been 
programmed into an ATM visa debit card.

Right now your ATM card parcel is in DHL office waiting for your address of where to deliver it.

**6.Note any mismatched URLs (hover to see real link).**

There
 are no clickable URLs in the email, but if there were, it’s important 
to hover over any links to check if the displayed text matches the 
actual URL. In phishing emails, attackers often use mismatched URLs to 
trick users into clicking malicious sites that look legitimate. Always 
verify the real destination before clicking.

**7.Verify presence of spelling or grammar errors.**

In this mail too much error in spelling and gramatically

The
 message contains several errors, including incorrect number formats 
(e.g., “$6,400,000.00 million” is wrong), awkward greetings (“Greetings 
Dear,” should be “Dear [Name],”), missing articles (“in DHL office” 
should be “in the DHL office”), and run-on sentences without proper 
punctuation. Also, phrases like “Best Regard” should be plural (“Best 
Regards”), and closings like “Yours In Service” are not standard and 
should be replaced with “Sincerely” or “Yours sincerely.” Proper 
formatting for lists and clear sentence structure will make the message 
more professional and easier to read.

**8.Summarize phishing traits found in the email.**

Phishing Traits in the Email:

. Unexpected large money offer: Claims of $6.4 million compensation out of nowhere.

. Urgency and pressure: Asking to call immediately.

. Suspicious contact details: Uses a generic Gmail address instead of an official company email.

. Poor grammar and formatting: Shows unprofessional language and mistakes.

. Request for personal information: Asks for name, address, and phone number.

. Unverified sender: Email headers show inconsistent and suspicious sources.

. Too good to be true: Offers huge money with little explanation.
