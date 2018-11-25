### OVERVIEW

This POSTMAN Collection has the REST APIs showcasing how to Disconnect and Logoff users with Active Sessions to Desktops. In order to disconnect or logoff users, tenant administrator user will require the Id for the Active Session.

The collection also shows the API call to fetch the Active Session id and stores it into a variable taActiveSessionId. The retrieved session id value is then used for the subsequent Logoff and Disconnect API invocations. Since these are sample invocations, there is an assumption that the pool has only one desktop with an active user session.

### POSTMAN Collection Contents

The Collection has four REST API calls for:

1. Login as Tenant Administrator to retrieve an Authorization and a x-dt-csrf-header.
2. Fetch all active sessions using the Pool Id. The Pool Id is specified as part of the Request Body.
3. Logoff a user with an Active Session. Session Id is specified as part of Request Body.
4. Disconnect a user's Active Session. Session Id is specified as part of Request Body.