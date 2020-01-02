### OVERVIEW

Deleting a static pool is a two step process. A static/dedicated pool cannot be deleted until the pool size is zero (0). Hence, the desktops in the pool need to be deleted prior to deleting the pool itself.

This POSTMAN collection shows the API calls to delete a desktop in a static/dedicated pool and delete a pool. Since there are POSTMAN collections in the repository that cover how to fetch pool Id and pattern Id for a desktop in the pool, the collection is built with an assumption that the tenant administrator user invoking the API knows the pattern Id for the desktop and pool Id for the desktop pool. 

Pattern Id for a desktop in a pool is a unique identifier for the desktop, in format - S.1001.4.1. Deleting a desktop (using the pattern id) will return a task object - with attributes type, percentageComplete, status. These attributes indicate the progress of delete desktop pool task.


### POSTMAN COLLECTION CONTENTS

1. Delete Static Pattern (or Desktop) in a Pool.
2. Delete Desktop Pool.