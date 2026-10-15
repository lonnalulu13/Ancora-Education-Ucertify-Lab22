# Ancora-Education-Ucertify-Lab22
# Getting information about the TCP Ports

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=5]

## Objective of the Lab
In this lab, you will learn to get information about the TCP ports. 

The Transmission Control Protocol (TCP) establishes connections to recover packets that are lost during the transmission.

## Instructions
### STEP 1
On the taskbar, click the Start menu and then click Windows PowerShell to open the Windows PowerShell window.

### STEP 2
In the Windows PowerShell window, enter the following command to obtain information about the TCP ports:
```bash
Get-NetTCPConnection | Select-Object LocalPort,Remoteport
```
Where, 

Get-NetTCPConnection: It gets information about the current connection statistics. 

Select-Object LocalPort,Remoteport: It selects specified properties of an object. Here, the properties of the object are LocalPort and Remoteport.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
