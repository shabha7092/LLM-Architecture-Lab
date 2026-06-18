# LLM Architecture Lab

This repository contains Jupyter notebooks that explore the architecture and internal building blocks of modern Large Language Models.

The goal of this project is to understand LLM systems from the inside out by building and explaining key architectural components step by step. Each notebook focuses on one concept, with an emphasis on tensor shapes, implementation details, intuition, and how the component fits into the broader Transformer architecture.

The repository covers foundational Transformer components as well as advanced architecture ideas used in recent LLM systems, including attention variants, positional embeddings, RoPE, KV caching, sparse attention, latent attention, latent KV cache, multi-token prediction, and manifold residual hyper-connections.

This is a learning and research-oriented repository intended for understanding how LLM architectures work beyond high-level APIs. The focus is on clarity, experimentation, and architectural insight rather than production-level optimization.

## Topics Covered

* Multi-Head Attention
* Sinusoidal Positional Embeddings
* Rotary Positional Embeddings, also known as RoPE
* Sparse Attention
* Latent Attention
* Standard KV Cache
* Latent KV Cache
* Multi-Token Prediction
* Manifold Residual Hyper-Connections
* Decoder-only Transformer architecture
* Autoregressive generation
* Efficient LLM inference concepts

## Purpose

Modern LLMs are built from a collection of reusable architectural ideas. This repository breaks those ideas into focused notebooks so each component can be studied independently and understood from first principles.

The notebooks are designed to be useful for:

* Learning LLM internals
* Research prototyping
* ML engineering and research interview preparation
* Understanding efficient inference mechanisms
* Studying recent Transformer architecture improvements
