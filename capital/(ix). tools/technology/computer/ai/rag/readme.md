# rag (retrieval-augmented generation).

## start with the basic truths
i. **model memory is bounded and imperfect.**
   parametric knowledge can be stale or incomplete.

ii. **external data can improve answers.**
   retrieval can inject current and domain-specific evidence.

iii. **grounding reduces unsupported claims.**
   conditioning on sources improves traceability.

iv. **retrieval quality gates generation quality.**
   weak documents produce weak responses.

---

## what is rag?

**rag** = **retrieval-augmented generation, a pattern where a model fetches external documents at runtime and conditions generation on that evidence.**

---

## how rag works

1. **index knowledge base**
   store documents for efficient search.

2. **retrieve relevant context**
   query and rank documents for the prompt.

3. **inject evidence into prompt**
   provide selected passages to the model.

4. **generate grounded output**
   produce response conditioned on retrieved text.

5. **cite or verify**
   expose source links or run checks when needed.

---

## why rag matters

- it **improves factuality and freshness**
- it **supports enterprise/private knowledge use**
- it **enables auditable, source-grounded responses**
- it **reduces dependence on periodic full retraining**

---

## rag summary

**rag = retrieve relevant evidence + generate conditioned response.**
