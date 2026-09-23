# Scenario 05: RAM Installation / Memory Upgrade

## 1. Scenario

This scenario simulates an IT Support Technician performing a physical RAM installation and verifying that the operating system correctly detects the newly installed memory.

---

## 2. User Report

The user reports that the computer has limited available memory and requests a RAM upgrade to improve the system's ability to handle multiple applications.

---

## 3. Symptoms

The reported symptoms include:

* Limited available system memory.
* Reduced performance when running multiple applications.
* Increased memory usage during multitasking.
* User requests a memory upgrade.

---

## 4. Initial Investigation

Before performing the hardware upgrade, the existing system configuration was investigated to determine the current memory capacity and whether the computer could support an additional RAM module.

The following areas were checked:

* Current installed RAM capacity.
* Available memory.
* System information.
* RAM type.
* RAM form factor.
* Available RAM slots.
* RAM compatibility.

### Initial System Information

**Device:** MSI Thin GF63 12VE

**Operating System:** Windows 11 Home Single Language

**Current RAM:** 8 GB

**RAM Type:** SO-DIMM DDR4

**Available RAM Slots:** 1 of 2 RAM slots occupied

### Initial Finding

The computer had 8 GB of SO-DIMM DDR4 RAM installed, with one of the two available RAM slots occupied. The system was suitable for a RAM upgrade.

---

## 5. Tools and Commands Used

### Hardware

* Compatible SO-DIMM DDR4 RAM module.
* Screwdriver.
* Computer/laptop.

### Software

* Windows 11.
* Windows Task Manager.
* System Information.

### Commands / Utilities

* `msinfo32`
* Task Manager → Performance → Memory

### Shortcuts

```
Ctrl + Shift + Esc
Win + R
```

### System Information Location

```
System Information → System Summary
```

---

## 6. Findings

The existing memory configuration was checked using Windows Task Manager and System Information. The computer was confirmed to have 8 GB of installed RAM and an available RAM slot.

The RAM specifications were reviewed before installation to ensure that the replacement module was compatible with the computer.

**Finding:**

The computer had 8 GB of SO-DIMM DDR4 RAM installed and had an available RAM slot for an additional compatible memory module. The system was suitable for upgrading the memory to 16 GB.

---

## 7. Possible Causes

Several possible causes for the limited memory performance were considered:

* Insufficient installed RAM capacity.
* Multiple applications using large amounts of memory.
* High memory usage during multitasking.
* Background applications consuming system memory.
* Limited available physical memory.
* System requiring additional memory for heavier workloads.

---

## 8. Troubleshooting Procedure

### Step 1: Check Existing RAM Configuration

The technician checked the current RAM capacity using:

```
Ctrl + Shift + Esc
```

Task Manager was opened and the following location was checked:

```
Task Manager → Performance → Memory
```

System Information was also opened using:

```
Win + R
msinfo32
```

The current RAM capacity and system information were recorded before performing the hardware upgrade.

**Result:**

The computer was confirmed to have 8 GB of installed RAM.

---

### Step 2: Check RAM Compatibility

Before installing the new RAM module, the technician checked the RAM specifications and confirmed that the module was compatible with the computer.

The following were checked:

* RAM type.
* DDR generation.
* SO-DIMM form factor.
* RAM capacity.
* Available memory slot.
* System compatibility.

**Result:**

The RAM module was confirmed to be compatible with the computer and suitable for installation.

---

### Step 3: Shut Down the Computer

The computer was completely shut down before any hardware work was performed.

The power supply was disconnected and the computer was allowed to power off completely.

**Result:**

The computer was completely powered off and prepared for hardware installation.

---

### Step 4: Open the Computer Access Panel

The technician carefully opened the laptop's access panel using the appropriate screwdriver.

The internal components were inspected to locate the RAM slots.

**Result:**

The RAM slots were located and the existing RAM configuration was identified.

---

### Step 5: Install the RAM Module

The compatible RAM module was carefully aligned with the available RAM slot.

The module was inserted at the appropriate angle and pressed down until it was securely seated by the retaining clips.

The technician checked that the RAM module was properly installed before closing the access panel.

**Result:**

The additional RAM module was successfully installed and securely seated in the available RAM slot.

