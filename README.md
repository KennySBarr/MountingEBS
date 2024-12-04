<p align="center">
       
![AWS_logo_new](https://github.com/user-attachments/assets/a7a389ae-0c58-4096-afdf-d0586aaa44e3)

   

</p>

<h1>AWS Cloud </h1>
AWS (Amazon Web Services) is a comprehensive and widely adopted cloud platform that offers a variety of on-demand computing services, storage, networking, and analytics, enabling businesses to scale and innovate with flexibility and efficiency.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free AWS credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create a new Volume </h3>

- Select Volumes Under the "Elastic Book Store" Tab 
     
![Screenshot 2024-12-04 154044](https://github.com/user-attachments/assets/d0983d63-95ce-4aa9-ae4c-d11a8987f5e8)

- Follow the prompt to create a new Volume top right "Orange" Tab
     - In this Screen you will be deciding how much extra memory "Volume" you'll be adding to your VM
     - I chose to add 20 more GB to this VM
    
![Screenshot 2024-12-04 171747](https://github.com/user-attachments/assets/cd422848-5c9e-435f-af49-dad4325c328d)


 <h3>Step 2: Attatch the Volume to the correct Instance created </h3>
 - Be sure to go back to the Volumes Tab
 - Click the Action
 - Then click the Attatch volume
   
![Screenshot 2024-12-04 160925](https://github.com/user-attachments/assets/3dd44d86-b49d-4b49-8f25-398bc0dc4ebf)


<h3>Step 3: Sign into your AWS Instance and access the Server Manager </h3>

- From your search bar once connected into your VM go to "Server Maanger"
- Click into files and Storage services
- 
![Screenshot 2024-12-04 171641](https://github.com/user-attachments/assets/c4eda0f3-b4af-4eea-b102-5fe32eedeac3)


- Click the Disk option

![Screenshot 2024-12-04 172304](https://github.com/user-attachments/assets/5eae90c6-a948-4dde-8c3f-b545d0e43122)

- right click on the new volume
- Click "Add New Volume" 

![Screenshot 2024-12-04 172314](https://github.com/user-attachments/assets/ca89befa-fd21-41b1-8a1e-38d4a596ee94)

- This screen should pop up 
- Click "Next" 

![Screenshot 2024-12-04 172320](https://github.com/user-attachments/assets/910e5bc2-eb93-472a-b026-bfb2b79f1bec)



<h3>Step 2: Create an IAM User with Amazon S3 Access</h3>

- Go to the search bar at the top and search "IAM"
- Select Users tab to the left 
- You will need to name the user JohnDoe 
- Then click create passwordd
-  Create a Custom password and follow the rules and unclick "User has to reset password on next login" 

 
![Screenshot 2024-12-04 143727](https://github.com/user-attachments/assets/fe05ddf6-bafa-43a4-9ef8-0cad535fc875)





<h3>Step 3: Set Permissions to the IAM USer "JohnDoe" </h3>

- Click custom policy
- then click the Permissions Policy
- Select or Search Amazon S3 Access 
- You will need to select amazon S3 Access
- Then click Next 
 

![Screenshot 2024-12-04 143953](https://github.com/user-attachments/assets/d636cb79-6e74-4a8b-b859-0fb763253c10)

<h3>Step 4: Confirm IAM User</h3>
     
- Copy the sign in link provided for IAM User into another browser 

![Screenshot 2024-12-04 144025](https://github.com/user-attachments/assets/962700ee-03ea-4240-9961-83db19d8fb90)

- Log into the IAM user with the Username and Password created
    - The number you see attatched in the login screen is the number assocaited with your root account 

![Screenshot 2024-12-04 145254](https://github.com/user-attachments/assets/8589c3a8-f924-461d-a997-695276fa8a55)

- As seen in the third picture below the "JohnDoe" account has permission restrictions flagged on his/her dashboard upon launch

![Screenshot 2024-12-04 145335](https://github.com/user-attachments/assets/5bfff862-501b-48ce-b18a-97467e75497a)
