### OVERVIEW

The accompanying POSTMAN Collection shows how to specify a criteria and retrieve a Virtual Machine and User Mapping report. There is an underlying assumption when creating the sample that there is only one Desktop Manager in the Tenant Organization.

### POSTMAN Collection Contents

This collection only has three REST API calls:

1. **Retrieve a filter (criterion) for fetching details**.
2. **Retrieve vm-user mapping details for the specified criterion**. This is only a helper API call to retrieve the value for Desktop Manager Id.
3. **Retrieve vm-user mappings for the specified criterion**. The sample API call fetches results using the Tenant Desktop Manager and is sent across in the Request Body. Results can be sorted using two uri parameters: sortCriteria and sortOrder.

#### Valid Values for Sort Criteria

1. poolName
2. vmName
3. desktopManagerId

#### Valid Values for Sort Order

1. ascending
2. descending