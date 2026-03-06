# 📂 Complete EFI Collection for Desktop & Laptop Hackintosh Systems

Welcome!  
This folder contains a fully organized collection of ready-to-use EFI folders for a wide range of Desktop and Laptop platforms.  
Each EFI is pre-configured, optimized, and structured based on the CPU generation to ensure maximum stability and compatibility with macOS.

https://hackinos.com/files/file/18-efi-collection/

Simply **download → copy → reboot**, and your system is ready.

**Download Password:** `www.hackinOS.com`

## 🖥️ Desktop EFI Collection

Includes EFI folders for the most common Intel desktop generations:

- Desktop-SandyBridge - https://cuty.io/DSandyBridge
- Desktop-IvyBridge - https://cuty.io/DIvyBridge
- Desktop-Haswell - https://cuty.io/DHaswell
- Desktop-Broadwell - https://cuty.io/DBroadwell
- Desktop-Skylake - https://cuty.io/DSkylake
- Desktop-Kabylake - https://cuty.io/DKabyLake
- Desktop-Coffeelake - https://cuty.io/DCoffeeLake
- Desktop-Cometlake - https://cuty.io/DCometLake

**Optimizations included:**
- Reliability & stable performance  
- Sleep/Wake support  
- Integrated graphics (if applicable)  
- Smooth macOS operation  

## 💻 Laptop EFI Collection

A complete EFI set for various laptop generations:

- Laptop-SandyBridge - https://cuty.io/LSandyBridge
- Laptop-IvyBridge - https://cuty.io/LIvyBridge
- Laptop-Haswell - https://cuty.io/LHaswell
- Laptop-Skylake - https://cuttlinks.com/LSkylake
- Laptop-Kabylake - https://cuty.io/LKabyLake
- Laptop-Coffeelake-Whiskeylake - https://cuty.io/LCoWhisLake
- Laptop-Coffeelakeplus-Cometlake - https://cuty.io/LCoffComet
- Laptop-Icelake - https://cuty.io/LIceLake

**Laptop-specific patches included:**
- Trackpad (I2C/PS2) drivers  
- Battery management  
- Audio layout-ID patches  
- Brightness/Backlight control  
- Sleep/Wake fixes  

## ⭐ Why This EFI Collection is Useful

- ✔️ Clearly organized by CPU generation  
- ✔️ 100% pre-configured – ready to use  
- ✔️ Ideal for beginners and advanced users  
- ✔️ Stable and optimized for macOS on real hardware  

## 📘 How to Copy the EFI Using Explorer++ (Recommended)

Using **Explorer++ (Run as Administrator)** is the safest way to mount and write to the EFI partition on Windows.

## 🔧 Step-by-Step Instructions

### 1️⃣ Download Explorer++
- Download the portable version of Explorer++  
- **Right-click → Run as Administrator**  
  (Required to write to protected EFI partitions)

### 2️⃣ Mount the EFI Partition
Use any of these tools to mount EFI:

- MountEFI.exe  
- BootDiskUtility  
- EaseUS Partition Master  
- DiskGenius  
- Any tool that can mount the hidden EFI partition  

After mounting, an EFI drive (e.g., `EFI` or `H:\`) will appear.

### 3️⃣ Open the Mounted EFI Partition
Inside **Explorer++ (Admin mode)**:

- Navigate to the mounted EFI partition  
- Open:  
  `EFI → OC` or  
  `EFI → CLOVER`  
  (depending on your previous installation)

### 4️⃣ Delete the Old EFI
Before copying the new one:

- Select the existing `EFI` folder  
- Press **Delete**  

(This prevents leftover files from causing boot issues.)

### 5️⃣ Copy the New EFI
- Go to your downloaded EFI folder (e.g., `Desktop-Coffeelake`, `Laptop-Skylake`)  
- Copy the entire **EFI** folder  
- Paste it into the mounted EFI partition  

### 6️⃣ Close Explorer++ and Reboot
- Close the app  
- Restart your PC  
- Boot into macOS using the new EFI  

## 🎉 Done!
Your system should now boot with full Hackintosh support using the pre-configured EFI.
