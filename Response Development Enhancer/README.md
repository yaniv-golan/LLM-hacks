# Response Development Enhancer

This repository contains a prompt designed to improve the quality of LLM responses by guiding the response development process through structured analysis, refinement, and synthesis.

## Purpose

This prompt aims to enhance the way LLMs generate responses by focusing on the thought process behind the answer. It emphasizes a systematic approach to problem-solving, encouraging the LLM to:

- **Consider Multiple Approaches**: Explore different perspectives and methods.
- **Critically Evaluate Ideas**: Assess the strengths and weaknesses of each idea.
- **Refine Ideas**: Improve upon initial thoughts until confident in their soundness.
- **Synthesize Information**: Combine the strongest ideas into a coherent response.
- **Present Logically**: Organize the response in a logical progression, highlighting key points.
- **Ensure Engaging Flow**: Maintain a natural and engaging narrative throughout the response.

By following this process, the LLM produces responses that are well-thought-out, logically structured, and effectively communicate complex ideas.

## What the Prompt Achieves

The Response Development Enhancer prompt **focuses on the process of generating the response, detailing how to approach and construct the answer**. It **provides a step-by-step method for developing and refining ideas**, making it **process-oriented, guiding LLMs through a methodical approach to problem-solving**.

This prompt is designed using the technique described in the paper ["On the Diagram of Thought"](https://arxiv.org/abs/2409.10038). The technique models iterative reasoning in LLMs as the construction of a directed acyclic graph (DAG). By organizing propositions, critiques, refinements, and verifications into a cohesive DAG structure, the LLM can explore complex reasoning pathways while maintaining logical consistency. This approach allows the model to iteratively improve its reasoning through natural language feedback, enhancing both the coherence and depth of its responses.

## When to Use the Prompt

This prompt should be used in scenarios where the process of arriving at the answer is as important as the answer itself. It is particularly beneficial when:

- **Complex Problem-Solving Is Required**: For tasks that involve intricate issues needing deep analysis.
- **Multiple Solutions Are Possible**: When exploring different perspectives or solutions is valuable.
- **Critical Thinking Is Essential**: In situations that require thorough evaluation and justification of ideas.
- **Logical Structure Is Important**: When presenting arguments or explanations that benefit from a clear, logical progression.
- **Educational Contexts**: For generating responses that teach or explain by walking through reasoning steps.

By focusing on the process and guiding the LLM through structured development, this prompt ensures that responses are not only informative but also demonstrate the reasoning behind them.

## Original Source

The prompt is based on the "Response Development Enhancer" concept, emphasizing structured thinking and systematic problem-solving in LLM responses. It is designed using the technique described in the paper ["On the Diagram of Thought"](https://arxiv.org/abs/2409.10038). This paper introduces a framework that models iterative reasoning in LLMs as constructing a directed acyclic graph (DAG), enabling the exploration of complex reasoning paths while maintaining logical consistency and soundness in the reasoning process.

## Technique Used

The technique used to create this prompt involved having an LLM digest the paper ["On the Diagram of Thought"](https://arxiv.org/abs/2409.10038) and generate a prompt that implements its core ideas. The steps included:

- **Digesting the Article**: The LLM read and understood the key concepts and methodologies presented in the paper.
- **Extracting Core Ideas**: Identified the essential elements of modeling iterative reasoning as a directed acyclic graph (DAG) within a single model.
- **Prompt Generation**: Created a prompt that encapsulates these core ideas, guiding the LLM to apply them in generating responses.
- **Iterative Refinement**: Fine-tuned the prompt through follow-up prompts to ensure it effectively instructs the LLM to use the DAG-based reasoning approach.

By leveraging the LLM's ability to comprehend and implement advanced reasoning techniques, the prompt enhances the model's capacity to produce logically consistent and well-structured responses.

## Usage

If you're unsure about what this prompt does, you can ask any LLM the following:

```
Explain this prompt:

[Insert the prompt text from prompt.txt here]
```

The LLM should be able to interpret and explain the prompt's purpose and functionality.

### Incorporating the Prompt

#### For ChatGPT (Using Custom Instructions)

1. Log in to your ChatGPT account (requires ChatGPT Plus).
2. Go to **Settings** -> **Personalization** -> **Custom Instructions**.
3. In the "How would you like ChatGPT to respond?" section, add:

   ```
   Please follow the response development process outlined here: [Insert the content of prompt.txt here]
   ```

4. Click **Save** at the bottom of the page.

**Note**: While Custom Instructions influence ChatGPT's responses, they may not be as powerful as modifying the core system prompt.

#### For Claude

Currently, Claude does not have an option to set persistent custom instructions across all chats. To use this prompt with Claude:

1. Start a new conversation with Claude.
2. Begin your interaction by pasting the following:

   ```
   For all responses in this conversation, please adhere to the following response development process:
   [Insert the content of prompt.txt here]
   ```

3. Follow this with your actual query or request.

Remember to include this instruction at the start of each new conversation with Claude for consistent application of the process.

## Contribution

Feel free to contribute to this project by suggesting improvements or reporting issues. Please ensure that any contributions maintain the spirit of the original prompt.

## License

See the [LICENSE](LICENSE) file for details.
