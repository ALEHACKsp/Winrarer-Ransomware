# WinrarRansomware

- Just for fun lulz
- Hope no one will use it for illegal stuff
- POC code


#What is this? :
- Ransomware
- Create rar archive with some listed extension and password with 32 bits long
- Delete all archived file after archive
- Reboot system
- Move all archived file to desktop
- Create list of archived file


#TODO : 
- I will quickly add Server files where the ransomware can send the key back to Server.But now it havent save key to anywhere.So that becareful when test it
- It will work with 7z
- It will work with Winzip


#Critical Process :
-Prevent user from ending process by taskmanager
-It will make process (run as administrator privilliges) become system process (examples : winlogon.exe) and cause bsod if user try end process by task manager
-Credit to napalm, _FIL73R_.

-System process : 

![alt tag](https://github.com/kuqadk3/WinrarRansomware/blob/master/img/systemprocess.PNG)

-BSOD (if user try to end process) :

![alt tag](https://github.com/kuqadk3/WinrarRansomware/blob/master/img/bosd.PNG)


#Feeling : 
![alt tag](https://github.com/kuqadk3/WinrarRansomware/blob/master/img/bloody_work.gif)
