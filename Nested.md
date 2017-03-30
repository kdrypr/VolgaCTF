# VolgaCTF
We search pcap file for what it hide inside.

![image](https://cloud.githubusercontent.com/assets/19524941/24472421/500d230e-14ce-11e7-90f8-9f13cd17cc8f.png)

after that we extract files from pcap file.

For this step we use this command:

![image](https://cloud.githubusercontent.com/assets/19524941/24472484/861c63e2-14ce-11e7-9f2a-32a6a2e0da39.png)

or this command:

![image](https://cloud.githubusercontent.com/assets/19524941/24508437/0f5c07fa-156c-11e7-872f-3c8a43309834.png)

![image](https://cloud.githubusercontent.com/assets/19524941/24472500/9a921a6a-14ce-11e7-8079-4d2fb4910928.png)

extract detected.7z 

![image](https://cloud.githubusercontent.com/assets/19524941/24472525/b33447dc-14ce-11e7-93ae-d974d78294b3.png)

when open the other.zip file it wants to password for to extract hide file, and we search password from each.jpg file,

but we use OutGuess tool for extract steg information.

install command: # sudo apt-get install outguess

![image](https://cloud.githubusercontent.com/assets/19524941/24472627/0b8421be-14cf-11e7-913f-eb065ff3eb8c.png)

then we have the password:

![image](https://cloud.githubusercontent.com/assets/19524941/24472637/1b9bea64-14cf-11e7-8047-53ec309c43c6.png)

use this password for extract hide file:

![image](https://cloud.githubusercontent.com/assets/19524941/24472700/5037560a-14cf-11e7-980a-82d26e574abc.png)

after that we use gzsteg tool:

https://packetstormsecurity.com/files/21616/gzsteg.zip.html download from here and apply the instructions: https://dl.packetstormsecurity.net/crypt/stego/DOS/gzsteg.txt

use this command for gzsteg:

![image](https://cloud.githubusercontent.com/assets/19524941/24472756/8f23fc6a-14cf-11e7-80ed-462413e205a3.png)


WE HAVE THE FLAG:

![image](https://cloud.githubusercontent.com/assets/19524941/24472774/9de048bc-14cf-11e7-97ce-17e515b6e031.png)






