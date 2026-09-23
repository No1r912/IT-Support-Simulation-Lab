# Scenario 04: Linux System Troubleshooting

## 1. Scenario

This scenario simulates an IT Support Technician diagnosing and resolving a system performance and service issue on a Linux computer.

---

## 2. User Report

The user reports that the Linux computer has become slow and some applications or system services are not responding correctly, preventing them from completing their normal tasks.

---

## 3. Symptoms

The reported symptoms include:

* System responds slowly.
* Applications may freeze or become unresponsive.
* System services may not function correctly.
* High CPU or memory usage may be observed.
* Commands may take longer than expected to execute.
* The problem may occur repeatedly.
* The user may experience delays when opening applications or accessing system resources.

---

## 4. Initial Investigation

Before applying any changes, the Linux system was investigated to identify the source of the performance or service problem.

The following areas were checked:

* CPU usage.
* Memory usage.
* Running processes.
* Disk space.
* System uptime.
* Running services.
* System logs.
* Network connectivity.
* Application or service status.

### Initial Finding

The issue was isolated to the Linux system rather than the physical computer hardware. Further investigation was required to determine whether the problem was caused by a resource-intensive process, insufficient system resources, disk usage, or a system service failure.

---

## 5. Tools and Commands Used

### Software

* Ubuntu Linux.
* Linux Terminal.
* System Monitor.
* GNOME System Monitor.

### Commands / Utilities

* `top`
* `ps`
* `free`
* `df`
* `uptime`
* `systemctl`
* `journalctl`
* `kill`
* `ping`

### Shortcuts

```
Ctrl + Alt + T
```

### System Log Location

```
/var/log/
```

---

## 6. Findings

The Linux system was examined using terminal-based diagnostic commands to identify resource usage, running processes, disk capacity, system services, and system log information.

CPU and memory usage were reviewed using `top` and `free`. Running processes were examined using `ps`, while disk space was checked using `df`.

System services and system logs were also investigated using `systemctl` and `journalctl`.

**Finding:**

A resource-intensive process was identified as contributing to the system performance problem. The affected process was consuming an unusually high amount of system resources and affecting normal system responsiveness.

---

## 7. Possible Causes

Several possible causes were considered:

* Resource-intensive process.
* High CPU usage.
* High memory usage.
* Too many running processes.
* Failed system service.
* Insufficient available disk space.
* Application or service error.
* Background process consuming system resources.
* System configuration issue.
* Temporary system or application failure.

---

## 8. Troubleshooting Procedure

### Step 1: Reproduce the System Performance Issue

The technician used the Linux computer normally to confirm that the reported performance problem could be reproduced.

Applications were opened and system responsiveness was observed.

**Result:**

The Linux system was confirmed to be responding slowly during normal operation.

---

### Step 2: Check System Resource Usage

The Linux Terminal was opened using:

```
Ctrl + Alt + T
```

The following command was executed:

```
top
```

CPU and memory usage were monitored to identify processes consuming excessive system resources.

**Result:**

A process with unusually high resource usage was identified and selected for further investigation.

---

### Step 3: Check Running Processes

The running processes were reviewed using:

```
ps aux
```

The technician examined the process list to identify the application or service associated with the high resource usage.

**Result:**

The resource-intensive process was identified and its process information was recorded before making any changes.

---

### Step 4: Check Memory Usage

System memory usage was checked using:

```
free -h
```

The technician reviewed the total, used, free, and available memory.

**Result:**

Memory usage was reviewed and sufficient available memory was confirmed after identifying the main resource-intensive process.

---

### Step 5: Check Disk Space

Available disk space was checked using:

```
df -h
```

The technician reviewed the filesystem usage to determine whether insufficient disk space could be contributing to the system problem.

**Result:**

Disk usage was checked and no critical filesystem capacity issue was identified.

---

### Step 6: Check System Services

The technician checked the status of relevant system services using:

```
systemctl --failed
```

The command was used to identify services that had entered a failed state.

The status of an affected service could then be checked using:

```
systemctl status service-name
```

**Result:**

System services were reviewed and the service status information was used to determine whether a failed service was contributing to the problem.

