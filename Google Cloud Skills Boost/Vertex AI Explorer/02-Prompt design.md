# Prompt Design with Gemini

Prompt engineering is all about how to design your prompts so that the response is what you were indeed hoping to see. The idea of using "unfancy" prompts is to minimize the noise in your prompt to reduce the possibility of the LLM misinterpreting the intent of the prompt.

The first thing is to be consice and provide only the required information to the LLM so that the response is exactly what you asked.

```Python
wrong_prompt = "Give me names for a tire store that specializes in repairing tires rather than selling new ones."

correct_prompt = "Give me names for a tire store."
```

Try to be consice but correctly define how the LLM should respond to your prompt.

```Python
wrong_prompt = "Tell me about flowers"

correct_prompt = "List all the flowers can grow indoors"
```

LLMs perform best when you only give them one task at a time rather than giving all of your tasks at once since doing so can cause the model to hallucinate and provide wrong responses or just straight up gibberish.

```Python
wrong_prompt = "Tell me the population of france and how can I make spaghetti at home."

correct_prompt = "How can I make spaghetti at home"
second_prompt = "What is the total population of france."
```

## Adding Guardrails

If your users keep on giving multiple instructions at once or ask something that is irrelevant to the context of the model or maybe they give partial instructions etc. All of these things can cause the LLM to hallucinate.

Gemini allows the developers to give the model `system instructions.` These instructions tell the model what type of questions it can answer and how it should answer them. You can also add responses for questions that the model cannot answer.

You can also add options in your prompt so that the response is more on the acquracy side and less on the generative side.

```Python
wrong_prompt = "What should I cook for dinner?"

correct_prompt = "I only have eggs and bread what can I prepare for dinner."
```

## Providing Examples

Giving the model an example is a great way to make the response more acqurate. Typically, one to five examples (shots) are enough to improve the quality of responses. Including too many examples can cause the model to over-fit the data and reduce the quality of responses.

- Zero-shot prompting is when you don't give the model any examples.
- One-shot prompting is when you only provide a single example.
- Few-shot prompting is when you only provide multiple examples.

```Python
zero_shot = "Generate an Image of a garden"

one_shot = "Generate an Image of a garden like central park."

few_shot = "Generate an Image of a garden like central park and in the style of starry night"
```
