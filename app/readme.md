Have to check connection to RDS via nc command , have to download nc

to authenticate ECR
aws ecr get-login-password --region us-east-2 | docker login --username AWS --password-stdin 312846473135.dkr.ecr.us-east-2.amazonaws.com

Command to build docker images and push 

Now need service account connection between ec2 and ecs

now build image in ec2 
,

we need command to entrypoint into binbash, so it doesnt fail. after which i want to declare echo DATABASE variable with postgres username postgres and password is Chinnu-1212
