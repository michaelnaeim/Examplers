## Experiments

### **GSM8K Results**

| Model        | COT   | NONCOT | BERT-5 | BERT-10 | TEXT-5 | TEXT-10 | MiniLM-5 | MiniLM-10 | PHI-5  | PHI-10 |
|--------------|-------|--------|--------|---------|--------|---------|----------|-----------|--------|--------|
| **GPT-3.5**  | 0.7916| 0.7655 | 0.8120 | 0.9287  | 0.8052 | 0.8196  | 0.8180   | 0.8052    | 0.8105 | 0.8089 |
| **GPT-4o**   | 0.9272| 0.9272 | 0.8597 | 0.8650  | 0.9348 | 0.9386  | 0.8287   | 0.9348    | 0.9356 | 0.9333 |

### **SVAMP Results**

| Model        | COT   | NONCOT | BERT-5 | BERT-10 | TEXT-5 | TEXT-10 | MiniLM-5 | MiniLM-10 | PHI-5  | PHI-10 |
|--------------|-------|--------|--------|---------|--------|---------|----------|-----------|--------|--------|
| **GPT-3.5**  | 0.8133| 0.8067 | 0.7933 | 0.7967  | 0.8100 | 0.8000  | 0.8267   | 0.7967    | 0.7967 | 0.8133 |
| **GPT-4o**   | 0.9267| 0.9267 | 0.9267 | 0.9100  | 0.9233 | 0.9200  | 0.9300   | 0.9300    | 0.9300 | 0.9267 |

### **AQUA-RAT Results**

| Model        | COT   | NONCOT | BERT-5 | BERT-10 | TEXT-5 | TEXT-10 | MiniLM-5 | MiniLM-10 | PHI-5  | PHI-10 |
|--------------|-------|--------|--------|---------|--------|---------|----------|-----------|--------|--------|
| **GPT-3.5**  | 0.5362| 0.5435 | 0.4928 | 0.5000  | 0.5507 | 0.5072  | 0.5000   | 0.4855    | 0.5507 | 0.5652 |
| **GPT-4o**   | 0.8116| 0.8116 | 0.7899 | 0.8116  | 0.5507 | 0.8261  | 0.8333   | 0.7720    | 0.7826 | 0.7681 |

---

### **GSM8K F1, Precision, and Recall**

| Model        | Precision | Recall  | F1 Score |
|--------------|-----------|---------|----------|
| **GPT-3.5 COT**    | 0.7716    | 0.7823  | 0.6126   |
| **GPT-3.5 NONCOT** | 0.7690    | 0.7692  | 0.6003   |
| **GPT-3.5 BERT-5** | 0.7626    | 0.8321  | 0.6470   |
| **GPT-3.5 BERT-10**| 0.8944    | 0.9121  | 0.8240   |
| **GPT-4o COT**     | 0.8974    | 0.9162  | 0.8320   |
| **GPT-4o NONCOT**  | 0.8940    | 0.9088  | 0.8208   |

---

### **SVAMP F1, Precision, and Recall**

| Model        | Precision | Recall  | F1 Score |
|--------------|-----------|---------|----------|
| **GPT-3.5 COT**    | 0.7954    | 0.8318  | 0.6652   |
| **GPT-3.5 NONCOT** | 0.7931    | 0.8275  | 0.6571   |
| **GPT-3.5 BERT-5** | 0.6045    | 0.6198  | 0.2446   |
| **GPT-4o COT**     | 0.8994    | 0.9124  | 0.8247   |
| **GPT-4o NONCOT**  | 0.8994    | 0.9124  | 0.8247   |

---

### **AQUA-RAT F1, Precision, and Recall**

| Model        | Precision | Recall  | F1 Score |
|--------------|-----------|---------|----------|
| **GPT-3.5 COT**    | 0.6132    | 0.4111  | 0.0277   |
| **GPT-3.5 NONCOT** | 0.5916    | 0.4320  | 0.0266   |
| **GPT-4o COT**     | 0.6188    | 0.4135  | 0.0332   |
| **GPT-4o NONCOT**  | 0.6188    | 0.4135  | 0.0332   |



## NOT USED!
## Experiments

