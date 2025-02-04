# Basic Local LLM (Large Language Model) Python Script

### Using Ollama: A Free Open-Source Tool That Runs LLMs on Local Machines

## Tutorial How to Use:
Make Sure Python is Installed on Your Local Machine:
https://www.python.org/downloads/

Also, Visual Studio Code:
https://code.visualstudio.com/

Download Ollama for Appropriate OS Version Here:
https://ollama.com/download

Note Which Version You Want to Run Here:
https://github.com/ollama/ollama

Run the installer. Then proceed to type the following commands 
```
ollama // Shows available commands
ollama pull llama3.1 // llama3.1 is just an example and the one I used
```

Let the Installation Finish.

You can test the functionality locally by typing
```
ollama run llama3.1 // This will start llama3.1
hello world // You can type whatever you want to ask it here but hello world is just an example prompt
/bye // To exit
```

In Visual Studio Code, you need to setup a Python Virtual Environment to install the dependencies we need.

Create a folder, then open said folder.

NOTE: Python Installations Can Vary from System to System But This is What Worked for Me

After ensuring the terminal is directed to the folder: In the terminal, type the following:
```
py -m venv chatbot // Instantiates the venv virtual environment in the folder.
.\chatbot\Scripts\activate.ps1 // Runs the virtual environment.
py main.py // Runs the script I made.
```

And that's it!

I wanted to explore how LLMs can be implemented using Python, and upon completing this and doing research, Ollama is also a suitable tools to use for Web Applications! Pretty Neat!
