# text-embedding-openai-azure-clojure

Based on [wkok-openai](https://github.com/wkok/openai-clojure), **text-embedding-openai-azure-clojure** is a Clojure library that calls azure to generate text embeddings using the `text-embedding-3-large` model from OpenAI.

- **Input**: Accepts single text strings or arrays of text strings. You simply provide your input as plain text.
- **Token Limit**: Each input string must not exceed **8192 tokens**. To check how many tokens your input text contains, you can use [this tokenizer tool](https://gpt-tokenizer.dev/).
- **Array Input**: You can process up to **2048** inputs in a single array request.
- **Output**: Returns embeddings as vectors of floating-point numbers, one vector for each input text.

