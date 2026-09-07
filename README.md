Linux Logic Engine

This is a lightweight, standalone logic engine designed to execute control logic files created using a Windows-based control logic design tool. It was developed to enable HMI testing by deploying logic to a Linux server, avoiding the need to keep a desktop design PC running 24/7. It is also suitable for educational purposes and small-scale automation applications.


Overview

This repository provides a headless Linux execution engine for the control logic design ecosystem. After designing and verifying control logic on an engineering PC, you can deploy the exported logic file directly to a Linux environment (such as a Raspberry Pi or other Linux hardware) for execution.

The engine communicates via Modbus TCP, allowing for seamless connectivity with HMIs, external I/O modules, or microcontrollers.


Architecture and Workflow

Engineering / Simulation PC (Logic design and verification)

↓

Verified logic file

↓

Linux Logic Engine (This project)

↓

Modbus TCP

↓

HMI or External I/O


Pre-compiled binaries for the Linux Logic Engine are available on the Releases page.

Select the package appropriate for your hardware architecture:

Linux x64: SDFLogix_linux-x64.tar.gz

Linux ARM64 (e.g., Raspberry Pi): SDFLogix_linux-arm64.tar.gz


Key Features

Headless Execution: Runs efficiently on resource-constrained Linux systems without a GUI.

Modbus TCP Interface: Supports standardized industrial communication for easy interaction with SDFLogix HMIs and other devices.

Prototyping and Small-Scale Systems: Ideal for operating small control loops, test benches, or educational systems without the need for large-scale PLC hardware.
 
