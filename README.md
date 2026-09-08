# Xeowa | Computer Science Portfolio

Computer Science student interested in artificial intelligence, programming languages, systems software, and computer architecture.

資工系學生，關注人工智慧、程式語言、系統軟體與計算機架構。這個 GitHub Profile 集中展示可執行、可驗證，並清楚標示專案背景與個人貢獻的作品。

## Featured projects

### [Gomoku AI Engine](https://github.com/Xeowa/gomoku-ai-engine)

Deterministic 15x15 Gomoku engine with Negamax, Alpha-Beta pruning, PVS, transposition tables, tactical threat detection, and time-bounded search.

- **Course:** 人工智慧
- **Language:** Python
- **Focus:** adversarial search, heuristic evaluation, runtime control
- **Evidence:** automated rule/protocol tests and passing GitHub Actions

### [OurScheme Interpreter](https://github.com/Xeowa/ourscheme-interpreter)

C++ Scheme-like interpreter with a hand-written scanner, recursive parser, S-expression model, lexical environments, closures, special forms, primitives, and structured errors.

- **Course:** 程式語言
- **Language:** C++17
- **Focus:** language implementation, parsing, evaluation, lexical scoping
- **Evidence:** smoke tests pass with GCC, Clang, and MSVC in GitHub Actions

### [Parallel Sorting Benchmark](https://github.com/Xeowa/parallel-sorting-benchmark)

Experimental comparison of sequential partitioning, Linux processes with shared memory, C++ threads, and an in-place QuickSort baseline.

- **Course:** 作業系統
- **Language:** C++17
- **Focus:** processes, threads, IPC, performance methodology
- **Evidence:** reproducible output validation passes on Linux and Windows in GitHub Actions

## Systems and computer architecture

### [Pipelined MIPS-Lite CPU](https://github.com/Xeowa/pipelined-mips-cpu)

Five-stage educational Verilog processor with explicit pipeline registers, control/ALU/memory modules, divider and HI/LO paths, and a self-checking Icarus Verilog integration test.

- **Course:** 計算機組織
- **Language:** Verilog
- **Focus:** pipelined datapath, processor control, simulation, verification boundaries
- **Context:** four-person team project; personal contribution and publication consent documented

### [ARM Julia Set Renderer](https://github.com/Xeowa/arm-julia-set)

ARMv7 fixed-point Julia set renderer with an AAPCS-correct assembly implementation, cross-compilation workflow, and deterministic 640 × 480 output verification under QEMU.

- **Course:** 嵌入式與組合語言
- **Language:** ARM assembly and C
- **Focus:** fixed-point arithmetic, register allocation, ABI correctness, cross-platform verification
- **Context:** two-person team project; personal contribution and publication consent documented

## Competition projects

### [AI CUP 2025 Cardiac CT Segmentation](https://github.com/Xeowa/aicup-2025-cardiac-segmentation)

An nnU-Net v2 3D full-resolution pipeline for cardiac CT segmentation.

- **Competition:** AI CUP 競賽（教育部全國大專校院人工智慧競賽）
- **Official website:** <https://www.aicup.tw/ai-cup-2025-competition>
- **Role:** team lead in a three-student team with one faculty advisor
- **Result:** Public 35/253 (top 13.8%); Private 55/253 (top 21.7%)
- **Focus:** medical-image segmentation, reproducible experiment configuration, data-governance boundaries

### [IMBD 2025 Thermal Displacement Prediction](https://github.com/Xeowa/imbd-2025-thermal-displacement)

Mamba-inspired multivariate time-series model for predicting two-axis CNC lathe thermal displacement from sensor histories.

- **Competition:** IMBD 競賽（2025 全國智慧製造大數據分析競賽；教育部指導）
- **Official website:** <https://imbd2025.thu.edu.tw/>
- **Role:** team lead in a three-student team with one faculty advisor
- **Result:** advanced to the national final; historical internal validation RMSE 1.269709 μm
- **Focus:** sequence regression, leakage-aware validation, industrial-data constraints

## Research and applied AI

### [SEM Music Dataset](https://github.com/Xeowa/A-Social-Emotional-Music-DataSet)

Expert-annotated 419-track dataset associated with the peer-reviewed LSEL music-classification study.

- **Focus:** research data, expert annotation, citation metadata, rights and limitation statements
- **Evidence:** public Kaggle release and peer-reviewed paper

### [MoodTune](https://github.com/Xeowa/MoodTune)

React/FastAPI research prototype for local mood journaling, audio-library management, and explainable music exploration.

- **Focus:** research-to-prototype translation, local-first data, transparent recommendation rules
- **Evidence:** automated backend tests, production frontend build, and documented research boundary

## Additional work

- [RPG Quest Notification System](https://github.com/Xeowa/rpg-quest-system) — **Course:** 物件導向程式設計；Java Observer/Strategy design-pattern exercise with JUnit verification.
- [Poker Hand Evaluator](https://github.com/Xeowa/poker-hand-evaluator) — **Course:** 計算機概論；dependency-free C11 evaluator with category, tie-break, parsing, and validation tests passing on Linux and Windows.

## Technical areas

| Area | Tools and concepts |
| --- | --- |
| Artificial intelligence | Negamax, Alpha-Beta, PVS, heuristic search, threat detection |
| Applied machine learning | 3D medical-image segmentation, nnU-Net, time-series regression, Mamba-inspired sequence modeling, leakage-aware validation |
| Programming languages | scanner, parser, S-expressions, evaluator, lexical environment, closures |
| Systems | processes, threads, shared memory, synchronization, benchmarking |
| Computer architecture | Verilog, pipelined datapath, ALU, control, testbench |
| Low-level programming | ARMv7 assembly, fixed-point arithmetic, AAPCS, cross-compilation, QEMU |
| Research data | dataset documentation, citation metadata, rights and limitation statements |
| Web applications | React, FastAPI, SQLite, REST APIs, responsive interfaces, local-first data |
| Software engineering | Git, CMake, Maven, automated tests, GitHub Actions, technical documentation |

## Portfolio principles

- Each substantial project has its own repository, build instructions, tests, and limitations.
- Course handouts and instructor-authored reference implementations are not republished.
- Team projects explicitly distinguish personal contribution from team output.
- Competition repositories exclude organizer datasets and distinguish official leaderboard results from internal validation.
- Historical benchmark results are labeled as historical rather than presented as current universal claims.

## Contact

For application-related contact, please use the information provided in the résumé.
