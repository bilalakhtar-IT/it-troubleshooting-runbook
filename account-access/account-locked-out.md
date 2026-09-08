# User Account Locked Out

## Symptoms

- User unable to log into their computer or apps.
- Receiving "Account Locked" message.
- Password is being denied.
- Company email/resources unable to be used.

## Possible Causes

- Too many incorrect password attempts.
- Logged into an old device with the same password.
- Failed login attempt from a connected device.
- Account security locked the user out.

## Resolution Steps

1. Verify user is logging into their work device with their login credentials.
2. Check if the account is locked.
3. In Active Directory Users and Computers, unlock the user's account:
   - Open Active Directory Users and Computers.
   - Find the user's account.
   - Right-click the account > Properties.
   - Select the Account tab.
   - Check Unlock account.
   - Click Apply > OK.
4. Have the user log in again to make sure their access is working.

**Guide:** [Manage user accounts with Active Directory Users and Computers](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/manage-user-accounts-in-windows-server)

## Escalation

- Escalate issue if the account is constantly locking the user out after unlocking the account.
- Escalate if there are unauthorized login attempts.
- Document all findings and escalate the issue.