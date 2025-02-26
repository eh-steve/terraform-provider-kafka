---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "kafka Provider"
subcategory: ""
description: |-
  
---

# kafka Provider





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `bootstrap_servers` (List of String) A list of kafka brokers

### Optional

- `ca_cert` (String) CA certificate file to validate the server's certificate.
- `ca_cert_file` (String, Deprecated) Path to a CA certificate file to validate the server's certificate.
- `client_cert` (String) The client certificate.
- `client_cert_file` (String, Deprecated) Path to a file containing the client certificate.
- `client_key` (String) The private key that the certificate was issued for.
- `client_key_file` (String, Deprecated) Path to a file containing the private key that the certificate was issued for.
- `client_key_passphrase` (String) The passphrase for the private key that the certificate was issued for.
- `sasl_mechanism` (String) SASL mechanism, can be plain, scram-sha512, scram-sha256
- `sasl_password` (String) Password for SASL authentication.
- `sasl_username` (String) Username for SASL authentication.
- `skip_tls_verify` (Boolean) Set this to true only if the target Kafka server is an insecure development instance.
- `timeout` (Number) Timeout in seconds
- `tls_enabled` (Boolean) Enable communication with the Kafka Cluster over TLS.
