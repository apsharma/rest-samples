### OVERVIEW

Editing a static pool requires specifying the final or desired state of the pool for a particular pool. It is necessary that the desired state is defined correctly - with all necessary attributes. The best way to ensure correctness of the desired state is to retrieve the intial state and make changes to attributes. For e.g. - Pool Provisioning is likely fail or produce unexpected results, in the absence or incompleteness of attributes such as DtDesktopModel, DtGoldPattern or DtPoolPolicy, etc.

This POSTMAN collection shows the API calls to fetch these attibutes needed to edit a Pool and then eventually invoke the API to update the pool. 

In the attached sample, the pool initially has a size 1. The attribute `requestedSize` is incremented to `2` to change the pool size from 1 to 2.

### POSTMAN COLLECTION CONTENTS

1. Login as a Tenant Administrator
2. Get all Pools on the Tenant.
3. Get pool attributes using pool Id.
4. Edit Pool with updated values.