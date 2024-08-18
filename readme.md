## What's Missing
- [ ] Related Information
- [ ] Results
- [ ] Discussion
- [ ] Conclusion
- [ ] Future Work

## Links
- [Overleaf Link](#)  <!-- Replace with actual link -->
- [Code](LatestCode-gsm8k.ipynb)
- [Results](New Data)  <!-- Replace with actual link -->

## Experiments

### GSM8k
- **GPT-3.5 Turbo (All)** 
  - [x] GSM8k with GPT-3.5 Turbo W/ COT → 0.7908
  - [ ] GSM8k with GPT-3.5 Turbo W/ Non-COT
- **GPT-3.5 Turbo with BERT**
  - [ ] 5K
  - [ ] 10K
- **GPT-3.5 Turbo with Embeddings**
  - [ ] embeddings-3 large 5K
  - [ ] embeddings-3 large 10K
- **GPT-3.5 Turbo with all-MiniLM-L6-v2**
  - [ ] 5K
  - [ ] 10K

- **GPT-4o-mini**
  - [ ] GSM8k with GPT-4o-mini W/ COT
  - [ ] GSM8k with GPT-4o-mini W/ Non-COT
  - [ ] GSM8k with GPT-4o-mini W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] GSM8k with GPT-4o-mini W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] GSM8k with GPT-4o-mini W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

- **phi-3**
  - [ ] GSM8k with phi-3 W/ Non-COT
  - [ ] GSM8k with phi-3 W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] GSM8k with phi-3 W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] GSM8k with phi-3 W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

### AQUA-RAT
- **GPT-3.5 Turbo (All)**
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ COT
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ Non-COT
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

- **GPT-4o-mini**
  - [ ] AQUA-RAT with GPT-4o-mini W/ COT
  - [ ] AQUA-RAT with GPT-4o-mini W/ Non-COT
  - [ ] AQUA-RAT with GPT-4o-mini W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] AQUA-RAT with GPT-4o-mini W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] AQUA-RAT with GPT-4o-mini W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

- **phi-3**
  - [ ] AQUA-RAT with phi-3 W/ Non-COT
  - [ ] AQUA-RAT with phi-3 W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] AQUA-RAT with phi-3 W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] AQUA-RAT with phi-3 W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

### SVAMP
- **GPT-3.5 Turbo (All)**
  - [ ] SVAMP with GPT-3.5 Turbo W/ COT
  - [ ] SVAMP with GPT-3.5 Turbo W/ Non-COT
  - [ ] SVAMP with GPT-3.5 Turbo W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] SVAMP with GPT-3.5 Turbo W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] SVAMP with GPT-3.5 Turbo W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

- **GPT-4o-mini**
  - [ ] SVAMP with GPT-4o-mini W/ COT
  - [ ] SVAMP with GPT-4o-mini W/ Non-COT
  - [ ] SVAMP with GPT-4o-mini W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] SVAMP with GPT-4o-mini W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] SVAMP with GPT-4o-mini W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

- **phi-3**
  - [ ] SVAMP with phi-3 W/ Non-COT
  - [ ] SVAMP with phi-3 W/ BERT
    - [ ] 5K
    - [ ] 10K
  - [ ] SVAMP with phi-3 W/ Embeddings
    - [ ] embeddings-3 large 5K
    - [ ] embeddings-3 large 10K
  - [ ] SVAMP with phi-3 W/ all-MiniLM-L6-v2
    - [ ] 5K
    - [ ] 10K

## Instructions
- **Datasets**: GSM8k, SVAMP, AQ-RAT
- **Models**: GPT-3.5-turbo, GPT-4o, phi-3-mini
- **Embeddings**: text-embedding-3 large, all-MiniLM-L6-v2
- **K**: 5, 10

## Unused Folders
- **Implementation for every model/dataset/embedding**: `Implementations.ipynb`
- **AQ-RAT**: `LatestCode-aq-rat.ipynb`
- **SVAMP**: `LatestCode-svamp.ipynb`
- **Base code**: `TestingGSM8k.ipynb`
- **Cleaned data for each dataset**: `COT (1)`
- **Old Data**: `Data`
