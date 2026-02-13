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
## OUTPUT
<img width="568" height="413" alt="image" src="https://github.com/user-attachments/assets/c808452b-a703-49fb-b0b5-c2d004c058d2" />




The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="426" height="240" alt="image" src="https://github.com/user-attachments/assets/9f54c3d5-4ae0-4617-ac77-6ca4a8cfb690" />




It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="394" height="292" alt="image" src="https://github.com/user-attachments/assets/6e505e01-ff9b-4336-afb7-cd244705930c" />




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="1658" height="468" alt="image" src="https://github.com/user-attachments/assets/7fcafae3-1405-4831-b085-4f29aed4ab4b" />
<img width="573" height="290" alt="image" src="https://github.com/user-attachments/assets/a5abaddb-7613-47eb-b945-130c92b29917" />





It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="753" height="375" alt="image" src="https://github.com/user-attachments/assets/bbd20626-1ae5-4873-94bc-ec5b7df65b19" />





It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="377" height="117" alt="image" src="https://github.com/user-attachments/assets/038e94ff-afc1-4bf0-a2bb-530ced4e606f" />






SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1156" height="178" alt="image" src="https://github.com/user-attachments/assets/3acee7a2-e0ea-461f-b4a2-5bbc93aba1df" />





In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1668" height="996" alt="image" src="https://github.com/user-attachments/assets/c322a8ef-d301-41b1-994d-bc801504753e" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1573" height="330" alt="image" src="https://github.com/user-attachments/assets/bf2d586d-e2d3-4bc4-a994-151ae5699bda" />




SET logs the information in the xml file under /root/.set directory:
## OUTPUT













## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
