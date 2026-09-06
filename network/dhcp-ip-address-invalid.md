## DHCP/IP Address Invalid

## Symptoms

- User is unable to access internet or network resources
- Computer has invalid IP address
- Receiving "No Internet" network error
- Other devices working normally

## Possible Causes

- DHCP isn't assigning IP address
- Network connection failure
- Incorrect TCP/IP settings
- Faulty network adapter
- DHCP server may be down

## Resolution Steps

1. Confirm computer is connected to Wi-Fi or Ethernet
2. Check computer IP address and network settings
3. Make sure IP address is gathered automatically
4. Restart computer and check IP
5. Release and renew IP address in command prompt
    - ipconfig /release
    - ipconfig /renew

**Guide:** [Essential network settings and tasks in Windows](https://support.microsoft.com/en-us/windows/experience/connectivity-networking/essential-network-settings-and-tasks-in-windows)

## Escalation

Escalate issue if:

- Computer still unable to get valid IP address
- DHCP server or network unavailable
- In need of network admin access