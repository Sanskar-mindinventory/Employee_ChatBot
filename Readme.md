# ChatBot Project

## Overview
This is a small demo ChatBot project based on AI/ML with Python.In this project ChatBot will read the Employee data from the CSV. It will generate vector using AI model and after that we can ask question related to any employee and it will provide output.  

## Features
- **Chatbot:** This is a small chatbot based on AI to acquire the information about employee.
- **Ask Question:** Questions related to employee dataset can be asked
- **Answer Question:** Generate AI based answer for the asked question using provided employee dataset.

## Project Setup
To set up the Quora project, follow the steps below:

- Clone the repository to your local machine using 
```
git clone https://github.com/Sanskar-mindinventory/Employee_ChatBot.git
```

- Navigate to the project directory using 
```
cd Test (Folder name is the Test)
```
## Install Requirements
- Create Virtual environment
```
python -m venv <name_of_virtual_environment>
```
- To activate virtual environment
```
source <name_of_virtual_environment>/bin/activate
```
- To install requirements
```
pip install -r requirements.txt
```

## Database
This app consists 1 vector database which is automatically created at the runtime.

## Running the Project
To run the Chatbot project locally, execute the following command:
- Step-1:Crete folder with the name **models** at root level of project directory and Need to add llm model inside **models** directory (For the setup and need to add model once).

    [You can download model from here](https://huggingface.co/TheBloke/Llama-2-13B-chat-GGML/resolve/main/llama-2-13b-chat.ggmlv3.q4_0.bin)

- After creating models folder project folder structure will become similar to this.

    ![Image is unsupported](https://github.com/Sanskar-mindinventory/Employee_ChatBot/blob/main/folder_structure.png)


- Step-2: To run the project 
```
python app.py
```

## Packages Used
- **flask:** Flask is a python based web framework which is used to develop API for the Chatbot Integration.

- **pandas:** Pandas is a Python library used for working with data sets.It has functions for analyzing, cleaning, exploring, and manipulating data.

- **langchain:** LangChain is a framework for developing applications powered by language models. It enables applications that:
    1. Are context-aware: connect a language model to sources of context (prompt instructions, few shot examples, content to ground its response in, etc.)
    2. Reason: rely on a language model to reason (about how to answer based on provided context, what actions to take, etc.)
