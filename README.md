# MOS in Rust
Welcome to the official repository of the MOS-Rust project, where we are actively porting the MOS operating system, originally designed for the MIPS architecture and written in C, to Rust. This repository is the core hub for all development activities related to this project.

## Overview
MOS-Rust aims to recreate the MOS operating system in Rust, focusing on educational use to teach operating system concepts and Rust programming. The project is divided into several phases, each focusing on a specific aspect of the operating system. 

The project is currently in the early stages of development of Phase 3.

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
- Rust toolchain (latest **nightly** release) with these components: 
    - `rust-src`, `llvm-tools`, `rust-docs`, `clippy`
- QEMU
- Git (for version control)

### Building the project
To build the MOS-Rust project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/MOS-Rust/mos.git --recursive
    cd mos
    ```
2. Build the kernel:
    ```bash
    cd kernel
    cargo build
    ```

3. Run the operating system:
    ```bash
    cargo run
    ```

## Project Phases

**Phase 1**: Bootstrapping and basic IO (completed)

**Phase 2**: Memory management (mostly completed)

**Phase 3**: Exception handling (working)

**Phase 4**: Process management

**Phase 5**: File system

**Phase 6**: Pipe and shell

