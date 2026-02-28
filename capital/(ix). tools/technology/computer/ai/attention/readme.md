# attention.

## start with the basic truths
i. **not all context is equally useful.**  
   some tokens matter more than others for a given prediction.

ii. **relevance can be weighted.**  
   influence can be represented as numeric importance scores.

iii. **weights can be learned from data.**  
   training adjusts focus patterns toward lower error.

iv. **dynamic focus improves prediction.**  
   each token can attend differently depending on context.

---

## what is attention?

**attention** = **a mechanism that assigns importance weights between tokens so a model can focus on the most relevant context for each prediction.**

---

## how attention works

1. **compare tokens**  
   compute compatibility signals between query and context tokens.

2. **normalize scores**  
   convert raw scores into probability-like weights.

3. **aggregate context**  
   form a weighted sum of value vectors.

4. **pass forward**  
   use the focused representation for downstream prediction.

---

## attention summary

**attention = learned relevance weighting over context.**
