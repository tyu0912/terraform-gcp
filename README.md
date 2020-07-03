# Spinning up an austoscaling platform with Terraform and Ansible on GCP

## Steps:


1. Install terraform via `brew install terraform`

2. Enable Computer Engine API: https://console.developers.google.com/apis/library/compute.googleapis.com?pli=1

3. Create a GCP service key and store it appropriately

4. Create a tfvars file with the key. Will need it to launch with -var-file parameter

## Resources Used:
1. https://learn.hashicorp.com/terraform/gcp/build
2. https://cloud.google.com/community/tutorials/getting-started-on-gcp-with-terraform