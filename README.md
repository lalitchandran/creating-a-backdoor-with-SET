# Creating a Backdoor with SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/Bhargava-Shankar/creating-a-backdoor-with-SET/assets/85554376/8706e0dc-e29e-4e87-91ad-fadd493bc1ce)


It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/Bhargava-Shankar/creating-a-backdoor-with-SET/assets/85554376/c79b4cda-c08e-4493-afc1-434947e57c70)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/Bhargava-Shankar/creating-a-backdoor-with-SET/assets/85554376/b178ac4b-f588-4f5f-aa31-ed61192d4d1c)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: ![280444401-069a27c5-c26c-4879-bb4b-1d33d34b8298](https://github.com/Bakkiyalakshmi29/creating-a-backdoor-with-SET/assets/119406233/f0def0a1-6da4-468c-b369-d8247777eb37)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:![280444437-b4dd7564-de55-437b-94ae-d716800eb28d](https://github.com/Bakkiyalakshmi29/creating-a-backdoor-with-SET/assets/119406233/25405d76-1dda-4eb6-ad43-73a944e9118e)

It shows the following screen in which the option Google can be selected:![280444472-c274553b-8037-423c-b20d-a266f535941a](https://github.com/Bakkiyalakshmi29/creating-a-backdoor-with-SET/assets/119406233/20ce9fe5-ad11-4db8-a439-b8dde59a045f)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![280444508-559638dd-3271-4b4e-a44c-cff62000b67a](https://github.com/Bakkiyalakshmi29/creating-a-backdoor-with-SET/assets/119406233/4c5b7af1-82fb-4f3a-ae44-8de0c9a07b73)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password ![280444543-cdff94c7-af85-4bd4-b076-26cf1651a673](https://github.com/Bakkiyalakshmi29/creating-a-backdoor-with-SET/assets/119406233/6a63480f-5342-4ffb-b1c9-2c4f2527f509)

SET logs the information regarding the Google credentials:
![280444571-9b08b886-8601-43db-a8db-2debbbfb66ff](https://github.com/Bakkiyalakshmi29/creating-a-backdoor-with-SET/assets/119406233/ce3e98dc-c84b-4b21-b76a-ac09b623e7d2)

SET logs the information in the xml file under /root/.set directory: ![280444636-8195f72c-c634-4d50-b1a7-bd1f6675b893](https://github.com/Bakkiyalakshmi29/creating-a-backdoor-with-SET/assets/119406233/76566090-9ef4-464c-bff1-f499923519c8)













## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
