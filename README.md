

--- 
    
### ❗・Important
 
- When you register a new account to play You will get banned after playing 1-3 games because you get Shadow Bans or HWID ban
- All these steps will help you get back to playing it, please read all steps before asking.
- Read step all 
- All archives and text are from the original UC, so it's not mine.
 
---   
 

## 🤓・ How To Use 
#### 1. First , you have to check your current hwid to compare it with the new ones:

- Open HWID Checker.bat
- Copy and paste results into notepad and save the file
 
---
### 2. Then clean trace files:

- Run "cleaner.bat"
---
### 3.Change your Disks IDs:

 - Start "HardDiskSerialNumberChanger"
 - Erase Serial and write again, ex: ASD1-515A
 - Change and Close
 - Restart your pc
---
### 4.Now you have to change your mac addresses:
 
- Start "MAC Address Changer"
- Select the adapter you use
- Click on generate a random mac
- Click on update mac address
---
### 5.And now you have to Change Hardware ids:

- Open the link to Command Prompt and type this commands:

```
cd [path to "HWID spoof" folder]
```
![NVIDIA_Share_DYOz9gH96h](https://user-images.githubusercontent.com/94861415/203697194-75663f87-e7ae-49db-a717-0d63a79a255d.gif)

### Then type to change UUID (replace X with a random character uppercase or lowercase or with a number)

- AMIDEWINx64.EXE /SU AUTO 
- AMIDEWINx64.EXE /BS XXXXXXXX
- AMIDEWINx64.EXE /CS XXXXXX
- AMIDEWINx64.EXE /SS XXXXXXXX
- AMIDEWINx64.EXE /PSN XXXXXXXXXXXXXXX

---

### 6.Type following commands to save your changes

- net stop winmgmt /y
- net start winmgmt /y
- sc stop winmgmt
- sc start winmgmt

---

### 7.Then modify some registers:

- Press win + r and type in "regedit" and press enter
- Follow the path: "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Cryptography"
- Open this website
- Generate a new GUID
- Copy and paste the new GUID into the "MachineGuid" key.
- Do the same thing with this path: "Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\IDConfigDB\Hardware Profiles\0001"


