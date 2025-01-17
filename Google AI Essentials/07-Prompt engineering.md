# Prompt Engineering

Prompt engineering is the practice of developing effective prompts to get useful output from generative AI. It involves writing clear and specific prompts that include relevant context.

The more clear and specific the prompt is, the more likely you are to get useful output. Prompt engineering also involves evaluating output and revising prompts to improve the quality of the output. This iterative approach is essential in prompt engineering.

Prompts should be clear, specific, and provide relevant context to guide the LLM (large language model). For example, instead of asking for restaurant recommendations in San Francisco, you should specify that you are looking for vegetarian options.

Prompt engineering is an iterative process. It often requires multiple attempts before getting the optimal output. If the output is not what you want, evaluate why, revise the prompt, and try again. Try different prompts and see how the LLM behaves differently. You can experiment with the length, wording, and level of detail in the prompt.

LLMs respond to the context provided in the prompt. Providing enough context is crucial to getting useful output from an LLM. It is important to critically evaluate all LLM output to determine if it is factually accurate, unbiased, relevant, and provides sufficient information. Do not make assumptions about an LLM's capabilities.

LLMs are trained on large amounts of text to identify patterns between words, concepts, and phrases. They predict the next word in a sequence based on probabilities. However, LLMs have limitations including bias, a tendency to hallucinate, and knowledge cutoffs. Because of these limitations, it is important to critically evaluate all LLM output.

- LLMs are trained on millions of sources of text, including books, articles, and websites. The more high-quality data an LLM receives, the better it performs.
- LLMs can predict what word is most likely to come next in a sequence of words, using statistical analysis to determine probabilities for different words.
- An LLM’s output may be biased because the data it was trained on contains bias. The data an LLM was trained on may not contain sufficient information on a specific domain or topic. An LLM may hallucinate and generate factually incorrect text.

## Prompting Techniques

Prompting techniques can help you get better results.

- Zero-shot prompting: Provides no examples in a prompt, and is best for simple tasks.
- Few-shot prompting: Provides two or more examples in a prompt, and can help clarify the desired format, phrasing, or general pattern.
- Chain-of-thought prompting: Requests an LLM to explain its reasoning processes step by step, which can help with complex problem solving.
- Prompt Chaining: Links connected prompts together, using the output from one prompt as input for the next, which is useful for solving complex tasks.

Combining Chain-of-Thought and Prompt Chaining significantly enhances the problem-solving process by breaking down a complex task into smaller steps.

> Previous prompts in the same conversation can influence the output of your most recent prompt, so you may want to start a new conversation if needed.
