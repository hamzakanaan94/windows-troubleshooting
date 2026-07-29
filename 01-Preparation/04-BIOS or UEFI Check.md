# BIOS or UEFI Check

## Overview

Before installing Windows, I always verify the device firmware configuration. Identifying whether the system uses Legacy BIOS or UEFI is essential for selecting the correct partition scheme and preparing compatible installation media.

Skipping this step may result in boot failures or Windows installation errors.

---

## Objectives

- Identify the firmware mode.
- Verify boot configuration.
- Confirm storage device detection.
- Ensure the device is ready for Windows installation.

---

## Accessing the Firmware

Enter the BIOS or UEFI setup using the appropriate key for the device manufacturer.

Verify that:

- The internal storage drive is detected.
- Installed RAM is detected.
- USB boot is supported.
- The boot order is correct.

---

## Identify the Firmware Mode

Determine whether the system is using:

### Legacy BIOS

Typically found on older computers.

Recommended partition style:

- MBR

### UEFI

Used by most modern computers.

Recommended partition style:

- GPT

UEFI also supports:

- Secure Boot
- Faster boot times
- Windows 11 requirements

---

## Verify Firmware Settings

Check the following settings:

- Boot Mode
- Secure Boot status
- TPM availability (if Windows 11 is planned)
- Boot Priority
- USB Boot support
- Storage detection

---

## Technician Decision

After identifying the firmware mode, I decide which partition scheme will be used later when preparing the Windows installation USB.

This simple verification helps prevent boot compatibility issues during Windows installation.

---

## Best Practices

- Always check BIOS or UEFI before preparing installation media.
- Keep the original firmware mode whenever possible.
- Do not modify firmware settings unless necessary.
- Verify that all storage devices are correctly detected.

---

## Checklist

- Firmware mode identified
- Storage detected
- RAM detected
- USB boot available
- Boot priority verified
- Secure Boot checked
- TPM checked (if required)
