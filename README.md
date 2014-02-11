## Generate DFXML with EnCase  ##
-------------------------------

This EnScript was developed to generate Digital Forensics XML from EnCase v6. It has only been tested with NTFS file system.  

**Installation**
-------------------------

Copy the EnScript in your EnCase Folder (i.e: C:\Program Files\EnCase6\EnScript)


**How to use it**
-------------------------

1) Create a new case and load your E01 image in EnCase.

2) Before generating the DFXML output, you need to set the time zone to UTC for the entire case with the "Case Time Settings" dialog. 

	First, go in the "home" tab and right click on your case. 
	Then select the option "Modify time settings". 
	
![My image](https://raw.github.com/Sebastienbr/DFXML-EnCase/master/img/EnCaseModifyTimeSettings.png)
	
	Then, unselect "Account for seasonal Daylight Saving Time" and select the UTC time zone.
	

![My image](https://raw.github.com/Sebastienbr/DFXML-EnCase/master/img/EnCaseTimeZoneConfig.png)

3) Double click on the EnScript to run it. 

4) Data will be exported in the EnCase export folder (i.e: Default is C:\Program Files\EnCase6\Export).

![My image](https://raw.github.com/Sebastienbr/DFXML-EnCase/master/img/DFXMLOutput.png)


