<img width="1324" height="802" alt="image15" src="https://github.com/user-attachments/assets/00fa1601-0640-410b-96ea-600c4b95c15a" />


## Camunda Platform | Kubernetes  ☸️
Camunda provides a scalable process automation and orchestration platform. It is available self-managed or on-demand as-a-service. Camunda brings powerful execution engines for BPMN processes and DMN decisions, paired with tools for collaborative modeling, operations, and analytics.


🎯  The core of Camunda Platform
```
✅ Console - Configure and deploy clusters in SaaS with Console.
✅ Zeebe - The cloud-native workflow and decision engine.
✅ Operate - Manage, monitor, and troubleshoot your processes through Operate.
✅ Optimize - Improve your processes by identifying constraints in your system with Optimize.
✅ Tasklist - Use Tasklist to complete tasks which need human input.
✅ Identity - Identity is the component within the Camunda 8 stack responsible for authentication and authorization.
✅ Connectors - Integrate external systems with reusable, pre-defined building blocks
✅ Web Modeler - Collaborate and model processes, deploy and start new instances all without leaving Camunda Platform
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

