### OVERVIEW

This collection shows the REST APIs for submitting a job to Initialize various Reporting Jobs, monitoring the submitted job status and then downloading the successfully completed jobs.

### POSTMAN Collection Contents

The Collection has three API calls.

1. Initialize/Submit a Reporting Job by specifying the Job Name. Job Name is USER_EVENT_ALL in the sample POSTMAN Collection. An exhaustive list of job names is listed below. This API returns a jobId in the response.
2. Monitor the Reporting Job Status using a jobId and
3. Download the Report using the jobId.



	The values for job Names are: 

	    USER_EVENT("user_event"),
	    VM_MAPPING("vm_mapping"),
	    USER_MAPPING("user_mapping"),
	    USER_EVENT_ALL("user_event_all"),
	    POOL_USER_ACTIVITY_ALL("pool_user_activity_all"),
	    POOL_USER_ACTIVITY("pool_user_activity"),
	    POOL_SYS_ACTIVITY_ALL("pool_sys_activity_all"),
	    POOL_SYS_ACTIVITY("pool_sys_activity"),
	    SYS_ACTIVITY_ALL("sys_activity_all"),
	    SYS_ACTIVITY("sys_activity")
	    VM_COMPONENT_VERSION("vm_component_version")
	