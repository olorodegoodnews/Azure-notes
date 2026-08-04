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


---

## Soft Delete

Soft Delete protects secrets, keys, and certificates from accidental deletion.

### Benefits

- Recover deleted secrets.
- Protect against accidental deletion.
- Improve security and business continuity.

### What I Learned

I deleted and recovered a secret using Azure Key Vault Soft Delete and learned how Azure protects sensitive information from permanent loss.


---

## Azure RBAC for Key Vault

Azure RBAC controls who can access Azure Key Vault resources.

### Common Roles

- Key Vault Administrator
- Key Vault Secrets Officer
- Key Vault Secrets User

### Benefits

- Least privilege access
- Improved security
- Centralized access management

### What I Learned

I reviewed Azure RBAC role assignments for my Key Vault and learned how Azure controls access to secrets using role-based permissions.
