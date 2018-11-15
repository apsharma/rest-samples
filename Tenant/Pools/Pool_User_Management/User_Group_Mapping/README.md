README will describe API calls related to mapping/un-mapping users to Desktops or Assignments.

The POSTMAN collection has API calls for the following:

1. Login to the Tenant
2. Get all existing Assignments.
3. Fetch Usergroups in the Tenant Active Directory.
4. Find the id for a particular usergroup.
5. Get usergroups mapped to an assignment.
6. Get users mapped to an assignment.
7. Unassign usergroups to assignment.
8. Assign usergroups to assignment.


#### ASSUMPTIONS
For testing or demo purposes, we assume that the Tenant environment contains an assignment with name *vdi* and an Active Directory usergroup with name *portalusers*. These values can be changed in the Tests tab of Get-Pools and Get-User-Groups API calls.


