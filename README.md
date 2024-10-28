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
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![Screenshot 2024-10-28 161718](https://github.com/user-attachments/assets/61365591-01d1-479f-9ddb-aa9b14c1f49d)
sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2024-10-28 161731](https://github.com/user-attachments/assets/b83fb580-af54-49f0-9887-53dd8babedc8)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![Screenshot 2024-10-28 161739](https://github.com/user-attachments/assets/09fd7c0c-cbe5-4cdc-8139-9d2b9da3293f)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![Screenshot 2024-10-28 161749](https://github.com/user-attachments/assets/68d676f1-13a6-459e-91ea-ca6e14ce1120)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![Screenshot 2024-10-28 161800](https://github.com/user-attachments/assets/7084fd63-e3e4-473d-8d13-bb42ab3c5395)
It shows the following screen in which the option Google can be selected:

![Screenshot 2024-10-28 161809](https://github.com/user-attachments/assets/22e1b99c-2cea-4e18-a031-1dee3982d64c)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![Screenshot 2024-10-28 161822](https://github.com/user-attachments/assets/8ab48bde-be63-4ec0-b89c-72b1377fa403)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![Screenshot 2024-10-28 161831](https://github.com/user-attachments/assets/cfa402b5-3e6d-4449-8f4c-b83ed3c9c3d9)
SET logs the information regarding the Google credentials:
![Screenshot 2024-10-28 161840](https://github.com/user-attachments/assets/05fcc4fd-e575-41d9-915f-da2906a2cb89)
SET logs the information in the xml file under /root/.set directory:
![Screenshot 2024-10-28 161847](https://github.com/user-attachments/assets/12cdb560-8ede-4bef-8b5a-a4e4bd851c1e)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
