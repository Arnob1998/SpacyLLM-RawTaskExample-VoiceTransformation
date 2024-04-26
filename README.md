# SpacyLLM-RawTaskExample-VoiceTransformation

## Description
A powerful yet user-friendly toolkit for natural language processing (NLP) tasks, showcasing the seamless integration of Large Language Models (LLMs) into spaCy pipelines. Effortlessly prototype and execute complex NLP transformations with minimal effort. The project features a modular system that allows for fast prototyping and prompting, enabling you to turn unstructured text into robust outputs for various NLP tasks without the need for extensive training data.

## Features

- Easy integration of Large Language Models into spaCy pipelines
- Fast prototyping and execution of complex NLP transformations
- Example: Seamless voice transformation (e.g., active to passive and passive to active)
- Minimal setup and configuration required
- Example-driven configuration files for quick setup
- Outputs structured JSON for easy integration with other systems

## Files and Their Purposes

- `app.ipynb`: This Jupyter notebook showcases the inferencing process using the custom pipeline. It provides a clear demonstration of how to use the toolkit for NLP tasks.
  
- `examples.yml`: This YAML file contains examples for few-shot prompting that is customized configured. It serves as a reference for users to understand how to structure input examples for different NLP tasks.

- `fewshot.cfg`: This configuration file defines the pipeline for the task. It specifies the sequence of operations to be performed on the input text to achieve the desired NLP transformation.

- `raw.custom.jinja`: This file is a prompt template and injects documents’ data into the prompt. It plays a crucial role in generating prompts for the Large Language Models used in the pipeline.
