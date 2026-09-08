# DHCP/IP Address Invalid

## Symptoms

- User is unable to access the internet or network resources.
- Computer has an invalid IP address.
- Receiving a "No Internet" network error.
- Other devices are working normally.

## Possible Causes

- DHCP isn't assigning an IP address.
- Network connection failure.
- Incorrect TCP/IP settings.
- Faulty network adapter.
- DHCP server may be down.

## Resolution Steps

1. Confirm the computer is connected to Wi-Fi or Ethernet.
2. Check the computer's IP address and network settings.
3. Make sure the IP address is being obtained automatically.
4. Restart the computer and check the IP address again.
5. Open Command Prompt and release and renew the IP address:
   - `ipconfig /release`
   - `ipconfig /renew`
6. Confirm the computer receives a valid IP address and test the network connection.

**Guide:** [Essential network settings and tasks in Windows](https://support.microsoft.com/en-us/windows/experience/connectivity-networking/essential-network-settings-and-tasks-in-windows)

## Escalation

Escalate issue if:

- Computer is still unable to get a valid IP address.
- DHCP server or network is unavailable.
- Multiple users are experiencing the same issue.
- Network admin access is needed.