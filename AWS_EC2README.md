# AWS EC2

### Click on Instances
!["Alt Text"](aws/1.png)

### Click on Launch instances
!["Alt Text"](aws/2.png)

### Give it an appropriate name & description
!["Alt Text"](aws/3.png)

### Select the server. Here we choose ```Ubuntu 22.04```
!["Alt Text"](aws/4.png)

### Select Instance Type. Here we choose ```t2.micro```
!["Alt Text"](aws/5.png)

### Select the Key Pair login. Ours is ```DataStudents```
!["Alt Text"](aws/6.png)

### Create or select a security group 
!["Alt Text"](aws/7.png)

### Review the summary before launching
!["Alt Text"](aws/8.png)

### Click on the instance to view the details, click connect
!["Alt Text"](aws/9.png)

### Click on the SSH Client tab
!["Alt Text"](aws/10.png)

```cd``` into the ```.ssh``` directory & run ```chmod 400 "DataStudents.pem"``` command
!["Alt Text"](aws/11.png)

### Connect to your instance using public DNS e.g.
```ssh -i "DataStudents.pem" ubuntu@ec2-3-72-10-29.eu-central-1.compute.amazonaws.com```
!["Alt Text"](aws/12.png)

### View the status of your Instance in the Instance tab
!["Alt Text"](aws/13.png)

### Enter ```exit``` to close the connection 
