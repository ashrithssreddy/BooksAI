# Understanding Tokenizers for Beginners

A **tokenizer** is a tool that splits sentences or text into smaller parts called **tokens**. Tokens are usually pieces of words or whole words that the model can understand and work with. Think of it as breaking down a sentence into chunks that the AI can process.

## Example Sentence and Tokens

Let's take an example sentence and see how it turns into tokens:

### Sentence
> "Hello, how are you?"

### Tokens
The tokenizer might split this into:
1. "Hello"
2. ","
3. "how"
4. "are"
5. "you"
6. "?"

Each of these parts is a token. Some tokenizers break words into even smaller chunks. For example, instead of “Hello,” you might get “Hel” and “lo” as separate tokens. This breakdown depends on the model, which has been trained to understand text this way.

Once we have these tokens, each one gets a unique number (like 1532 for "Hello"), so the model can use them in calculations. Here’s how the sentence might look in numbers:

- **Tokens as numbers**: `[1532, 45, 82, 108, 10, 59]`

These numbers are what the model actually "sees" and understands, even though we think of it as working with words. The tokenizer lets us go back and forth between words and the numbers the model needs.
