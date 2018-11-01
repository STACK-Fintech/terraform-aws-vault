# Vault with ACL-Enabled Consul

This is identical to the root-example, except it takes an extra argument for the
`user-data-vault.sh` script that allows passing a Consul ACL token.

This is useful for preventing unauthorized users from attacking your Consul setup by deleting
random key-value entries, as well as granting read/write access to the Vault cluster so that it
can store data in Consul.
