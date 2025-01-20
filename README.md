# TinyThink: Fine-tuning a Small LLM for Question Answering

This project demonstrates how to fine-tune a small language model (LLM) for the task of question answering. We use the "google/flan-t5-small" model (around 1 billion parameters) and the Stanford Question Answering Dataset (SQuAD) to create a compact and efficient question-answering system.

## Goals

* **Fine-tuning:**  Fine-tune the "google/flan-t5-small" model on the SQuAD dataset to achieve optimal performance on question answering.
* **Efficiency:**  Demonstrate the feasibility of using a small LLM for a complex task like question answering.
* **Evaluation:**  Evaluate the fine-tuned model using appropriate metrics (e.g., Exact Match, F1 score) to measure its accuracy.
* **Deployment:**  Deploy the fine-tuned model using Hugging Face Spaces to make it easily accessible for others to use.
* **(Optional) Chain-of-Thought Prompting:** Explore the potential of chain-of-thought prompting to further enhance the model's reasoning abilities.

## Project Structure

* `finetune.py`:  Contains the code for fine-tuning the LLM.
* `app.py`:  Contains the code for the Gradio interface for interacting with the model.
* `requirements.txt`:  Lists the required Python packages.
* `README.md`:  This file.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/TinyThink.git](https://github.com/your-username/TinyThink.git)
