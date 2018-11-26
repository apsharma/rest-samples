### OVERVIEW

The accompanying POSTMAN Collection shows how to specify a criteria and retrieve a user mapping report. There is an underlying assumption when creating the sample that there is only one Desktop Manager in the Tenant Organization.

### POSTMAN Collection Contents

This collection only has three REST API calls:

1. **Retrieve a filter (criterion) for fetching user mappings**.
2. **Retrieve Desktop Manager Id**. This is only a helper API call to retrieve the value for Desktop Manager Id.
3. **Retrieve user mappings for the specified criterion**. Results can be sorted using two uri parameters: sortCriteria and sortOrder.

#### Valid Values for Sort Criteria

1. domain
2. id
3. userName
4. vmName

#### Valid Values for Sort Order

1. ascending
2. descending