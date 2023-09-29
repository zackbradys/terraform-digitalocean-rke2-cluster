# Terraform Module for RKE2 on Digital Ocean

***Please review the information below and follow the instructions to deploy this module!**

## Prerequisites
* Git Utility, Terminal Utility, and HashiCorp Terraform with Access to the AWS Provider
* Digital Ocean Account with Read/Write capable Personal Access Token

## Configuration

**Step 1:** Ensure Terraform is installed and create a working directory.

**Step 2:** Copy the code below into a file named `main.tf` and set the required variables or additional optional variables!
```bash
module "rke2-cluster" {
  source  = "zackbradys/rke2-cluster/digitalocean"
  version = "0.0.1"

  varibles = "tbd-tbd-tbd"
}
```

**Step 3:** Run the commands below to deploy and provision your infrastructure!
```bash
terraform init

terraform plan

terraform apply --auto-approve
```

### Contributing
Please utilize GitHubs features such as Issues, Forks, and Pull Requests to contribute to this code!

### About Me
A little bit about me, my history, and what I've done in the industry. If you have any questions, please reach out to me on my GitHub (https://github.com/zackbradys)!
- Former Contractor
- U.S. Military Veteran
- Open-Source Contributor
- Built and Exited a Digital Firm
- Active Volunteer Firefighter/EMT