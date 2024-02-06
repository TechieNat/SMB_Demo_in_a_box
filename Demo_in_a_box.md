# SMB Demo in a box

Repository to promote the creation of basic demo environment in a free Azure Subscription for SMB scenarios

Base line of a demo based on Infrastructure is strating your practice with Azure VM, Windows and Linux, so can use the below Azure Resource Manager Templates to deploy them, it is important to have basic concepts about this deployments, some of them  arel listed here:

A resource manager template is a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your project. The template uses declarative syntax. In declarative syntax, you describe your intended deployment without writing the sequence of programming commands to create the deployment.

**Instructions to build a demo, it could be a Windows VM, Linux VM, or both, follow the steps:**

1. Create an** Azure Free Subscription** in the link here: https://azure.microsoft.com/en-us/pricing/offers/ms-azr-0044p/
   
3. Confirm your access to **Deploy a custome template**, using the search bar as below:
   
![image](https://github.com/TechieNat/SMB_Demo_in_a_box/assets/61152897/644d24ad-f212-46f5-baf5-66fc997f9509)
5. Clic on **Build your own template**
   
![image](https://github.com/TechieNat/SMB_Demo_in_a_box/assets/61152897/3128a5f2-7b0b-4868-ab41-dbfee2f98246)
5. Use the deployment file template for Windows or Linux VM, using the **Load file** option and **Save**
Here is:
- Windows VM ARM Template https://github.com/TechieNat/SMB_Demo_in_a_box/blob/main/LinuxVM_B1S.json
- Linux VM ARM Template  https://github.com/TechieNat/SMB_Demo_in_a_box/blob/main/LinuxVM_B1S.json

![image](https://github.com/TechieNat/SMB_Demo_in_a_box/assets/61152897/9939683a-8823-4037-a81b-c670d3dc3089)
5. Complete the Resource Group, Admin Username and Admin Password, then **Review + Create**
  
![image](https://github.com/TechieNat/SMB_Demo_in_a_box/assets/61152897/4d761157-8393-4e9d-95f0-213790c61f34)
6.- after validation, clic on **Create**
  
![image](https://github.com/TechieNat/SMB_Demo_in_a_box/assets/61152897/73e16cf0-b66c-49e7-837d-37e36d144e8c)

