# pretraining.

## start with the basic truths
i. **general capability requires broad exposure.**
   narrow data cannot produce broad language competence.

ii. **patterns are learned before specialization.**
   foundations are built first, then adapted.

iii. **scale changes quality.**
   large data and compute create qualitatively stronger priors.

iv. **unsupervised objectives are efficient.**
   next-token prediction uses abundant raw text.

---

## what is pretraining?

**pretraining** = **the initial large-scale training phase where a model learns broad statistical structure from massive general data before task-specific adaptation.**

---

## how pretraining works

1. **collect broad corpora**
   gather diverse text and code sources.

2. **define base objective**
   usually predict next tokens from context.

3. **optimize over many steps**
   update parameters across huge batches.

4. **form general representations**
   learn syntax, facts, and reasoning heuristics.

5. **produce a base model**
   hand off to fine-tuning or alignment stages.

---

## why pretraining matters

- it **builds reusable language intelligence**
- it **reduces labeled-data requirements later**
- it **enables transfer to many downstream tasks**
- it **defines the ceiling for later specialization**

---

## pretraining summary

**pretraining = large-scale foundation learning before specialization.**
