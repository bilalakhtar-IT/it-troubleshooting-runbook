# Shared Drive Access

## Symptoms

- User can't access shared drive or folder
- User receiving an "Access Denied" message
- Shared device is missing from File Explorer
- User was able to access drive but no longer can

## Possible Causes

- User doesn't have required permissions
- Network connection may be unavailable
- Shared drive isn't connected
- User account or group membership may have changed
- Shared drive is currently down

## Resolution Steps

1. Confirm if user has working network connection
2. Confirm if shared drive or folder path is right
3. Check if other users are able to access the same drive
4. Check if permissions are needed in AD
5. If permissions needed, reconnect the shared drive

**Guide:** [Checking file/folder permissions in Windows](https://learn.microsoft.com/en-us/troubleshoot/windows-client/networking/cannot-access-shared-folder-file-explorer)

**Guide:** [Map a network drive in Windows](https://support.microsoft.com/en-us/windows/experience/connectivity-networking/file-sharing-over-a-network-in-windows#bkmk_map_network_drive)

## Escalation

Escalate issue if:

- User still receiving an "Access Denied" message
- Shared device showing up as unavailble
- Permission changes or admin access is needed