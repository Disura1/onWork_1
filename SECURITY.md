# Security Policy

## Reporting a Security Issue

Do not disclose sensitive security findings through a public GitHub issue.

Report suspected vulnerabilities, exposed credentials or confidential-data incidents directly to the Team Lead through the approved private project communication channel. Include only the minimum information needed to investigate safely.

## Public Repository Rules

Never commit:

- `.env` files or real environment values
- MongoDB connection strings
- JWT secrets
- Email or Brevo credentials
- Cloudinary credentials
- API keys or personal access tokens
- Passwords
- Real CV files
- Personal user information
- Private company documents
- Database exports
- Production logs
- Confidential screenshots
- Private Postman environments

Use fake sample data and safe placeholders only.

## Exposed Secret Procedure

1. Inform the Team Lead immediately.
2. Revoke or rotate the exposed credential.
3. Remove the secret from active files.
4. Clean repository history when required.
5. Update ignore rules and documentation.
6. Record the incident internally.

Deleting the value in a later commit does not by itself make the exposure safe.
