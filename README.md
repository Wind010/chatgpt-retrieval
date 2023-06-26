# chatgpt-retrieval

Simple script to use ChatGPT on your own files.

Here's the [YouTube Video](https://youtu.be/9AXP7tCI9PI).

## Installation

Install [Langchain](https://github.com/hwchase17/langchain).
```
pip install langchain
pip install openai
pip install chromadb
pip install tiktoken
```
Create a `secrets.py` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys).
```python
API_KEY = "YOUR_API_KEY"
```

Place your own files into the mydata folder.


## Example usage
```
> python sync.py
> python chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
```

