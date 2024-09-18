# Response Quality Enhancer

This repository contains a condensed version of a prompt designed to improve the quality of LLM responses by setting a high standard for relevance, practicality, specificity, personalization, and comprehensiveness.

## What the Prompt Achieves

The Response Quality Enhancer prompt **emphasizes the qualities of the final response, focusing on what the answer should be like**. It **provides a checklist of criteria for self-evaluation**, making it **outcome-oriented, aiming for an ideal response based on specific attributes**.

By adhering to specific criteria, the prompt ensures that the generated content is:

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

By incorporating these qualities, the prompt helps LLMs aim for an "ideal" response, enhancing overall communication effectiveness and user satisfaction.

## When to Use the Prompt

This prompt should be used in scenarios where the quality and depth of the LLM's response are crucial. It is particularly beneficial when:

- **Detailed Explanations Are Required**: For complex topics that need thorough and clear explanations.
- **User Engagement Is a Priority**: When encouraging ongoing interaction and addressing user needs comprehensively.
- **Cultural Sensitivity Matters**: In contexts involving diverse audiences where respect and sensitivity are important.
- **Accuracy and Verifiability Are Essential**: When providing information that must be precise and backed by credible sources.
- **Anticipating User Needs**: In situations where foreseeing and addressing potential follow-up questions enhances the user experience.

By focusing on the outcome and aiming for an ideal response based on specific attributes, this prompt ensures that the LLM provides high-quality, user-centric content.

## Original Source

The original prompt is based on the "Response Quality Enhancer" found in the [Awesome_GPT_Super_Prompting](https://github.com/CyberAlbSecOP/Awesome_GPT_Super_Prompting) repository by CyberAlbSecOP.

## Why a Condensed Version?

The original Response Quality Enhancer prompt, while highly effective, has two main limitations:

- **Token Consumption**: The original prompt is quite lengthy, consuming a significant number of tokens. This can be problematic in contexts where token usage directly affects costs or where there are strict limits on input length.
- **Character Limit in ChatGPT**: ChatGPT's custom instructions are limited to 1500 characters. The original prompt exceeds this limit, making it impossible to use in its entirety within ChatGPT's custom instruction feature.

By creating a condensed version, we address both of these issues:

- **Reduced Token Consumption**: Potentially lowering costs and allowing for more efficient use of the available context window.
- **Compatibility with ChatGPT's Custom Instructions**: Enabling users to fully implement the quality enhancement features within character limits.

## Condensed Version

The condensed version in this repository was created using an AI-assisted technique to minimize token usage while maintaining the prompt's effectiveness. This version is optimized for LLMs and may not be easily readable by humans.

You can find the condensed prompt in the [prompt.txt](prompt.txt) file in this repository.

## Technique Used

The condensation technique involved:

- Using an LLM to rewrite the original prompt with minimal tokens.
- Iterative refinement through follow-up prompts.
- Focusing on preserving the prompt's core functionality and intent.

## Usage

If you're unsure about what this condensed prompt does, you can ask any LLM the following:

**Explain this prompt:**

```
[Insert the condensed prompt text from prompt.txt here]
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
   For all responses in this conversation, please adhere to the following quality criteria: [Insert the content of prompt.txt here]
   ```

3. Follow this with your actual query or request.

Remember to include this instruction at the start of each new conversation with Claude for consistent application of the quality criteria.

## Contribution

Feel free to contribute to this project by suggesting improvements or reporting issues. Please ensure that any contributions maintain the spirit of the original prompt while optimizing for token efficiency.

## License

See the [LICENSE](LICENSE) file for details.
