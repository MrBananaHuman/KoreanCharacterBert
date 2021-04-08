# KoreanCharacterBert
Korean BERT model using character tokenizer

Small model (3 layers) and base model (12 layers) download link
- Small model: https://drive.google.com/drive/folders/1Ae_3LzxzAiVT2NigGdqklfTGR87ACbO1?usp=sharing
- Base model: https://drive.google.com/drive/folders/1MoQ9oQL4ENGzishdLZ1VzZ8SnOuTgJAE?usp=sharing

KorQuAD v1.0 results
- Small model (450,000 steps, 512 batch size): f1=86.75, em=77.14
- Base model (450,000 steps, 128 batch size): f1=90.59, em=82.47

Inference time (RTX 2070 Super, 1 batch size)
- Small model: 10 ms
- Base model: 30 ms
