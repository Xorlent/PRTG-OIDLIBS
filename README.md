# PRTG-OIDLIBS
PRTG Custom OID Libraries (MIBs) and device templates for various devices  
## Installation
1. Download the desired device .ZIP file
2. Right-click the downloaded file, click Properties, and click "Unblock"
3. Extract the .ZIP to an empty directory
4. Copy the files into your PRTG installation directories (Don't worry if the ZIP does not contain one or two of the folders listed below.)  
   - Copy the contents of \snmplibs to the \snmplibs folder within your PRTG installation directory, usually C:\Program Files (x86)\Paessler Network Monitor
   - Copy the contents of \devicetemplates to the \devicetemplates folder within your PRTG installation directory, usually C:\Program Files (x86)\Paessler Network Monitor
   - Copy the contents of \lookups\custom to the \lookups\custom folder within your PRTG installation directory, usually C:\Program Files (x86)\Paessler Network Monitor
8. Restart PRTG or within the GUI go to Setup -> System Administration -> Administrative Tools and click "Go!" under "Load Lookups and File Lists"
## Using
### If the ZIP contained a \snmplibs folder
1. Create a device object in PRTG
2. Select "Add Sensor"
3. Search for and select "SNMP library"
4. Click the name of the imported custom library
### If the ZIP contained a \devicetemplates folder
1. Create a device object in PRTG
2. Select "Auto-Discovery" and choose "Run Auto-Discovery with Template"
3. Choose the name of the imported device template
