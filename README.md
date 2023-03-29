# AM0N-Eye
AM0N-Eye is a compilation of a group of the most important scripts that were written specifically for Cobaltsetrike and the rest of the files such as de for modification in colors and images. All property rights reserved to the original developers. Just open the Cobaltsetrike.jar file and replace it with de and default.cna and resources The names of the projects that have been added. ScareCrow,CrossC2,CSSG-xor,InvokeCredentialPhisher,Registry-Recon,StayKit


![Screenshot from 2023-03-10 11-53-32](https://user-images.githubusercontent.com/121706460/226493992-1b6194b7-13a3-4ac5-bb3c-d473bbf0dd31.png)

<install>

chmod +x install.sh
__________________________________________________________________________________________________________________________________________________________
##PayloadGenerator

Generates every type of Stageless/Staged Payload based off a HTTP/HTTPS Listener
    
Creates /opt/amon-eye/Staged_Payloads, /opt/amon-eye/Stageless_Payloads
    
#Linux & MacOS C2 Server

A security framework for enterprises and Red Team personnel, supports AM0N-Eye penetration testing of other platforms (Linux / MacOS / ...), supports custom modules, and includes some commonly used penetration modules.


![Screenshot from 2023-03-09 13-47-25](https://user-images.githubusercontent.com/121706460/226558264-db460f06-92f1-445e-b428-80a13a69f487.png)

	
# Fake Alert update

to send toast notifications on behalf on an (installed) application or the computer itself. The user will be asked to supply credentials once they click on the notification toast. The second one is a AM0N-Eye module to launch the phishing attack on connected beacons and you can learn the types of victim's defense mechanisms and exploit this to issue an update alert or to take action

![Screenshot from 2023-02-21 02-42-37](https://user-images.githubusercontent.com/121706460/226552401-6666bc29-2b9b-4248-9056-faafe28af324.png)


#AV/EDR evasion

(AV/EDR evasion) is a payload creation framework for side loading (not injecting) into a legitimate Windows process (bypassing Application Whitelisting controls). Once the DLL loader is loaded into memory, it utilizes a technique to flush an EDR’s hook out of the system DLLs running in the process's memory. This works because we know the EDR’s hooks are placed when a process is spawned. (AV/EDR evasion) can target these DLLs and manipulate them in memory by using the API function VirtualProtect, which changes a section of a process’ memory permissions to a different value, specifically from Execute–Read to Read-Write-Execute.
	
![Screenshot from 2023-03-21 04-48-45](https://user-images.githubusercontent.com/121706460/226556701-11379ed8-66de-4303-9daf-aca85f78af85.png)
	
#shellcode obfuscatior
 
Generates beacon stageless shellcode with exposed exit method, additional formatting, encryption, encoding, compression, multiline output, etc
shellcode transforms are generally performed in descending menu order
Requirements:
The optional AES encryption option uses a python script in the /assets folder
Depends on the pycryptodome package to be installed to perform the AES encryption

![Screenshot from 2023-03-21 04-46-30](https://user-images.githubusercontent.com/121706460/226556899-c1253b00-8e08-469c-9a46-f1012b1f2795.png)


# Persistence threat _Menu
		
![Screenshot from Screencast 2023-03-22 08-14-28 mp4](https://user-images.githubusercontent.com/121706460/226905003-ff4a8f85-de5a-4ad1-840f-0a3f411db32c.png)
	
* (UserSchtasksPersist)

* (ServiceEXEPersist)

* (WMICEventPersist)

* (StartupGPOPersist)

* (RegistryPersist)

* (HKCURunKeyPSRegistryPersist)

    
##AVQuery

    Queries the Registry with powershell for all AV Installed on the target
    
    Quick and easy way to get the AV you are dealing with as an attacker
    
##checkmate request 
version of the checkmate request Web Delivery attack


    Stageless Web Delivery using checkmate.exe 
    
    Powerpick is used to spawn checkmate.exe to download the stageless payload on target and execute with rundll32.exe


##Curl-TLS  

simple web requests without establishing SOCKS PROXY. Example use case could be confirming outbound access to specific service before deploying a relay from [F-Secure's C3]


#AV/EDR Recon & EDR exact query
 
As a red-team practitioner, we are often using tools that attempt to fingerprint details about a compromised system, preferably in the most stealthy way possible. Some of our usual tooling for this started getting flagged by EDR products, due to the use of Windows CLI commands.
This aims to solve that problem by only probing the system using native registry queries, no CLI commands.


# BypassUAC-eventvwr
 
silentcleanup UAC bypass that bypasses "always notify" aka the highest UAC setting, even on Windows
