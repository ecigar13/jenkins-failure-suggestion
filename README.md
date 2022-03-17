# jenkins-failure-suggestion
Get the log of the error, then suggest solution to user. 

## Motivation
In normal businesses, identity management and access management are not important, so Jenkins is only used for building/deploying. In financial sector, IAM has to conform to audit standard. This leads to the fragmentation of three areas:
- Identity
- Authentication
- Authorization

This makes it hard to onboard application teams to Jenkins. Besides, engineers rarely touch DevOps tools. Quite a few principals do not know how to debug. This system aims to fix this.

##