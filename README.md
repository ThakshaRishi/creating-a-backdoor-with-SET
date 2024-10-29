# creating-a-backdoor-with-SET
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
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/user-attachments/assets/1fa3e0c3-fa6a-4903-a816-d2aa4e19c259)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
It displays the following menu and select 2 for Website Attack Vectors: 

![image](https://github.com/user-attachments/assets/e8d46f04-8b16-4b21-bae8-ff9632762db5)

![image](https://github.com/user-attachments/assets/0bcb9ed9-3374-4366-a323-52a840ad0cb6)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected

![image](https://github.com/user-attachments/assets/fdaf13ad-e820-46c3-a6a6-8373223afd81)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected

![image](https://github.com/user-attachments/assets/634b9f54-0aab-462b-b00e-e1af0f461b7a)


It shows the following screen in which the option Google can be selected

![image](https://github.com/user-attachments/assets/92e501b4-43ee-46dc-9584-093918f55d9a)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done
In windows IE, on giving the url (http://192.168.237.134/), the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/user-attachments/assets/45893aff-4211-4e88-8037-a0116489fd53)


SET logs the information regarding the Google credentials

![image](https://github.com/user-attachments/assets/4cc38c80-d5d3-4226-80ea-c35d49701b55)






## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
