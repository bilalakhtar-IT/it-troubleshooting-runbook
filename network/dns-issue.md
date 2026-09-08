# DNS Issue

## Symptoms

- User connected to the internet but unable to access websites.
- Receiving a DNS error.
- Some websites are working while others are not.
- Apps and services are unable to connect.

## Possible Causes

- DNS server isn't responding.
- DNS cache may need to be flushed.
- Network connection problem.
- DNS settings are configured incorrectly.

## Resolution Steps

1. Confirm the computer has a proper network connection.
2. Test different websites to see if the issue is affecting several websites.
3. Restart the computer and test the connection again.
4. Open Command Prompt and flush the DNS cache:
   - `ipconfig /flushdns`
5. Use `nslookup` to check if a domain name can be resolved to an IP address.
6. Check the computer's DNS settings to make sure they are configured correctly.

## Escalation

Escalate issue if:

- DNS is still not working after troubleshooting.
- DNS servers are unavailable.
- Multiple users are facing the same problem.
- Network or admin access is needed.