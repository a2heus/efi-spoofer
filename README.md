# 🚀 EFI Spoofer

Here is my personal EFI spoofer. You can change serials in `Startup.nsh`.

## 📖 Tutorial

1. **🔑 Prepare a USB Key:**
   - Take a USB key.
   - Format it as FAT32.

2. **💾 Transfer Files:**
   - Put the files you just downloaded onto the USB key.

3. **⚙️ Modify BIOS Settings:**
   - Go to your BIOS.
   - Disable TPM and Secure Boot.

4. **🔄 Change Boot Order:**
   - Set the boot order to prioritize your USB key first and then Windows.
   - Save the changes and exit the BIOS.

5. **🎉 Boot and Confirm:**
   - Boot into Windows using the USB key.
   - Once you're on Windows, all your serial numbers should be changed.

## ✏️ Customize

To customize the serial numbers, open `Startup.nsh` and modify the serials (e.g., `65D4F654SD56SDF6`).
