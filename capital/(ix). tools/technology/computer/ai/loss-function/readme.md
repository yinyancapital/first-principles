# loss function.

## start with the basic truths
i. **learning needs a target signal.**
   without error measurement, parameters cannot improve.

ii. **quality must be quantified.**
   optimization requires a numeric objective.

iii. **different objectives produce different behaviors.**
   what you measure shapes what the model learns.

iv. **trade-offs must be encoded.**
   loss definitions balance accuracy, safety, and robustness goals.

---

## what is a loss function?

**loss function** = **a mathematical objective that quantifies model error so training can optimize parameters toward better performance.**

---

## how loss functions work

1. **predict output**
   run model on current batch.

2. **compare to target**
   compute discrepancy between prediction and desired result.

3. **aggregate error**
   reduce per-example differences into a scalar loss.

4. **backpropagate signal**
   derive gradients for parameter updates.

5. **iterate toward lower loss**
   repeat until performance stabilizes.

---

## why loss functions matter

- they **define what “better” means during training**
- they **control optimization direction**
- they **mediate trade-offs between objectives**
- they **strongly influence final model behavior**

---

## loss function summary

**loss function = numeric error objective that drives learning.**
