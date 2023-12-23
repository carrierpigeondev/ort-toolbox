# Ort Toolbox -- Version 0.0.1

Assembled by Carrier Pigeon Dev; Programs made by different authors and contributors.

Revision Date: December 22, 2023

The Windows 10/11 USB toolbox for various situations named after a spelling mistake.

# Ort Toolbox is a recommended list of tools to be installed on a USB drive and does not redistribute any of the tools. Please use the links provided to download the tools from their creators :)

# File Structure

Note that the file structure below is just a recommendation and how I use the toolbox. Feel free to organize anything in any way you want.

```
Drive:
    Programs\
    Installers\
    Local\
        ISOs\
    README.md
```

The `Drive:` is the USB drive itself. In this top level directory are shortcuts to programs, this file, and 3 other directories.

`Programs\` is the directory for programs and their data. Similar to the Windows Program Files. Extract zip files here and choose this as the install location for executable installers.

`Installers\` is the directory where installers (executables, zip files, etc) should be kept in order to preserve a working version without redownloading (such as if no internet access is available).

`Local\` is the directory for local files on the USB drive. Do not use this often, rather store files on the host machine if possible. Also contains installers for recommended programs (in the directory itself) for the host machine and OS ISOs in (Local\ISOs\ directory).

# Programs List

Quick note: If you plan on going and downloading the programs in order, just know 7Zip is in the Miscellaneous section near the bottom ;)

## Development

### VSCodium (VSCode "Portable Mode") 1.85.1
Home: https://vscodium.com/  
Download: https://github.com/VSCodium/vscodium/releases/download/1.85.1.23348/VSCodium-win32-x64-1.85.1.23348.zip  
Note: To use "Portable Mode" on VSCode or VSCodium, a folder called `data` must be created in the extracted zip directory. Use this as a text/code editor unless system cannot handle it.

### Notepad++ (Zip) 8.6
Home: https://notepad-plus-plus.org/  
Download: https://github.com/notepad-plus-plus/notepad-plus-plus/releases/download/v8.6/npp.8.6.portable.x64.zip  
Note: Use this as a lighter weight code/text editor.

## Browsers

### Firefox (Portable Exe) 121.0
Home: https://portableapps.com/apps/internet/firefox_portable/  
Download: https://portableapps.com/redir2/?a=FirefoxPortable&s=s&d=pa&f=FirefoxPortable_121.0_English.paf.exe  
Note: Use this as the web browser.

### K-Meleon (Portable Exe) 76.5.0
Home: https://portableapps.com/apps/internet/k-meleon-portable/  
Download: https://portableapps.com/redir2/?a=K-MeleonPortable&s=s&d=pa&f=K-MeleonPortable_76.5.0-2023-12-16.paf.exe  
Note: Use this if for some reason system is on the lower end or is old.

## System

### CPU-Z (Zip) 2.08 
Home: https://www.cpuid.com/softwares/cpu-z.html/  
Download: https://download.cpuid.com/cpu-z/cpu-z_2.08-en.zip  
Note: Use this for checking CPU, GPU, memory, and motherboard details.

### HWMonitor (Zip) 1.52
Home: https://www.cpuid.com/softwares/hwmonitor.html/  
Download: https://download.cpuid.com/hwmonitor/hwmonitor_1.52.zip  
Note: Use this instead of Task Manager during benchmarking.

### HWiNFO (Zip) 7.68
Home: https://www.hwinfo.com/  
Download: https://sourceforge.net/projects/hwinfo/files/Windows_Installer/hwi_768.exe  
Note: Use this for more details on the hardware (such as ports, audio, networking, etc.).

### CrystalDiskInfo (Zip) 9.2.1
Home: https://crystalmark.info/en/software/crystaldiskinfo/  
Download: https://downloads.sourceforge.net/project/crystaldiskinfo/9.2.1/CrystalDiskInfo9_2_1.zip  
Note: Use this for checking details about drives.

## Benchmarking

### Prime95 (Zip) 30.8
Home: https://www.mersenne.org/  
Download: https://www.mersenne.org/download/software/v30/30.8/p95v308b17.win64.zip  
Note: Use this for checking stability of the CPU and memory. Recommended to run for 4-24 hours. Does not stop automatically, don't expect it to.

### Cinebench (Zip) 2024
Home: https://www.maxon.net/en/cinebench/  
Download: https://mx-app-blob-prod.maxon.net/mx-package-production/website/windows/maxon/cinebench/Cinebench2024_win_x86_64.zip  
Note: Use this for benchmarking the CPU/GPU and getting a score for it. Compare it against the known Cinebench 2024 score.

### CrystalDiskMark (Zip) 8.0.4
Home: https://crystalmark.info/en/software/crystaldiskmark/  
Download: https://sourceforge.net/projects/crystaldiskmark/files/8.0.4c/CrystalDiskMark8_0_4c.zip  
Note: Use this for benchmarking drives.

## Miscellaneous

### 7-Zip (Portable Exe) 23.01
Home: https://portableapps.com/apps/utilities/7-zip_portable/  
Download: https://portableapps.com/redir2/?a=7-ZipPortable&s=s&d=pa&f=7-ZipPortable_23.01.paf.exe  
Note: Better zip file extractor.

### Rufus 4.3p (Official Portable Exe)
Home: https://rufus.ie/en/  
Download: https://github.com/pbatard/rufus/releases/download/v4.3/rufus-4.3p.exe  
Note: Use this on your own computer to create a bootable USB drive with OS ISOs. DO NOT USE YOUR TOOLBOX DRIVE AS THE BOOTABLE USB!

### Paint.NET (Zip) 5.0.12
Home: https://getpaint.net/  
Download: https://github.com/paintdotnet/release/releases/download/v5.0.12/paint.net.5.0.12.portable.x64.zip  
Note: Image manipulator (better than MS paint). Not sure why this would be particularly useful, but can be installed on the host machine if wanted.

# Non-Portable Programs (Keep on Host Machine)

Make sure to check the version of the installers on the USB drive to make sure they are up to date before installing on host machine.

### Firefox
Home: https://www.mozilla.org/en-US/firefox/  
Download: https://download.mozilla.org/?product=firefox-stub&os=win&lang=en-US  
Note: English Windows version of the Firefox web browser. Not a direct download link, but redirects to download an installer for the latest version.

### Malwarebytes
Home: https://www.malwarebytes.com/  
Download: https://www.malwarebytes.com/api/downloads/mb-windows?filename=MBSetup.exe  
Note: Free anti-malware scanner. The installer / setup executable installs the latest version.

### LibreOffice 7.6.4
Home: https://www.libreoffice.org/  
Download: https://www.libreoffice.org/donate/dl/win-x86_64/7.6.4/en-US/LibreOffice_7.6.4_Win_x86-64.msi  
Note: Free equivalent to Microsoft Office.

# Operating Systems

Make sure to check the version of the installers on the USB drive to make sure they are up to date before installing on host machine.

## Windows

### Windows 10 22H2 ISO
Download: Used Windows 10 Media Creation Tool (https://go.microsoft.com/fwlink/?LinkId=691209)

### Windows 11 23H2 ISO
Download: Windows 11 Multi-edition ISO for x64 devices, English US from this page (https://www.microsoft.com/en-us/software-download/windows11)

## Ubuntu Desktop 22.04.3 LTS
Download: https://releases.ubuntu.com/22.04.3/ubuntu-22.04.3-desktop-amd64.iso

### Ubuntu Server 23.10
Download: https://releases.ubuntu.com/23.10/ubuntu-23.10-live-server-amd64.iso
