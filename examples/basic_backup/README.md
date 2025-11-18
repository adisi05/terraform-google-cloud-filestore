# Zonal Filestore Backup Example


This example illustrates how to create a Zonal Filestore instance and a backup for it.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| project_id | The ID of the project in which the resource belongs. | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| backup_id | The fully qualified ID of the Filestore backup. |
| backup_location | The location of the Filestore backup. |
| backup_name | The name of the Filestore backup. |
| instance_ip_address | The IP address of the Filestore instance. |
| source_file_share | The name of the source file share for the backup. |
| source_instance_id | The ID of the source Filestore instance for the backup. |
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

## Usage

To provision this example, run the following from within this directory:

- `terraform init` to get the plugins
- `terraform plan` to see the infrastructure plan
- `terraform apply` to apply the infrastructure build
- `terraform destroy` to destroy the built infrastructure