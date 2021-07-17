VMs-behind-Azure-LB
Deploy 2 Linux VMs behind an Azure Basic Load Balancer Via Terraform (100% automation)
A  .tfars was also created which contained the password and username of VMs
Quite unsettling that I was unable to call the cidr blocks for the subnet via index.
Terraform plan/apply did not pass validation for that.
The next tutorial would be about orchestrating Docker containers deployed on the VMs via Minikube.
