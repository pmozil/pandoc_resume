---
header-includes: |
    \usepackage[paperwidth=210mm, paperheight=840mm, margin=1.5cm, top=2cm, bottom=2cm]{geometry}
    \usepackage{setspace}
    \linespread{1.5}
    \usepackage[T1]{fontenc}
    \fontfamily{helvet}\selectfont
    \pagenumbering{gobble}
    \usepackage{etoolbox}
    \AtBeginEnvironment{quote}{\singlespace\vspace{-\topsep}}
    \AtEndEnvironment{quote}{\vspace{-\topsep}\endsinglespace}
---

Petro Mozil
============
----

>   I am a student at the Ukrainian Catholic University,
>   and an engineer at Infineon, experienced in OS / embedded development,
>   GPGPU programming and Networking.
>   I work well in teams and have good communication skills.

----

## Education

**2022 - 2026 (expected)**

-   **Bachelors, Computer Science**; Ukrainian Catholic University (Lviv)

## Experience

### September 2022 - January 2023: CPU design and development

I designed and developed 4 CPUs in SystemVerilog for the de10-nano devkit,
according to the specification of 4 ISAs. The work also included writing test scripts
written in esoteric assembly and writing documentation for the CPU implementation.

### February 2023 - June 2023: CUDA app development

I designed a program for simulation of patchy particle systems.
[Link](https://ucu-computer-science.github.io/poc,/acs,/os,/c++/2024/09/01/preprints-2024-1.html)

### 2023 - 2025: Teaching assistant for Principles of Computer organisation, Architecture of Computer Systems and Operating Systems courses

At this position, I was responsible for  editing the course materials, organizing consultations,
writing tests for the laboratory works the students submitted and, sometimes, organizing and reading lectures.

### Google Summer of Code 2024 @ FFmpeg

I developed a hardware-accelerated version of the VC-2 codec decoder
for [FFmpeg](https://ffmpeg.org/).
This job involved optimising data transfer from CPU to GPU with Vulkan API,
creating optimised compute pipelines and minimizing disk idle time to speed up the VC-2 codec,
as well as writing tests and modifying the build configuration for FFmpeg.

links:

-   [https://summerofcode.withgoogle.com/myprojects/details/Vlx5W3Md](https://summerofcode.withgoogle.com/myprojects/details/Vlx5W3Md)

-   [https://github.com/pmozil/FFmpeg](https://github.com/pmozil/FFmpeg)

### November 20224 - Present: Softwware Engineer @ Infineon

My work at Infineon included writing tests, developing software for the PSoC family of microcontrollers
and general debugging. On this position, I worked with many communication protocols, such as
I2C, SPI, UART, USB, CAN-FD, bluetooth and Wi-Fi (mostly TCP).
I also wrote code for the modus toolbox development environment in Qt and CPP.

### Contributor to CLAD

CLAD (Clang Auto-Differentiation) is a plugin for the clang C/C++ compiler that supports
automatic differentiation of mathematical functions. I contributed to it by adding support
for templated functions and more smaller, miscellaneous features.

links:

-   [https://github.com/vgvassilev/clad](https://github.com/vgvassilev/clad)

## Spoken Languages

- **Ukrainian (native speaker)**

- **English (C1)**

- **German (B2)**

- **Polish (A2)**

## Published papers

[Modelling Of Protein Systems Using Monte-Carlo Simultaion](https://ucu-computer-science.github.io/poc,/acs,/os,/c++/2024/09/01/preprints-2024-1.html)

## Technical Experience

### Theoretical knowledge

-   **Internet Protocol**, **User Datagram Protocol**, **Transmission Control Protocol**:
    I have experience with IP, UDP and TCP from the developer level.
    I am familiar with header formats, and have experience with manual UDP header creation and parsing.

-   **Routing algorithms**:
    I am familiar with routing algorithms, though I lack practical experience with any dynamic routing algorithms beyond RIP.

-   **Linux OS environment**: I am familiar with linux both on the level of OS development as well as OS usage.
    I am able to manage a linux system as well as write kernel modules to extend it.

-   **Computer-Aided Design (CAD):** I have experience with CAD, specifically with designing printed circuit boards and CPUS.
    I have experience with multiple CAD tools, such ad alterra quartus and KiCAD.

-   **High knowledge of mathematics**: I am familiar with a wide range of mathematical theories:
    **mathematical analysis**, **probability theory and statistics**, **linear algebra**, **topology**,
    **set theory** and **catrgory theory**.
    I am also familiar, but not profficient with:
    **Measure theory**,  **algebraic topology** and **Distribution theory**.

-   **Parsing, automata and compilers**: I have experience with creating ASTs and using them to efficiently process user input.
    I have created an AST builder and a regex engine. I have also worked with YACC,  LLVM and clang's libraries for creating compiler plugins.

-   **Machine Learning:** I have experience with Machine Learning.


### Projects

-   [**Paraflop** - a vulkan ray tracer](https://github.com/pmozil/paraflop)

-   [**Custom boards for google's CFU playground**](https://github.com/pmozil/cfu_playground_custom_boards)

-   [**Zot** - a regex engine written in zig](https://github.com/pmozil/zot)

-   [**An AST builder written**](https://github.com/pmozil/ast_builder)

-   [**Monistode** - a project implementing multiple CPUs for educational purposes](https://github.com/monistode)

-   [**Monad implementation with CPP concepts**](https://github.com/pmozil/is_that_a_monad)

-   [**Blendage - a wayland compositor with lua configuration**](https://github.com/pmozil/blendage)

### Programming Languages

-   **C:** I have 5 years of experience with C, most of it in academic and open-source work.
    I am familiar with C and abstractions of C machine.
    I used C for my time at FFmpeg, and I am accustomed to writing modern-style C,
    and have experience with libc.

-   **C++:** I have 4 years of experience with C++, and am profficient with STL and boost.
    I am familliar with most of the C++ standard, with focus on newer parts of it.
    Most of my practical experience in CPP comes from my work at Infineon and for CLAD,
    and my theoretical knowledge of cpp comes from my academic work.

-   **Python:** I have 5 years of experience with python. I am familiar with the python ecosystem
    and I have build many apps with python.

-   **X86 assembly:** I have experience with X86 assembly, mostly with SYSV ABI.

-   **SystemVerilog:** I have experience with SystemVerilog and Verilog and I am able to
    design digital circuits with it.

-   **Zig:** I am proficcient in zig and the zig build system. I have experience with zig-c interoperability.

-   **Rust:** I am experienced with Rust and the C/C++ FFI for rust.

-   **Other useful tools:** **CMake**, **make**, **bash**

-   Basic knowledge of **ARM assembly**, **Haskell**, **Common Lisp**

### Other Useful Tools I am Experienced With

-   **nmap**, **ss**, **tcpdump**

-   **gdb**, **lldb**

-   **yosys**, **Quartus**, **Vivado**, **litex**

----

> <mozil.petryk@gmail.com> • +380 95 867 2148 • 20 years old\
> [https://github.com/pmozil](https://github.com/pmozil) • [https://www.linkedin.com/in/petro-mozil-a94583170](https://www.linkedin.com/in/petro-mozil-a94583170)
> Address - Lviv, Ukraine
