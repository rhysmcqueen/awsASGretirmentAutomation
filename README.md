# awsASGretirmentAutomation
This is used to help with aws retirments for ASGs that have small amounts of instances. 
System manage Automation name: RetirmentAutomation
Account: 
https://us-east-1.console.aws.amazon.com/systems-manager/documents/RetirmentAutomation/description?region=us-east-1
This automation will:
1. Take Input for what ASG and what Instance to retire (terminate)
2. Call the AWS API to get the current size of the ASG
3. run a Script to do currentAsgDesiredSize +1
4. Increase the ASG to the NewDesiredSize
5. Wait for new instance to be in a healthy and inService state
6. Terminate instance that was specified and scale in 
![image](https://user-images.githubusercontent.com/46686598/180082486-0a3a2eb3-cc3b-4230-b0ee-5499fd301491.png)
![image](https://user-images.githubusercontent.com/46686598/180082517-033baed9-3aa1-4b2c-a948-121ff089a6d2.png)
![image](https://user-images.githubusercontent.com/46686598/180082575-75dfc55e-769e-4550-a2be-52de934418fa.png)
![image](https://user-images.githubusercontent.com/46686598/180082612-d4ca7405-d132-479e-af78-09ff1c019c07.png)
![image](https://user-images.githubusercontent.com/46686598/180082631-4e3482b0-e261-4b69-ae81-0aa6a4cd8c03.png)
![image](https://user-images.githubusercontent.com/46686598/180082651-22bd73ba-ace1-48b4-9dbc-085c50abf1db.png)
![image](https://user-images.githubusercontent.com/46686598/180082665-09db5cb1-fb8b-48b3-a4e0-3d13b8d14b6c.png)
![image](https://user-images.githubusercontent.com/46686598/180082684-36e89e3c-85a4-4f8b-93ae-65a8b791b2c9.png)
![image](https://user-images.githubusercontent.com/46686598/180082700-bcd310d0-91ab-4a87-b274-89095fc81d8d.png)
![image](https://user-images.githubusercontent.com/46686598/180082729-5449a032-4fd9-42a1-829b-25d0d264d009.png)
