# Siamese Network on Quora duplication questions problem
Text Siamese Network provides a CNN based implementation of Siamese Network to solve Quora duplicate questions identification problem.
Quora question pair dataset has ~400k question pairs along with a binary label which states whether a pair of questions are similar or dissimilar. The Siamese Network based tries to capture the semantic similarity between questions.

## Requirements
- Python 3
- Pip 3
- Tensorflow
- FastText
- faiss

## Environment Setup
Execute requirements.txt to install dependency packages
```bash
pip install -r requirements.txt
```

## Training
1. Quora questions dataset is provided in ./data_repository directory. 
2. To train 
```bash
python train_siamese_network.py
```





