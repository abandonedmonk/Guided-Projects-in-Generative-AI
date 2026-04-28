# Project 1: FinBot - Financial Markets LLM

## 📂 Project Contents

### Files

- **`fintech_global_exchanges_finetune.jsonl`** - Training dataset (50+ Q&A pairs on global exchanges, indices, trading)
- **`USE_CASE_DEFINITION.md`** - Use case & 7 key customer support scenarios
- **`README.md`** - This file

### Folder

- **`fine_tuning_resources/`** - For training scripts, commands, model outputs, and evaluation results

## 🎯 What is This?

FinBot is a fine-tuned LLM for financial customer support. It answers questions on:

- Global stock exchanges (NYSE, NASDAQ, LSE, NSE, HKEX, etc.)
- Trading operations & order types
- Indices & financial products
- Market regulations & settlement cycles
- KYC/compliance
- Risk management

## 📊 Dataset Format

```jsonl
{
  "messages": [
    {
      "role": "system",
      "content": "You are FinBot..."
    },
    {
      "role": "user",
      "content": "Question?"
    },
    {
      "role": "assistant",
      "content": "Answer..."
    }
  ]
}
```

## ✅ Next Steps

1. Review `USE_CASE_DEFINITION.md`
2. Create training scripts in `fine_tuning_resources/`
3. Fine-tune model using OpenAI/HuggingFace
4. Test & evaluate outputs
