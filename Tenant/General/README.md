### OVERVIEW 
This collection provides details for Tenant APIs that are used across the board.

### POSTMAN Collection Contents
1. Login as Tenant Administrator

	All REST API methods are authenticated. The login API call returns an Authorization header as well as a CSRF header(x-dt-csrf-header). The Authorization header is needed for all API calls (GET, PUT, POST, DELETE). In addition, the CSRF header is required for PUT, POST and DELETE operations.
	
2. Get values for the various timeout settings.

