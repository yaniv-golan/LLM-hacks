# LLM-hacks

This repository contains a collection of prompts and techniques designed to enhance the capabilities of Large Language Models (LLMs). Our goal is to improve various aspects of LLM performance, from reasoning to response quality.

## Repository Structure

- **Deductive Reasoning Enhancer**: Tools to improve the deductive reasoning capabilities of LLMs.
- **Response Development Enhancer**: Methods to guide LLMs through a structured approach to response generation.
- **Response Quality Enhancer Plus**: An advanced prompt for improving overall response quality and reasoning.
- **Response Quality Enhancer**: A condensed version of quality enhancement techniques for token-efficient applications.

## Key Files

- `merged_best_practice_prompt.txt`: A comprehensive prompt that combines best practices for LLM interaction, including deductive reasoning, response development, and quality enhancement techniques.

## Key Features

1. **Deductive Reasoning Enhancer**
   - Empowers LLMs to perform accurate deductive reasoning
   - Applies reasoning internally without exposing steps
   - Provides clear answers with logical explanations

2. **Response Development Enhancer**
   - Guides LLMs through a systematic approach to problem-solving
   - Encourages consideration of multiple perspectives
   - Implements ideas from "On the Diagram of Thought" paper

3. **Response Quality Enhancer Plus**
   - Builds upon the original Response Quality Enhancer
   - Incorporates Chain-of-Thought (CoT) principles
   - Ensures logical consistency and comprehensive guidance

4. **Response Quality Enhancer**
   - Condensed version for minimal token usage
   - Emphasizes qualities of the final response
   - Provides a checklist of criteria for self-evaluation

5. **Merged Best Practice Prompt**
   - Combines key aspects of all enhancers
   - Provides a unified approach to improving LLM interactions
   - Ideal for users seeking a comprehensive solution

## Usage

Each sub-directory contains specific instructions on how to use the prompts and techniques. Generally, you can incorporate these prompts into your LLM interactions by:

1. Using them as custom instructions (for platforms that support this feature)
2. Pasting the prompt at the beginning of your conversation with the LLM

For detailed usage instructions, please refer to the README.md file in each sub-directory.

To use the merged best practice prompt, simply include the content of `merged_best_practice_prompt.txt` at the beginning of your LLM interaction or in the custom instructions section where available.

## Contributing

We welcome contributions to improve and expand these LLM hacks. Please read our contributing guidelines (if available) before submitting pull requests.

## License

This project is licensed under the terms of the LICENSE file in the root directory of this project.

## Acknowledgments

- The "Response Quality Enhancer" is based on work from the [Awesome_GPT_Super_Prompting](https://github.com/CyberAlbSecOP/Awesome_GPT_Super_Prompting) repository by CyberAlbSecOP.
- The "Response Development Enhancer" is inspired by the paper ["On the Diagram of Thought"](https://arxiv.org/abs/2409.10038).
- The "Response Quality Enhancer Plus" incorporates concepts from the paper ["Chain of Thought Empowers Transformers to Solve Inherently Serial Problems"](https://arxiv.org/pdf/2402.12875) by Zhiyuan Li, Hong Liu, Denny Zhou, and Tengyu Ma.

## Contact

For questions and feedback, please open an issue in the GitHub repository.
