**Neural-Network-NLP-Preprocessing-NER-Attention-Sentiment-Analysis

---

### Q1: NLP Preprocessing Pipeline
**Steps Performed:**
1. Tokenization
2. Stopword Removal
3. Stemming

**Example Output:**
- Tokens: ['NLP', 'techniques', 'are', ...]
- Without Stopwords: ['NLP', 'techniques', 'used', ...]
- Stemmed: ['nlp', 'techniqu', 'use', ...]

**Short Answers:**
- **Stemming vs Lemmatization:**
  - Stemming: Crude shortening (e.g., *running* → *runn*)
  - Lemmatization: Dictionary-based (e.g., *running* → *run*)
- **Stopwords:**
  - Helpful: Removes common, uninformative words
  - Harmful: Can remove important context (e.g., negation in sentiment)

---

### Q2: Named Entity Recognition (NER) with spaCy
**Task:** Extract named entities and their positions from a sentence.

**Example Output:**
- "Barack Obama" → PERSON (0–12)
- "2009" → DATE (93–97)

**Short Answers:**
- **NER vs POS Tagging:**
  - NER: Semantic role (who/what the word represents)
  - POS: Syntactic role (how the word functions)
- **NER Applications:**
  - Financial news analysis (company/event detection)
  - Search engines & assistants (understanding user queries)

---

### Q3: Scaled Dot-Product Attention
**Steps Performed:**
1. Compute Q ⋅ Kᵀ
2. Scale by √(d)
3. Apply softmax
4. Multiply by V

**Example Output:**
- Attention Weights: [[0.88, 0.12], ...]
- Output: Weighted sum of V values

**Short Answers:**
- **Why Scale by √(d):**
  - Prevents softmax saturation due to large dot products
- **Self-Attention Purpose:**
  - Captures relationships across all words in a sequence
  - Useful for context understanding and long-range dependencies

---

### Q4: Sentiment Analysis using Hugging Face
**Steps Performed:**
1. Load pre-trained sentiment pipeline
2. Analyze sentence
3. Output label and score

**Example Output:**
- Sentiment: POSITIVE
- Confidence Score: 0.9991

**Short Answers:**
- **BERT vs GPT:**
  - BERT: Encoder-only (contextual understanding)
  - GPT: Decoder-only (text generation)
- **Why Use Pretrained Models:**
  - Saves training time & resources
  - Effective even with small datasets
  - Achieve high accuracy with minimal tuning

---

**End of Summary**

