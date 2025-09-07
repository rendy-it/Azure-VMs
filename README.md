<p align="center">
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/90071583-3d0c-42b0-a960-a2f0c4651b32" />
</p>

<h1>Creating a Windows and Linux Virtual Machine with Microsoft Azure</h1>
This tutorial demonstrates the methods of setting up a Windows and Linux Virtual Machine using the Azure Cloud infrastructure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Windows and Linux Virtual Machines on Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 Pro </b> (21H2)
- Linux Ubuntu

<h2>Configuration Steps</h2>

-	Step 1: Create a Resource Group
-	Step 2: Create a Windows 10 Virtual Machine within Azure
-	Step 3: Create a Linux Virtual Machine within Azure 
  

<h2>Steps in Creating Virtual Machines in Azure</h2>
<h2> << Step 1: Create a Resource Group >> </h2>
<p>
<img width="465" height="241" alt="Step 1" src="https://github.com/user-attachments/assets/6195e77c-076f-408e-8be6-7c8edfd42411" />
</p>
<p>
  
- On the Azure home page search bar, type “Resource Group”. 
- Then, select “Resource Groups” under Services.

</p>
<br />

<p>
<img width="543" height="396" alt="Step 1a" src="https://github.com/user-attachments/assets/957f27ad-3c2b-4754-8a76-9dddbb618df2" />
<p>
  
- On the next page, click on “Create”.
  
</p>
<br />

<p>
<img width="628" height="524" alt="Step 1b" src="https://github.com/user-attachments/assets/47d0db55-56de-4f6e-9585-54b210ba3571" />
</p>
<p>
  
- On the next page:
    
  - Select the subscription you prefer.
    
  - Create your resource group name.
    
  - Select a preferred region that is closest to you.
    
  - Then select “Review + Create”.

</p>
<br />

<p>
<img width="319" height="523" alt="Step 1c" src="https://github.com/user-attachments/assets/e7981b6c-b212-4ec0-8730-9c7fcb2f874b" />
</p>
<p>
  
- On the next page:
    
  - Double Check to make sure everything is to your liking.
    
  - Select “Create”.
   
</p>
<br />

<h2> << Step 2: Create a Windows 10 Virtual Machine within Azure >> </h2>

<p>
<img width="366" height="430" alt="Step 2" src="https://github.com/user-attachments/assets/267b85c2-3469-4ae4-9987-fa30ca81901a" /> <img width="88" height="430" alt="Arrow-Pointing-Right" src="https://github.com/user-attachments/assets/45bfd18c-04b9-43ec-97eb-fee73f38c146" /> <img width="283" height="430" alt="Step 2a" src="https://github.com/user-attachments/assets/240fcf46-aef5-4da9-aae0-95aca704f553" />

</p>
<p>
  
- On the Azure home page, hover you mouse cursor on “Virtual Machines”. 
  - A small window will appear, then click on “Create”.
  - Then select “Virtual Machine” 


</p>
<br />

<p>
<img width="580" height="701" alt="Step 2b" src="https://github.com/user-attachments/assets/4ba29e83-782a-4bd0-8d37-3d4a90663989" />

<p>
  
- On the next page, select the resource group that we created in Step 1.
  - Give the VM a name.
  - Select a Zone
  - Select “Windows 10 Pro” for the OS image.
    - Click on “See all images” to search for it, if you can’t find it.
  - And select at least 2 vcpus, with 8 or 16 gig memory
    - Click on “See all sizes” to search for it, if you can’t find it.
   
  
</p>
<br />

<p>
<img width="692" height="384" alt="Step 2c" src="https://github.com/user-attachments/assets/f7044866-727f-49ed-b3fe-de4ea2a3a487" />

</p>
<p>
  
- Next, create a Username and Password.

</p>
<br />

<p>
<img width="355" height="402" alt="Step 2d" src="https://github.com/user-attachments/assets/c7a8852e-036a-41c1-ab3a-c5442e06b2a9" /> 

</p>
<p>
  
- Next, go back up and click on the “Networking” tab.
   
