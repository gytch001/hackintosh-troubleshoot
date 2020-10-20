# Kernel Panic

While booting to the macOS Installer you'll get stuck on this error
>Kernel Panic, Visit panic.apple.com to report this panic

## Causes
1. Misconfigured EFI
2. Outdated / Wrong Kexts
3. Old Kexts New OS
4. New Kexts Old OS
5. Wrong SMBios
6. Misconfigured ACPI
<br> ** This error mostly has something with kexts or config.plist **

## Basic Solutions
1. Do Sanity Checker on your config.plist
2. Remove unneeded kexts and remove their injection from config.plist
3. Be sure that the kexts are appopriate for your hardware
4. Be sure that the kexts are correctly in the config.plist
5. Reconfigure your EFI Folder
6. Check if there's errors in the ACPI Folder
<br>

## Other solutions
1. Check your SMBios if it's correct
2. Check your BIOS Settings If they're correct for hackintosh
3. Be sure the kexts are up-to-date 
4. Be sure that you are installing vanilia hackintosh instead of Distro
5. Your Config file must be correct for your hardware
6. Check if your OpenCore is outdated

** Rarely, You have only one solution **

## Always-Work Solutions
1. Download different version of macOS That is 1 step lower/higher than your current ( ex: catalina->mojave )
2. Follow the dortania-guide completley step-by-step
3. Replace the USB
4. Clean your USB-Ports carefully
