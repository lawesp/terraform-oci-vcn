# Terraform VCN for Oracle Cloud Infrastructure

[changelog]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/blob/master/CHANGELOG.adoc
[contributing]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/blob/master/CONTRIBUTING.adoc
[contributors]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/blob/master/CONTRIBUTORS.adoc
[docs]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/tree/master/docs

[license]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/blob/master/LICENSE
[canonical_license]: https://oss.oracle.com/licenses/upl/

[oci]: https://cloud.oracle.com/cloud-infrastructure
[oci_documentation]: https://docs.cloud.oracle.com/iaas/Content/home.htm

[oracle]: https://www.oracle.com
[prerequisites]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/blob/master/docs/prerequisites.adoc

[quickstart]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/blob/master/docs/quickstart.adoc
[repo]: https://github.com/oracle/terraform-oci-vcn
[reuse]: https://github.com/oracle/terraform-oci-vcn/examples/db
[subnets]: https://erikberg.com/notes/networks.html
[terraform]: https://www.terraform.io
[terraform_cidr_subnet]: http://blog.itsjustcode.net/blog/2017/11/18/terraform-cidrsubnet-deconstructed/
[terraform_hashircorp_examples]: https://github.com/hashicorp/terraform-guides/tree/master/infrastructure-as-code/terraform-0.12-examples
[terraform_oci]: https://www.terraform.io/docs/providers/oci/index.html
[terraform_options]: https://github.com/oracle-terraform-modules/terraform-oci-vcn/blob/master/docs/terraformoptions.adoc
[terraform_oci_examples]: https://github.com/terraform-providers/terraform-provider-oci/tree/master/examples
[terraform_oci_oke]: https://github.com/oracle-terraform-modules/terraform-oci-oke

The [Terraform VCN][repo] for [Oracle Cloud Infrastructure][OCI] provides a reusable [Terraform][terraform] module that provisions a minimal VCN on OCI.

It creates the following resources:

* A VCN with customizable CIDR block
* An optional internet gateway
* An optional NAT gateway
* An optional service gateway

This module is primarily meant to be reusable to create more advanced infrastructure on {uri-oci}[OCI] either manually in the OCI Console or by extending the Terraform code.

## [Documentation][docs]

### [Pre-requisites][prerequisites]

#### Instructions
- [Quickstart][quickstart]
- [Reusing as a Terraform module][reuse]
- [Terraform Options][terraform_options]

## Related Documentation, Blog
- [Oracle Cloud Infrastructure Documentation][oci_documentation]
- [Terraform OCI Provider Documentation][terraform_oci]
- [Erik Berg on Networks, Subnets and CIDR][subnets]
- [Lisa Hagemann on Terraform cidrsubnet Deconstructed][terraform_cidr_subnet]

## Projects using this module

## Changelog

View the [CHANGELOG][changelog].

## Acknowledgement

Code derived and adapted from [Terraform OCI Examples][terraform_oci_examples] and Hashicorp's [Terraform 0.12 examples][terraform_oci_examples]

## Contributors

[Folks who contributed with explanations, code, feedback, ideas, testing etc.][contributors]

Learn how to [contribute][contributing].

## License

Copyright &copy; 2019 Oracle and/or its associates. All rights reserved.

Licensed under the [Universal Permissive License 1.0][license] as shown at 
[https://oss.oracle.com/licenses/upl][canonical_license].
