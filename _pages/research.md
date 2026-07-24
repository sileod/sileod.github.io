---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on reasoning, evaluation and data for language models.

## Reasoning and training environments

I develop procedural environments and synthetic datasets for formal logic, mathematics, planning, algorithms and related symbolic domains. The goal is to make training and evaluation data scalable, verifiable and diagnostically useful.

Current work includes [Reasoning Core](https://github.com/sileod/reasoning-core), a suite of tasks with native scorers for pre-training, post-training, evaluation and reinforcement learning, and [gramforge](https://github.com/sileod/gramforge), a library for synthetic data generation with declarative context-sensitive grammars.

## Evaluation and benchmarks

I study how language models reason under long contexts, difficult retrieval settings and expert-level evaluation. This includes [Logic Haystacks](https://aclanthology.org/2026.eacl-short.3/), [Humanity's Last Exam](https://www.nature.com/articles/s41586-025-09962-4) and work on attention limitations in long-context models.

## Datasets and data ecosystems

I work on reusable task infrastructure, dataset provenance, licensing and attribution. Projects include [tasksource](https://github.com/sileod/tasksource) and the [Data Provenance Initiative](https://www.dataprovenance.org/), including its ICLR and NeurIPS publications.

## Encoder models

I train efficient encoder models for natural language inference, reasoning and zero-shot classification. [ModernBERT-base-nli](https://huggingface.co/tasksource/ModernBERT-base-nli) is trained on a broad collection of NLI and reasoning tasks and remains state of the art on several benchmarks.
