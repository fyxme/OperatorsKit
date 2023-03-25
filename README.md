# OperatorsKit
This repository contains a collection of tools that integrate with Cobalt Strike through Beacon Object Files (BOFs).  

## Kit content
The following tools are currently in the operators' kit: 

|Name|Decription|
|----|----------|
|**[BlindEventlog](KIT/BlindEventlog)**|Blind Eventlog by suspending its threads.|
|**[DllEnvHijacking](KIT/DllEnvHijacking)**|BOF implementation of DLL environment hijacking published by [Wietze](https://www.wietzebeukema.nl/blog/save-the-environment-variables) |
|**[FindDotnet](KIT/FindDotnet)**|Find processes that most likely have .NET loaded.|
|**[FindHandle](KIT/FindHandle)**|Find "process" and "thread" handle types between processes.|
|**[FindLib](KIT/FindLib)**|Find loaded module(s) in remote process(es).|
|**[FindRWX](KIT/FindRWX)**|Find RWX memory regions in a target process.|
|**[FindSysmon](KIT/FindSysmon)**|Verify if Sysmon is running through enumerating Minifilter drivers and checking the registry.|
|**[HideFile](KIT/HideFile)**|Hide file or directory by setting it's attributes to systemfile + hidden.|
|**[LoadLib](KIT/LoadLib)**|Load a on disk present DLL via RtlRemoteCall API in a remote process.|
|**[PSremote](KIT/PSremote)**|List all running processes on a remote host.|
|**[SilenceSysmon](KIT/SilenceSysmon)**|Silence the Sysmon service by patching its capability to write ETW events to the log.|
|**[TaskScheduler](KIT/TaskScheduler)**|Create or delete a scheduled task.|

## Usage
Each individual tool has its own README file with usage information and compile instructions. 

## Credits
A round of virtual applause to [reenz0h](https://twitter.com/SEKTOR7net). Lots of tools in this kit are based on his code examples from the Malware Development and Windows Evasion courses. I highly recommend purchasing them!

Furthermore, some code from the [C2-Tool-Collection](https://github.com/outflanknl/C2-Tool-Collection) project is copied to neatly print beacon output. 
