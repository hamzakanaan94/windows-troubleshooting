# Windows Installation

## Purpose

The Windows installation process is not simply about deploying an operating system. It is about building a stable, reliable, and maintainable working environment that matches both the customer's requirements and the device's hardware capabilities.

Every installation should result in a clean, optimized, and professional system rather than just a functioning Windows installation.

---

# Installation Language

Windows installation is always performed using the English version of Windows.

Using the original English installation media provides better compatibility with official Microsoft documentation, simplifies troubleshooting, and avoids translation inconsistencies.

If the customer prefers another language, the display language can be installed and configured after Windows installation has been completed.

---

# Windows Edition Selection

Windows Pro is the preferred edition for all supported devices.

The Pro edition provides additional administrative, networking, management, and security capabilities that may become valuable in the future, even if they are not immediately required.

Home Edition is only installed when specifically requested by the customer.

---

# Product Activation

If the computer contains a valid OEM license, Windows will activate automatically.

Otherwise, installation continues by selecting:

> **I don't have a product key**

Product activation is discussed with the customer after installation has been completed.

Whenever possible, official Microsoft licensing is recommended.

---

# Installation Type

Always select:

> **Custom: Install Windows only (Advanced)**

Upgrade installations are intentionally avoided.

A clean installation provides:

- Better long-term system stability.
- Fewer compatibility issues.
- Removal of corrupted system files.
- Elimination of previous software conflicts.
- A predictable installation environment.

---

# Target Partition

The Windows partition is selected according to the storage layout agreed upon during the **Preparation** phase.

Partition modifications should not be made during installation unless a technical issue requires them.

---

# Installation Monitoring

The installation process should always be monitored.

Observe:

- File copying progress.
- Installation stages.
- Unexpected error messages.
- Restart sequence.

Continuous monitoring allows immediate response if any issue occurs and reduces unnecessary downtime.

---

# First Restart

After the first restart, Windows may display:

> **Press any key to boot from USB...**

Do **not** press any key.

The USB installation media remains connected until Windows reaches the desktop successfully.

Removing the USB drive too early is unnecessary and may interrupt recovery if Windows temporarily requires installation files.

---

# Initial Setup (OOBE)

Internet connectivity is preferred during the initial setup.

The account type depends on the customer's requirements.

### Microsoft Account

Recommended for personal devices because it provides:

- Password synchronization.
- Microsoft services integration.
- OneDrive synchronization.
- Easier account recovery.
- Cross-device settings synchronization.

### Local Account

Recommended for customers who:

- Prefer maximum privacy.
- Do not require Microsoft cloud services.
- Use the computer offline.
- Prefer complete local control over the operating system.

---

# First Desktop Boot

After Windows reaches the desktop, do not begin configuration immediately.

Allow Windows approximately **1–2 minutes** to complete its background initialization.

Typical background activities include:

- Windows Services startup.
- Device initialization.
- Search indexing.
- Microsoft Defender initialization.
- Scheduled background tasks.

Beginning configuration too early may interfere with these processes and produce inaccurate performance observations.

---

# Initial System Validation

Before continuing, verify:

- System responsiveness.
- Correct date and time.
- Correct time zone.
- Successful internet synchronization (if connected).
- No unexpected startup errors.

Correct system time is essential for:

- Windows Update.
- HTTPS certificates.
- Microsoft Account synchronization.
- Software activation.

---

# Computer Name

Computer naming depends on the deployment environment.

### Business Devices

Use the customer's naming convention or the organization's IT policy.

### Personal Devices

Either:

- Use the customer's preferred computer name.
- Keep the default Windows-generated name.

---

# Next Stage

Once Windows installation has been completed successfully, continue with:

1. Create a System Restore Point.
2. Install stable Windows Updates.
3. Install manufacturer drivers.
4. Verify Device Manager.
5. Install core applications.
6. Install customer-requested software.
7. Perform final system optimization.

---

# Summary Checklist

- ✅ English installation media used.
- ✅ Windows Pro selected.
- ✅ Correct installation type (Custom).
- ✅ Correct target partition selected.
- ✅ Installation monitored successfully.
- ✅ USB left connected until desktop.
- ✅ Account configured according to customer requirements.
- ✅ Windows allowed to complete background initialization.
- ✅ Date, time, and time zone verified.
- ✅ Computer name confirmed.
- ✅ Ready for Windows Update.