</p>
<br />
<p>
<img width="548" height="402" alt="Step 2e" src="https://github.com/user-attachments/assets/278ba11d-16f4-4902-aa64-c79d17cd1fe0" />


</p>
<p>

- On the next page:
  - Create a new name for the “Virtual network” box.
  - You will need that same virtual network for the Linux Virtual machine.
  - Everything else is set by default.
</p>
<br />
<p>
<img width="518" height="213" alt="Step 2f" src="https://github.com/user-attachments/assets/3e1d9a16-318f-4dfb-b451-6b34fd4d274f" />
</p>
<p>

- Go back to the “Basics” tab. 
- Scroll to the bottom and check the Licensing checkbox to confirm.
- Then select “Review + Create”.

</p>
<br />
<p>
<img width="336" height="266" alt="Step 2g" src="https://github.com/user-attachments/assets/87223c89-d6b7-40e8-a7fd-63733f2aad11" /> <img width="88" height="266" alt="Arrow-Pointing-Right for Step 2g" src="https://github.com/user-attachments/assets/56f4a4a0-919b-4b9b-8fda-1c7de3a359ab" /> <img width="336" height="266" alt="Step 2g1" src="https://github.com/user-attachments/assets/49586aa9-c625-45df-a11e-86d8f3955cb1" />

</p>
<p>

- On the next Page:
  -	Double Check to make sure everything is to your liking.
  -	Then select “Create”.


</p>
<br />
<p>
<img width="394" height="357" alt="Step 2h" src="https://github.com/user-attachments/assets/c603d0c8-8b4f-433c-a8c3-b194cc23b401" /> 
</p>
<p>
  
- Deployment will take a couple of minutes to complete, so be patient.
  
</p>
<br />
<p>
<img width="357" height="445" alt="Step 2i" src="https://github.com/user-attachments/assets/9c83be4a-7794-4e91-866f-5ac5eff89e82" />

</p>
<p>
  
- Once completed you can click on “Go to resource”. 
  
</p>
<br />
<p>
<img width="906" height="555" alt="Step 2j" src="https://github.com/user-attachments/assets/6bcdbe06-270b-4f2e-9e41-58029cdb5857" />

</p>
<p>
  
- Then you will be able to see the VM that you just created with all the information.
  
</p>
<br />
<h2> << Step 3: Create a Linux Virtual Machine within Azure >> </h2>

<p>
<img width="643" height="595" alt="Step 3" src="https://github.com/user-attachments/assets/887a00b4-561a-4e1c-a6e4-ed3434c42aa8" />

</p>
<p>
  
- Repeat the same step process as you did in Step 2:
  - Select the same resource group as the Windows VM.
  - Give the VM a name.
  - Select a Zone.
  - Select “Ubuntu Server 24.04 LTS – x64 Gen2”.



</p>
<br />
<p>
<img width="674" height="491" alt="Step 3a" src="https://github.com/user-attachments/assets/41b9416c-1ec1-4a42-bb96-1a6f57134131" />


</p>
<p>
  
- For the memory size, keep it the same as the Windows VM.
- Next, check the “Password” box for “Authentication type”.
- Next, create a Username and Password.


</p>
<br />
<p>
<img width="645" height="815" alt="Step 3b" src="https://github.com/user-attachments/assets/98b50ea7-43c9-4079-9b63-774136dfe81d" />

</p>
<p>
  
- Then go to the “Networking” tab
- Make sure to select the same Virtual Network as the Windows VM.
- Keep everything else default and select “Review + create”


</p>
<br />
<p>
<img width="445" height="442" alt="Step 3c" src="https://github.com/user-attachments/assets/fd7afc21-a6a9-4762-99ae-68bcd3c7d917" /> <img width="88" height="442" alt="Arrow-Pointing-Right for Step 3c" src="https://github.com/user-attachments/assets/4818d701-1d71-4125-ad02-8b2d8f4ad061" /> <img width="439" height="442" alt="Step 3c1" src="https://github.com/user-attachments/assets/e1d77209-a445-4591-a371-0794087ed0db" />




</p>
<p>
  
- On the next Page:
  - Double Check to make sure everything is to your liking.
  - Then select “Create”.



</p>
<br />


