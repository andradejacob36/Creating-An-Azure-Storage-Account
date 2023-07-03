<p align="center">
<img src="https://i.imgur.com/gbeZ9C5.png" alt="Microsoft Azure Logo"/>
</p>

<h1>Creating a First Resource Group and Storage Account on Azure</h1>
This tutorial provides a comprehensive guide on creating your first Azure Storage Account.<br />

<h2>Environments and Technologies Used</h2>
- Microsoft Azure 
- Resource Group

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: You need to authenticate and authorize yourself by logging into the Azure portal
- Step 2: Create a Resource Group
- Step 3: Create a Storage Account
- Step 4: Interaction with your Storage Account
- Step 5: Editing the Container 

<h2>Step 1: You need to authenticate and authorize yourself by logging into the Azure portal</h2>

1.Go to the Azure Portal website (https://portal.azure.com/) and sign in with your Azure account credentials. 

- Note: If you do not have an Azure account, you must sign up for one before you can log in.

2.Once you have successfully logged in, you will be redirected to the Azure portal dashboard where you can create and manage your resources. 

3.You should be able to see the following display:

<p>
<img src="https://i.imgur.com/zr0sGpt.png" height="80%" width="80%"/>
</p>
<p>  
  
<h2>Step 2: Create a Resource Group</h2>

1.Locate the search bar and type "Research groups".

2.To create a new item, click on the "+ Create" button in the top left corner next to the "Manage View" option.
   <ol type="a">
      <li>Choose your subscription (For Ex: Azure Subscription 1).</li>
      <li>Create a name of your resource group (Use: RG-Lab1).</li>
      <li>Select the region that aligns perfectly with your requirements and preferences (For Ex: West US 3).</li>   
    </ol>

3.After typing the specifications, click on the box "Review + create".

4.You should be able to see the following display:

<p>
<img src="https://i.imgur.com/ZidiTxR.png" height="80%" width="80%"/>
</p>
<p>   

5.Then click "Create" located at the bottom left corner.
 
- Note: By creating a Resource group, it would be like creating a folder that will hold all of your related resources in one centralized location.

<h2>Step 3: Create a Storage Account</h2>

1.Locate the search bar and type "Storage accounts".

- Note: The Azure Storage Account offers a wide range of storage options that are both scalable and secure. It comes packed with fantastic features such as redundancy, backups, and access control, ensuring that your data is always protected.

2.You will be redirected to the Azure Storage Accounts where you can store data.

3.You should be able to see the following display:

<p> 
<img src="https://i.imgur.com/4ox6ks4.png" height="80%" width="80%"/>
</p>
<p>  

4.Located at the top left corner, click the "+ create" button.

5.Next step is that you will have to choose specific configurations for your storage account. 
   <ol type="a">
      <li>Choose your subscription (For Ex: Azure Subscription 1).</li>
      <li>Create a name of your resource group (Use: RG-Lab-1).</li>
      <li>Name your own Storage Account Name. It must be unique (For example jacobcoursecareer01).</li>
      <li>Select the region that aligns perfectly with your requirements and preferences (For Ex: West US 3).</li> 
      <li>Pick your "Redundancy" depending on what services you need. For this example, I will use "RA-GRS"</li>
    </ol>

- Note: After inputting the settings you should have the following: 

<p> 
<img src="https://i.imgur.com/Ee0y5dq.png" height="80%" width="80%"/>
</p>
<p>  

6.Click Create. Locate the search bar and type "Storage Account".

7.Your new Storage Account should be available within the "Storage Account" dashboard. 

<p> 
<img src="https://i.imgur.com/P940HmK.png" height="80%" width="80%"/>
</p>
<p>  

<h2>Step 4: Interaction with your Storage Account</h2>

1.Continue by clicking your Storage Account.

2.Under Data Storage, click on "Containers".

3.Afterward, proceed by clicking "+ Container" 
   <ol type="a">
      <li>On the top right corner, you can name your container. I will use "cclab01".</li>
      <li>Since this is just a lab, I will have my public access level as "Private".</li>
      <li>On the bottom right corner, click the blue "Create" button.</li>
    </ol>

<p> 
<img src="https://i.imgur.com/Qi6DUn4.png" height="80%" width="80%"/>
</p>
<p>  

<h2>Step 5: Editing the Container </h2>

1.Click the newly created folder or container. Mine is called cclab01.

<p> 
<img src="https://i.imgur.com/xgQIE7x.png" height="80%" width="80%"/>
</p>
<p>  

- Note: Here you can finally store whatever data you are allowed to store here. For example, I will demonstrate how to store a Notepad in this folder.


2.Open Notepad and type anything within it. 
   <ol type="a">
      <li>Make sure to save it on your desktop</li>
    </ol>

<p> 
<img src="https://i.imgur.com/absg7Za.png" height="80%" width="80%"/>
</p>
<p>  

3.Go back to Azure and upload the Notepad to your folder/container
   <ol type="a">
      <li>Click the "upload" button</li>
      <li>Find "Browse for files"</li>
      <li>Pick the notepad from your desktop</li>
      <li>Click the blue "Upload" button</li>
    </ol>

<p> 
<img src="https://i.imgur.com/3WVvxmM.png" height="80%" width="80%"/>
</p>
<p>  

- Note: You should be able to open/edit/download your Notepad on Azure. Also, be advised that you can in addition store different data such as Blobs, Tables, Queues, Files, etc.

<h2>The End </h2>

  
 


