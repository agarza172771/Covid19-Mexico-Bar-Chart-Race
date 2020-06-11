# Covid19-Mexico-Bar-Chart-Race
This code is to show one way to made a animated bar chart (race) using Mexico's open dataset about Covid19

This repository was created in three modules, one to read the data directly from the Secretaria de Salud database, 
the second to clean the data and leave only what is necessary and the third to display the bar race graph. It should be 
noted that the data in the ./data folder is for reference only if you want to use it without  accessing the database 
on the web (or in case there is no access to such database). The data are updated
daily.

To run and generate the graph, you must first run module 1, then 2 and then 3. If you want to make changes to 
modules 2 and 3, with the data, it is important to observe where it will be done, given that You may get 
an error because module 2 seeks to read 2 files from ./data, but there are already others that were created.


Note: The data is obtained from the Secretary of Health.
Note: On June 10, 2020, the data could not be accessed.

Data: http://187.191.75.115/gobmx/salud/datos_abiertos
