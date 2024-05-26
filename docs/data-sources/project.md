---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "openai_project Data Source - terraform-provider-openai"
subcategory: ""
description: |-
  Retrieve a project by ID.
---

# openai_project (Data Source)

Retrieve a project by ID.

## Example Usage

```terraform
data "openai_project" "example" {
  id              = "proj_000000000000000000000000"
  organization_id = "org-000000000000000000000000"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) Project ID.
- `organization_id` (String) Organization ID.

### Read-Only

- `title` (String) Human-friendly label for the project, shown in user interfaces.