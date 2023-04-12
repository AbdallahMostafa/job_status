# A NodeJS App to play around with short polling by provind two end points 
# Submit a job
```
POST /submit
Request {}
Response
[
    jobId
]
```
# Check Job Status
```
Get /checkStatus?jobId=jobId
Response 
JobStatus: 50%
```