
# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective
Provision a local Docker container using Terraform.

## Tools Used
- Terraform
- Docker

## Files
- `main.tf`: Terraform configuration to provision an NGINX container.
- `execution_logs.txt`: Logs for `terraform init`, `plan`, `apply`, `destroy`.

## Steps to Run

1. Initialize Terraform:
```bash
terraform init
```

2. Preview the changes:
```bash
terraform plan
```

3. Apply the changes:
```bash
terraform apply
```

4. Destroy the infrastructure:
```bash
terraform destroy
```

## Interview Questions Covered

1. **What is IaC?**  
   IaC (Infrastructure as Code) is the practice of managing and provisioning infrastructure using code.

2. **How does Terraform work?**  
   Terraform uses declarative configuration files to define infrastructure, which it then applies using providers.

3. **What is Terraform state file?**  
   It's a file that keeps track of the resources Terraform manages.

4. **Difference between apply and plan?**  
   `plan` shows what will happen; `apply` makes it happen.

5. **What are Terraform providers?**  
   Plugins that interact with APIs (e.g., Docker, AWS).

6. **What is resource dependency?**  
   When one resource relies on another (handled automatically via references).

7. **How do you handle secret variables?**  
   Use `.tfvars` files, environment variables, or secret managers.

8. **Benefits of Terraform**  
   Reusability, automation, version control, and consistency.
