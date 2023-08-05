
## Project description

The repo is about how to create single chatbot for data available on public forum and custom data which can act as our personal chatbot.

The application has been built using Streamlit, OpenAI & LangChain.

An OpenAI API key must be created and added to the environment. The commands have been given below.


## Installation

##### To create a virtualenv: lang
```
 virtualenv lang
```

##### To activate virtualenv on Windows: lang
```
 lang\Scripts\activate
```

##### To activate virtualenv on Mac: lang
```
 source lang/bin/activate	
```

##### To install requirements:
```
 pip install -r requirements.txt
```

##### To set OPENAI_API_KEY, run the following in terminal in Mac:
```
 echo "export OPENAI_API_KEY='yourkey'" >> ~/.zshrc
```
##### To set OPENAI_API_KEY, run the following in cmd in Windows:
```
 setx OPENAI_API_KEY “<yourkey>”
```

#### To run the application:
```
 streamlit run Chat_engine.py
```
## Avatars link

[Avatars](https://www.dicebear.com/styles)
