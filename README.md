# How to install DeepSeek-R1 on Mac
1. On Browser, go to [ollama](https://ollama.com/) to download your ollama app.
2. Unzip the zip file, get an ollama.app.
3. Move ollama.app to your Application folder.
4. Double click ollama.app under Application folder to activate it.
5. On Browser, go to [Model](https://ollama.com/search) and click on [deepseek-r1](https://ollama.com/library/deepseek-r1), and select the model you want from the dropdown menu. Copy the command from right side.
6. Open your MacOS Terminal, paste command "ollama run deepseek-r1:1.5b" and enter.
7. Terminal will start to pull model data and summon DeepSeek on your Terminal.
8. Start to use DeepSeek-R1.

# Create a shortcut to summon DeepSeek-R1
1. On Terminal, input 'alias DS1="ollama run deepseek-r1:1.5b"'
2. Next time, just use "DS1" to summon DeepSeek-R1,1.5b model

## alias sample for all
- alias DS1="ollama run deepseek-r1:1.5b"
- alias DS7="ollama run deepseek-r1:7b"
- alias DS8="ollama run deepseek-r1:8b"
- alias DS14="ollama run deepseek-r1:14b"
- alias DS32="ollama run deepseek-r1:32b"
- alias DS70="ollama run deepseek-r1:70b"
- alias DS671="ollama run deepseek-r1:671b"