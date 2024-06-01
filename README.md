# GenAI: HuggingFace Integration

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


## Requirements

To run the examples in this repository, you need to install several Python packages, including:
- `langchain`
- `huggingface_hub`
- `transformers`
- `sentence_transformers`
- `accelerate`
- `bitsandbytes`
- `langchain_community`

## Installation

You can install the required Python packages using `pip`. Make sure to install all dependencies to ensure compatibility and functionality.

## Setup

Set your HuggingFace API token as an environment variable to access models hosted on the HuggingFace Hub.

## Usage

### Using HuggingFaceHub via API

#### T5 Encoder-Decoder Model

This section explains how to use the T5 encoder-decoder model hosted on HuggingFace Hub via API. You'll learn how to set up the model, create a prompt template, and execute queries to get answers.

#### Decoder Only Models

This section covers the usage of decoder-only models (such as GPT-J and StableLM) hosted on HuggingFace Hub via API. You'll learn how to configure and use these models for text generation tasks.

### Local Pipelines

#### T5-Flan - Encoder-Decoder (Seq2Seq Model)

This section details how to download and use the T5-Flan encoder-decoder model locally. It includes steps to set up the model, tokenizer, and pipeline, and how to use them for text generation tasks.

#### Decoder Only Model

This section explains how to use locally downloaded decoder-only models (such as GPT-2) for text generation. You'll learn about setting up the model and tokenizer, creating a local pipeline, and executing queries.

## Notes

- Ensure that you have a valid HuggingFace API token to access models hosted on HuggingFace Hub via API.
- The examples provided demonstrate how to use both encoder-decoder models and decoder-only models in various scenarios.
- You can modify the `model_id` parameter to use different models based on your requirements.