### GSM8k
- **GPT-3.5 Turbo**
  - [x] GSM8k with GPT-3.5 Turbo W/ COT. Acc: ```0.7908```
  - [x] GSM8k with GPT-3.5 Turbo W/ Non-COT. Acc: ``` ``` - HAVE ALREADY
  - [x] GSM8k with GPT-3.5 Turbo W/ BERT
    - [x] 5K. Acc: ```0.8120```
    - [x] 10K. Acc: ``` ```- DONE
  - [x] GSM8k with GPT-3.5 Turbo W/ Embeddings
    - [x] embeddings-3 large 5K. Acc: ```0.8052```
    - [x] embeddings-3 large 10K. Acc: ``` ``` -DONE
  - [x] GSM8k with GPT-3.5 Turbo W/ all-MiniLM-L6-v2
    - [x] 5K. Acc: ```0.8180```
    - [x] 10K. Acc: ```0.8052```
  - [ ] GSM8k with GPT-3.5 Turbo W/ phi-3
    - [ ] 5K. Acc: ``` ``` -MISSING
    - [ ] 10K. Acc: ```0.8089```

- **GPT-4o-mini**
  - [x] GSM8k with GPT-4o-mini W/ COT. Acc: ```0.9272```
  - [x] GSM8k with GPT-4o-mini W/ Non-COT. Acc: ```0.9272```
  - [x] GSM8k with GPT-4o-mini W/ BERT
    - [x] 5K. Acc: ```0.9356``` - DONE
    - [x] 10K. Acc: ``` ```- DONE
  - [x] GSM8k with GPT-4o-mini W/ Embeddings
    - [x] embeddings-3 large 5K. Acc: ``` ```
    - [x] embeddings-3 large 10K. Acc: ``` ```
  - [ ] GSM8k with GPT-4o-mini W/ all-MiniLM-L6-v2
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] GSM8k with GPT-4o-mini W/ phi-3
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```

### AQUA-RAT
- **GPT-3.5 Turbo (All)**
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ COT. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ Non-COT. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ BERT
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ Embeddings
    - [ ] embeddings-3 large 5K. Acc: ``` ```
    - [ ] embeddings-3 large 10K. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ all-MiniLM-L6-v2
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-3.5 Turbo W/ phi-3
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```

- **GPT-4o-mini**
  - [ ] AQUA-RAT with GPT-4o-mini W/ COT. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-4o-mini W/ Non-COT. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-4o-mini W/ BERT
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-4o-mini W/ Embeddings
    - [ ] embeddings-3 large 5K. Acc: ``` ```
    - [ ] embeddings-3 large 10K. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-4o-mini W/ all-MiniLM-L6-v2
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] AQUA-RAT with GPT-4o-mini W/ phi-3
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```

### SVAMP
- **GPT-3.5 Turbo (All)**
  - [ ] SVAMP with GPT-3.5 Turbo W/ COT. Acc: ``` ```
  - [ ] SVAMP with GPT-3.5 Turbo W/ Non-COT. Acc: ``` ```
  - [ ] SVAMP with GPT-3.5 Turbo W/ BERT
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] SVAMP with GPT-3.5 Turbo W/ Embeddings
    - [ ] embeddings-3 large 5K. Acc: ``` ```
    - [ ] embeddings-3 large 10K. Acc: ``` ```
  - [ ] SVAMP with GPT-3.5 Turbo W/ all-MiniLM-L6-v2
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] SVAMP with GPT-3.5 Turbo W/ phi-3
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```

- **GPT-4o-mini**
  - [ ] SVAMP with GPT-4o-mini W/ COT. Acc: ``` ```
  - [ ] SVAMP with GPT-4o-mini W/ Non-COT. Acc: ``` ```
  - [ ] SVAMP with GPT-4o-mini W/ BERT
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] SVAMP with GPT-4o-mini W/ Embeddings
    - [ ] embeddings-3 large 5K. Acc: ``` ```
    - [ ] embeddings-3 large 10K. Acc: ``` ```
  - [ ] SVAMP with GPT-4o-mini W/ all-MiniLM-L6-v2
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```
  - [ ] SVAMP with GPT-4o-mini W/ phi-3
    - [ ] 5K. Acc: ``` ```
    - [ ] 10K. Acc: ``` ```

## What's Missing
- [ ] Related Information
- [ ] Results
- [ ] Discussion
- [ ] Conclusion
- [ ] Future Work

## Links
- [Overleaf Link](https://www.overleaf.com/project/6556c5d2c63beffb0d5ca1d8)  <!-- Replace with actual link -->
- [Code](https://colab.research.google.com/drive/1T1aH1maYGtT9ewOMmI50qxdpSv4ADFn-?usp=sharing)


## Instructions
- **Datasets**: GSM8k, SVAMP, AQ-RAT
- **Models**: GPT-3.5-turbo, GPT-4o, phi-3-mini
- **Embeddings**: text-embedding-3 large, all-MiniLM-L6-v2
- **K**: 5, 10

## Unused Folders refer to [this link](https://docs.google.com/document/d/1FmGi_OMaKwEh1aoDscGmYDxdoNNEXYw74-kwaMHUnqI/edit)
