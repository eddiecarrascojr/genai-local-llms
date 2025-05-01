# genai-local-llms
Part of the GenAI series on YouTube here is a simple intro video on how to run LLMs locally on your computer.

## Set up 
1) Download Ollama from the offical website. [Here](https://ollama.com/download)
2) install python libraries
    - 

### Quick Install Test
```bash
ollama run llama3.2:1b
```
Note: llama3.2:1b is a small model that can run nearly everywhere because of it's 1.4Gb size.

```bash
>>> write me a poem about python programming lanaguge.
```
```bash
output: 
In Python's realm, where code does reign
A language born, with simplicity and gain
 Syntax so clean, the syntax so bright
Guides developers through day and night

With loops and functions, it makes its way
Through data and logic, in a computational sway
 Object-Oriented, it's a delight
 Classes and instances, shining with all their might

The `print()` function, a hero true and bold
 Spreading messages, stories untold
 While the `len()` function, a count so grand
 Reveals the length of data within the land

The `if` statement, a conditional guide
Helping developers navigate the code's tide
 For or not, it does decide the fate
 Of the program's flow, in an automated state

Python's magic, with indentation so neat
 Reduces errors, and makes the code feel complete
 The famous phrase, "It's better to keep it short"
 A mantra for programmers, to never doubt

With libraries galore, it's a developer's best friend
 NumPy, pandas, and scikit-learn, until the very end
 Machine learning, with TensorFlow so fine
 Python's power, makes data science shine

So here's to Python, a language so divine
 A tool for coders, all around the vine
 Its simplicity, its elegance, its might
 Make it a favorite, day and night.
```
### List of Models can be found here:
- Gemma
- DeepSeek-R1
- Llama3.3
- Llama3.2
- Mistral

for more comprehensive list can be found [here](https://github.com/ollama/ollama)

### Run LLMS locally
Choose a model from Ollama and pull it.
```bash
ollama pull llama3.2:1b
```
This will pull the model locally for you to run and save them to your local computer.
```bash
ollama list
```
Will list all the models you have locally.

Run the model locally
```bash
ollama run llama3.2:1b 
```
### Create a Virtual Enjoinment
Run this command to create a virutal environment
```bash
python -m venv locall_llama3_1b
```

Activate the Vitural env
```bash
locall_llama3_1b/Scripts/activate
```

Install Ollama API
```bash
pip install ollama
```

### Run the notebook
Now you should be able to run the python notebook and experiment with various prompts and models.

# Happy Prompting!

