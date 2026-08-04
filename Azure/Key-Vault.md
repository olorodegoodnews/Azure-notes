# Azure Key Vault

## What is Azure Key Vault?

Azure Key Vault is a cloud service used to securely store and manage:

- Secrets
- Encryption Keys
- Certificates

## Benefits

- Centralized secret management
- Azure RBAC integration
- Improved security
- Supports encryption and certificate management

## What I Learned

I created my first Azure Key Vault and learned how it provides a secure location for storing sensitive information instead of embedding secrets in applications.
---

## Azure Key Vault Secrets

A secret is sensitive information stored securely in Azure Key Vault.

### Examples

- Passwords
- API keys
- Connection strings
- Access tokens

### Best Practices

- Never hardcode secrets in application code.
- Use Azure RBAC to control access.
- Do not expose secret values in screenshots or public repositories.

### What I Learned

I created my first Azure Key Vault secret and learned how Azure securely stores sensitive information while helping protect applications from credential exposure.



---

## Retrieving Secrets

Retrieving a secret means securely reading a stored value from Azure Key Vault.

### Best Practices

- Grant access using Azure RBAC.
- Never expose secret values publicly.
- Applications should retrieve secrets at runtime instead of storing them in code.

### What I Learned

I retrieved a secret from Azure Key Vault and learned how Azure securely provides sensitive information only to authorized users or applications.
