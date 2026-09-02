# Scenario 03: Network Connection Issue

## 1. Scenario

This scenario simulates an IT Support Technician diagnosing and resolving a network connection problem on a Windows computer.

---

## 2. User Report

The user reports that the computer is unable to access the internet or other network resources. The issue prevents the user from browsing websites, accessing online services, or using applications that require network connectivity.

---

## 3. Symptoms

The reported symptoms include:

* Internet connection is unavailable.
* Websites fail to load.
* Network icon may show a disconnected or limited connection.
* The computer may appear connected to Wi-Fi or Ethernet but cannot access the internet.
* Network resources may be unreachable.
* Applications requiring internet access may not function correctly.
* The problem may occur repeatedly.

---

## 4. Initial Investigation

Before applying any changes, the network connection was investigated to identify where the connectivity problem was occurring.

The following areas were checked:

* Physical Ethernet or Wi-Fi connection.
* Network connection status.
* Network adapter status.
* IPv4 configuration.
* Subnet mask.
* Default gateway.
* DNS configuration.
* Connectivity to the local gateway.
* Connectivity to an external IP address.
* DNS name resolution.
* Whether other devices could access the network.

### Initial Finding

The issue was isolated to the affected computer's network connectivity. Further investigation was required to determine whether the problem was related to IP configuration, DHCP, DNS, the local network, or the internet connection.

---

## 5. Tools and Commands Used

### Hardware

* Windows computer/laptop.
* Ethernet cable or Wi-Fi connection.
* Network router.

### Software

* Windows 10/11.
* Windows Network Settings.
* Command Prompt.
* Device Manager.

### Commands / Utilities

* `ipconfig`
* `ipconfig /all`
* `ipconfig /release`
* `ipconfig /renew`
* `ipconfig /flushdns`
* `ping`
* `tracert`
* `nslookup`

### Shortcuts

```text
Win + R
```

### Network Settings Location

```text
Settings → Network & Internet
```

---

## 6. Findings

The computer's network configuration and connectivity were examined using Windows network diagnostic tools.

The assigned IPv4 address, subnet mask, default gateway, and DNS configuration were checked using `ipconfig` and `ipconfig /all`.

Connectivity tests were then performed against the local gateway and an external IP address. DNS resolution was also tested using `nslookup`.

**Finding:**

The computer was connected to the local network but was experiencing an incorrect or incomplete network configuration that prevented normal internet connectivity.

---

## 7. Possible Causes

Several possible causes were considered:

* Disconnected Ethernet cable.
* Wi-Fi connection failure.
* Disabled network adapter.
* Incorrect IP configuration.
* Invalid IP address.
* Missing or incorrect default gateway.
* DHCP configuration problem.
* DNS configuration problem.
* Corrupted DNS cache.
* Network adapter driver issue.
* Router or network equipment problem.
* Internet service interruption.

---

## 8. Troubleshooting Procedure

### Step 1: Reproduce the Network Connection Issue

The technician attempted to access a known working website to confirm that the reported problem could be reproduced.

The Windows network connection status was also checked.

**Result:**

The computer was confirmed to have no normal internet connectivity.

---

### Step 2: Check Physical and Network Connection

The technician checked whether the Ethernet cable was securely connected or whether the computer was connected to the correct Wi-Fi network.

The connection status was checked using:

```text
Settings → Network & Internet
```

The network adapter was also checked to determine whether it was enabled.

**Result:**

The physical and network connection were checked, and the computer's network connection status was confirmed.

---

### Step 3: Check IP Configuration

Command Prompt was opened and the following command was executed:

```text
ipconfig
```

The technician checked the:

* IPv4 address.
* Subnet mask.
* Default gateway.

The complete network configuration was then reviewed using:

```text
ipconfig /all
```

The technician also checked the DHCP and DNS server information.

**Result:**

The computer's IP configuration was examined and an issue with the network configuration was identified.

---

### Step 4: Test the Local Gateway

The default gateway identified using `ipconfig` was tested with the `ping` command.

Example:

```text
ping 192.168.1.1
```

The actual default gateway address shown on the computer was used during testing.

**Result:**

The computer was able to communicate with the local gateway, confirming that local network connectivity was available.

---

### Step 5: Test External Network Connectivity

An external IP address was tested using:

```text
ping 8.8.8.8
```

This test was performed without relying on DNS name resolution.

**Result:**

