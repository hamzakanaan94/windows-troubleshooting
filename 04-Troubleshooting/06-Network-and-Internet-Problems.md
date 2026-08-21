# Network and Connectivity Problems

## Overview

Network and connectivity problems can prevent devices from accessing the Internet, communicating with other devices, sharing files, or operating correctly within a local network.

Troubleshooting should begin by identifying whether the problem originates from the device, network adapter, Ethernet connection, switch, router, IP configuration, or the Internet connection itself.

The diagnostic process should move from the simplest and most local causes toward the network infrastructure.

## Common Symptoms

Typical network-related symptoms include:

- No Internet connection
- Wi-Fi connected but no Internet access
- Ethernet connected but no Internet access
- Intermittent connection
- IP address conflicts
- Incorrect IP configuration
- DHCP-related problems
- Network adapter problems
- Network adapter driver problems
- Damaged or incorrectly connected Ethernet cables
- Router configuration problems
- Switch configuration problems
- Devices unable to communicate with each other
- File sharing problems within a LAN
- Reduced Internet speed
- Network device detection problems

## 1. Initial Assessment

Before changing network configuration:

- Identify whether the problem affects one device or multiple devices.
- Determine whether the connection uses Wi-Fi or Ethernet.
- Check the physical connection.
- Check the network adapter.
- Check the Ethernet cable when applicable.
- Check whether other devices can access the network.
- Check the router.
- Check the switch when applicable.
- Check the device's IP configuration.
- Determine whether the problem is local or Internet-related.

The objective is to identify where the connection fails before changing multiple network settings.

## 2. Device and Network Adapter Check

When a device cannot connect to the network:

- Check whether the network adapter is detected.
- Check whether the adapter is enabled.
- Check the network adapter driver.
- Check for recent driver changes or updates.
- Check the physical adapter when applicable.
- Test the connection again after correcting the adapter or driver problem.

In some desktop systems, a damaged onboard network adapter required the use of a separate network adapter.  
This provided a practical hardware-level solution when the integrated network interface was no longer functioning correctly.

## 3. Ethernet Connection Check

Ethernet connections were commonly used for local networks and Internet connectivity.

Basic checks include:

- Verify that the Ethernet cable is connected correctly.
- Check the physical cable and connectors.
- Check whether the network link is established.
- Reconnect the cable when necessary.
- Check the connection from the device to the switch or router.
- Replace the cable when physical damage is suspected.

Hands-on experience also included assembling and connecting Ethernet cables when required.  
A dedicated professional cable tester was not used; cable problems were primarily investigated through physical inspection, connection testing, and network behavior.

## 4. Wi-Fi Connectivity Troubleshooting

When a device is connected to Wi-Fi but has no Internet access:

1. Check the device.
2. Check the Wi-Fi connection.
3. Check the network adapter.
4. Check the router.
5. Check the router configuration.
6. Check IP configuration.
7. Check whether other devices have Internet access.
8. Reconfigure the router when required.
9. Re-test the connection.

The diagnostic process should determine whether the problem is isolated to one device or affects the wider network.

## 5. IP Address Configuration

IP addressing was used extensively in local networks.

In offline gaming environments and local networks, devices were assigned specific IP addresses to allow reliable communication between systems.

Static IP addresses were also used to make devices easier to identify and troubleshoot within a local network.

A typical local network arrangement could include:

```
Router / Network
       ↓
Switch
       ↓
PC 1 → Static IP
PC 2 → Static IP
PC 3 → Static IP
PC 4 → Static IP
PC 5 → Static IP
```

Assigning predictable IP addresses made it easier to identify individual systems and troubleshoot network communication problems.

## 6. IP Address Conflicts

An IP address conflict can occur when two devices attempt to use the same IP address.

A practical troubleshooting process includes:

1. Identify the affected device.
2. Check the current IP configuration.
3. Determine whether the IP address is already assigned to another device.
4. Select an appropriate unused IP address.
5. Configure the device with the new address.
6. Reconnect to the network.
7. Test communication with other devices.

