# Zonal Filestore Instance Example

This example provisions a zonal Google Cloud Filestore instance with a single share.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name            | Description                         | Type         | Default                 | Required |
| --------------- | ----------------------------------- | ------------ | ----------------------- | :------: |
| `project_id` | The ID of the project in which the resource belongs. | `string` | n/a | yes |

## Outputs

| Name                 | Description                                    |
| -------------------- | ---------------------------------------------- |
| `instance_id`  | The fully qualified ID of the Filestore instance. |
| `instance_ip_address` | The IP address of the Filestore instance.      |
| `instance_name`  | The name of the Filestore instance. |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

To provision this example, run the following from within this directory:

- `terraform init` to get the plugins
- `terraform plan` to see the infrastructure plan
- `terraform apply` to apply the infrastructure build
- `terraform destroy` to destroy the built infrastructure