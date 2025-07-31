<img width="1324" height="802" alt="image15" src="https://github.com/user-attachments/assets/00fa1601-0640-410b-96ea-600c4b95c15a" />


## Camunda Platform | Kubernetes  ☸️



🎯  Key Features
```
✅ Launch EC2 Instances
✅ Install K3S Binary ( Kubernetes )
✅ Prepare Cluster Configuration
✅ Deploy Helm Charts 
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```

🧩 Config 

```
scp -i ~/.ssh/<your pem file> <your pem file> ec2-user@<terraform instance public ip>:/home/ec2-user
chmod 400 <your pem file>
```

