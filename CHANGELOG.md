# Changelog

# v2.0.1 - 2020/09/17

- Add `depends_on` to enforce the order in which the resources get instantiated / evaluated.

# v2.0.0 - 2020/09/17

- Set minimum terraform version to 0.13.0
- Added variable validation to optional `assume_role_arn` to match syntax described in 
  [IAM Identifiers](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_identifiers.html).

# v1.3.0 - 2020/08/03

- Set minimum version of random provider to 2.3.0

# v1.2.2 - 2020/05/11

- Updated examples in [README.md](README.md).

# v1.2.1 - 2020/05/11

- Updated [README.md](README.md) to reflect `digiticketsgroup/terraforming` image that includes all the required
  resources for using this module.

# v1.2.0 - 2020/05/11

- Drop down to using `sh` rather than `bash` so this module can operate with Hashicorp Terraform Docker image.

# v1.1.0 - 2020/05/07

- Updated examples in README.md with registry path as displayed by registry.
- Updated `assume_role_arn` to reflect that it is optional.

# v1.0.0 - 2020/05/07
Initial release
