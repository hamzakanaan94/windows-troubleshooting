# BIOS or UEFI Configuration

## Overview

Before starting the Windows installation, I verify the firmware configuration of the device.

Understanding whether the system uses Legacy BIOS or UEFI is essential for selecting the correct installation method and avoiding compatibility issues.

At this stage, I inspect the firmware configuration without making unnecessary changes.

My goal is to keep the system as close as possible to its original configuration unless a specific technical issue requires modification.

---

# Objectives

- Identify the firmware type.
- Verify installation compatibility.
- Prevent boot-related errors.
- Confirm the USB installation media matches the firmware mode.
- Make changes only when necessary.

---

# Identify Firmware Type

The first step is determining whether the device is using:

- Legacy BIOS
- UEFI

This decision affects:

- Partition style (MBR or GPT)
- Windows installation compatibility
- Boot process
- Secure Boot availability
- TPM support

---

# Verify Installation Media Compatibility

Before booting from the USB drive, confirm that the installation media matches the firmware configuration.

General guideline:

- Legacy BIOS → MBR
- UEFI → GPT

Using the correct combination helps prevent installation and boot errors.

---

# Review BIOS Settings

Before changing anything, review the current firmware configuration.

Items to check include:

- Boot Mode
- Secure Boot
- Fast Boot
- CSM / Legacy Support
- TPM Status
- Boot Priority

Most systems do not require any changes if everything is already configured correctly.

---

# Secure Boot

Secure Boot is left enabled whenever possible.

If the installation media cannot boot because of Secure Boot restrictions, I evaluate the situation before making any changes.

Secure Boot is only disabled when it is technically necessary.

---

# Fast Boot

Some modern systems boot so quickly that accessing the BIOS or Boot Menu becomes difficult.

If Fast Boot prevents access to firmware settings or USB booting, it may be temporarily disabled.

Otherwise, no changes are made.

---

# CSM / Legacy Support

Legacy Support (CSM) is only enabled when required for older hardware or legacy operating systems.

Modern UEFI systems should continue using native UEFI mode whenever possible.

---

# Boot Order

I normally avoid changing the permanent Boot Order.

Instead, I prefer using the temporary Boot Menu to boot from the USB drive.

This keeps the customer's firmware configuration unchanged after the installation is complete.

Boot Order is modified only if a technical issue requires it.

---

# GPT and MBR Considerations

If the device fully supports UEFI, I generally recommend using GPT during a clean Windows installation.

GPT provides better compatibility with modern hardware and Windows features.

If converting from MBR to GPT is appropriate, I explain the process to the customer before proceeding.

---

# Troubleshooting

If the USB drive fails to boot, I verify:

- Firmware mode
- USB compatibility
- Partition style
- Secure Boot settings
- CSM configuration
- Boot device selection

Only after identifying the actual cause do I modify firmware settings.

---

# Technician Philosophy

The BIOS is not something to modify without reason.

If the system is already configured correctly, I leave the firmware settings unchanged.

Every adjustment should have a clear technical purpose.

Understanding the firmware is more important than changing it.

My objective is to achieve a successful Windows installation while preserving the stability of the customer's device.

---

# Checklist

- Firmware type identified
- USB installation media verified
- Secure Boot reviewed
- Fast Boot reviewed
- CSM checked (if required)
- TPM status reviewed
- Boot Menu confirmed
- Boot Order preserved whenever possible
- Ready to boot from USB
