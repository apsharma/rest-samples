### OVERVIEW 
This collection provides details for Tenant APIs that are used across the board.

### POSTMAN Collection Contents
1. Login as Tenant Administrator

	All REST API methods are authenticated. The login API call returns an Authorization header as well as a CSRF header(x-dt-csrf-header). The Authorization header is needed for all API calls (GET, PUT, POST, DELETE). In addition, the CSRF header is required for PUT, POST and DELETE operations.
	
2. Get values for the various timeout settings.

3. Get Capacity Usage Details

	This API returns Service Capacity Usage aggregated by Data Center Id and Desktop Manager Id. The Data Center Id and Desktop Manager Id can also be retrieved using API calls. Those are covered in the [Tenant-Create-Pool-Static](https://github.com/apsharma/rest-samples/tree/master/Tenant/Pools/Create_Pool/Static_Pool) POSTMAN collection.