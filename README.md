# Setting-VPN-connection
A VPN(Virtual Private Network) creates a secure site-to-site connection between a server and a remote client. Data is transmitted through an encrypted tunnel, and it is a secure way for remote desktop, file sharing, and secure communication.<br><br>
Lab Objective: Using Windows Server Management, install and configure VPN.<br><br>
Background: VPNs are used to securely establish end-to-end connections between a private network and a remote device.<br><br>
Devices used: Two virtual Microsoft Windows Servers are used in this lab.<br><br>

1.	Before we proceed, we need to turn off the Windows firewall to allow us to have a remote network connection.
After that, I installed and configured Role-based Remote Access VPN  in Windows Server ZYWIN01.<br><br>
<img width="675" height="425" alt="image" src="https://github.com/user-attachments/assets/eaa076e0-07c1-4940-8a70-b13b934252ac" /> <br> <br><hr >

2.	After creating the Remote Access Role, I applied specific rules and configurations. Here, I added specific IP addresses that allow connection to the VPN. <br><br>
  <img width="675" height="425" alt="image" src="https://github.com/user-attachments/assets/788d79ae-18e8-4cf1-8581-795150db07bd" />  <br> <br><hr >
  
3. Using Server Manager, I created a security group and added users to the group. These specific group members are added as members of the VPN connection.<br><br>
<img width="675" height="426" alt="image" src="https://github.com/user-attachments/assets/7de41af9-1380-49f1-9d56-ad5b3be45253" />
<img width="675" height="426" alt="image" src="https://github.com/user-attachments/assets/e83dc063-fbfc-468b-9d8f-b74d38671a9c" /> <br> <br><hr >

4. Network Policy Server is used to enforce network access policies and set rules for authentication and authorization for remotely accessed VPN users.<br><br>
   <img width="673" height="425" alt="image" src="https://github.com/user-attachments/assets/ccd9bae8-dfac-4898-8e84-4f72d0a9e94e" />
   <img width="671" height="425" alt="image" src="https://github.com/user-attachments/assets/ea09aabd-fdd6-46e4-af27-a202f013634e" /> <br> <br><hr >
   
5. Now I go to another machine, and  configure a VPN client, and after giving credentials and setting encryption properties, I can now connect to the Working VPN created on the first server.<br><br>
   <img width="671" height="425" alt="image" src="https://github.com/user-attachments/assets/72fc8314-d121-48fe-af0b-ee16f3dd0f94" /> <br> <br><hr >

6.	Checking VPN Connections on Command Prompt.<br><br>
   <img width="675" height="425" alt="image" src="https://github.com/user-attachments/assets/6fd725e1-81aa-43c5-a83a-ab5fbc531647" /> <br> <br><hr >

7.	Now I can access files and folders from the ZYWIN01 server from my VPN client computer. <br><br>
   <img width="675" height="425" alt="image" src="https://github.com/user-attachments/assets/c3c033c0-d0a0-4abd-b1e3-92b9730799cd" /> <br> <br><hr >
8.	I map a network drive and give a drive letter to a folder from the VPN server for easy accessibility. .<br><br>
   <img width="675" height="425" alt="image" src="https://github.com/user-attachments/assets/a068f5aa-95d0-4fbf-8765-b5bfad382108" /> <br> <br><hr >

   Thanks for going through my lab.   <br>
  

 This lab work is part of the exercises from NT 3120: Networking Standards and Protocols zyBook ISBN: 979-8-203-38907-7.





   





  


