# Boot Menu

## Overview

After verifying the BIOS/UEFI configuration and installation media, the next step is to boot the system from the Windows installation USB drive.

Rather than permanently changing the boot order, I prefer using the temporary Boot Menu whenever possible. This preserves the customer's original firmware configuration while providing a safe and efficient way to start the Windows installation.

---

# Objectives

- Access the Boot Menu.
- Select the correct boot device.
- Verify successful USB boot.
- Troubleshoot boot-related issues.
- Preserve the customer's firmware configuration.

---

# Accessing the Boot Menu

After connecting the prepared USB drive:

1. Power on or restart the computer.
2. Press the appropriate Boot Menu key for the manufacturer.
3. Select the Windows installation USB drive.
4. Wait for Windows Setup to load.

Using the Boot Menu avoids unnecessary changes to the permanent boot order.

---

# Selecting the Correct Boot Device

Some systems display multiple entries for the same USB drive.

For example:

- UEFI: Kingston
- Kingston

When installing Windows in UEFI mode, the UEFI entry should be selected.

The selected boot option must always match the firmware mode verified earlier.

---

# If the USB Drive Does Not Appear

If the USB drive is not listed in the Boot Menu:

1. Try another USB port.
2. Restart the computer.
3. Check whether the USB drive is fully inserted.
4. Test another USB drive if available.
5. Verify BIOS/UEFI settings if necessary.

In many cases, changing the USB port is enough to resolve the issue.

---

# USB Ports

Although modern systems usually support all USB ports during boot, some devices may behave differently.

Possible causes include:

- Loose USB connection.
- Dirty USB port.
- Faulty USB port.
- Hardware-specific limitations.

Whenever possible, test another USB port before assuming there is a software problem.

---

# BIOS Verification

If no bootable USB device is detected after testing multiple USB ports, verify firmware settings such as:

- USB Boot Support
- Secure Boot
- Boot Mode
- CSM / Legacy Support

Firmware settings should only be modified if they are preventing the system from booting correctly.

---

# Confirm Successful Boot

Selecting the USB drive does not necessarily mean the boot process has succeeded.

A successful boot is confirmed only when the Windows Setup screen appears.

If an error message appears instead of Windows Setup, investigate the cause before continuing.

Possible causes include:

- Corrupted installation media
- Damaged USB drive
- USB communication errors
- Firmware compatibility issues

---

# Troubleshooting Philosophy

I avoid making assumptions.

Each issue is diagnosed step by step.

Rather than immediately changing BIOS settings or recreating the installation media, I first identify the actual source of the problem.

Many boot issues are resolved by simple actions such as changing the USB port or selecting the correct boot option.

---

# Technician Philosophy

A successful boot process begins with careful preparation.

Reliable installation media, proper firmware configuration, and systematic troubleshooting eliminate most boot-related problems before Windows installation even begins.

My objective is to make the boot process predictable, reliable, and repeatable without introducing unnecessary configuration changes.

---

# Checklist

- USB drive connected
- Boot Menu opened
- Correct boot device selected
- Firmware mode matched
- Windows Setup loaded successfully
- Boot issues resolved (if any)
- Ready for disk partitioning
