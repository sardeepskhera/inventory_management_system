# inventory_management_system
An object-oriented C# application to do the above inventory warehouse processing. Each of the six warehouses is treated as an individual object. 

A wholesale distributor has six warehouses (Atlanta, Baltimore, Chicago, Denver, Ely and Fargo) and sells five different items 
(identified by part number: 102, 215, 410, 525 and 711). Each warehouse may stock any or all of the five items. 
The company buys and sells these items constantly. Company transaction records contain a transaction code (‘P’ for a purchase or ‘S’ for a sale) 
followed by an item number and the quantity  (bought or sold).


In the beginning of the program, the status data file (Inventory.txt) is read and an object for each warehouse created. The Inventory.txt data file is
in the following order: the first line is the Atlanta  warehouse, the second line is the Baltimore warehouse, third Chicago, then Denver, Ely and Fargo.
After the objects are created, the transactions data file (Transactions.txt) are read and processed.The objects are updated as the transaction records are 
read and processed.