---

### Step 6: Close the Access Panel and Reconnect Power

The laptop access panel was replaced and secured.

The power supply was reconnected before starting the computer.

**Result:**

The computer was securely reassembled and ready to be powered on.

---

### Step 7: Boot the Computer

The computer was powered on and allowed to complete the normal startup process.

The technician observed the boot process to ensure that the system started successfully after the RAM installation.

**Result:**

The computer booted successfully without displaying a hardware or startup error.

---

### Step 8: Verify RAM Detection

After Windows started, Task Manager was opened using:

```
Ctrl + Shift + Esc
```

The following location was checked:

```
Task Manager → Performance → Memory
```

System Information was also checked using:

```
Win + R
msinfo32
```

The installed memory capacity was compared with the original configuration.

**Result:**

Windows detected the newly installed memory and reported a total installed RAM capacity of 16 GB.

---

### Step 9: Test System Operation

The technician tested the computer after the upgrade by opening multiple applications and observing the system's performance and stability.

The system was monitored for:

* System responsiveness.
* Application operation.
* Memory detection.
* Unexpected errors.
* System stability.

**Result:**

The computer operated normally after the RAM upgrade and no hardware or system problems were observed during testing.

---

## 9. Verification

After completing the RAM installation, the computer was tested to confirm that the new memory was correctly detected and that the system was operating normally.

The technician verified that:

* The computer booted successfully.
* Windows detected the new RAM.
* The installed memory increased from 8 GB to 16 GB.
* The RAM module was properly installed.
* The system operated normally.
* Multiple applications could run normally.
* No hardware or startup errors were observed.

### Verification Result

**The RAM upgrade was successfully completed, Windows detected 16 GB of RAM, and the computer was functioning normally.**

---

## 10. Result

The RAM installation was successfully investigated, performed, and verified.

The computer's memory capacity was upgraded from 8 GB to 16 GB. Windows successfully detected the newly installed memory, and the system was tested to confirm that it was operating normally after the upgrade.

**Status: RESOLVED**

---

## 11. Evidence

The following evidence will be collected:

* System showing the original 8 GB RAM configuration.
* Task Manager showing the original memory capacity.
* System Information showing the system configuration.
* Compatible RAM module.
* RAM installation process.
* RAM module installed in the available slot.
* Computer booting after installation.
* Task Manager showing 16 GB RAM.
* System Information showing the upgraded memory.
* Final system functionality test.

### Evidence Files

```
Screenshots/
├── 01-before-installation.png
├── 02-ram-compatibility.png
├── 03-ram-module.png
├── 04-ram-installed.png
├── 05-system-boot.png
├── 06-ram-verification.png
├── 07-system-information.png
└── 08-final-verification.png
```

---

## 12. Technician Notes

The technician should confirm RAM compatibility before performing the installation. The computer should be completely powered off and disconnected from its power source before handling internal hardware.

The RAM module should be handled carefully and installed correctly into the available slot. The technician should confirm that the module is securely seated before closing the access panel.

After installation, the computer should be powered on and checked to confirm that Windows detects the new memory capacity. The system should also be tested to ensure that it boots successfully and operates normally.

---

## 13. Skills Demonstrated

This scenario demonstrates the following IT Support skills:

* Hardware installation and maintenance.
* RAM identification and compatibility checking.
* Laptop hardware handling.
* RAM installation.
* System configuration checking.
* Windows Task Manager usage.
* System Information usage.
* Hardware troubleshooting.
* Hardware upgrade procedures.
* Physical hardware safety.
* Post-installation verification.
* System boot verification.
* System performance testing.
* Troubleshooting documentation.
* Technical evidence collection.

---

## 14. Conclusion

This scenario demonstrates a structured approach to performing a RAM upgrade by investigating the existing memory configuration, checking RAM compatibility, safely installing the additional memory, verifying that the hardware was correctly installed, confirming that Windows detected the upgraded 16 GB memory capacity, and testing the system to ensure that it booted and operated normally after the upgrade.

The structured hardware troubleshooting and installation process helps reduce the risk of incorrect installation, provides clear evidence of the upgrade, and creates a documented record of the investigation, installation, verification, and final result.
