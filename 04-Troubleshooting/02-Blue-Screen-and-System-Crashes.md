# Blue Screen and System Crashes

## Overview

Blue Screen of Death (BSOD), unexpected restarts, and system crashes can be caused by hardware faults, incompatible drivers, Windows problems, overheating, or other system-level issues.

Troubleshooting begins by identifying when the problem occurs and what changed before the problem appeared.

The most likely causes are tested first before moving to less common possibilities.

---

## Common Symptoms

Typical symptoms include:

- Blue Screen of Death (BSOD)
- Unexpected system restart
- System freezing
- Software or system crashes
- Random shutdowns
- Repeated crashes during normal use
- Crashes after installing or updating a driver
- Crashes under heavier system load

---

## 1. Initial Assessment

Before making changes, identify:

- What the user was doing when the crash occurred.
- Whether the problem happens repeatedly.
- Whether the crash occurs during startup or normal Windows use.
- Whether new hardware or software was recently installed.
- Whether Windows or a driver was recently updated.
- Whether the system is overheating.
- Whether the problem occurs under higher system load.

If a BSOD displays an error message or stop code, record the available information before restarting when possible.

---

## 2. Check for Recent Changes

Recent changes can provide an important diagnostic clue.

Check whether the problem started after:

- Installing new hardware
- Replacing RAM
- Installing or updating a GPU
- Installing a new driver
- Windows Update
- Installing new software
- Changing system configuration
- Hardware cleaning or maintenance

If the timing strongly corresponds to a recent change, investigate that change first.

---

## 3. RAM Diagnosis

RAM problems were a common cause of BSOD and system instability in the systems handled during troubleshooting.

When memory is suspected:

1. Power off the system.
2. Check the RAM modules and connections.
3. Test the installed memory.
4. Test modules individually when appropriate.
5. Replace a suspected faulty module with a known-good module when available.
6. Restart the system.
7. Re-test for stability.

A system that becomes stable after replacing or isolating a RAM module provides a strong indication that the memory was contributing to the problem.

---

## 4. Driver-Related Crashes

Drivers can cause system instability when they are:

- Incorrect
- Incompatible
- Corrupted
- Intended for different hardware
- Incorrectly updated

When a crash appears after a driver installation or update:

1. Identify the affected hardware.
2. Check the installed driver.
3. Determine whether the timing corresponds to the driver change.
4. Verify compatibility.
5. Replace or correct the driver when appropriate.
6. Restart the system.
7. Re-test the affected hardware.

Driver troubleshooting is documented further in:

[03 - Driver and Hardware Problems](./03-Driver-and-Hardware-Problems.md)

---

## 5. Overheating and Thermal Problems

System instability may also be related to excessive temperatures.

Check:

- CPU temperature
- GPU temperature when applicable
- Fan operation
- Airflow
- Dust accumulation
- Cooling performance
- Thermal paste condition when hardware maintenance is required

If overheating is identified, address the cooling problem before continuing with software troubleshooting.

---

## 6. Hardware Isolation

When the cause is unclear, use a process of elimination.

Possible checks include:

- RAM testing
- PSU testing
- GPU testing
- Storage testing
- Hardware substitution
- Multimeter measurements when appropriate

The suspected component should be tested before replacing other hardware unnecessarily.

The diagnostic process should move from the most likely cause toward less likely causes based on the symptoms.

---

## 7. Software and Windows-Related Problems

If hardware appears to be functioning correctly, investigate software-related causes.

Consider:

- Recently installed applications
- Windows updates
- Driver changes
- Corrupted system components
- Malware
- Software conflicts

System Restore may be considered when an appropriate restore point exists and the problem appeared after a recent system or software change.

---

## 8. Repeated Crashes

When crashes continue after an initial fix:

1. Record the symptoms again.
2. Identify whether the crash pattern has changed.
3. Re-check the previously suspected component.
4. Test another likely cause.
5. Avoid replacing multiple components without diagnostic evidence.
6. Re-test the system after each significant change.

This helps isolate the actual cause instead of masking the problem through unnecessary hardware replacement.

---

## 9. Verification

After applying a corrective action:

- Restart the system.
- Perform normal Windows operations.
- Run the applications associated with the original problem.
- Monitor system stability.
- Monitor temperatures when relevant.
- Check for additional crashes or BSOD events.
- Verify that the original symptom has not returned.

For problems that occur under load, perform an appropriate workload test before considering the repair complete.

---

## Completion Criteria

The troubleshooting process is considered successful when:

- The original crash or BSOD no longer occurs.
- The suspected hardware or software problem has been addressed.
- Windows starts and operates normally.
- Required hardware functions correctly.
- The system remains stable during normal use.
- No new symptoms have been introduced.
- Final post-repair verification has been completed.

---

## Diagnostic Principle

A BSOD or system crash should not automatically be attributed to Windows.

Hardware, drivers, overheating, storage, power, and software should all be considered based on the symptoms.

The preferred approach is:

**Identify → Test → Isolate → Correct → Re-test → Verify**