---

### Step 7: Review System Logs

Linux system logs were reviewed using:

```
journalctl -p err -b
```

The technician examined recent error messages to identify system or service-related problems.

The `/var/log/` directory was also considered when reviewing available system logs.

**Result:**

Recent system errors were reviewed and no unrelated critical system failure was identified.

---

### Step 8: Investigate the Resource-Intensive Process

The identified process was investigated to determine whether it was required for normal system operation.

The technician confirmed the process name and process ID before deciding whether it could safely be terminated.

If the process was confirmed to be unresponsive or unnecessary, it was terminated using:

```
kill PID
```

The actual process ID identified during the investigation was used.

**Result:**

The resource-intensive process was safely terminated after confirming that it was contributing to the system performance issue.

---

### Step 9: Test the System Again

After terminating the affected process, the technician tested the Linux system again.

The following areas were checked:

* System responsiveness.
* CPU usage.
* Memory usage.
* Application performance.
* System services.
* General system operation.

The `top` command was used again to monitor resource usage.

**Result:**

System responsiveness improved and CPU usage returned to a normal operating level.

---

## 9. Verification

After applying the troubleshooting steps, the Linux system was tested again to confirm that the performance issue had been resolved.

The technician verified that:

* The system responded normally.
* CPU usage returned to a normal level.
* Memory usage was stable.
* Applications opened normally.
* The affected process was no longer consuming excessive resources.
* System services were operating normally.
* No new critical errors were observed.
* The system remained stable during testing.

### Verification Result

**The Linux system returned to normal operation and was functioning correctly after the troubleshooting process.**

---

## 10. Result

The Linux system performance issue was successfully investigated and resolved.

The technician identified a resource-intensive process that was affecting system responsiveness. The process was safely terminated and the system was tested again to confirm that normal performance had been restored.

**Status: RESOLVED**

---

## 11. Evidence

The following evidence will be collected:

* Linux system showing the reported performance problem.
* `top` showing CPU and memory usage.
* `ps aux` showing running processes.
* `free -h` showing memory usage.
* `df -h` showing disk usage.
* `systemctl --failed` showing service status.
* `journalctl` showing system logs.
* Resource-intensive process identification.
* Process termination.
* Final system performance verification.

### Evidence Files

```
Screenshots/
├── 01-system-performance-issue.png
├── 02-top-resource-usage.png
├── 03-running-processes.png
├── 04-memory-usage.png
├── 05-disk-usage.png
├── 06-service-status.png
├── 07-system-logs.png
├── 08-process-identification.png
├── 09-process-termination.png
└── 10-system-verification.png
```

---

## 12. Technician Notes

The technician should investigate system performance problems systematically before terminating processes or modifying system services.

Resource usage should be checked using appropriate monitoring commands, and the process responsible for abnormal resource consumption should be identified before taking action.

Processes should only be terminated after confirming that they are safe to stop and are contributing to the reported problem. System logs should also be reviewed to identify relevant errors or service failures.

The technician should record important process information, system resource usage, service status, and relevant log entries before and after making changes.

---

## 13. Skills Demonstrated

This scenario demonstrates the following IT Support skills:

* Linux system troubleshooting.
* Linux command-line usage.
* System performance monitoring.
* CPU usage analysis.
* Memory usage analysis.
* Process management.
* Linux process identification.
* System service management.
* Linux log analysis.
* Disk space monitoring.
* `top` usage.
* `ps` usage.
* `free` usage.
* `df` usage.
* `systemctl` usage.
* `journalctl` usage.
* `kill` usage.
* Problem identification.
* Troubleshooting documentation.
* Verification and validation.
* Technical evidence collection.

---

## 14. Conclusion

This scenario demonstrates a structured approach to troubleshooting a Linux system performance issue by reproducing the problem, monitoring system resources, examining running processes, checking memory and disk usage, investigating system services and logs, identifying a resource-intensive process, safely terminating the affected process, and verifying that normal system performance has been restored.

The structured troubleshooting process helps the technician identify the source of Linux system problems while reducing unnecessary system changes and provides a clear record of the investigation, troubleshooting process, resolution, and verification.
