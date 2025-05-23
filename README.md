JOURNEY OF GENERATIVE AI

GPT-2 Fine-Tuning with Hugging Face Transformers
This project demonstrates how to fine-tune OpenAI's GPT-2 model on a small dataset (wikitext-2) using the Hugging Face Transformers library. It includes steps for preprocessing, training, and text generation using the fine-tuned model.

🚀 Project Goal
The goal of this project is to learn how generative AI models work, specifically GPT-2. As part of my learning journey, I fine-tuned GPT-2 on a sample dataset to understand the pipeline of model training, tokenization, and text generation. This hands-on project helped me explore how generative models can be adapted for custom tasks using Hugging Face's powerful APIs.

📦 Dependencies
Install the required libraries:

pip install transformers datasets torch
📚 Dataset
Dataset Used: wikitext-2-raw-v1 from Hugging Face Datasets

Purpose: A small and clean dataset ideal for experimenting with language modeling tasks.

🛠️ Steps Involved
Install Dependencies

Load and Preprocess Dataset

Tokenize the Text using GPT-2 Tokenizer

Load GPT-2 Model

Fine-tune the Model on Wikitext-2

Generate Text interactively in a loop

Save the Model and Tokenizer

🧠 Training
The model is trained for 3 epochs on the Wikitext-2 training split. You can adjust the number of epochs and learning rate for better performance.

✨ Text Generation
After training, you can generate text by providing prompts. The script includes a loop that allows you to regenerate outputs or enter new prompts continuously.

📁 Saving the Model
The fine-tuned model and tokenizer are saved locally in ./fine_tuned_gpt2 for reuse or deployment.

📌 Personal Note
I created this project while learning how to use Generative AI. My goal was to understand the process of fine-tuning large language models like GPT-2. Working on this gave me practical experience in how these models operate behind the scenes and how they can be adapted for specific tasks using transfer learning.

🔗 Resources

Hugging Face Transformers
Wikitext Dataset