External connectivity was tested to determine whether the issue affected general internet access or was primarily related to DNS resolution.

---

### Step 6: Test DNS Resolution

DNS resolution was tested using:

```text
nslookup google.com
```

The technician checked whether the configured DNS server could resolve the domain name into an IP address.

**Result:**

DNS resolution was tested and the results were used to determine whether DNS was contributing to the connectivity problem.

---

### Step 7: Renew the IP Configuration

Because the computer's network configuration was suspected to be incorrect, the existing DHCP configuration was released using:

```text
ipconfig /release
```

A new network configuration was then requested using:

```text
ipconfig /renew
```

The resulting configuration was checked again using:

```text
ipconfig
```

**Result:**

The computer successfully obtained a renewed IP configuration from the DHCP server.

---

### Step 8: Flush the DNS Cache

The Windows DNS cache was cleared using:

```text
ipconfig /flushdns
```

This was performed to remove potentially outdated or incorrect cached DNS information.

**Result:**

The DNS resolver cache was successfully cleared.

---

### Step 9: Test Network Connectivity Again

After renewing the IP configuration and clearing the DNS cache, the technician performed the connectivity tests again.

The following were checked:

* Default gateway connectivity.
* External IP connectivity.
* DNS resolution.
* Website access.
* Applications requiring internet access.

**Result:**

Network connectivity was restored and the computer was able to access internet resources normally.

---

## 9. Verification

After applying the troubleshooting steps, the network connection was tested again.

The technician verified that:

* The computer had a valid IPv4 address.
* The subnet mask was correctly configured.
* The default gateway was available.
* The computer could communicate with the local gateway.
* External network connectivity was available.
* DNS resolution was functioning.
* Websites loaded successfully.
* Applications requiring internet access functioned normally.

### Verification Result

**Network connectivity was successfully restored and the computer was functioning normally.**

---

## 10. Result

The network connection issue was successfully investigated and resolved.

The technician identified an incorrect or incomplete network configuration, renewed the computer's DHCP configuration, cleared the DNS cache, and performed multiple connectivity tests to confirm that network access had been restored.

**Status: RESOLVED**

---

## 11. Evidence

The following evidence will be collected:

* Windows network connection showing the reported problem.
* Network Settings showing connection status.
* `ipconfig` output.
* `ipconfig /all` output.
* Default gateway ping test.
* External IP ping test.
* DNS lookup test.
* IP release and renewal process.
* DNS cache flush.
* Successful website access.
* Final network connectivity verification.

### Evidence Files

```text
Screenshots/
├── 01-network-failure.png
├── 02-network-settings.png
├── 03-ipconfig.png
├── 04-ipconfig-all.png
├── 05-gateway-ping.png
├── 06-internet-ping.png
├── 07-dns-lookup.png
├── 08-ip-renewal.png
├── 09-dns-flush.png
├── 10-website-access.png
└── 11-network-verification.png
```

---

## 12. Technician Notes

The technician should troubleshoot network connectivity systematically by identifying where communication fails.

Testing the local gateway first helps determine whether the computer can communicate with the local network. Testing an external IP address helps determine whether general internet connectivity is available without relying on DNS. Testing DNS separately helps identify name-resolution problems.

The technician should record the IPv4 address, subnet mask, default gateway, DNS servers, and other relevant network information before making changes.

Network settings should only be modified after the existing configuration has been investigated and documented.

---

## 13. Skills Demonstrated

This scenario demonstrates the following IT Support skills:

* Network troubleshooting.
* Problem reproduction.
* Windows network configuration.
* IPv4 addressing.
* DHCP troubleshooting.
* DNS troubleshooting.
* Network connectivity testing.
* Command Prompt usage.
* `ipconfig` usage.
* `ping` usage.
* `nslookup` usage.
* Basic network diagnostics.
* Problem identification.
* Troubleshooting documentation.
* Verification and validation.
* Technical evidence collection.

---

## 14. Conclusion

This scenario demonstrates a structured approach to troubleshooting a network connection problem by reproducing the issue, checking the physical and network connection, examining the IP configuration, testing the local gateway, testing external connectivity, investigating DNS resolution, renewing the DHCP configuration, clearing the DNS cache, and verifying that network access has been restored.

The structured troubleshooting process helps the technician identify where the network problem is occurring while reducing unnecessary system changes and provides a clear record of the investigation, troubleshooting process, and final resolution.
