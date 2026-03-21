# embedding.

## start with the basic truths
i. **models require numeric input.**
   text and concepts must be converted into computable form.

ii. **meaning can be represented relationally.**
   similar items can be placed near each other in vector space.

iii. **distance can encode usefulness.**
   geometry can approximate semantic similarity.

iv. **representations are task-shaped.**
   embeddings improve as training pushes them toward useful distinctions.

---

## what is an embedding?

**embedding** = **a dense numeric vector that represents a token, sentence, or item so semantic similarity and relationships can be computed geometrically.**

---

## how embeddings work

1. **map item to vector**
   convert discrete input into continuous coordinates.

2. **learn from objective**
   update vectors so useful patterns reduce model error.

3. **compare in vector space**
   use cosine or distance metrics to measure relatedness.

4. **reuse across tasks**
   apply learned representations to retrieval, clustering, and generation.

---

## why embeddings matter

- they **make symbolic data numerically learnable**
- they **capture semantic structure compactly**
- they **improve generalization across similar inputs**
- they **power search, recommendation, and llm context matching**

---

## a simple example

question: *why does semantic search work better with embeddings than keyword matching?*

first principles:
- keywords only detect literal overlap
- embeddings capture similarity in meaning
- near vectors retrieve conceptually related text

so semantic search improves because **embeddings encode meaning, not just exact words.**

---

## embedding summary

**embedding = item → vector coordinates that preserve useful relationships.**
