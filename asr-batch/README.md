Variables: 
- folder-id
- service account key
- s3 bucket and prefixes

1) Connect to bucket > Error if not found
2) List inbound folder
3) Check if already in process or has been processed
4) Process
5) Create request for each object in inbound folder
6) Register status of object (being processed and process id; processed and result neet to be downloaded)
7) Save processing errors
8) Restart