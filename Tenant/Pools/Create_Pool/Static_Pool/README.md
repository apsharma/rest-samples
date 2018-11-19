### OVERVIEW

Creating a static pool requires specifying certain attributes such as Image Name, Desktop Model, Tenant Organization along with other pool specific attributes such as Pool Policy, Supported Protocols. The POSTMAN collection shows the API calls to fetch these attibutes needed to create a Pool and then eventually make the API call to create the pool. As details such as Images, Desktop Model are retrieved each attribute is stored in variable that is eventually referred to the Create Pool request body.

### POSTMAN COLLECTION CONTENTS

1. Login as a Tenant Administrator
2. Get Data Center details
3. Retrieve the Tenant Desktop Manager Id.
4. Fetch available or existing Gold Patterns.
5. Get Tenant Organization details.
6. Get Enabled Desktop Model definitions
7. Create Pool.