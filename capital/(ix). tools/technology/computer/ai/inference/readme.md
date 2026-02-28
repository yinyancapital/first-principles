# inference.

## start with the basic truths
i. **training and usage are different phases.**
   learning builds the model; inference applies it.

ii. **predictions require fixed weights.**
   runtime outputs come from current parameters.

iii. **latency and cost matter in production.**
   useful systems must answer fast enough and cheaply enough.

iv. **decoding choices affect output quality.**
   generation settings change behavior without retraining.

---

## what is inference?

**inference** = **the runtime process of using a trained model to generate predictions or outputs for new inputs.**

---

## how inference works

1. **receive input**
   tokenize and prepare request data.

2. **run forward pass**
   compute model activations with fixed parameters.

3. **decode outputs**
   choose next tokens via greedy or sampling strategies.

4. **assemble response**
   detokenize and format the result.

5. **return and monitor**
   track quality, latency, and failure patterns.

---

## why inference matters

- it **turns trained models into usable behavior**
- it **determines real user experience**
- it **sets serving cost and scalability constraints**
- it **exposes model strengths and weaknesses in practice**

---

## inference summary

**inference = applying fixed learned weights to new inputs at runtime.**
