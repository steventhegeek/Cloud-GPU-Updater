This script is made to run on Paperspace P4000, P5000, P6000, AWS G3.4xLarge and Azure NV6 machines.

This script checks NVIDIA.com for updates, and will download and install graphics drivers including
setting NVIDIA-SMI to the correct value on required GPUs.

Supported Operating Systems

Windows 10
Windows Server 2016
Windows Server 2019

Supported GPUs
AWS G3.4xLarge (Tesla M60)  
AWS G2.2xLarge (GRID K520)  
AWS G4dn.xLarge (Tesla T4 with vGaming driver)  
Azure NV6 (Tesla M60)  
Paperspace P4000 (Quadro P4000)  
Paperspace P5000 (Quadro P5000)  
Paperspace P6000 (Quadro P6000)  
Google P100 VW (Tesla P100 with Virtual Workstation Driver) 
Google P4 VW (Tesla P4 with Virtual Workstation Driver)  
Google T4 VW (Tesla T4 with Virtual Workstation Driver)  

Instructions: 
1. Download https://github.com/steventhegeek/Cloud-GPU-Updater/archive/master.zip
2. Extract the folder, right click "GPU Updater Tool.ps1" and run with Powershell - if the script immediately closes, right click and click edit, then the green play button in the Powershell ISE toolbar.

Q&A - Why aren't Windows 8.1 or Server 2012 supported

Windows 8.1 and Server 2012
There is no need currently.

