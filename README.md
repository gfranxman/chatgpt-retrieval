# chatgpt-retrieval

Run ChatGPT on your own files.
Video summary: https://youtu.be/9AXP7tCI9PI

**Installation**

Install Langchain https://github.com/hwchase17/langchain.
```
pip install langchain
pip install openai
```
Modify `constants.py` to use your own OpenAI API key. https://platform.openai.com/account/api-keys.

Place your own data into "data.txt".

**Example usage:**
```
> python chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
```