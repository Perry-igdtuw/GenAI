# GenAI
# HuggingFace Integration

This repository provides comprehensive examples of using HuggingFace models in two different ways:
1. Models hosted on HuggingFace Hub via API.
2. Local pipelines (downloading models locally).

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Setup](#setup)
- [Usage](#usage)
  - [Using HuggingFaceHub via API](#using-huggingfacehub-via-api)
    - [T5 Encoder-Decoder Model](#t5-encoder-decoder-model)
    - [Decoder Only Models](#decoder-only-models)
  - [Local Pipelines](#local-pipelines)
    - [T5-Flan - Encoder-Decoder (Seq2Seq Model)](#t5-flan---encoder-decoder-seq2seq-model)
    - [Decoder Only Model](#decoder-only-model)
- [Notes](#notes)
- [License](#license)

## Requirements

To run the examples in this repository, you need to install the following Python packages:
- `langchain`
- `huggingface_hub`
- `transformers`
- `sentence_transformers`
- `accelerate`
- `bitsandbytes`
- `langchain_community`

## Installation

Install the required Python packages using `pip`:

```bash
pip install langchain huggingface_hub transformers sentence_transformers accelerate bitsandbytes langchain_community
