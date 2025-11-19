# OpenTofu: AWS Module Template

This repository serves as a **standardized, secure template** for quickly scaffolding new reusable Infrastructure as Code (IaC) modules. It enforces consistency across all your cloud components and is configured to use the **`.tofu` file extension** to clearly identify its use of the OpenTofu project.

Use this repository as a **GitHub Template** to instantly create a new module (e.g., `tofu-aws-s3-bucket`).

<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.10.6 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | ~> 6.21 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 6.21.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_s3_bucket.example](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_bucket_name"></a> [bucket\_name](#input\_bucket\_name) | A unique and descriptive name for the primary resource managed by this module. | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_resource_arn"></a> [resource\_arn](#output\_resource\_arn) | The ARN of the main resource. |
| <a name="output_resource_id"></a> [resource\_id](#output\_resource\_id) | The ID of the main resource created by this module. |
<!-- END_TF_DOCS -->
