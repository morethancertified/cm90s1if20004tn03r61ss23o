**Ticket Type:** Task \
**Title:** External Files Project: AWS VPC and Security Group Deployment \
**Assignee:** You \
**Reporter:** Derek Morgan \
**Priority:** High \
**Labels:** Terraform, AWS, CSV, External Files, Locals \
**Epic Link:** AWS Expansion \
**Sprint:** Sprint 01/ExternalFiles

**Description**:

As part of our strategic initiative to enhance cloud infrastructure capabilities, you are tasked with deploying an AWS VPC and security group using Terraform, leveraging data from fwrules.csv to ensure configurations align with best practices for scalability and security. Our department is currently undergoing a migration to the cloud, and the Network Operations Center (NOC) has exported the firewall rules for a specific application. Since the switchover hasn't been completed, all ports open to the world must be stripped from the configuration until we are ready. Additionally, protocol capitalization must be normalized to lowercase for consistency and compatibility across our systems.

> **Note:** If the `terraform validate` command fails, all tasks in the lab will fail!

**Implementation Notes**:

Feel free to use code from previous labs. The values aren’t as important as the concepts.

- <a href="https://registry.terraform.io/providers/hashicorp/aws/latest/docs/html" target="_blank">AWS Provider Docs</a>
- <a href="https://developer.hashicorp.com/terraform/language/functions/csvdecode" target="_blank">Terraform csvdecode()</a>
- <a href="https://developer.hashicorp.com/terraform/language/values/locals" target="_blank">Terraform Locals</a>