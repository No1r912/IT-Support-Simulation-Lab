# Scenario 01: Slow Computer / System Performance Issue

## 1. Scenario

This scenario simulates resolving a Windows computer that is experiencing slow system performance.

---

## 2. User Report

The user reports that the computer has become slow and takes longer than normal to start applications, respond to commands and perform everyday tasks.

---

## 3. Symptoms

The reported symptoms include:

* Slow system startup.
* Applications take longer to open.
* Computer becomes slow when multiple applications are running.
* Delayed response when opening files or folders.
* System may temporarily freeze or become unresponsive.
* High CPU, memory or disk usage may be observed.
* Overall system performance is reduced.

---

## 4. Initial Investigation

Before applying any changes to the system the performance will be investigated to identify the cause of the performance issue and determine which system resources may be contributing to the slowdown.

The following areas of the system will be checked throughly:

* CPU usage.
* Memory usage.
* Disk usage.
* Running applications and background processes.
* Startup applications.
* Available storage space.
* Windows updates.
* System responsiveness.

### Initial Finding

The computer will be checked to confirmed whether it is experiencing reduced system performance and if a further investigation is required to identify the cause of the slowdown.

---

## 5. Tools and Commands Used

### Software

* Windows 10/11
* Task Manager
* Windows Settings
* File Explorer
* Windows Security
* Command Prompt

### Commands / Utilities

* `taskmgr`
* `msconfig`
* `cleanmgr`
* `sfc /scannow`

### Task Manager Locations

```
Task Manager → Processes
Task Manager → Performance
Task Manager → Startup apps
```

---

## 6. Findings

The system resources were examined using Task Manager and other Windows utilities. The CPU, memory and disk utilization were checked to determine whether any specific resource was being heavily used. The startup applications, background processes and available storage space were also checked to identify any potential issues.

**Finding:**

The system performance issue was associated with excessive resource usage and unnecessary background/startup processes affecting system responsiveness.

---

## 7. Possible Causes

Several possible causes were considered:

* Excessive CPU usage.
* High memory usage.
* High disk usage.
* Too many startup applications.
* Unnecessary background processes.
* Insufficient available storage space.
* Outdated Windows or application software.
* Malware or unwanted software.
* Corrupted Windows system files.
* Hardware limitations.

---

## 8. Troubleshooting Procedure

### Step 1: Reproduce the Performance Issue

The computer was used normally to confirm the reported slowdown. Applications were opened and closed while system responsiveness was observed.

**Result:**

The system was confirmed to respond slowly during normal operation.

---

### Step 2: Check Task Manager

The Processes and Performance tabs were checked to identify high CPU, memory or disk utilization. Applications and processes consuming significant system resources were reviewed.

Task Manager was opened using:

`Ctrl + Shift + Esc`

OR

`taskmgr`

**Result:**

Resource usage was examined, and processes contributing to the slowdown were identified.

---

### Step 3: Check Startup Applications

The Startup apps section in Task Manager was checked. Any unnecessary applications that were configured to start automatically with Windows were identified and disabled if they were not required at startup.

**Result:**

Unnecessary startup applications were disabled to reduce the number of processes loaded when Windows started.

---

### Step 4: Check Available Storage

Available storage space was checked using File Explorer. Temporary files and unnecessary files were reviewed to determine whether insufficient storage could be contributing to the performance issue.

Disk Cleanup was opened using:

`cleanmgr`

**Result:**

Available storage was checked and unnecessary temporary files were removed.

---

### Step 5: Check Windows Updates

Windows Update was checked to determine whether system updates were available.

The Windows Update were checked through:

`Settings → Windows Update`

**Result:**

The Windows Update status was checked and available updates were installed.

---

### Step 6: Perform Windows Security Check

Windows Security was used to perform a security check to determine whether malware or unwanted software could be affecting the overall performance of the system.

**Result:**

The system was checked for security-related causes of the performance issue.

---

### Step 7: Check Windows System Files

System File Checker was used to check and identified any corrupted Windows system files.

To check this the following command was executed:

```
sfc /scannow
```

The scan results were reviewed to determine whether any system file problems were detected.

**Result:**

Windows system files were checked for corruption and repaired if necessary.

---

### Step 8: Restart and Test the System

The computer was restarted after the troubleshooting actions were completed. System startup time, application launch time, and general responsiveness were observed to determine whether the performance issue had been resolved.

**Result:**

The computer started normally and system responsiveness improved after the troubleshooting actions.

---

## 9. Verification

After applying the troubleshooting steps, the system was tested again.

The system will be verified that:

* Windows started normally.
* Applications opened normally.
* The system responded to user input without significant delays.
* CPU, memory and disk usage were within reasonable levels during normal use.
* Unnecessary startup applications remained disabled.
* The computer operated normally during testing.

### Verification Result

**Overall system performance improved and the computer is functioning normally.**

---

## 10. Result

The slow computer issue was successfully investigated and resolved. Any unnecessary background and startup processes were reduced, system resources were checked, unnecessary files were removed and Windows system integrity was verified.

---

## 11. Evidence

The following evidence will be collected:

* Computer showing slow performance
* Task Manager showing CPU, memory and disk usage
* Task Manager Startup apps
* Available storage space
* Disk Cleanup
* Windows Update status
* Windows Security scan
* SFC scan results
* Computer after troubleshooting
* Successful performance verification

### Evidence Files

```
Screenshots/
├── 01-slow-performance.png
├── 02-task-manager-processes.png
├── 03-task-manager-performance.png
├── 04-startup-apps.png
├── 05-storage-space.png
├── 06-disk-cleanup.png
├── 07-windows-update.png
├── 08-windows-security.png
├── 09-sfc-scan.png
├── 10-system-restart.png
└── 11-performance-verification.png
```

---

## 12. Technician Notes

The technician should identify the specific resource causing the performance issue before making system changes. The CPU, memory and disk utilization should be examined using Task Manager. Any unnecessary startup applications should only be disabled when they are not required for normal system operation. Important Windows services and security software should not be disabled without a valid reason. System performance should be tested again after each major troubleshooting step to determine whether the one of the changes have fix the problem.

---

## 13. Skills Demonstrated

This scenario demonstrates the following IT Support skills:

* Windows performance troubleshooting
* Task Manager usage
* CPU, memory and disk analysis
* Startup application management
* Storage management
* Windows Update management
* Basic malware/security checking
* Windows system file checking
* Command Prompt usage
* Problem identification
* Troubleshooting documentation
* Performance verification
* Technical evidence collection

---

## 14. Conclusion

This scenario demonstrates a structured approach to troubleshooting a slow Windows computer by reproducing the problem, analysing system resource usage, investigating startup applications, storage, checking Windows updates, security, verifying system files and testing the computer after applying the appropriate troubleshooting steps. This structured process helps identify the source of performance problems while reducing unnecessary system changes and provides a clear record of the investigation and resolution.
