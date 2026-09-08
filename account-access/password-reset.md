# User Account Password Reset

## Symptoms

- User cannot remember their password.
- Unable to sign in to their account.
- Receiving incorrect password message.
- Multiple failed attempts caused the account to lock out.

## Possible Causes

- Forgotten password.
- User entered incorrect password several times.
- Password may have expired.
- Account may be locked due to security purposes.

## Resolution Steps

1. Confirm user ID before resetting their password.
2. Check if account is locked out or if password has expired.
3. Reset password using the management tool:
   - Open Active Directory.
   - Locate the user account.
   - Right-click the user name.
   - Select Reset Password.
   - Type and confirm the new password.
   - Check "User must change password at next logon" if the user needs to create their own password.
4. Provide the user with steps on how to create their own password following company security guidelines.

**Guide:** [Manage user accounts with Active Directory Users and Computers](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/manage-user-accounts-in-windows-server)

## Escalation

Escalate the issue if:

- Password reset does not resolve the problem.
- Account is unable to be unlocked.
- User is unable to sign in after the password reset.
- There is a security issue within the account.