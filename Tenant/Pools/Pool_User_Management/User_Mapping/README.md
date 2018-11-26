### OVERVIEW

README will describe API calls related to mapping/un-mapping users to Desktops. 


### POSTMAN COLLECTION Contents

The POSTMAN collection has API calls for the following:

1. Login to the Tenant. 
2. Get all existing Assignments or Pools. This API call retrieves the pool Id for a pool with name vdi in a variable **taDesktopPoolId**, in the POSTMAN Collection.
3. Fetch Id for User using the username.
4. Find user details from the userId. The API call retrieves and saves the value for user id in a variable, **taUserId**, in the POSTMAN Collection.
5. Get virtual machines in a Desktop Pool using **taDesktopPoolId**. The API call then retrieves the Desktop Pattern Id for *vdi0000* from the response in a variable, **taDesktopPatternId**.
6. Retrieve user-desktop mappings using the **taDesktopPoolId**.
7. Assign user to desktop using **taDesktopPatternId** and **taUserId**.
8. Unassign user from desktop.


#### ASSUMPTIONS
For the purposes of the attached sample collection, we made the following assumptions: 

1. the Tenant environment contains an assignment with name *vdi*.
2. The assignment or pool with name *vdi* contains a Desktop with id *vdi0000*.
2. Active Directory has a usergroup with name *portalusers*. 

These values can be changed in the Tests tab of Get-Pools and Get-User-Groups API calls, if necessary.
