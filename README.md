# awsASGretirmentAutomation
This is used to help with aws retirments for ASGs that have small amounts of instances. 

This automation will:
1. Take Input for what ASG and what Instance to retire (terminate)
2. Call the AWS API to get the current size of the ASG
3. run a Script to do currentAsgDesiredSize +1
4. Increase the ASG to the NewDesiredSize
5. Wait for new instance to be in a healthy and inService state
6. Terminate instance that was specified and scale in 
