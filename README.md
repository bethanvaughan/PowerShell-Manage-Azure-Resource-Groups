# PowerShell-Manage-Azure-Resource-Groups

This Repo contains 4 functions separated into 3 files. Each function manages an aspect of Azure Resource Groups.

Function 1: this function can be used to create a new Resource Group in Azure.
Function 2: this function can be used to update an aspect of a preexisting Resource Group in Azure, for example it's tags or its name. 
Function 3: this function can be used to delete a preexisting Resource Group in Azure.
Function 4: this function can be used to call one of the 3 functions above. 

The functions have each been designed interactively and save the input of the user to call 1 of the functions depending on the input. 

Note: the functions ideally should be in the same file as function 4, the 'Main' function, lists all 3 as options. However, I have separated them into 3 files in this repo for clarity. 
