# Scenario 02: Application Failure

## 1. Scenario

This scenario simulates an IT Support Technician diagnosing and resolving an application failure on a Windows computer.

---

## 2. User Report

The user reports that an application does not open correctly or closes unexpectedly after launch, preventing them from continuing their tasks.

---

## 3. Symptoms

The reported symptoms include:

- Application fails to launch.
- Application may freeze or become unresponsive.
- Application may close unexpectedly.
- An error message may appear.
- Other applications continue to work normally.
- The problem may occur repeatedly when launching the affected application.

---

## 4. Initial Investigation

Before applying any changes, the application failure was investigated to identify the cause of the problem.

The following areas were checked:

- Affected application.
- Application launch behaviour.
- Error messages.
- Application process in Task Manager.
- Other running applications.
- Windows Event Viewer logs.
- Application permissions.
- Application version and available updates.

### Initial Finding

The issue was isolated to the affected application rather than the entire Windows operating system. Further investigation was required to identify the specific cause of the application failure.

---

## 5. Tools and Commands Used

### Software

- Windows 10/11
- Task Manager
- Event Viewer
- Windows Settings
- Control Panel
- Application settings

### Commands / Utilities

- `eventvwr`
- Task Manager
- Application Repair
- Application installer/updater

### Shortcuts

```
Ctrl + Shift + Esc
Win + R
```

### Event Viewer Location

```
Windows Logs → Application
```
---

## 6. Findings

The application was tested and the failure was reproduced. Task Manager was used to check whether the application process was running in the background, while Event Viewer was reviewed for application-related errors. The application permissions and available updates were also checked before attempting to repair or reinstall the application.

**Finding:**

The application failure was associated with corrupted application files, which prevented the application from launching correctly.

---

## 7. Possible Causes

Several possible causes were considered:

* Corrupted application files.
* Outdated application version.
* Missing or corrupted dependencies.
* Application process becoming stuck.
* Insufficient permissions.
* Corrupted user configuration.
* Conflict with another background process.
* Windows or application-related errors.

---

## 8. Troubleshooting Procedure

### Step 1: Reproduce the Application Failure

The affected application was launched to confirm that the reported problem could be reproduced. The application behaviour was observed and any error messages were recorded.

---

### Step 2: Check Task Manager

Task Manager was opened using:

```
Ctrl + Shift + Esc
```

The Processes tab was checked to determine whether the application was running in the background. If an unresponsive application process was identified, it was terminated using End task.

---

### Step 3: Check Event Viewer

Windows Event Viewer was opened using:

```
Win + R
eventvwr
```

The following location was checked:

```
Windows Logs → Application
```

Application-related error events were reviewed around the time the failure occurred. Event timestamps were compared with the time of the application failure.

---

### Step 4: Check Application Permissions

The application was tested with elevated permissions by right-clicking the application and selecting:

```
Run as administrator
```

This was performed to determine whether insufficient permissions were preventing the application from launching correctly.

**Result:**

The application was successfully tested with elevated permissions and insufficient permissions were ruled out as the primary cause.

---

### Step 5: Check for Application Updates

The application was checked for available updates because an outdated version may cause compatibility issues or software errors.

**Result:**

The application version was checked and updated if an update was available.

---

### Step 6: Repair or Reinstall the Application

The application's Repair option was used to restore damaged or corrupted application files. If the repair option was unavailable or unsuccessful, the application was reinstalled using the appropriate installer.

**Result:**

The corrupted application files were repaired or replaced, allowing the application to launch normally.

---

## 9. Verification

After applying the solution, the application was launched again and its functionality was tested.

The technician verified that:

* The application launched successfully.
* The application did not immediately crash.
* The application responded normally.
* The main application functions worked correctly.
* No new application failure was observed during testing.

### Verification Result

**The application launched successfully and was functioning normally after the troubleshooting process.**

---

## 10. Result

The application failure was successfully investigated and resolved. The corrupted application files were repaired or replaced, and the application was tested to confirm that it was functioning normally.

---

## 11. Evidence

The following evidence will be collected:

* Application showing the reported failure.
* Task Manager showing the affected application process.
* Event Viewer showing application-related errors.
* Application permissions/settings.
* Application update status.
* Application repair or reinstallation process.
* Application launching successfully after repair.
* Successful application functionality test.

### Evidence Files

```
Screenshots/
├── 01-application-failure.png
├── 02-task-manager.png
├── 03-event-viewer.png
├── 04-application-settings.png
├── 05-application-update.png
├── 06-application-repair.png
├── 07-application-launch.png
└── 08-application-verification.png
```

---

## 12. Technician Notes

The technician should record the exact error message and approximate time of the failure. Event Viewer timestamps should be compared with the failure time to identify relevant application errors. Simple troubleshooting steps should be attempted before performing more invasive actions such as repairing or reinstalling the application. Application processes should only be terminated when they are confirmed to be unresponsive or causing the issue.

---

## 13. Skills Demonstrated

This scenario demonstrates the following IT Support skills:

* Application troubleshooting
* Problem reproduction
* Windows Task Manager usage
* Windows Event Viewer usage
* Event and timestamp analysis
* Application permissions management
* Application update management
* Application repair and reinstallation
* Root-cause identification
* Windows troubleshooting
* Troubleshooting documentation
* Verification and validation
* Technical evidence collection

## 14. Conclusion

This scenario demonstrates a structured approach to troubleshooting an application failure by reproducing the issue, checking the application process, investigating Windows Event Viewer logs, checking permissions and application updates, repairing or reinstalling the application, and verifying the result. This structured troubleshooting process helps identify the cause of application failures while reducing unnecessary system changes and provides a clear record of the investigation and resolution.