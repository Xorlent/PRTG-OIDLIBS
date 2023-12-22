# PRTG-OIDLIBS
PRTG Custom OID Libraries (MIBs) for various devices  
## Installation
1. Download the desired device .ZIP file
2. Right-click the downloaded file, click Properties, and click "Unblock"
3. Extract the .ZIP to an empty directory
4. Copy the contents of /snmplibs to the /snmplibs folder within your PRTG installation directory, usually C:\Program Files (x86)\Paessler Network Monitor
5. Copy the contents of /lookups/custom to the /lookups/custom folder within your PRTG installation directory, usually C:\Program Files (x86)\Paessler Network Monitor
   - Note: Don't worry if the ZIP does not contain a /lookups folder.  For some devices lookup overlay files are not necessary.
7. Restart PRTG or within the GUI go to Setup -> System Administration -> Administrative Tools and clicking "Go!" under "Load Lookups and File Lists"
## Using
1. Create a device object in PRTG
2. Select "Add Sensor"
3. Search for and select "SNMP library"
4. Click the name of the imported custom library
