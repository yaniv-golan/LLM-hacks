# Deductive Reasoning Enhancer

This repository contains a prompt designed to improve the deductive reasoning capabilities of Large Language Models (LLMs). The prompt guides the LLM to assess when deductive reasoning is needed and to apply it effectively without revealing internal reasoning processes.

## What the Prompt Achieves

The Deductive Reasoning Enhancer prompt **empowers LLMs to perform accurate deductive reasoning by providing a structured yet internal approach**. It ensures that the LLM:

- **Detects the Need for Deductive Reasoning**: Analyzes the prompt to determine if deductive reasoning is required for a correct response.
- **Applies Reasoning Internally**: Utilizes a step-by-step reasoning process internally without exposing these steps in the final answer.
- **Provides Clear Answers with Explanations**: Delivers concise and accurate answers supported by logical explanations.
- **Uses Up-to-Date Knowledge**: References information available up to its knowledge cutoff date without specifying the exact date.

By following this approach, the prompt enhances the LLM's ability to produce logically sound and contextually accurate responses while maintaining clarity and professionalism.

## When to Use the Prompt

This prompt is particularly useful in scenarios where deductive reasoning is essential for accuracy and reliability. It is ideal for:

- **Logical Evaluations**: Assessing the validity of statements, arguments, or claims.
- **Problem Solving**: Addressing questions that require applying general principles to specific cases.
- **Critical Analysis**: Engaging in discussions that necessitate careful reasoning and evidence-based conclusions.
- **Educational Contexts**: Assisting learners in understanding logical structures and reasoning processes.

By enhancing deductive reasoning, the prompt ensures that the LLM can handle complex reasoning tasks effectively.

## Original Source

The prompt was developed based on a discussion in the Reddit thread: [Apparently, LLMs are strong inductive reasoners but poor deductive reasoners](https://www.reddit.com/r/LocalLLaMA/comments/1f2zyv7/apparently_llms_are_strong_inductive_reasoners/). The goal was to address the identified gap in LLMs' deductive reasoning abilities.

## Prompt Overview

The prompt instructs the LLM to:

- **Assess the Need for Deductive Reasoning**: Determine if deductive reasoning is necessary for the given prompt.
- **Apply Deductive Reasoning Internally**: Use logical reasoning steps internally without revealing them in the response.
- **Provide Clear Answers and Explanations**: Offer a concise answer accompanied by a logical explanation.
- **Utilize Knowledge Up to the Cutoff Date**: Base responses on information available up to its knowledge cutoff date without mentioning the specific date.
- **Maintain Professionalism**: Avoid disclosing internal reasoning processes and present information clearly and professionally.

## Usage

To use this prompt:

1. **Incorporate the Prompt into the LLM's Instructions**:

   Include the prompt at the beginning of your interaction to guide the LLM's responses.

   ```
   [Insert the Deductive Reasoning Enhancer prompt here]
   ```

2. **Interact with the LLM**:

   Pose questions or statements as you normally would. The LLM will internally determine if deductive reasoning is needed and respond accordingly.

### Example Interaction

**User**:

"Humans built one airport every day from the time planes were invented."

**LLM**:

"The claim that humans built one airport every day since planes were invented is inaccurate. Airplanes were invented in 1903, and the total number of days since then far exceeds the current number of airports worldwide. Moreover, the development of aviation infrastructure was gradual, and airports were not built at such a rapid pace. Therefore, this statement is false."

**Note**: This example interaction is inspired by a post by [Jikku Jose (@jikkujose)](https://x.com/jikkujose/status/1836400611895517595). 

## Contribution

Contributions are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request. Please ensure that any changes align with the prompt's goal of enhancing deductive reasoning without revealing internal processes.

## License

See the [LICENSE](LICENSE) file for details.
