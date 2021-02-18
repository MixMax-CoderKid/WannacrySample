# WannacrySample
Sample of the wanna cry ransomware. Later I might add some other stuff ;)
For people who don't understand what this file is don't download it, it will infect your machine and encrypt your files and ask for a ransom.

Virus Name: WannaCrypt, WannaCry, WanaCrypt0r, WCrypt, WCRY
Vector: All Windows versions before Windows 10 are vulnerable if not patched for MS-17-010. It uses EternalBlue MS17-010 to propagate.
Ransom: between $300 to $600. There is code to 'rm' (delete) files in the virus. Seems to reset if the virus crashes.
Backdooring: The worm loops through every RDP session on a system to run the ransomware as that user. It also installs the DOUBLEPULSAR backdoor. (source: malwarebytes)
Kill switch: If the website www.iuqerfsodp9ifjaposdfjhgosurijfaewrwergwea.com is up the virus exits instead of infecting the host. (source: malwarebytes). This domain has been sinkholed, stopping the spread of the worm.

Please note that the exe file is now moved to the release section because of a warning from github, The password for the zip file is "okgithub"
