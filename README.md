<div align="center">
    <p align="center">
        <a href="https://github.com/cybersecurity-dev/awesome-linux-driver-development">
          <img width="5%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Tux.svg" />
        </a>
    </p>

```mermaid
ishikawa-beta
    Competent Linux Driver Toolkit User
        Phase 1  - <br/>Source Environment
            Obtain kernel source
            Select target branch
            Install development packages
            Prepare kernel headers
            Configure source repository
            Record target kernel version

        Phase 2  - <br/>Toolchain
            Install GCC
            Install Clang
            Configure cross-compiler
            Select architecture
            Verify compiler compatibility
            Inspect generated tool versions

        Phase 3  - <br/>Kernel Configuration
            Use defconfig
            Use menuconfig
            Enable driver dependencies
            Enable debug options
            Enable test frameworks
            Preserve configuration file

        Phase 4  - <br/>Build System
            Create Kconfig entry
            Create Kbuild rules
            Configure external module Makefile
            Compile object files
            Run MODPOST
            Generate kernel module

        Phase 5  - <br/>Style and Static Checks
            Run checkpatch
            Format selected code
            Run Sparse
            Run Smatch
            Run Coccinelle
            Review compiler warnings

        Phase 6  - <br/>Binary Inspection
            Inspect module metadata
            Inspect symbol table
            Inspect module dependencies
            Inspect ELF sections
            Check undefined symbols
            Compare target architecture

        Phase 7  - <br/>Deployment
            Install module
            Run depmod
            Load with modprobe
            Inspect with lsmod
            Inspect device binding
            Unload module safely

        Phase 8  - <br/>Device Observation
            Inspect sysfs
            Inspect procfs
            Inspect debugfs
            Inspect device nodes
            Inspect udev events
            Verify permissions

        Phase 9  - <br/>Logging
            Use printk and dev logging
            Select log levels
            Read dmesg
            Read journal logs
            Add request identifiers
            Preserve timestamps

        Phase 10  - <br/>Tracing
            Use dynamic debug
            Configure ftrace
            Filter functions
            Enable tracepoints
            Capture perf events
            Correlate trace evidence

        Phase 11  - <br/>Debugging
            Build symbols
            Configure GDB helpers
            Configure KGDB
            Use KDB
            Inspect crash dumps
            Analyze stack traces

        Phase 12  - <br/>Testing
            Write KUnit tests
            Run kselftest
            Build test modules
            Run functional tests
            Run stress tests
            Test error paths

        Phase 13  - <br/>Dynamic Verification
            Enable KASAN
            Enable KCSAN
            Enable UBSAN
            Enable lockdep
            Use fault injection
            Collect coverage

        Phase 14  - <br/>Delivery
            Check kernel compatibility
            Sign module
            Prepare DKMS package
            Prepare distribution package
            Test clean installation
            Archive source symbols and logs
```

# **`LDDT`** | Linux [Driver](https://github.com/cybersecurity-dev/awesome-linux-driver-development-resource) Development [Toolkit](https://github.com/cybersecurity-dev/awesome-linux-driver-development)
</div>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://elixir.bootlin.com/linux/v6.17/source)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
treemap-beta
    "Linux Driver Development Toolkit"
        "Environment"
            "Kernel Source": 6
            "Kernel Headers": 4
            "GCC and Clang": 6
            "Cross Toolchains": 5
            "QEMU and Test Targets": 5

        "Build System"
            "Kconfig": 5
            "Kbuild": 6
            "GNU Make": 4
            "MODPOST": 4
            "Module Metadata": 3

        "Static Analysis"
            "checkpatch": 4
            "Sparse": 6
            "Smatch": 5
            "Coccinelle": 6
            "Clang Analysis": 5

        "Deployment"
            "modprobe and insmod": 5
            "depmod": 3
            "modinfo": 3
            "udev": 5
            "sysfs and procfs": 4

        "Diagnostics"
            "printk and dmesg": 5
            "Dynamic Debug": 4
            "ftrace": 8
            "Tracepoints": 5
            "perf": 5
            "GDB and KGDB": 6
            "Crash Analysis": 5

        "Verification"
            "KUnit": 7
            "kselftest": 5
            "KASAN": 6
            "KCSAN": 5
            "UBSAN": 4
            "Lockdep": 5
            "KCOV and gcov": 4
            "Fault Injection": 4

        "Delivery"
            "Module Signing": 4
            "DKMS": 5
            "Distribution Packaging": 5
            "Compatibility Testing": 5
```


## 📖 Contents
- [My Awesome Lists](#my-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


```mermaid
mindmap
  root((Linux<br/>Driver<br/>Development))

    🔵 Fundamentals
      C Programming
      Data Structures
      Computer Architecture
      Operating Systems

    🟣 Kernel Basics
      Kernel Source Tree
      Kbuild
      Kconfig
      System Calls

    🔴 Driver Types
      Character Drivers
      Block Drivers
      Network Drivers
      USB Drivers
      PCI Drivers

    🟡 Hardware
      Interrupts
      DMA
      MMIO
      Device Tree

    🟠 Debugging
      printk
      dmesg
      ftrace
      kgdb
      perf

    🟢 Advanced
      Power Management
      Security
      eBPF

    ⚫ Contribution
      Git
      checkpatch.pl
      Patch Submission
      Mailing Lists
```

##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/linux-driver-development-toolkit/graphs/contributors)!

[🔼 Back to top](#lddt--linux-driver-development-toolkit)
