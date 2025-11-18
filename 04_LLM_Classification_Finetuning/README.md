# LLM Classification Fine-tuning  
Kaggle Link: https://www.kaggle.com/competitions/llm-classification-finetuning

##  Goal  
Fine-tune a large language model (LLM) to classify short text queries into multiple instruction categories.

##  Techniques Used  
- HuggingFace Transformers  
- Tokenization (WordPiece / BPE)  
- GPU-based fine-tuning  
- Cross-entropy loss  
- Learning rate scheduling and early stopping  

##  Training Details  
- Model: (e.g., DistilBERT / BERT-base / other, depending on your notebook)  
- Epochs: (add number)  
- Batch size: (add number)  
- Optimizer: AdamW  
- Evaluation: accuracy + F1  

##  Results  
Leaderboard Score: **1.11371**  
This shows the model successfully learned class distinctions.

## Files  
- `LLM Classification Finetuning.ipynb` – full fine-tuning script  
- *(submission.csv optional if provided)*  

## Improvements  
- Fine-tune RoBERTa or BERT-large  
- Use stratified k-fold cross-validation  
- Try adapters (LoRA) to reduce training cost  
