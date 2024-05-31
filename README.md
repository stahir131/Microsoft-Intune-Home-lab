<b><p align="center">Microsoft Intune Homelab</p></b>
Microsoft Intune is a cloud-based endpoint management solution. It manages user access to organizational resources and simplifies app and device management across your many devices, including mobile devices, desktop computers, and virtual endpoints.<br />

<b>Windows Autopilot</b><br />
Windows Autopilot is a cloud-native service that sets up and pre-configures devices, getting them ready for use. It can also reset and repurpose existing devices.

<b>Objectives of this Lab</b><br />
This is just a simple home lab to practice and document some Intune skills I'm currently learning. I intend to grow this lab as I learn more skills. Below is a simple network illustration of my homelab.
<br />
![Screenshot 2024-05-26 214133](https://github.com/stahir131/Microsoft-Intune-Home-lab/assets/64047385/85cd01d1-10e3-4337-97e4-40b9d70157f5)

<b>Environment used
</b><br />
- Microsoft Tenant: I created my tenant as deenetch.onmicrosoft.com.
- Required license is Microsoft Intune Plan1: There are other licenses you can use like Business Premium, 365 E5, E3 and so on
- Users and devices to be Intune-joined.<br />

Microsoft will set up a <b>.onmicrosoft.com</b> tenant for you if you do a one month trial version of Microsoft Business Premium [here](https://signup.microsoft.com/get-started/signup?products=53e11149-82f9-4bca-a7f2-8f72592e4f03&mproducts=CFQ7TTC0LCHC:0003&fmproducts=CFQ7TTC0LCHC:0003&culture=en-us&country=us&ali=1) or any other Intune-eligible licenses. A credit card is needed and just ensure to cancel your subscription before 29 days<br />
- Users and devices to be Intune-joined<br />
With this trial I have 25 Business Premium licenses so I created 4 users(1,2,3,4) with 1 admin user.
![Screenshot 2024-05-26 214950](https://github.com/stahir131/Microsoft-Intune-Home-lab/assets/64047385/be72310a-d912-4e56-aa72-4b2a7dfb8f5a)

<b>Devices:</b><br />I have created three windows 10 virtual machines on the Hyper-V host named
Admin PC, HR-PC and ENG. LT shown below<br />
![Screenshot 2024-05-26 215542](https://github.com/stahir131/Microsoft-Intune-Home-lab/assets/64047385/684ee9ef-2ee7-4076-8248-7f55a9c55de1)<br />


<b>Creating Deployment profile</b><br />
Autopilot deployment profiles are used to configure the Autopilot devices. Up to 350 profiles can be created per tenant. Simply put, Windows Autopilot deployment profiles lets you customize the out-of-box experience for your devices.

<b>Steps</b><br />
Intune admin center -> Devices -> Windows -> Windows enrollment -> Deployment Profiles -> Create Profiles> Give it a name

![Screenshot 2024-05-26 220349](https://github.com/stahir131/Microsoft-Intune-Home-lab/assets/64047385/d6ead02e-b6d1-473a-9c98-0f7c385652a1)

<b></b><br />
