# DevOps216921

Script1
A CloudFormation script that will create and deploy apache server using the two Resources: AWS::EC2::SecurityGroup and AWS::EC2::Instance.

SecurityGroup Properties
Security Group which only allows inbound access on TCP port 80 and also allows unrestricted outbound access.

EC2 Properties
AMI AMzon Linux 2 AMI (HVM)
AssociatePublicIpAddress: true
instancetype t3.micro
EC2 Servers associate network interface with the security group mentioned above.