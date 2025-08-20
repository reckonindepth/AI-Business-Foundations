# AI-Business-Foundations
My learning repo for AI Business Fluency.
## Why Version Control Matters for AI Compliance in Healthcare Startups

Version control isn’t just an engineering best practice — it’s a compliance requirement.

- **Reproducibility:** Regulators and investors must be able to re-run AI results step by step.  
- **Traceability:** Every commit links data, code, and configuration to an outcome.  
- **Auditability:** Git history serves as an audit trail during HIPAA/FDA/DPDP checks.  
- **Risk Management:** Prevents “silent changes” in models that could harm patients or mislead customers.  
- **Business Trust:** Enterprise clients only adopt AI products that demonstrate audit readiness.  

This is why my AI learning repo starts with GitHub — to build investor- and regulator-ready discipline from day one. 

## Embeddings = profile cards; AI uses them for similarity decisions.
AI defines similarity mathematically, using vectors—numerical representations of data points (words, products, patients, etc.). These vectors live in a multi-dimensional space, and similarity is measured by how close they are to each other (using metrics like cosine similarity or Euclidean distance).

## Embeddings
The core concept of word embeddings is that every word used in a language can be represented by a set of real numbers (a vector). They have learned representations of text in an n-dimensional space where words that have the same meaning have a similar representation. That means two similar words are placed very closely in vector space almost having similar vector representations. So, When constructing a word embedding space the goal is to capture some sort of relationship in that space, be it meaning, morphology, context, or some other kind of relationship.

As you might have noticed already, when we’re setting one element using the word index of the entire vector. As the vocabulary size increases, we’d end up using an extensive length sparse vector for encoding a single word which would result in performance and storage penalties because of the curse of dimensionality. In addition to that, such representation is incapable of learning semantic relationships between words which is of essential importance when dealing with textual data.

Word embeddings eliminate all the above shortcomings and equip us with enriched powerful representations that are capable of capturing contextual and semantic similarities between words.

Two word embedding methods which are more advanced in nature.
- **Word2vec: proposed at Google by Mikolov et al. These models are shallow, two-layer neural networks that are trained to reconstruct linguistic contexts of words. This takes corpus of texts as input and produces a vector for each word that is represented in the corpus.

- **Glove: The Global Vectors for Word Representation, or GloVe, the algorithm is an extension to the word2vec method for efficiently learning word vectors, developed by Pennington, et al. at Stanford in 2014. This is an unsupervised learning algorithm for word representation. It learns vectors or words on basis of their frequency of occurring together. GloVe’s contribution was the addition of global statistics in the language modeling task to generate the embedding. There is no window feature for the local context. Instead, there is a word-context/word co-occurrence matrix that learns statistics across the entire corpora. It first constructs a matrix X where the rows are words and the columns are contexts with the element value X_ij equal to the number of times a word i appear in a context of word j. By minimizing reconstruction loss, this matrix is factorized to a lower-dimensional representation, where each row represents the vector of a given word. Rather than using a window to define local context, GloVe constructs an explicit word-context or word co-occurrence matrix using statistics across the whole text corpus. The result is a learning model that may result in a generally better word embedding.

## Embeddings = profile cards.
Every patient, customer, or product gets turned into a vector (like a multi-attribute card).

## Similarity = business leverage.

- **Healthcare: AI can suggest similar patient cases → better diagnostics.

- **Retail: AI can recommend “customers like you also bought this.”

- **Language: AI connects context → GPT can answer semantically, not literally.

Leader’s takeaway: You don’t compute vectors yourself, but you must know what decisions embeddings enable (recommendations, clustering, personalization, multimodal analysis).

## How probability connects to business risk.

AI = likelihoods, not certainties.
Predictions are expressed as probabilities (e.g., “70% churn risk”) — they’re never binary truth.

False Positives vs False Negatives = business trade-offs.

- Healthcare: Missing a sick patient (false negative) = catastrophic risk.

- Retail: Over-predicting demand (false positive) = wasted discounts + lost margin.

Probability mindset = better decisions.
Leaders must ask: “What’s the cost of being wrong?”, not just “What’s the accuracy?”

