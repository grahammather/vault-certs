# Vault TLS Certs

This module generates TLS certs for use with Vault. It takes just one variable: `shared_san`

## shared_san

Set this variable to the hostname of the Vault cluster. If you're using the `terraform-aws-vault/examples/hvd-vault` example, set this to the value of `vault_hostname`