# AWS-Deploy-NetApp-ONTAP-Cloud-HA
AWS Deploy NetApp ONTAP Cloud HA

To launch High Availability (HA) pairs in AWS, create an HA working environment in Cloud Manager.
Make sure there is a working connector that is associated with one’s workspace. One must also have the correct AWS networking information. Log into the NetApp dashboard and click the Add Working Environment button.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/working_environ.png)

Click on Amazon Web Services and then Cloud Volumes ONTAP high availability, click continue.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/environ.png)

A pop up to create a Connector will appear if one doesn’t have one yet. Click let’s start.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/connector.png)

Choose AWS and click continue.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/connector2.png)

One will need the correct AWS IAM user access key and secret key for user that has the correct permissions. One will also need a VPC, at least three subnets, and keypair. On the get ready page, click continue. On the AWS Credentials page, enter a connector instance name, the IAM access key and secret key, and click continue. On the location page, choose a region, VPC, subnet, and click continue.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/location.png)

Choose a key pair, enable the public IP, and click continue. On the security group page allow inbound traffic for HTTP(S) and SSH, click create.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/succed.png)

From here one can change the AWS credentials and subscription if needed.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/addsub.png)

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/addsup2.png)

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/Addsub3.png)

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/addsub4.png)

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/addsub5.png)

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/addsub6.png)

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/addsub7.png)

Enter a working environment name, a tag if needed, and a password, and click continue.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/pass1.png)

Choose which services one would like to run and click continue.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/services.png)

Select Multiple Availability Zones (AZs).

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/AZs.png)

Choose the correct VPC and a different subnet in different AZs for node1, node2, and mediator, click continue.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/multi%20%20_node.png)

For connectivity and SSH authentication, choose the connection methods for the HA pair and the mediator and click continue.

![alt text](https://github.com/doyle199/AWS-Deploy-NetApp-ONTAP-Cloud-HA/blob/master/connectivity.png)
