Opdracht Rapport – Azure Virtuele Machine en File Share

Student: Serhan Köylü
Datum: 28 februari 2026
Project Onderwerp: Azure Virtuele Machine Implementatie en Azure File Share Gebruik

Stap 1 – Azure-account aanmaken
Een gratis Azure proefaccount is aangemaakt via Azure Portal
![Azure11](https://github.com/Serhankyl/AzureVM_deneme/blob/main/Azure11.png?raw=true)

Stap 2 – Resource Group aanmaken

Azure Portal → Resource Groups → + Create
Resource Group Naam: SerhanKoylu_RG
Locatie: West Europe
![Azure Resource Groups](https://github.com/Serhankyl/AzureVM_deneme/blob/main/Azure_Resource_Groups.png?raw=true)

Stap 3 – Virtuele Machine aanmaken

Azure Portal → Virtual Machines → + Create
Resource Group: SerhanKoylu_RG
VM Naam: SerhanKoyluVM
Regio: West Europe
Image: Windows Server 2025 Datacenter
Grootte: Standard_B1s (rekening houdend met proefcredits)
Administrator Gebruikersnaam & Wachtwoord: ingesteld
Disks: Standaard, OS-schijf Premium SSD
Networking:
Standaard virtueel netwerk en subnet gebruikt
Public IP toegewezen
Inkomende poort: RDP (3389) geselecteerd
![Azure Virtual Machines](https://github.com/Serhankyl/AzureVM_deneme/blob/main/Azure_Virtual%20Machines.png?raw=true)

Stap 4 – Verbinden met Virtuele Machine (RDP)
Virtuele Machine geselecteerd → Connect → RDP
RDP-bestand gedownload en geopend
Inloggen met administrator gebruikersnaam en wachtwoord
![Azure RDP](https://github.com/Serhankyl/AzureVM_deneme/blob/main/Azure_RDP.png?raw=true)

Stap 5 – Azure File Share aanmaken en verbinden
Azure Portal → Storage Accounts → + Create
Storage Account Naam: SerhanKoyluStorage
File Share aangemaakt: tasksharing
Verbonden met Windows VM als Z: schijf (via PowerShell of Map Network Drive)
Testbestand geüpload en toegang gecontroleerd
![Azure File Share](https://github.com/Serhankyl/AzureVM_deneme/blob/main/Azure_File%20_Share.png?raw=true)

![Azure Storage Accounts](https://github.com/Serhankyl/AzureVM_deneme/blob/main/Azure_Storage_Accounts.png?raw=true)

