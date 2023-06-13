# Question-Answer-Generation

This project aims to generate multiple-choice questions in Vietnamese using the mT5 (Multilingual T5) transformer model. The project consists of two models: the first model fine-tunes the mT5 model to generate question-answer pairs from an input paragraph, and the second model takes the output from the first model to generate distractors for multiple-choice questions.

**Features**
- Question-Answer Generation: The fine-tuned mT5 model generates high-quality question-answer pairs in Vietnamese.
- Distractor Generation: The second model uses the output from the first model to generate plausible distractors for the multiple-choice questions.
- Transformer-based Architecture: The project utilizes the powerful mT5 transformer model, which has shown excellent performance in natural language processing tasks.
- Customizability: The code allows for fine-tuning the mT5 model on different datasets, enabling adaptation to specific domains or use cases.
- Evaluation Metrics: The generated questions and distractors are evaluated using ROUGE, BERTScore, and human evaluation to assess their quality and effectiveness.

Check file **requirements.txt** for more info on dependencies.
