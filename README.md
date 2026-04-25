# AWS IAM Security Checklist

This project contains a basic checklist to secure AWS IAM environments.

## Root Account Security
- Avoid using the root account for daily tasks
- Enable MFA on the root account
- Store root credentials securely

## IAM Users
- Create individual IAM users for each person
- Avoid shared accounts
- Assign permissions using groups

## IAM Policies
- Follow the principle of least privilege
- Avoid using AdministratorAccess unless necessary
- Use managed policies where possible

## Credential Security
- Rotate access keys regularly
- Remove unused credentials
- Avoid storing access keys in code

## Monitoring and Logging
- Enable CloudTrail
- Monitor IAM login activity
- Review IAM policies regularly

## Best Practices
- Use IAM roles instead of long-term credentials
- Enable MFA for sensitive actions
- Regularly audit IAM permissions

## Author
Kanishka Shahjee