# 📝 Text Generation using Hugging Face Transformers

This project demonstrates how to generate text using Hugging Face’s pre-trained language models. A dataset of Robert Frost’s poetry is used as the base for prompts, and the transformers pipeline is used to extend or generate new poetic lines.

## 🎯 Project Overview

• Task: Text generation using prompts

• Model: Pre-trained transformer model (default: GPT-2)

• Dataset: robert_frost_collection.csv (a collection of Robert Frost poems)

• Libraries Used: transformers, pandas, numpy, textwrap, matplotlib, seaborn, sklearn, torch

## 📁 File Structure

• text_generation_hugging_face.py: Main Python script for text generation

• robert_frost_collection.csv: Dataset file containing poetry (must be in the same directory)

## ⚙️ How to Run

1.Clone the repository.

2.Install the required dependencies:

command: pip install transformers pandas numpy matplotlib seaborn scikit-learn torch

3.Place the dataset file robert_frost_collection.csv in the same directory.

4.Run the script:

command: python text_generation_hugging_face.py

## 🔍 Features

• Loads and cleans a poetry dataset

• Extracts and processes lines from poems

• Uses Hugging Face’s text-generation pipeline (GPT-2 by default)

• Allows for:

   • Text generation with maximum length

   • Multiple sequence generation (num_return_sequences)

   • Custom prompts for user-defined outputs

• Uses textwrap for clean and readable output formatting

## ✨ Sample Output

### plaintext

Prompt: "transformers have a wide variety of applications in nlp"
Generated: transformers have a wide variety of applications in nlp and a large number of ways to learn about

## 🚀 Future Improvements

• Add fine-tuning on custom poetry dataset

• Experiment with different models like EleutherAI/gpt-neo or GPT-J

• Build a Streamlit or Gradio app for interactive demo

• Add rhyme or meter constraints for stylistic control

##📬 Contact

For suggestions, issues, or questions, feel free to open an issue or reach out.
