# UR-Robot-coms-with-PLCnext
This Sample Project sets set all the available communications (Read/Write) from the PLCnext to the UR Robot

The Scope of this Project was to take the UR Robot ProfiNet Example that was originally created and proven with
	the Siemens' PLC and convert all the data for use with the PLCnext Controller.

This Program is not for actually controlling the UR Robot because there are so many uses and needs.  The intent
	was to set all the available communications (Read/Write) from the PLCnext to the UR Robot to save the programmer
	many, many hours that would be required to perform these coms.

This Program Example Creates the Necessary Input/Output Interfaces between a
	UR Robot with ProfiNet Interface and the PLCnext (in this case, a AXC F 2152).

This Interface, althought not tested, should also work for all of the PLCnext Hardware Platforms,
	as the Interface is all Done over the ProfiNet Network, which is avaiable for all the PLCnext Controllers.

This Project was layed out so that it could easily be imported into another PLCnext Engineer Project.
The Minimum version: PLCnext Engineer 2023.3.

A necessary component for the ProfiNet Connection is the GSDML file.
The File is included with the Project Example, but also the GSD-V2.31-UR Zipped Files is also included as reference.

If background information is required, the entire UR Robot Definitions and ProfiNet examples and base code
	can be viewed and understood from thr UR Robot WebSite.
	The UR Website is: www.universal-robots.com
	In the Main Search Bar, type in 'Profinet How-To' and several listings will appear.
	This project used the 'Profinet How-To Guide CB3'.
	The GSDML File located here (and also included) is the Correct File 'GSDML-V2.31-UR.zip).
	Please note that if the GSML file that has the words 'ProfiSafe' is NOT the correct File.. Do not use it.
