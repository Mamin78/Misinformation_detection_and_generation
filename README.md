# Exploring the Dual Role of AI: RNNs and BERT for Fake News Detection and LLMs for Fake News Generation

This repository contains the code and data associated with the paper "Exploring the Dual Role of AI: RNNs and BERT for Fake News Detection and LLMs for Fake News Generation" by Mohammadamin Shafiei. The paper explores how AI can be utilized for both detecting fake news and generating it, highlighting the capabilities and challenges posed by modern AI technologies in the realm of misinformation.

## Contents

- **` data/`**: Directory containing the dataset used generated by LLMs. For training dataset, please refer to [fake](https://drive.google.com/file/d/18CU1_M5d5_3lB000CzvtHvUWdD7Q7IU4/view?usp=sharing) and [real](https://drive.google.com/file/d/1csUn_iwl_WizitBQ7Do-fS4XQ6qpE9rN/view?usp=sharing).
- **`Exploring_the_Dual_Role_of_AI__RNNs_and_BERT_for_Fake_News_Detection_and_LLMs_for_Fake_News_Generation__Detection_and_Generation.pdf`**: The full research paper detailing the study, methodologies, and findings.
- **`RNN_fake_news_detection.ipynb`**: Jupyter Notebook implementing and training a Recurrent Neural Network (RNN) for detecting fake news.
- **`fake_news_detection_mbert.ipynb`**: Jupyter Notebook implementing and fine-tuning a BERT model for fake news detection.
- **`README.md`**: This file provides an overview and instructions for the repository.

## Overview

The spread of misinformation and fake news is a significant challenge in today's digital world. This project investigates the dual role of AI in this context:
1. **Fake News Detection**: Using AI models to accurately detect fake news. This includes:
   - **RNN Model**: Implemented in `RNN_fake_news_detection.ipynb`, this model achieved an accuracy of 97.8% on the test dataset.
   - **BERT Model**: Implemented in `fake_news_detection_mbert.ipynb`, this fine-tuned model achieved a perfect accuracy of 100% on the test dataset.
2. **Fake News Generation**: Using Large Language Models (LLMs) like ChatGPT and Claude to generate convincing fake news articles.

## Getting Started
### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mamin78/Misinformation_detection_and_generation.git
   cd Misinformation_detection_and_generation
   ```

2. **Download the Dataset**:
   Ensure you have the dataset in the `data/` directory. The dataset includes labeled news articles used for training and evaluation.

3. **Run the Notebooks**:
   - Open the Jupyter notebooks `RNN_fake_news_detection.ipynb` and `fake_news_detection_mbert.ipynb` to explore and execute the models for detecting fake news.
   - Follow the instructions in each notebook to preprocess the data, train the models, and evaluate their performance.

## Results

- **RNN Model**: Demonstrated an impressive accuracy of 97.8% in detecting fake news.
- **BERT Model**: Achieved a perfect accuracy of 100%, showcasing its robustness in handling natural language tasks.
- **LLM-Generated Fake News**: The models tested on LLM-generated content showed varied performance, highlighting the challenges in detecting sophisticated fake content.

## Paper

For a detailed explanation of the methodologies, results, and implications of this study, please refer to the PDF file.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For any questions or suggestions, feel free to contact the author at aminsh78@gmail.com.
