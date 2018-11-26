### OVERVIEW

This POSTMAN Collection has the REST APIs showcasing how to Disconnect and Logoff users with Active Sessions to Desktops. In order to disconnect or logoff users, tenant administrator user will require the Id for the Active Session. In case there are no active sessions when invoking the Active_Sessions API, POSTMAN will show an error because the associated Tests script will fail.

The collection has an API call to fetch the Active Session Id. The value is stored into a variable userSessionId. The retrieved session id value is then used for the subsequent Logoff and Disconnect API invocations. The API samples were created with an assumption that the pool has only one desktop with an active user session. (See the Tests tab in POSTMAN)

### POSTMAN Collection Contents

The Collection has four REST API calls for:

1. **Login as Tenant Administrator** to retrieve an Authorization and a x-dt-csrf-header.
2. **Fetch all active sessions** using the Pool Id. The Pool Id is specified as part of the Request Body. It can either be set in Request Body or initialized by invoking the API Get_Pools in the Map Usergroup to Pool.
3. **Logoff a user** with an Active Session. Session Id is specified as part of Request Body.
4. **Disconnect a user**'s Active Session. Session Id is specified as part of Request Body.