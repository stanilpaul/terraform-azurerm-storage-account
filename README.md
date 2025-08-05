# terraform-azurerm-storage-account



<!-- BEGIN_TF_DOCS -->
# Default example

# What is Storage Account

This is Storage Account module script using terraform. (for learning demo)

```hcl
resource "azurerm_storage_account" "this" {
  name                     = lower(var.storage_name)
  resource_group_name      = var.rg_name
  location                 = var.location
  account_tier             = var.storage_accounte_type
  account_replication_type = var.account_replication_type
}
```

<!-- markdownlint-disable MD033 -->
## Requirements

No requirements.

## Providers

The following providers are used by this module:

- <a name="provider_azurerm"></a> [azurerm](#provider\_azurerm)

## Resources

The following resources are used by this module:

- [azurerm_storage_account.this](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/storage_account) (resource)

<!-- markdownlint-disable MD013 -->
## Required Inputs

The following input variables are required:

### <a name="input_account_replication_type"></a> [account\_replication\_type](#input\_account\_replication\_type)

Description: n/a

Type: `string`

### <a name="input_location"></a> [location](#input\_location)

Description: n/a

Type: `string`

### <a name="input_rg_name"></a> [rg\_name](#input\_rg\_name)

Description: n/a

Type: `string`

### <a name="input_storage_accounte_type"></a> [storage\_accounte\_type](#input\_storage\_accounte\_type)

Description: n/a

Type: `string`

### <a name="input_storage_name"></a> [storage\_name](#input\_storage\_name)

Description: n/a

Type: `string`

## Optional Inputs

No optional inputs.

## Outputs

The following outputs are exported:

### <a name="output_storage_account"></a> [storage\_account](#output\_storage\_account)

Description: n/a

## Modules

No modules.

This is paul
<!-- END_TF_DOCS -->