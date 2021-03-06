Expected variables:
- `project_id`

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| datalab\_user\_email | Create the Datalab instance on behalf of the specified user | string | `"integration-test@google.com"` | no |
| project\_id | The ID of the project in which to provision resources. | string | n/a | yes |
| region | The region the network will be created in | string | `"us-central1"` | no |
| zone | The zone the Datalab instance will be deployed to | string | `"us-central1-c"` | no |

## Outputs

| Name | Description |
|------|-------------|
| disk\_name | The name of the persistent disk |
| disk\_size | The size of the persistent disk |
| firewall\_name | The name of the firewall rule |
| instance\_name | The instance name |
| nat\_name | Google Cloud NAT name |
| network\_name | Network name |
| project\_id | The ID of the project in which resources are provisioned. |
| region | Region |
| router\_name | Google Cloud Router name |
| subnet\_name | Subnet name |
| zone | Zone |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
