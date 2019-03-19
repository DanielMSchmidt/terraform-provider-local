## 1.2.0 (Unreleased)

NEW FEATURES:

* The provider is now compatible with Terraform v0.12, while retaining compatibility with prior versions.
* `local_file` resource has optional `sensitive_content` attribute, which can be used instead of `content` in situations where the content contains sensitive information that should not be displayed in a rendered diff. [GH-9]

## 1.1.0 (January 04, 2018)

NEW FEATURES:

* `local_file` data source, for reading files in a way that participates in Terraform's dependency graph, which allows reading of files that are created dynamically during `terraform apply`. ([#6](https://github.com/terraform-providers/terraform-provider-local/issues/6))

## 1.0.0 (September 15, 2017)

* No changes from 0.1.0; just adjusting to [the new version numbering scheme](https://www.hashicorp.com/blog/hashicorp-terraform-provider-versioning/).

## 0.1.0 (June 21, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
