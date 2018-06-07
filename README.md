# Getting Started
The first thing I'd say is that starting out with **blue team** (defending networks) will give you breathing room and time to learn pen testing/red team, as blue team IMO is a bit easier (requires less deep and specific knowledge) and you really should have experience there anyways before you do red team so you know how to avoid being detected. You should also learn programming ASAP, as it helps with every aspect of security (Python is a good beginner language, but you will want to learn C as well at some point.)

# Blue Team
For blue team you should get a **mirrored switch** for home ([Amazon Link](https://www.amazon.com/s/ref=nb_sb_noss?url=search-alias%3Daps&field-keywords=mirror+port+switch&rh=i%3Aaps%2Ck%3Amirror+port+switch)), and use **Security Onion** to practice with **Suricata** and **Wireshark**. Basically you want to set up a mirror port to send packets to your Security Onion PC ([Amazon Link](https://www.amazon.com/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=zotac+zbox&rh=i%3Aaps%2Ck%3Azotac+zbox)), which you log in to and try your best to understand what is happening on your home network.  Go to [Test My IDS](http://testmyids.com/) to see what an alert looks like, and make sure your IDS is working properly.  The new Security Onion ([Github Link](https://github.com/Security-Onion-Solutions/securityonion-elastic))uses the **ELK stack**, which I've used professionally, so just learning that is a really good start.  If you don't understand Cisco, go out and get your **CCNA**, as this will also help with both red and blue team.

Also, you can learn a lot by looking at [**Malware Traffic Analysis**](https://malware-traffic-analysis.net), and writing up what you think is going on in the [**packet captures**](https://www.malware-traffic-analysis.net/training-exercises.html). If you use [**Packet Total**](https://packettotal.com), you can load up the captures they give you and analyze what's going on in them fairly easily. You could also download the capture files and replay them in Security Onion, so you will see a more real-world example of what attacks look like in "real-time".

# Red Team
If you want to get a head start on red team, I'd recommend checking out the [**Github "awesome" repos**](https://www.google.com/search?q=site%3Agithub.com+"awesome-"&oq=site%3Agithub.com+"awesome-"), which include "awesome-pentest", "awesome-ctf", and "awesome-security". There is a huge amount of good info there - my advice is just to not get overwhelmed, and try to set goals for yourself to stay on track - e.g. "I will get my S+ in 6 months", "I'll do 15 minutes of programming every day/weekend", "I will finish one CTF challenge per month", etc... 

[**Root-me.org**](https://root-me.org) is also awesome for learning hacking in general, where they give you concrete challenges, and the resources are attached to the challenges to make it easier to learn and understand.  Look at awesome-ctf for more platforms, but in my experience the best beginner ones are: 
* [Root-me](https://www.root-me.org/?lang=eng)
* [Exploit Exercises](https://exploit-exercises.com/)
* [Over the Wire](http://overthewire.org/wargames/)
* [Python Challenge](http://www.pythonchallenge.com/)

# Getting Hired
My advice here is to get both certifications **and** practical experience as soon as possible, because it will prepare you for first passing the initial resume screening/keyword search, and also make sure you are ready for some practical questions during your interview.  The above advice should set you on a path to get practical skills and experience, while the below list charts a rough order of which certs you may want in order to obtain employment in the IT Security field.

* S+
* CSA+
* GISF
* GSEC
* CISSP
* CISA
* OSCP

While certs and experience are very valuable, and can go a long ways towards landing you a job, the third thing that will give you the best chances at obtaining a desirable and well-paying job in the industry is **networking**.  No, I don't mean you should grab a firewall and some switches and start segmenting away (although that's never a bad idea).. I mean that you need to start talking with people in the IT Security industry.  

Go out and join your local hackerspace/makerspace, and see what people there are excited about.  Get on IRC and meet people that are working on Metasploit, PowerShell Empire, Security Onion, Root-Me, and other security projects.  Join some local/regional Cyber Security User Groups, and attend conferences like DEFCON, DerbyCon, and Wild West Hackin' Fest.  I can speak from experience, that all of the skills in the world can't beat good real-world connections.

# Overcoming obstacles
This last part is **crucial**:  if you encounter barriers, or hit a wall with challenges, go onto **IRC** or **reddit** and ask the professionals.  The infosec community is a very strong one, with one important caveat.  DO NOT ASK TO BE HAND-FED.  You must go in and ask questions so you don't get stuck and lost motivation, but do not go and say "hey everyone, I want to hack my wifi so where do I begin", or "I can't get this loop to work, can you tell me what's wrong with it?"  You should demonstrate that you have done basic Google searches first, and put in some effort before you start to ask for help, otherwise people will most likely be hesitant to spend their (most likely valuable) time doing your work for you.
