# No Internet Connection

## Symptoms

- User unable to connect to the internet.
- Apps and websites are not loading.
- Company software is unavailable.
- Wi-Fi is showing as disconnected.

## Possible Causes

- Wi-Fi or Ethernet connection issue.
- Incorrect IP address.
- DNS or network adapter issue.
- Network or ISP outage.

## Resolution Steps

1. Check the Wi-Fi or Ethernet connection and reconnect if needed.
2. Restart the network connection and test the internet again.
3. Open Command Prompt and run:
   - `ipconfig /renew` to request a new IP address from the network.
   - `ipconfig /flushdns` to clear the DNS cache.
4. Test connectivity using `ping` and `nslookup`:
   - `ping` checks if the computer can reach another device or server.
   - `nslookup` checks if a domain name can be resolved to an IP address.
5. Restart the user's computer and retest the connection.

## Escalation
- Troubleshooting does not resolve the issue.
- Multiple users are experiencing the same issue.
- There may be a network or ISP outage.
- Network admin access is needed.