BrainTeaser: A Novel Task Defying Common Sense

Overview

BrainTeaser is an AI-powered system designed to understand and answer complex lateral thinking questions. The project focuses on enhancing model comprehension by fine-tuning state-of-the-art Transformer-based models, including BERT, RoBERTa, and GPT-2. By leveraging the SemEval 2024 Dataset, the system achieves high accuracy on unseen data, demonstrating significant improvements in NLP-based reasoning tasks.

Features

Lateral Thinking Question Understanding: The model is trained to comprehend and respond to unconventional, tricky questions.

Transformer-Based Models: Fine-tuned BERT, RoBERTa, and GPT-2 to enhance comprehension and reasoning.

High Accuracy: Achieved 80% accuracy on unseen test data, outperforming traditional NLP models.

Robust Training Pipeline: Utilized advanced NLP techniques to improve model robustness and generalization.

Tech Stack

Programming Language: Python

Deep Learning Framework: PyTorch / TensorFlow

Models Used: BERT, RoBERTa, GPT-2

Dataset: SemEval 2024

Evaluation Metrics: Accuracy, F1 Score, BLEU Score

Other Libraries: Hugging Face Transformers, Scikit-learn, Pandas, NumPy

Installation

# Clone the repository
git clone https://github.com/yourusername/brainteaser.git
cd brainteaser

# Install dependencies
pip install -r requirements.txt

Dataset

The dataset used is from SemEval 2024, which contains a diverse set of lateral thinking questions. You can download it from SemEval Official Site or provide your own dataset.

Model Training

To fine-tune the models, use the following command:

python train.py --model bert --epochs 10 --batch_size 32

Replace bert with roberta or gpt2 to train other models.

Evaluation

To evaluate a trained model:

python evaluate.py --model bert

The output will display accuracy, F1 score, and other metrics.

Usage

To test the model with a custom question:

python infer.py --question "Why did the chicken cross the road?"

Results

The best-performing model achieved 80% accuracy on the test set, demonstrating superior reasoning capabilities compared to traditional NLP models.

Future Improvements

Integrate multi-modal reasoning (images + text) for better understanding.

Improve dataset size by incorporating human-annotated lateral thinking questions.

Optimize model efficiency for real-time inference.

Contributors

Devesh - AI Research & Model Training


License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

Inspired by SemEval 2024 and advancements in Transformer-based NLP models.

Thanks to the Hugging Face community for providing robust pre-trained models.
