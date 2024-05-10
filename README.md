# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows.

### Step 3:
Open terminal and try execute some kali linux commands.

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/9e1ced59-7bf2-4298-9813-0f31dc9932b9)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/ee27ada6-f929-473e-be06-c839756595a0)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/ab5259e5-e183-404e-938b-544843d3a21f)



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/5f47637e-02d4-4726-93a6-e644fb6bd1b6)



It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/3b09d197-666e-4e29-a63f-2e991900ba80)



It shows the following screen in which the option Google can be selected: 

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/73b9368c-f248-47b8-9a2f-f8670c0d85af)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/972664ca-4891-495f-b483-77fb9a95a807)



In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/bbc85743-75e5-4f97-892d-fd7766574530)



SET logs the information regarding the Google credentials: 

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/3abda5a8-c794-455e-b9dc-45f0df9ec0fd)


SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/lalitchandran/creating-a-backdoor-with-SET/assets/137707725/810ec39a-fa73-4af8-a89d-c4a46f00307c)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
