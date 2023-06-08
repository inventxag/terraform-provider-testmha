---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "ixcloud_data_source Resource - terraform-provider-ixcloud"
subcategory: ""
description: |-
  This resource represents a data source.
---

# ixcloud_data_source (Resource)

This resource represents a data source.

## Example Usage

```terraform
resource "ixcloud_data_source" "test" {
  name                   = "testdatasource"
  owner                  = "hans.mueller@inventx.ch"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String)
- `owner` (String)

### Optional

- `cost_center` (String)
- `organizational_unit` (String)
- `resource_group` (String)
- `shared_subscription` (List of String)
- `tags` (List of String)

