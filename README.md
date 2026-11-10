# Awesome AI Hardware [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for AI hardware accelerators, neural processing units (NPUs), tensor processing units (TPUs), hardware-level kernel optimization, systolic array architectures, and open-source EDA design flows.

AI hardware acceleration bridges the gap between deep learning software abstractions and silicon execution. By combining specialized matrix-multiplication units, high-bandwidth memory (HBM) interfaces, processing-in-memory (PIM) concepts, and customized instruction sets, AI silicon enables training and real-time inference for multi-billion-parameter models across data centers, edge devices, and embedded platforms. This list is intended for hardware architects, chip design engineers, system-level software developers, compiler engineers, and silicon verification leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Architectures & Acceleration Systems](#architectures--acceleration-systems)
- [Compilers & Low-Level DSLs](#compilers--low-level-dsls)
- [Hardware Simulation & Performance Modeling](#hardware-simulation--performance-modeling)
- [Open-Source Physical Design & EDA Toolchains](#open-source-physical-design--eda-toolchains)
  - [RTL & Logic Synthesis](#rtl--logic-synthesis)
  - [Place & Route (P&R) Flows](#place--route-pr-flows)
- [Hardware Verification & Interconnects](#hardware-verification--interconnects)
- [Related Awesome Lists](#related-awesome-lists)

## Architectures & Acceleration Systems

Silicon design taxonomies, domain-specific ASICs, and specialized hardware execution engines.

- [Eyeriss Dataflow Architecture](https://github.com/mit-eir/eyeriss) — Energy-efficient reconfigurable processing architecture optimizing spatial data reuse in deep neural network accelerators.
- [OpenTPU](https://github.com/open-tpu/open-tpu) — Open-source hardware implementation of a Tensor Processing Unit core modeled after classic matrix-multiplication architectures.
- [NVDLA (NVIDIA Deep Learning Accelerator)](https://github.com/nvdla/hw) — Modular open-source architecture designed to standardize inference acceleration across edge systems.
- [VTA (Versatile Tensor Accelerator)](https://github.com/apache/tvm/tree/main/vta) — Programmable open hardware design providing an end-to-end CPU/GPU/FPGA architecture for Apache TVM integrations.

## Compilers & Low-Level DSLs

Hardware compilation abstractions, IR translators, and domain-specific language engines for writing compute kernels.

- [Triton](https://github.com/triton-lang/triton) — Open-source Python-based programming language and compiler for writing highly efficient custom GPU compute kernels.
- [MLIR (Multi-Level Intermediate Representation)](https://github.com/llvm/llvm-project/tree/main/mlir) — Compiler infrastructure framework designed to simplify the mapping of AI algorithms down to diverse silicon targets.
- [Apache TVM](https://github.com/apache/tvm) — Open-source deep learning compiler stack for CPUs, GPUs, and specialized hardware accelerators.
- [XLA (Accelerated Linear Algebra)](https://github.com/openxla/xla) — Domain-specific compiler for machine learning models targeting GPUs, TPUs, and specialized execution units.

## Hardware Simulation & Performance Modeling

Analytical cost calculators, cycle-accurate simulators, and dataflow mappers for hardware design space exploration.

- [Timeloop & Accelergy](https://github.com/timeloop-accelergy/timeloop) — Infrastructure for evaluating, mapping, and estimating the energy/area efficiency of DNN accelerator architectures.
- [MAESTRO](https://github.com/maestro-project/maestro) — Analytical cost model for projecting execution cycles, energy, and throughput across DNN hardware dataflows.
- [gem5-gpu](https://github.com/gem5/gem5) — Modular platform for computer architecture research providing cycle-level simulation of heterogeneous processor nodes.
- [SCALE-Sim](https://github.com/ARM-software/SCALE-Sim) — Cycle-accurate systolic array simulator used for modeling memory bandwidth requirements and compute utilization.

## Open-Source Physical Design & EDA Toolchains

Open-source electronic design automation (EDA) frameworks, RTL synthesis engines, and place-and-route tools.

### RTL & Logic Synthesis

- [Yosys](https://github.com/YosysHQ/yosys) — Open-source framework for Verilog logic synthesis enabling automated ASIC and FPGA netlist transformations.
- [Chisel](https://github.com/chipsalliance/chisel3) — Scala-based hardware description language enabling advanced object-oriented design and parameterizable RTL generation.

### Place & Route (P&R) Flows

- [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane) — Automated, open-source RTL-to-GDSII physical design flow built around the SkyWater 130nm open PDK.
- [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) — Unified, open-source layout synthesis tool performing place and route for complex digital integrated circuits.

## Hardware Verification & Interconnects

Testbench frameworks, functional verification suites, and high-bandwidth interconnect specifications.

- [cocotb](https://github.com/cocotb/cocotb) — Coroutine-based co-simulation library for verifying VHDL and SystemVerilog RTL designs using Python testbenches.
- [Verilator](https://github.com/verilator/verilator) — High-performance open-source Verilog/SystemVerilog simulator translating RTL into optimized multi-threaded C++ models.
- [CXL (Compute Express Link)](https://www.computeexpresslink.org/) — Open industry standard interconnect offering high-bandwidth, low-latency cache-coherent memory expansion across CPUs and AI accelerators.

## Related Awesome Lists

- [Awesome Assembly](https://github.com/brandonhimpfen/awesome-assembly) — Low-level instruction sets, machine code mnemonics, and reverse engineering.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Best practices, licensing standards, and community governance for open repositories.
- [Awesome Infrastructure Monitoring](https://github.com/brandonhimpfen/awesome-infrastructure-monitoring) — Telemetry collection engines, metrics pipelines, and cluster monitoring tools.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