IP conflicts were encountered in local offline gaming networks where devices were manually assigned addresses.

## 7. DHCP Configuration

DHCP was considered when configuring and troubleshooting local networks.

The diagnostic process includes determining whether devices receive their network configuration automatically or use manually assigned addresses.

In environments where static IP addressing was preferred, individual devices could be assigned specific IP addresses to simplify identification and maintenance.

The selected configuration should be consistent across the network and should avoid duplicate IP addresses.

## 8. Router Configuration

Router configuration was part of practical network setup and troubleshooting.

Tasks included:

- Connecting the router.
- Configuring the router.
- Reconfiguring the router when required.
- Connecting devices through Ethernet.
- Configuring Wi-Fi.
- Checking local network connectivity.
- Checking Internet connectivity.
- Investigating incorrect router configuration.

When a network stopped working because of incorrect router configuration, the router could be reconfigured from the beginning when necessary.

Router troubleshooting should begin by determining whether the configuration itself is responsible for the connectivity problem.

## 9. Switch Configuration

Switches were used to connect multiple devices within local networks.

Practical tasks included:

- Connecting PCs to the switch.
- Connecting the switch to the router when required.
- Checking physical connections.
- Configuring the local network.
- Assigning IP addresses to connected systems.
- Testing communication between devices.
- Troubleshooting individual connections.

Local networks could include several connected computers, with the number of devices depending on the environment and requirement.

Practical setups included home networks, offices, and offline gaming environments.

## 10. LAN File Sharing

Local networks were also used for file sharing between connected devices.

A typical setup included:

```
PC 1
  │
PC 2 ── Switch ── Router
  │
PC 3
  │
PC 4
```

When devices were correctly configured on the same LAN, files could be shared between systems for:

- Data transfer
- Configuration
- Local work
- Shared resources

Network configuration and device identification were important for reliable local communication.

## 11. Network Adapter Driver Problems

Network connectivity problems can be caused by incorrect, missing, or outdated network adapter drivers.

A practical diagnostic process includes:

1. Check whether the network adapter is detected.
2. Check the installed driver.
3. Identify whether the problem started after a driver update.
4. Update or reinstall the appropriate driver when required.
5. Restart the system.
6. Test the network connection.
7. Verify stable connectivity.

Driver problems were encountered on both desktop and other computer systems.

## 12. Network Adapter Hardware Problems

When an onboard network adapter becomes defective, the motherboard's integrated network interface may no longer provide reliable connectivity.

A practical solution may be:

```
Onboard Network Adapter Problem
          ↓
Check Driver
          ↓
Check Network Configuration
          ↓
Check Physical / Hardware Condition
          ↓
Confirm Adapter Failure
          ↓
Install Compatible Separate Network Adapter
          ↓
Install Driver
          ↓
Configure Network
          ↓
Test Connectivity
```

This approach avoids unnecessary motherboard replacement when a separate compatible network adapter can restore network functionality.

## 13. Internet Connectivity Diagnosis

When a device is connected to Wi-Fi or Ethernet but has no Internet access, troubleshooting should proceed systematically.

A practical sequence is:

```
No Internet
     ↓
Check Device
     ↓
Check Wi-Fi / Ethernet
     ↓
Check Cable
     ↓
Check Network Adapter
     ↓
Check IP Configuration
     ↓
Check Router
     ↓
Check Router Configuration
     ↓
Check Other Devices
     ↓
Reconfigure if Required
     ↓
Re-test Internet Connection
```

The goal is to determine whether the problem is located at the device, local network, router, or Internet connection.

## 14. Network Speed Testing

Internet speed can be checked when slow connectivity is reported.

Speedtest was used as a practical tool for checking Internet connection performance.

Speed testing can help compare:

- Expected connection performance
- Download speed
- Upload speed
- Changes before and after troubleshooting

