# openDLP Virtual machine set up
https://code.google.com/archive/p/opendlp/
Current Version: 0.5.1 released 2012.08.27

"Given appropriate Windows, UNIX, MySQL, or MSSQL credentials, OpenDLP can simultaneously identify sensitive data at rest on hundreds or thousands of Microsoft Windows systems, UNIX systems, MySQL databases, or MSSQL databases from a centralized web application."

# Install Steps
## Download all of the 7zip files. Store them in one folder. 
- OpenDLP-0.5.1-VM.7z.007 	
- OpenDLP-0.5.1-VM.7z.006 	
- OpenDLP-0.5.1-VM.7z.005 	
- OpenDLP-0.5.1-VM.7z.004 	
- OpenDLP-0.5.1-VM.7z.003 	
- OpenDLP-0.5.1-VM.7z.002 	
- OpenDLP-0.5.1-VM.7z.001 	

## Extract
- Download 7zip in windows and click on the first file OpenDLP-0.5.1-VM.7z.007 to extract the ova file.

- in Ubuntu, install 7z and run the following command: 7za e OpenDLP-0.5.1-VM.7z.001
- Import OVA file to virtual box
- If you want to connect to OpenDLP from the host machine, configure networkign in "Bridge" mode, in you want a private network, set up a NAT Network.
- From your host machine, test that you can connect to the OpenDLP VM.
- Connect to VM - username: opendlp  passwd: opendlp
- scp sc.exe opendlp@ip:/var/www/OpenDLP/bin/ (you will need to downloa the sc.exe file)


## connect to the UI and configure
- from the host machine, visit IP of OpenDLP VM
- import cert (no passwd needed during import)
- connect back to https://ip-of-vm-/OpenDLP/index.html
- username: dlpuser, passwd: OpenDLP

# Download trial Windows 7 image
- here is a useful link https://getproductkey.net/download-windows-7-iso-from-microsoft/
- Download windows7 iso and create a Virtual Machine



