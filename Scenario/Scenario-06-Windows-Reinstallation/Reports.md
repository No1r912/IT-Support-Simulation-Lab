# Scenario 06: Windows Reinstallation

## 1. Scenario

This scenario simulates an IT Support Technician performing a clean Windows reinstallation to resolve persistent operating system and software-related problems and restore the computer to a stable working condition.

---

## 2. User Report

The user reports that the computer has been experiencing persistent Windows and software-related problems. Previous troubleshooting attempts have not fully resolved the issues, and the user requests a Windows reinstallation to restore the system to a clean and stable state.

---

## 3. Symptoms

The reported symptoms include:

* Slow or inconsistent system performance
* Applications failing or behaving unexpectedly
* Windows system errors
* General operating system instability
* Previous troubleshooting attempts have not fully resolved the problems
* User requests a clean Windows installation

---

## 4. Initial Investigation

Before performing the Windows reinstallation, the technician investigated the system to determine whether the problems were likely related to the operating system or installed software.

The following areas were checked:

* Current Windows version
* System performance
* Installed applications
* Windows system condition
* Available storage space
* Device functionality
* Existing user data
* Backup requirements

### Initial System Information

**Device:** MSI Thin GF63 12VE
**Operating System:** Windows 11 Home Single Language
**Storage:** Internal SSD
**Installation Type:** Existing Windows installation
**Support Action:** Clean Windows reinstallation

### Initial Finding

The computer was able to boot into Windows, but persistent software and operating system problems remained after standard troubleshooting. A clean Windows reinstallation was therefore selected to restore the operating system to a clean state.

---

## 5. Tools and Commands Used

### Hardware

* Computer/laptop
* USB flash drive
* Power adapter

### Software

* Windows 11 installation media
* Windows 11
* Windows Settings
* File Explorer
* Device Manager
* Windows Update

### Commands and Utilities

* `msinfo32`
* `winver`
* Windows Setup
* Device Manager
* Windows Update

### Keyboard Shortcuts

```text
Win + R
Win + E
```

### System Information

```text
Win + R
msinfo32
```

**Location:**

```text
System Information → System Summary
```

### Windows Version

```text
Win + R
winver
```

---

## 6. Findings

The existing Windows installation was investigated before proceeding with the reinstallation.

The system was confirmed to be experiencing persistent operating system and software-related problems that had not been fully resolved through standard troubleshooting.

Important user data and the existing Windows installation were also considered before proceeding because a clean installation can remove applications, settings, and files from the target installation.

**Finding:**
A clean Windows installation was selected to remove the existing software and operating system issues and provide a clean environment for further use.

---

## 7. Possible Causes

Several possible causes for the Windows problems were considered:

* Corrupted Windows system files
* Software conflicts
* Incorrect system configurations
* Failed or problematic applications
* Accumulated software issues
* Damaged operating system components
* Unwanted or unnecessary software
* General instability within the existing Windows installation

These were considered possible causes rather than confirmed root causes because the reinstallation itself removes the existing software environment.

---

## 8. Troubleshooting Procedure

### Step 1: Check the Existing Windows Installation

The technician checked the current Windows installation and system information.

The Windows version was checked using:

```
Win + R
winver
```

System Information was also opened using:

```
Win + R
msinfo32
```

The existing system configuration was recorded before beginning the reinstallation.

**Result:**
The computer was confirmed to be running Windows 11 Home Single Language and was able to boot normally into the existing Windows installation.

---

### Step 2: Check User Data and Backup Requirements

Before modifying the Windows installation, the technician identified important user files and determined which data needed to be preserved.

The following areas were considered:

* Documents
* Downloads
* Desktop files
* Pictures
* Project files
* Other important user data

Required data was backed up before continuing with the clean installation.

**Result:**
Important user data was identified and prepared for backup before the Windows installation process.

---

### Step 3: Prepare Windows Installation Media

A bootable Windows installation USB was prepared for the reinstallation process.

The technician verified that the installation media was available and that the computer could boot from the USB device.

**Result:**
The Windows installation media was prepared successfully and was ready for use.

---

### Step 4: Boot from Windows Installation Media

The computer was restarted and configured to boot from the Windows installation media.

The Windows Setup environment was loaded from the USB device.

**Result:**
The computer successfully booted into the Windows Setup environment.

---

### Step 5: Start Windows Setup

Windows Setup was opened and the required installation settings were selected.

The technician reviewed the Windows installation options before continuing.

**Result:**
Windows Setup was successfully started and the installation process was ready to continue.

---

### Step 6: Select the Installation Drive

The available storage devices and partitions were reviewed during Windows Setup.

The technician carefully identified the correct target drive before making changes to the existing Windows installation.

**Result:**
The correct target storage drive was identified for the Windows installation.

---

### Step 7: Perform the Clean Windows Installation

The existing Windows installation was removed as required, and Windows was installed onto the selected target drive.

The installation process copied the required Windows files and configured the operating system. The computer restarted during the installation process.

