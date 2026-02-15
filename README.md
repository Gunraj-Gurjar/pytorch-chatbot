# PyTorch Chatbot

This is a contextual chatbot implemented in PyTorch. I cloned this project to study and customize it.

## Project Overview
-   **Goal**: Easy-to-understand chatbot using a Feed Forward Neural Network.
-   **Customization**: Modify `intents.json` to change the chatbot's responses.

## Folder Structure
```
pytorch-chatbot-master/
├── chat.py              # Main script to run the chatbot
├── train.py             # Script to train the model
├── intents.json         # database of patterns and responses
├── model.py             # Neural network architecture
├── nltk_utils.py        # Helper functions for NLP
├── data.pth             # The trained model (generated after training)
├── run_chatbot.bat      # Double-click this to run the bot easily
└── venv/                # Virtual environment with all dependencies
```

## How I Run It
I have set up a batch script for easy execution.

**Option 1: The Easy Way**
Double-click on **`run_chatbot.bat`**.

**Option 2: Manual Run**
Open a terminal and run:
```console
.\venv\Scripts\activate
python chat.py
```

## Setup Details (How it was installed)
1.  Created a virtual environment: `python -m venv venv`
2.  Installed dependencies: `pip install torch nltk`
3.  Downloaded NLTK data: `python -c "import nltk; nltk.download('punkt')"`
4.  Trained the model: `python train.py`

## Original Attribution
This project is based on: [https://github.com/patrickloeber/pytorch-chatbot](https://github.com/patrickloeber/pytorch-chatbot)
Tutorial: [https://www.youtube.com/watch?v=RpWeNzfSUHw](https://www.youtube.com/watch?v=RpWeNzfSUHw)
