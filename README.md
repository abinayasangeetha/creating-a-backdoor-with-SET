# Creating-a-backdoor-with-SET
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

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/f24e71c5-ea99-48ce-8d50-d449ff746cb4)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/81095ccc-06ca-4f15-b8db-6f4b0e9918bb)


It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/1dfa92ee-934c-48bd-8ea9-a2e573c209f6)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/b31a7146-6690-4e69-b29b-6149a5a77225)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/756a68cb-65f7-4b76-b226-7813b5c7e8f1)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/08da0a23-ec84-4dec-9f9a-07a0e19f94a4)


It shows the following screen in which the option Google can be selected:

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/c9984e0e-e24d-404e-b48a-82269df0f57b)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/838e6919-874b-4c8e-b13f-7ddb2d8d8168)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/2a4c36d6-ca75-4afb-a682-eecba4840e20)


SET logs the information regarding the Google credentials:
![image](https://github.com/abinayasangeetha/creating-a-backdoor-with-SET/assets/119393675/4b806801-db67-4ec8-8c87-bb154520dff4)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
