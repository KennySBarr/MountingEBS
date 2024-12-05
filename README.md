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

- Click into Instances and get your Instance running
- then click connect

![Screenshot 2024-12-04 174415](https://github.com/user-attachments/assets/9e7ed69d-7876-4b4a-abd8-3e1158089d41)

![Screenshot 2024-12-04 174422](https://github.com/user-attachments/assets/4ef0b68a-565a-4126-a96f-04f9f7b2151e)


- Click RDP Client
- Click get Password - (when you created your Instance you should have created Key-Pairs which created a file)
- You will will use that file and AWS will decrpyt the file
- Then it will give you the password
- Copy the public IP
- by defualt the Username is "Administrator"
- Use the decrptyed password to login RDP
  
![Screenshot 2024-12-04 174430](https://github.com/user-attachments/assets/ce5c1ed5-45a4-49a9-b0e6-982716eeab31)


- From your search bar once connected into your Instance go to "Server Maanger"
- Click into files and Storage services

![Screenshot 2024-12-04 171641](https://github.com/user-attachments/assets/c4eda0f3-b4af-4eea-b102-5fe32eedeac3)


- Click the Disk option

![Screenshot 2024-12-04 172304](https://github.com/user-attachments/assets/5eae90c6-a948-4dde-8c3f-b545d0e43122)

- right click on the new volume
- Click "Add New Volume" 

![Screenshot 2024-12-04 172314](https://github.com/user-attachments/assets/ca89befa-fd21-41b1-8a1e-38d4a596ee94)

- This screen should pop up 
- Click "Next" 

![Screenshot 2024-12-04 172320](https://github.com/user-attachments/assets/910e5bc2-eb93-472a-b026-bfb2b79f1bec)

- Add the number of GB you are adding 
- Click "Next" 

![Screenshot 2024-12-04 172333](https://github.com/user-attachments/assets/e8129a30-3b50-4802-bf2b-df1f4abd3a35)

- Add the Path of the File in this case I chose "E"
- Click "Next"

![Screenshot 2024-12-04 172349](https://github.com/user-attachments/assets/4591a1ec-ea29-4123-acbf-5c7ad71855e3)


- Click "Create"

![Screenshot 2024-12-04 172403](https://github.com/user-attachments/assets/fc88fea6-4006-45b2-bd7c-9c209e972116)

- Once the creation is complete and successful
- Go to your folders tab on your task bar
- Go to Pc
- there should be your new volume you created "New Volume"

![Screenshot 2024-12-04 172457](https://github.com/user-attachments/assets/566dc2a3-1c13-42cd-928e-7b51b15a693d)



