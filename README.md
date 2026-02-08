# Baby-LLM: A Character/Subword Transformer from Scratch

![Python](https://img.shields.io/badge/Python-3.12-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange)
![License](https://img.shields.io/badge/License-MIT-green)

This project is a basic implementation of a **Large Language Model (LLM)** built from scratch using TensorFlow and Keras. It implements a Decoder-only Transformer architecture designed to learn and generate text based on specific linguistic patterns.

## 🚀 Project Pipeline

The following flowchart describes the logical steps implemented in the notebook:

```mermaid
graph TD
    M1[Module 1: Input Data] --> M2[Module 2: Tokenization System]
    M2 --> M3[Module 3: Encoding Process]
    M3 --> M4[Module 4: Sequence Creation - BLOCK_SIZE]
    M4 --> M5[Module 5: Embedding Demonstration]
    M5 --> M6[Module 6: Transformer Architecture]
    M6 --> M7[Module 7: Pipeline - Training & Saving]
    M7 --> M8[Module 8: Testing - Text Generation]

    style M1 fill:#f9f,stroke:#333,stroke-width:2px
    style M7 fill:#bbf,stroke:#333,stroke-width:2px
    style M8 fill:#bfb,stroke:#333,stroke-width:2px
