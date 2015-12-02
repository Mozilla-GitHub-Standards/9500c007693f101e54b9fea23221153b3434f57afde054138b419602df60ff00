Script is to be used to perform various operations against Taskcluster API.

Configs can be served two ways:
a) via json config file
b) env vars: TASKCLUSTER_CLIENT_ID, TASKCLUSTER_ACCESS_TOKEN, TASKCLUSTER_CERTIFICATE

Usage example following Pypi installation:
tctalker --verbose --conf config.json report_completed $taskid1 $taskid2 [...]
