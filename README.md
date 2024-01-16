# ASM Guard

## ```Attention! It is not a malicious file cryptor. Do not use it to encrypt malicious code - there will be no fewer detections. Antivirus tools use advanced heuristics to search for potentially malicious patterns.```

## What is it?!
ASM Guard is a packer utility for compressing and complicating reversing compiled native code (native files), protecting resources, adding DRM, and packing into an optimized software loader.
Its main purpose is to protect programs from static analysis (determining the framework/programming language or libraries used) and reading the machine code of the program through packing and mutations of the executable file. It will not stop a truly experienced reverser, but it will make it difficult to analyze it superficially or prevent an attempt to introduce malicious code.

### Features:
 * Instruction compression
 * Fake import of WinAPI functions
 * Add junk partitions
 * Enhanced flood mode
 * Different types flood
 * Add junk C/C++ functions
 * Leave a hidden message (message to a hacker)
 * Fake UPX detect in Detect it easy (MZ, PE)
 * Assembly mutation

### Peculiarities:
 * Usage for EXE and DLL
 * Simple and convenient GUI
 * 32-64 bit support
 * Association with .DLL, .ASMG files
 * Project and configuration system
 * Embedding in File Explorer context menu
 * The protector is portable and has a small size

 ### Absolutely free software. No restrictions. No paid subscriptions. Enjoy! :)
The program is written in VB NET and is still closed source. However, if the project is popular, then I will consider publishing the original source code.

## Use it for C++ application?
Use [obfusheader.h](https://github.com/ac3ss0r/obfusheader.h) by [ac3ss0r](https://github.com/ac3ss0r) for compile-time reliable obfuscation of your code before applying **ASM Guard**.
This is a complex protection using a CPP-header file that is almost impossible to remove using unpackers or other special tools.

## False-positive detections by antiviruses?
Antivirus programs may falsely detect ASM Guard file protection as unwanted or malware. This may be due to reasons including complex security algorithms that hide the source code from machine code analyzers or PE resources during the static scanning stage. **Unfortunately, this cannot be fixed**. The only sure way to avoid this is to use a CodeSign digital signature or ask your users to add your program to exceptions

# 💾 [DOWNLOAD](https://github.com/DosX-dev/ASM-Guard/releases/tag/Latest)

![](https://raw.githubusercontent.com/DosX-dev/ASM-Guard/main/2.8.jpg)
![](https://raw.githubusercontent.com/DosX-dev/ASM-Guard/main/2.9.4.jpg)
![](https://raw.githubusercontent.com/DosX-dev/ASM-Guard/main/dem.jpg)

#### DISCLAIMER
The use of ASM Guard is at the user's own risk. The developer assumes no responsibility for any damages, losses, or harm caused by the use of this software. The user is solely responsible for ensuring that their files are adequately protected and secured. The developer shall not be held liable for any unauthorized access, hacking, or other malicious activities that may occur as a result of using this software. <b>By using this software, the user acknowledges and agrees to these terms and conditions.</b>

### Developed with <3, by DosX
