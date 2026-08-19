### Docstring Generation

Input: A Python function or method without a docstring.

Output: A concise and informative doc-string describing the function’s purpose, in-puts, and outputs.

Prompt:

```
Generate a detailed docstring for the following function. Include:
1. A clear description of what the function does 
2. All parameters with their types and descriptions
3. The return value(s) with type and description 
4. Any exceptions that may be raised
```

Here is the function: [INPUT FUNCTION HERE] Format the docstring using Google-style docstring format. Be specific about types and ensure the documentation is clear and comprehensive. Provide only the docstring and nothing more

### Code Query Generation

Input: A code snippet implementing a specific functionality.

Output: A natural language query that a developer might use to search for this functionality.

Prompt:

```
You are a query generator. Your task is to produce ONLY a brief and concise natural-language search query that developers could use to find similar code solutions. The code snippet to analyze will be provided below.

OUTPUT RULES: 
– Generate ONLY the search query.
– No explanations or additional text.
– Length: 10-30 words.
– Use common programming terminology.
– Clearly capture the core functionality of the code.

GOOD EXAMPLES:
[Insert clear and concise examples of good code search queries here.]

BAD EXAMPLES:
[Insert examples of poor-quality queries here.]

INPUT FUNCTION:
[Insert function signature or definition here]

FUNCTION DOCSTRING:
[Insert existing or generated docstring here]

CODE SNIPPET:
[Insert the full code snippet here]
```