**Result:**
Windows was successfully installed onto the target storage drive.

---

### Step 8: Complete Initial Windows Configuration

After the installation was completed, the technician configured the initial Windows settings.

This included:

* Region settings
* Keyboard layout
* User account
* Network connection
* Basic Windows configuration
* Privacy settings

**Result:**
The newly installed Windows environment was successfully configured, and the computer was able to boot into the new Windows installation.

---

### Step 9: Check Device Drivers

After Windows was installed, Device Manager was opened to check the system hardware and identify any missing or problematic drivers.

The following hardware was checked:

* Display adapter
* Network adapter
* Audio device
* Chipset/system devices
* Input devices
* Other detected hardware

**Result:**
The system hardware was checked, and required drivers were installed or updated where necessary.

---

### Step 10: Install Windows Updates

Windows Update was opened, and available operating system updates were installed.

The technician allowed the system to complete the required updates and restarted the computer when necessary.

**Result:**
Windows Update completed successfully, and the operating system was brought up to date.

---

### Step 11: Install Required Applications

Required applications and utilities were reinstalled after Windows was configured.

Only necessary software was installed to provide the user with a clean and functional working environment.

**Result:**
The required applications were installed successfully and launched normally.

---

### Step 12: Test System Operation

The technician tested the computer after completing the Windows reinstallation.

The system was checked for:

* System responsiveness
* Application operation
* Network connectivity
* Hardware functionality
* Windows stability
* Unexpected errors
* Successful system startup

**Result:**
The computer booted successfully and operated normally after the Windows reinstallation.

---

## 9. Verification

After completing the Windows reinstallation, the computer was tested to confirm that the operating system was functioning correctly.

The technician verified that:

* The computer booted successfully
* Windows loaded normally
* The new Windows installation was detected correctly
* Required hardware drivers were functioning
* Network connectivity was working
* Windows Update completed successfully
* Required applications launched normally
* The system was responsive
* No major Windows errors were observed
* The system operated normally during testing

### Verification Result

**The Windows reinstallation was successfully completed. The operating system was functioning normally, and the computer passed the post-installation system checks.**

---

## 10. Result

The Windows reinstallation was successfully investigated, performed, and verified.

The previous Windows installation was replaced with a clean Windows environment. Required configuration, drivers, updates, and applications were restored, and the computer was tested to confirm that it was operating normally.

**Status: RESOLVED**

---

## 11. Evidence

The following evidence was collected or will be collected as part of the scenario:

* Existing Windows version before reinstallation
* System Information before reinstallation
* Important data backup
* Windows installation media
* Windows Setup screen
* Windows installation process
* Target drive selection
* Initial Windows configuration
* Device Manager after installation
* Windows Update after installation
* Required applications after installation
* Final Windows desktop
* Final system functionality test

### Evidence Files

```text
Screenshots/
├── 01-before-reinstallation.png
├── 02-windows-version.png
├── 03-system-information.png
├── 04-data-backup.png
├── 05-windows-installation-media.png
├── 06-windows-setup.png
├── 07-drive-selection.png
├── 08-installation-progress.png
├── 09-initial-windows-setup.png
├── 10-device-manager.png
├── 11-windows-update.png
├── 12-required-applications.png
└── 13-final-verification.png
```

---

## 12. Technician Notes

The technician should confirm that important user data has been backed up before performing a clean Windows installation.

The correct storage drive and partition must be identified carefully before deleting, formatting, or installing Windows. Selecting the incorrect drive may result in permanent data loss.

The computer should remain connected to power throughout the installation process to prevent an unexpected shutdown.

After installation, the technician should:

* Check Device Manager
* Install required drivers
* Run Windows Update
* Configure the system
* Install required applications
* Restore required user data
* Test the computer before returning it to the user

The technician should also confirm that the required applications have been reinstalled and that important user data has been successfully restored.

---

## 13. Skills Demonstrated

This scenario demonstrates the following IT Support skills:

* Windows operating system installation
* Operating system troubleshooting
* Windows system configuration
* Windows installation media preparation
* Boot device management
* Disk and partition identification
* Data backup procedures
* Driver management
* Windows Update
* Software installation
* Device Manager usage
* System Information usage
* Windows troubleshooting
* Post-installation configuration
* System boot verification
* Network connectivity testing
* System functionality testing
* Data protection considerations
* Technical documentation
* Evidence collection

---

## 14. Conclusion

This scenario demonstrates a structured approach to performing a Windows reinstallation by investigating the existing operating system, identifying possible software and operating system problems, preparing installation media, protecting important user data, performing a clean Windows installation, configuring the new operating system, installing required drivers and updates, and verifying that the computer operates normally after the reinstallation.

The structured reinstallation process provides a method for restoring an unstable Windows environment while reducing the risk of data loss and incorrect system configuration.

The documented investigation, installation, verification, and evidence collection also provide a clear record of the IT Support Technician's work.