Speed results should be interpreted together with the network configuration and the conditions under which the test was performed.

## 15. Network Device Identification

Fing was used to identify devices connected to a network.

This can help with:

- Identifying connected devices.
- Checking whether expected devices are present.
- Understanding the current network environment.
- Troubleshooting unknown or unexpected connections.

Device identification can be particularly useful when several computers and network devices are connected to the same LAN.

## 16. Offline Gaming Network Example

Local networking was also used for offline multiplayer gaming environments.

A typical setup could include several PCs connected through a switch.

The process included:

```
PC Assembly / Preparation
        ↓
Windows Installation
        ↓
Driver Installation
        ↓
Ethernet Connections
        ↓
Switch Configuration
        ↓
IP Address Assignment
        ↓
Check for IP Conflicts
        ↓
Test Local Communication
        ↓
Start Multiplayer Environment
        ↓
Verify Network Stability
```

Static IP addressing was useful in these environments because each system could be assigned a predictable address and identified easily.

## 17. Network Troubleshooting Process

The preferred troubleshooting approach is:

```
Reported Connectivity Problem
          ↓
Identify Affected Device(s)
          ↓
Check Physical Connection
          ↓
Check Wi-Fi / Ethernet
          ↓
Check Network Adapter
          ↓
Check Driver
          ↓
Check IP Configuration
          ↓
Check DHCP / Static IP
          ↓
Check for IP Conflict
          ↓
Check Switch
          ↓
Check Router
          ↓
Check Internet Connection
          ↓
Apply Corrective Action
          ↓
Re-test Connectivity
```

The process should move from the device and physical connection toward the network infrastructure.

## 18. Example: Wi-Fi Connected but No Internet

When Wi-Fi shows as connected but Internet access is unavailable:

```
Wi-Fi Connected
      ↓
Check Other Devices
      ↓
Check Network Adapter
      ↓
Check IP Configuration
      ↓
Check Router
      ↓
Check Router Configuration
      ↓
Correct Configuration if Required
      ↓
Reconnect Device
      ↓
Test Internet
      ↓
Verify Stable Connection
```

The objective is to determine whether the problem is isolated to the device or affects the router/network.

## 19. Example: Ethernet Connected but No Internet

When an Ethernet-connected device has no Internet access:

```
Ethernet Connected
       ↓
Check Cable
       ↓
Check Network Adapter
       ↓
Check Driver
       ↓
Check IP Configuration
       ↓
Check Switch / Router
       ↓
Check Internet Availability
       ↓
Correct Identified Problem
       ↓
Re-test Connection
       ↓
Verify Internet Access
```

Physical connection, adapter configuration, IP configuration, and network infrastructure should all be considered.

## 20. Verification

After completing network troubleshooting:

- Confirm that the device connects correctly.
- Verify the assigned IP configuration.
- Confirm that there are no IP conflicts.
- Test communication with other LAN devices.
- Verify Internet access when applicable.
- Test Wi-Fi or Ethernet stability.
- Check network speed when relevant.
- Confirm that required shared resources are accessible.
- Verify that the network remains stable after reconnection or restart.

Verification should confirm both the original connectivity problem and the stability of the final network configuration.

## 21. Completion Criteria

The troubleshooting process is considered successful when:

- The affected device connects correctly.
- The correct IP configuration is applied.
- No IP conflicts remain.
- LAN communication works as expected.
- Internet access is restored when required.
- Network adapters and drivers operate correctly.
- Router and switch configuration supports the required network.
- File sharing works when required.
- The connection remains stable during testing.
- Final verification has been completed.

## Diagnostic Principle

Network problems should be approached from the simplest physical and device-level causes toward the network infrastructure.

The preferred approach is:

**Identify → Inspect → Connect → Configure → Test → Correct → Re-test → Verify**

The objective is to identify whether the problem originates from the device, cable, network adapter, IP configuration, switch, router, or Internet connection and then apply the appropriate solution without unnecessary changes.
```
