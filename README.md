# CUEY
Cuey is an AI-powered assistant for pool, snooker, and billiard players. 
It uses a fine-tuned language model to answer questions, give playing tips, 
analyze techniques, and help players improve their game.

## Features
- AI chatbot for pool and snooker training
- Explains aiming, safety, and break shots
- Provides game analysis and tips
- Can be fine-tuned with custom Q&A datasets

## Future Improvements
- Deploy Cuey as a web application
- Improve dataset for advanced shot analysis

## Installation & Usage
This project is designed to run in [Google Colab](https://colab.research.google.com/) 
for easier access to GPUs.

### Run on Google Colab 
1. Open Google Colab.
2. Upload `Cuey.py` and `dataset.jsonl` to your Colab session.
3. Install dependencies:
   !pip install -r requirements.txt
4. Make sure that you go to Runtime > Change runtime type > and change the runtime type to Python 3 and the hardware accelerator to some sort of GPU
   (most commonly the T4-GPU)

Run:
!python cuey.py

