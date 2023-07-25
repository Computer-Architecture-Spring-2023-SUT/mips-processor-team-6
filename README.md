# MIPS - Computer Architecture Course Project(Spring 2023)

## Table of Contents
- [Introduction](#introduction)
- [Team Members](#team-members)
- [Project Phases](#project-phases)
  - [Phase 1: Designing MIPS Data Path](#phase-1-designing-mips-data-path)
  - [Phase 2: Adding Cache Memory](#phase-2-adding-cache-memory)
  - [Phase 3: Pipelining the Processor](#phase-3-pipelining-the-processor)
  - [Phase 4: Designing Branch Prediction](#phase-4-designing-branch-prediction)

## Introduction
Welcome to the MIPS Processor Project! This repository showcases the collaborative efforts of our team - Arash Ziyaei, Amir Mohammad, and Farbod haji Mohmmad Ali - during our Computer Architecture course. The project centers around designing and implementing a MIPS  processor with several enhancements. Through four distinct phases, we explore the fundamentals of processor design, including cache memory, pipelining, and branch prediction. We hope our project serves as an educational resource for those interested in computer architecture.

## Team Members

| Name          | SID        |
|---------------|------------|
| Arash Ziyaei Razban    | 400105109 |
| Amir Mohammad Drakhshandeh    | 400101153 |
| Farbod Haji Mohammad Ali | 401011038 |


## Project Phases

### Phase 1: Designing MIPS Data Path
In this phase, we designed a single-cycle MIPS processor data path. The processor contained the essential components, including instruction fetch, instruction decode, ALU (Arithmetic Logic Unit), and memory access. This initial phase served as the foundation for the subsequent enhancements.

### Phase 2: Adding Cache Memory
Building upon the Phase 1 design, we extended the MIPS processor by adding a 2-way set associative cache with 4 sets and 2 blocks in each set. Each cache block helds 4 words. The addition of cache memory aimed to reduce memory access latency and improve overall performance.

### Phase 3: Pipelining the Processor
In this phase, we introduced pipelining to the processor. Pipelining improved instruction throughput by dividing the instruction execution into multiple stages. However, it also introduced potential hazards such as data hazards and control hazards, which required careful consideration and handling.

### Phase 4: Designing Branch Prediction
To further optimize the processor's performance, we implemented a one-level branch predictor with a saturating counter having 4 states. Branch prediction aimed to reduce pipeline stalls caused by conditional branches by predicting the outcome of branch instructions before they were resolved.
