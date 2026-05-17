# Attribution

The Unified Cross Compiler (UCC) incorporates modified open source 
components. All original licenses and copyrights are preserved. 
The following projects were used in the development of UCC:

---

## LLVM Project
**License:** Apache License 2.0 with LLVM Exceptions  
**Source:** https://github.com/llvm/llvm-project  
**Copyright:** Copyright (c) 2003-2024 University of Illinois at 
Urbana-Champaign  
**Notes:** Core IR, CodeGen, Support, and SandboxIR layers adapted 
and modified for UCC.

---

## Apple LLVM
**License:** Apache License 2.0 with LLVM Exceptions  
**Source:** https://github.com/apple/llvm-project  
**Notes:** Apple Clang, ORC-RT, XNU Mach-O headers, and Buildbot 
components extracted and adapted for UCC.

---

## GCC - GNU Compiler Collection
**License:** GNU General Public License v3.0  
**Source:** https://gcc.gnu.org  
**Copyright:** Copyright (c) Free Software Foundation, Inc.

---

## GNU Binutils
**License:** GNU General Public License v3.0  
**Source:** https://www.gnu.org/software/binutils  
**Copyright:** Copyright (c) Free Software Foundation, Inc.

---

## NASM - Netwide Assembler
**License:** BSD 2-Clause License  
**Source:** https://www.nasm.us  
**Copyright:** Copyright (c) 1996-2024 the NASM Authors

---

## newlib-cygwin
**License:** Various — BSD, MIT, and others  
**Source:** https://sourceware.org/newlib  
**Notes:** C standard library for embedded targets.

---

## Zephyr RTOS
**License:** Apache License 2.0  
**Source:** https://github.com/zephyrproject-rtos/zephyr  
**Notes:** Zephyr SDK and sdk-ng included for embedded target support.

---

## FreeRTOS Kernel
**License:** MIT License  
**Source:** https://github.com/FreeRTOS/FreeRTOS-Kernel  
**Copyright:** Copyright (c) Amazon.com, Inc. or its affiliates.

---

## Poky - Yocto Project
**License:** MIT License  
**Source:** https://github.com/yoctoproject/poky  
**Notes:** Build system reference for embedded Linux targets.

---

## CMSIS Version 5
**License:** Apache License 2.0  
**Source:** https://github.com/ARM-software/CMSIS_5  
**Copyright:** Copyright (c) ARM Limited  
**Notes:** ARM Cortex-M processor support headers.

---

## musl libc
**License:** MIT License  
**Source:** https://musl.libc.org  
**Copyright:** Copyright (c) 2005-2024 Rich Felker and contributors  
**Notes:** Lightweight C standard library for Linux targets.

---

## libsodium
**License:** ISC License  
**Source:** https://github.com/jedisct1/libsodium  
**Copyright:** Copyright (c) 2013-2024 Frank Denis  
**Notes:** Used for inter-container hash verification and secure 
communication in the container overlay build architecture.

---

## libgcrypt
**License:** GNU Lesser General Public License v2.1  
**Source:** https://gnupg.org/software/libgcrypt  
**Copyright:** Copyright (c) Free Software Foundation, Inc.  
**Notes:** Used for FIPS compliance on automotive targets.

---

## OpenOCD
**License:** GNU General Public License v2.0  
**Source:** https://openocd.org  
**Notes:** Open On-Chip Debugger for embedded target debugging support.

---

## Apple Open Source Tarballs
**License:** Various — Apple Public Source License and others  
**Source:** https://opensource.apple.com  
**Notes:** Various Apple open source components extracted for 
macOS and Darwin target support.

---

## UCC Original Source Code
**Author:** Corbett Knowles  
**Year:** 2026  
**License:** GNU General Public License v3.0  
**Notes:** All original UCC source code including typedef layers, 
target architecture descriptors, codegen framework, and compiler 
infrastructure not derived from the above projects is authored 
by Corbett Knowles and licensed under GPL v3.0.

---

*This attribution file is maintained in compliance with the 
Apache License 2.0 requirements of the LLVM Project and other 
incorporated open source components. All original copyright 
notices have been preserved in the modified source files.*
