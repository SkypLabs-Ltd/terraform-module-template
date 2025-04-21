# OpenTofu/Terraform Module Template

Template of a minimal OpenTofu/Terraform module.

This module follows the [standard structure][standard-module-structure]
described in the [OpenTofu documentation][opentofu-docs].

The following non-standard but commonly used files and folders have also been
added:

* `local.tf`
* `data.tf`
* `providers.tf`
* `templates`
* `versions.tf`

A [pre-commit][pre-commit] configuration file is present to automatically format
and validate the code and update the readme file upon Git commits.

<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.6.0 |

## Providers

No providers.

## Modules

No modules.

## Resources

No resources.

## Inputs

No inputs.

## Outputs

No outputs.
<!-- END_TF_DOCS -->

 [pre-commit]: https://pre-commit.com/ "pre-commit Website"
 [standard-module-structure]: https://opentofu.org/docs/language/modules/develop/structure/ "Standard Module Structure - OpenTofu Documentation"
 [opentofu-docs]: https://opentofu.org/docs/ "OpenTofu Documentation"
