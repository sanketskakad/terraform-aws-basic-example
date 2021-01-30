# Terraform Infrastructure

## Usage

1. Configure your AWS credentials.
2. Run `terraform init` to initialize the project.
3. Run `terraform fmt` and `terraform validate` to verify the configuration.
4. Run `terraform plan` to preview infrastructure changes.
5. Run `terraform apply` to provision resources.
6. Run `terraform destroy` to remove resources when no longer needed.
7. Never commit `terraform.tfstate` or sensitive credentials to Git.
8. Store Terraform state in a remote backend for team collaboration.