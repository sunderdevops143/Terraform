# Terraform_WordPress_RDS

You can find a detailed article on the same here =>

https://medium.com/@daksh.jain00/wordpress-deployed-via-minikube-data-stored-in-aws-rds-28eb89ff9cb7
## USAGE
```
terraform apply
```
This will deploy the whole infrastructure on AWS consisting of:

* RDS and its dependencies
* WordPress over Kubernetes via Minikube
* Expose the WordPress pod
* Then magically load it on Chrome

To destroy the infrastructure use the command:
```
terraform destroy
```
