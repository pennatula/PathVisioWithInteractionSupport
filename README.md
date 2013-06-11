PathVisioWithInteractionSupport
===============================

This is a temporary version of the PathVisio (http://www.pathvisio.org/) application which works with the new 
interaction annotation database. The annotation database can be created using the code from https://github.com/pennatula/InteractionDB.git.

To test this version download the entire repository.

Windows Users
--------------
Run the PathVisio program by clicking on the pathvisio.bat file.

Linux/Mac OS Users
-------------------
Run the PathVisio program by running the pathvisio.sh file from the terminal.

1) Install the BridgeDbConfig plugin.

  * Click Plugins -> Install local plugins -> Browse 
  * Select the folder plugins.
  * Click Start
  * Check the box next to BridgeDbcConfig.jar
  * Click OK
  
On succesful installation a pop up box pops up saying so and you can check whether the plugin was properly installed
using Plugins -> Plugin Manager in the tab installed.

2) Load the interaction annotation database.

  * Click Data -> Idenitifier Mapping Setup... -> Add 
  * Click on Browse -> Chose the interactions_20130610.bridge file -> Open
  * Click Ok
  * Click OK

3) Open the test pathway

  * Click File -> Open
  * Select test.gpml
  * Click Open
  
Please go through the testing procedure outlined below, it will take a minute, and report any problems encountered as 
issues.

Testing Procedure
=================

Click on the first interaction. Click on the backpage tab

You should see the interaction annotated with the identifier 10003 from Rhea and crossrefernces to BioCyc, 
Enzyme Nomenclature, Rhea, and Kegg Reaction.

Now Click on the second interaction and the information in the backpage should now change to identifier R02938 
from Kegg Reaction and the cross references from the same databases as in the first interaction.

Many Thanks!
