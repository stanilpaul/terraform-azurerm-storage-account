<!-- BEGIN_TF_DOCS -->
# What is Storage account

This is storage account module script using terraform. (for learning demo)

```hcl
resource "azurerm_storage_account" "this" {
  name                     = var.storage_name
  account_tier             = var.storage_account_type
  account_replication_type = var.account_replication_type
  resource_group_name      = var.rg_name
  location                 = var.location
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

### <a name="input_storage_account_type"></a> [storage\_account\_type](#input\_storage\_account\_type)

Description: n/a

Type: `string`

### <a name="input_storage_name"></a> [storage\_name](#input\_storage\_name)

Description: n/a

Type: `string`

## Optional Inputs

No optional inputs.

## Outputs

The following outputs are exported:

### <a name="output_rg_details"></a> [rg\_details](#output\_rg\_details)

Description: n/a

## Modules

No modules.

This module created by Paul, for learning demo.
<!-- END_TF_DOCS -->