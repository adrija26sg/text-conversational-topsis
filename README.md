# Conversational Model Evaluation using TOPSIS

## Overview
This project evaluates different conversational AI models using cosine similarity and the TOPSIS method. The models are ranked based on their similarity scores, inference speed, and model size.

## Features
- Evaluates pre-trained conversational AI models.
- Computes similarity between model responses using cosine similarity.
- Uses the TOPSIS ranking method to select the best-performing model.
- Generates visualizations of model rankings.

## Installation
To run this project, install the necessary dependencies:
```bash
pip install torch transformers numpy pandas scikit-learn matplotlib seaborn
```

## Usage
Run the Python script to evaluate models and generate rankings:
```bash
python modified_model_eval.py
```

## Models Used
The script evaluates the following lightweight conversational models:
- `gpt2` (GPT-2 Small by OpenAI)
- `facebook/blenderbot_small-90M` (BlenderBot Small by Facebook)
- `microsoft/DialoGPT-small` (DialoGPT Small by Microsoft)

## Output
![image](https://github.com/user-attachments/assets/7e15ab06-e376-49a8-84b4-f4c4ae832650)


## Visualisation
![image]()



## License
This project is open-source under the MIT License.
