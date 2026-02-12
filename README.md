# Ventoy Drive Setup Guide  

How to setup Ventoy.  

---

## What is Ventoy?  

Ventoy is an open-source tool that allows you to create a bootable portable drive once and then copy multiple ISO files directly onto it.  
And you DON'T need to flash an ISO.  

Official website:  
https://www.ventoy.net  

---

## Requirements  

- USB drive (8GB minimum recommended, 16GB+ preferred)  
- A Windows PC to install Ventoy  
- Ventoy Windows ZIP package  

---

## Installing Ventoy (Windows)  

### 1. Download Ventoy  

Download the latest Windows version from the official website.  

### 2. Extract the ZIP  

Right-click the file → **Extract All** → open the extracted folder.  

### 3. Run Ventoy2Disk  

Open `Ventoy2Disk.exe`.  

If Windows SmartScreen appears:  
- Click **More info**  
- Click **Run anyway**  

### 4. Select Your USB Drive  

- Insert your USB stick  
- Select the correct device from the dropdown  

⚠️ **Warning:** The USB drive will be completely erased.  

---

## Choosing MBR or GPT  

Before clicking Install, you must choose the partition style.  

Click **Option → Partition Style** and select:  

### Use GPT if:  

- The target computer is modern (2015 or newer)  
- The system uses UEFI firmware  
- Secure Boot is enabled  
- The machine does not support Legacy/CSM boot  

### Use MBR if:  

- The target computer is older (Windows 7 era or earlier)  
- The system uses Legacy BIOS  
- You are unsure  

### Quick Rule  

- Modern PC → **GPT**  
- Older PC → **MBR**  
- Not sure → **MBR** (most compatible)  

Ventoy can be reinstalled later with a different option if needed.  

---

## Complete Installation  

1. Click **Install**  
2. Confirm the prompts  
3. Wait for completion  

Ventoy is now installed.  

---

## Adding ISO Files  

1. Open the USB drive in File Explorer  
2. Drag and drop ISO files onto the USB  
3. Safely eject the drive  

No flashing is required after installation.  

---

## Booting From the USB  

1. Insert the USB into the target computer  
2. Power on the computer  
3. Open the Boot Menu (commonly F12, F9, ESC, or DEL depending on manufacturer)  
4. Select the USB device  
5. Choose your ISO from the Ventoy menu  

---

## Troubleshooting  

If the USB does not appear in the boot menu:  

- Try switching between MBR and GPT  
- Check if Secure Boot needs to be enabled or disabled  
- Verify the ISO file is not corrupted  

Ventoy installation takes less than a minute, so changing settings is quick.  

---

## Notes  

- Most Windows and Linux ISOs work without additional configuration.  
- Keep ISO files in the root of the USB for simplicity.  

---

## License  

Ventoy is open-source software.  
Refer to the official website for licensing information.  

---
## OSes to try with Ventoy  

### Windows  

- Windows 11  
- Windows 10  
- Windows 8.1  
- Windows 7  

### Linux (Beginner Friendly)  

- Ubuntu  
- Linux Mint  
- Pop!_OS  
- Zorin OS  
- elementary OS  

### Linux (Advanced / Power Users)  

- Debian  
- Fedora  
- Arch Linux  
- openSUSE  
- Kali Linux  

### Lightweight / Older Hardware  

- Lubuntu  
- Xubuntu  
- antiX  
- Tiny Core Linux  
- Puppy Linux  

### Rescue / Recovery  

- Hiren’s BootCD PE  
- SystemRescue  
- Clonezilla  
- GParted Live  
- Rescuezilla  

### Other  

- Proxmox VE  
- FreeBSD  
- TrueNAS  
- Android-x86  
- ReactOS  

