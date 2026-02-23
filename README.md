---

# Aephestus Kernel System (AKS)

The **Aephestus Kernel System (AKS)** is the **core kernel for AephOS**, responsible for low-level system management, memory handling, process scheduling, hardware interaction, and integration with the **Aephestus language runtime**.

This repository contains the **private development version** of AKS, licensed under the **Aephestus Private Non-Commercial Copyleft License (APRNCL) v1.0**. All use and modifications must remain **private** and non-commercial.

---

## 1. Overview

AKS provides the essential runtime environment for AephOS and enables:

- **Memory Management:** Allocation, paging, and mapping for kernel and system processes.  
- **Interrupt Handling:** Low-level control over hardware and exceptions.  
- **Driver Support:** Interface with essential hardware modules.  
- **File System Integration:** Support for **AEPFS**, the proprietary filesystem used by AephOS.  
- **Kernel-User Communication:** Controlled interaction with Aephestus language programs.

---

## 2. Repository Structure

```text
AKS-Kernel/
├─ README.md
├─ LICENSE.md
├─ security.md
├─ docs/
│  ├─ overview.md
│  ├─ architecture.md
│  ├─ modules.md
│  └─ memory_management.md
├─ src/
│  ├─ kernel.c
│  ├─ memory.c
│  ├─ interrupts.c
│  └─ drivers/
├─ include/
│  ├─ kernel.h
│  ├─ memory.h
│  └─ interrupts.h
├─ tests/
│  └─ basic_boot_test.md
└─ .gitignore
