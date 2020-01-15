# MariaDB_Node-red
This flow on Node-red help you for example: Write down your inventory from your cellphone. No pen. No paper. No rewrite.

To use this flow you will need Node-Red. The flow cointains 4 nodes: text input, function, Database node and msg.payload.

********************************************************DOWNLOAD NODES!!******************************************************************
You will need to download some nodes like text input and Database node. Firts, go to 'MANAGE PALETTE' that its in right upper corner. Then,
click on the tab 'INSTALL' and search for 'NODE-RED-DASHBOARD' to 'Text input' and do it the same for 'Database node' that in this case you
will looking for 'NODE-RED-NODE-MYSQL'

******************************************************* FUNCTION NODE ********************************************************************
QUERY

It cointains the next text:
 
msg.topic = "INSERT INTO `node-red`.`inventario` (`nombre`) VALUES ('"+msg.payload+"');";
 
it means 'insert what I put on 'Text input' in the column 'nombre' inside table 'inventario' from Database 'node-red'.
 
THIS IS VERY IMPORTANT TO DO THE CONECCTION BETWEEN NODE-RED AND YOUR MYSQL
*******************************************************************************************************************************************


 
 
 

