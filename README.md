<img src="https://github.com/yasser-alghamdi/winterfell/blob/master/winterfell_logo.jpg" title="winterfell" height="15%" width="35%">

# Winterfell-Hunt
Winterfell-Hunt is a python script to help performing auto hunting looking for malicious activities in windows OS based on collected data by winterfell collection package https://github.com/yasser-alghamdi/winterfell-collection.

## Winterfell Package
Winterfell contains various batch scripts which are `Winterfell-System.bat` `Winterfell-Forensics.bat` `Winterfell-Network.bat` `Winterfell-Registry.bat` `Winterfell-Presistance.bat` `Winterfell-Malware.bat` `Winterfell-Web.bat` `Winterfell-Logs.bat` and `Winterfell-Location.bat`
Most of artifacts are automatically get parsed to ease the investigation by using group of available parsers. In additions, winterfell also collects most of forensics raw data to be processed through any type of fronsics analysis tools such as Magnet Axiom such as `Amcache.hve` `SRUDB.dat` `OBJECTS.DATA` `UsrClass.dat` `NTUSER.DAT` `Windows Logs` `Recent Files` etc.

```
Winterfell-System.bat

USERNAME AND SID INFORMATION, USER/SESSION INFORMATION, SYSTEM INFORMATION, DOMAIN TRUSTED SIDs, ENVIRONMENT SETTINGS, DIRECTORY LISTING, SEURITY POLICY, AUDIT POLICY, GROUP POLICY, SECURITY PRODUCT INFORMATION, DRIVERS INFORMATION, SHADOWS FILES INFORMATION, HANDLES INFORMATION, and DLLS INFORMATION 
```

```
Winterfell-Forensics.bat

USERS TIMELINE, JUMP LIST, PREFETCH FILES, AMCACHE HIVE, SRUDB HIVE, SHELLBAGS FILES, NTFS USNJRNL FILE, WMI PERSISTANCE, RECENT FILES, SYSTEM CONFIGURATION, ALTERNATIVE STREAM FILES, BMC CACHE, RECYCLE BIN FILES, USRCLASS HIVE, and NTUSER HIVE 
```

```
Winterfell-Network.bat

NETWORK INFORMATION, SHARING INFORMATION, and FIREWALL CONFIGURATION
```

```
Winterfell-Registry.bat

REGISTRY INFORMATION, and USUSPICIOUS REGISTRY KEY VALUES INFORMATION
```

```
Winterfell-Presistance.bat

SCHEDULED TASKS, SERVICES, RUNNING PROCESSES, and AUTORUNS INFORMATION
```

```
Winterfell-Malware.bat

LOKI CHECK 
```

```
Winterfell-Web.bat

BROWSING URLS HISTORY, and CACHE FILES 
```

```
Winterfell-Logs.bat

WINDOWS LOG FILES, POWERSHELL HISTORY, POWERSHELL LOGS FILES, SCHEDULE TASK LOG FILE, SECURITY LOG FILE, WINDOWS REMOTE LOG FILE, SMB LOGS FILES, and IIS LOGS Files 
```

```
Winterfell-Location.bat

MALICIOUS LOCATIONS
```

## Winterfell Usage
Make sure to keep all scripts, and tools folder under Winterfell folder. you can run the package by execute `All-Winterfell-Scripts.bat` through administrator command prompt `cmd.exe` by nevigate to Winterfell folder. the script has the capability to identify the folder location so you can place the folder anywhere in Windows OS.

```
	██╗    ██╗██╗███╗   ██╗████████╗███████╗██████╗ ███████╗███████╗██╗     ██╗     
	██║    ██║██║████╗  ██║╚══██╔══╝██╔════╝██╔══██╗██╔════╝██╔════╝██║     ██║     
	██║ █╗ ██║██║██╔██╗ ██║   ██║   █████╗  ██████╔╝█████╗  █████╗  ██║     ██║     
	██║███╗██║██║██║╚██╗██║   ██║   ██╔══╝  ██╔══██╗██╔══╝  ██╔══╝  ██║     ██║     
	╚███╔███╔╝██║██║ ╚████║   ██║   ███████╗██║  ██║██║     ███████╗███████╗███████╗
	╚══╝╚══╝ ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚══════╝╚══════╝╚══════╝	
	"+-------------------------------------------------------------------------+
	"| Winterfell is a windows batch script to collect windows forensics       |
	"| data and perform threat hunting for Incident Response Investigation.    |
	"| Created by yAsSeR Al-Ghamdi.                                            |
	"+-------------------------------------------------------------------------+

----------------------------------------------------
Command:
C:\Users\yasser\Desktop\winterfell-master>All-Winterfell-Scripts.bat
```

## Demo of Execution
below is to domenstrate a demo of execution of Winterfell package as the following:

**Run Winterfell Package**
![Run_Winterfell](https://github.com/yasser-alghamdi/winterfell/blob/master/winterfell.gif?raw=true)

## References

https://ericzimmerman.github.io/#!index.md

https://www.nirsoft.net/utils/
