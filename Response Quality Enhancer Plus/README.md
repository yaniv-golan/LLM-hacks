# Response Quality Enhancer Plus

This repository contains an **enhanced version of the Response Quality Enhancer prompt**. It builds upon the original prompt Response Quality Enhancer with CoT
 by incorporating additional criteria inspired by the paper [*Chain of Thought Empowers Transformers to Solve Inherently Serial Problems*](https://arxiv.org/pdf/2402.12875) by Zhiyuan Li, Hong Liu, Denny Zhou, and Tengyu Ma.

## What the Prompt Achieves

The **Response Quality Enhancer Plus** prompt not only emphasizes the qualities of the final response but also focuses on the reasoning process that leads to the answer. By integrating concepts from the referenced paper, it enables language models to better handle complex, serial reasoning tasks.

The prompt provides a checklist of criteria for self-evaluation, ensuring that the generated content is:

- **Relevant and Context-Fit**: Directly addresses the user's query within the appropriate context.
- **Practical and Actionable**: Provides useful information with clear, step-by-step guidance when necessary.
- **Specific and Verifiable**: Includes detailed information that can be confirmed, citing sources when needed.
- **Tailored and Scalable**: Customized to the user's needs while remaining applicable to broader scenarios.
- **Comprehensive and Anticipatory**: Covers all relevant aspects and anticipates potential follow-up questions.
- **Multimodal-Friendly**: Supports the inclusion of tables or alternative formats to enhance understanding.
- **Analogical**: Uses analogies to simplify complex concepts.
- **Uncertainty-Transparent**: Acknowledges any uncertainties or limitations in the provided information.
- **Culturally Sensitive**: Respects cultural differences and sensitivities.
- **Engagement-Encouraging**: Promotes further interaction and engagement with the user.
- **Breaks Down Complex Problems**: Deconstructs complicated issues into manageable parts.
- **Builds on Previous Points**: Ensures logical progression by connecting ideas cohesively.
- **Verifies Logic Consistency**: Checks reasoning for coherence and absence of contradictions.

By incorporating these additional qualities, the prompt helps language models produce responses that are not only high-quality but also exhibit robust reasoning and logical consistency.

## Incorporation of Chain-of-Thought

The enhancements in this prompt are inspired by the concept of **Chain-of-Thought (CoT)**, as detailed in the paper [*Chain of Thought Empowers Transformers to Solve Inherently Serial Problems*](https://arxiv.org/pdf/2402.12875). Key insights from the paper include:

- **Serial Reasoning Enhancement**: Encouraging models to think through problems step by step improves their ability to solve complex tasks.
- **Intermediate Reasoning Steps**: Making the reasoning process explicit helps models handle tasks requiring multi-step solutions.

The prompt leverages these insights by guiding the model to:

- **Break Down Complex Problems**: Approach complex queries by dissecting them into simpler components.
- **Build on Previous Points**: Ensure each part of the response logically follows from the previous one.
- **Verify Logic Consistency**: Check that the reasoning is coherent throughout the response.

## When to Use the Prompt

This enhanced prompt is ideal in scenarios where both the quality and the reasoning behind the LLM's response are crucial. It is particularly beneficial when:

- **Complex Problem Solving Is Required**: For tasks that involve multi-step reasoning or intricate logic.
- **Detailed Explanations Are Necessary**: When in-depth understanding and clarity are needed.
- **Logical Consistency Matters**: To ensure that responses are coherent and free of contradictions.
- **User Engagement Is a Priority**: When encouraging ongoing interaction and addressing user needs comprehensively.
- **Cultural Sensitivity and Accuracy Are Essential**: In contexts involving diverse audiences where respect, sensitivity, and precise information are important.

By focusing on both the outcome and the reasoning process, this prompt ensures that the LLM provides high-quality, logically sound, and user-centric content.

## Original Source

The original prompt is based on the "Response Quality Enhancer" found in the [Awesome_GPT_Super_Prompting](https://github.com/CyberAlbSecOP/Awesome_GPT_Super_Prompting) repository by CyberAlbSecOP. This enhanced version builds upon it by integrating concepts from recent research to further improve the LLM's performance.

## Why an Enhanced Version?

Prompt 1 addresses the following limitations of the original prompt:

- **Enhanced Reasoning Abilities**: By incorporating Chain-of-Thought principles, the prompt improves the model's ability to handle complex reasoning tasks.
- **Logical Consistency**: Ensures that the response is coherent and that all arguments and points are logically connected.
- **Comprehensive Guidance**: Provides more detailed instructions to the model, leading to better quality outputs.

## Condensed Version

The enhanced prompt is available in a condensed format to minimize token usage while maintaining effectiveness. You can find the prompt in the [prompt.txt](prompt.txt) file in this repository.

## Technique Used

The enhancement process involved:

- **Incorporating Research Findings**: Integrating insights from the Chain-of-Thought research paper.
- **LLM-Assisted Rewriting**: Using an LLM to refine the prompt with a focus on minimal token usage and maximal clarity.
- **Iterative Refinement**: Continuously improving the prompt through testing and feedback.

## Usage

If you're unsure about what this enhanced prompt does, you can ask any LLM the following:

```
Explain this prompt:

[Insert the enhanced prompt text from prompt.txt here]
```

The LLM should be able to interpret and explain the prompt's purpose and functionality.

### Incorporating the Prompt

#### For ChatGPT (Using Custom Instructions)

1. Log in to your ChatGPT account (requires ChatGPT Plus).
2. Go to **Settings** -> **Personalization** -> **Custom Instructions**.
3. In the "How would you like ChatGPT to respond?" section, add:

   ```
   Please always consider the following quality criteria when responding: [Insert the content of prompt.txt here]
   ```

4. Click **Save** at the bottom of the page.

**Note**: While Custom Instructions influence ChatGPT's responses, they may not be as powerful as modifying the core system prompt.

#### For Claude

Currently, Claude does not have an option to set persistent custom instructions across all chats. To use this prompt with Claude:

1. Start a new conversation with Claude.
2. Begin your interaction by pasting the following:

   ```
   For all responses in this conversation, please adhere to the following quality criteria:
   [Insert the content of prompt.txt here]
   ```

3. Follow this with your actual query or request.

Remember to include this instruction at the start of each new conversation with Claude for consistent application of the quality criteria.

## Contribution

We welcome contributions to improve this project. Please ensure that any suggestions or modifications maintain the spirit of the original prompt while enhancing its effectiveness and efficiency.

## License

See the [LICENSE](LICENSE) file for details.
