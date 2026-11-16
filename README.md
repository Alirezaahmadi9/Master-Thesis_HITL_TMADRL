# Master-Thesis

# Human-in-the-Loop Residential Energy Management Using Hybrid Transformer-MADRL and LLMs

This repository contains the Python implementations developed for my M.Sc. thesis, *A Human-in-the-Loop Control Strategy for Residential Energy Management Based on a Hybrid Transformer-MADRL with LLM*.

The project investigates multi-agent reinforcement learning for residential energy management, integrating Transformer-based temporal learning and human preferences to balance energy cost, thermal comfort, carbon emissions, and peak demand.

## Repository Contents

| Notebook | Description |
|---|---|
| `MADRL.ipynb` | Baseline Multi-Agent Deep Reinforcement Learning implementation. |
| `TAC_MADRL.ipynb` | Transformer/attention-based Multi-Agent Deep Reinforcement Learning implementation. |
| `HITL_Control_Base.ipynb` | Human-in-the-Loop control implementation for the base residential energy management scenario. |
| `HITL_Control_PV.ipynb` | Human-in-the-Loop implementation incorporating PV–battery integration and LLM-assisted preference compilation. |

## Key Methods

- Soft Actor-Critic (SAC) and Multi-Agent Reinforcement Learning.
- Transformer-based temporal representation learning.
- Attention-based architectures.
- Human-in-the-Loop preference integration.
- LLM-assisted preference-to-control specification.
- Integrated PV–battery energy management.

## Technologies

Python | PyTorch | Transformers | Hugging Face | Reinforcement Learning | LLMs

## Research Context

M.Sc. Thesis, Energy Systems Engineering, University of Tehran.
