# Gemma-The-Writer-9B-GGUF on your Local PC
A full fledged Writer assistant with LlamaCPP and python on your Local PC

<img src='https://huggingface.co/DavidAU/Gemma-The-Writer-9B-GGUF/resolve/main/the-writer.jpg' width=450>
<br><br>
Running 9B parameter Writer assistant based on Gemma2 on your PC
- No GPU is required
- textual interface in the terminal
- speed up to 1,7 tokens per seconds
- text steraming in the terminal
- generation and speed KPI
- chat history in Log file


### Virtual environment and requirements
Tested on Python 3.11 Windows 11 OS

#### Create a `venv`
```
python -m venv venv
venv\script\activate
```

#### Install the dependencies
```
pip install llama_cpp_python==0.2.85 tiktoken
```

#### Download the model from the repo into subdirectory called `model`
- here because of only 16GB ram I am using Q3
- REPO: [https://huggingface.co/DavidAU/Gemma-The-Writer-9B-GGUF](https://huggingface.co/DavidAU/Gemma-The-Writer-9B-GGUF)
- FileName: Gemma-The-Writer-9B-D_AU-Q3_k_s.gguf

From the terminal run
```
python .\writer.py
```

