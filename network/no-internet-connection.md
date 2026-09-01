# No Internet Connection

## Symptoms

- User unable to connect to internet
- Apps. and websites not loading
- Company software unavailable
- Wi-Fi is showing disconnected

## Possible Causes

- Wi-Fi/Ethernet issue
- Wrong IP address
- DNS or adapter issue
- ISP outage

## Resolution Steps

1. check Wi-Fi/Ethernet connection and reconnect
2. Run cmd ipconfig /renew and ipconfig /flushdns
    - renew requests new IP address from network
    - flushdns clears information to fix naming issues
3. Test connectivity using ping and nslookup
    - ping to check if device can reach another device
    - nslookup to see if a domain can be switched to IP address
4. Restart users device and retest

## Escalation
- If troubleshooting does not resolve issue escalate to senior
- Escalate if multiple users are experiencing same issue
- Document all finding before escalating