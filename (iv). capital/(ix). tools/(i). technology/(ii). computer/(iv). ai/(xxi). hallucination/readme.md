# hallucination.

## start with the basic truths
i. **prediction is not guaranteed truth.**  
   language models optimize likely sequences, not factual certainty.

ii. **fluency can mask error.**  
   confident wording can make incorrect statements appear credible.

iii. **missing evidence increases fabrication risk.**  
   when context is weak, models may fill gaps with plausible guesses.

iv. **verification is external.**  
   correctness must be checked against sources, tools, or observed outcomes.

---

## what is hallucination?

**hallucination** = **an ai output that is syntactically plausible but factually incorrect, unsupported, or fabricated relative to the task context.**  
it is confident generation without adequate grounding.

---

## how hallucinations emerge

1. **ambiguous or underspecified prompt**  
   unclear tasks leave too many plausible continuations.

2. **insufficient grounding context**  
   required facts are absent or incomplete.

3. **model fills gaps probabilistically**  
   likely wording substitutes for verified evidence.

4. **response appears coherent**  
   fluency hides factual defects.

5. **error propagates unless checked**  
   downstream actions inherit the false output.

---

## why hallucination matters

- it **creates hidden reliability risk**  
- it **can cause bad decisions and automation failures**  
- it **requires validation loops for high-stakes use**  
- it **defines the boundary between helpfulness and trustworthiness**  

---

## a simple example

question: *why is a fake citation a hallucination?*

first principles:
- the citation looks structurally valid
- the source does not exist or does not support the claim
- plausibility replaced evidence

so it is a hallucination because the output **sounds correct but is not grounded in verifiable fact.**

---

## hallucination summary

**hallucination = plausible language - grounded evidence → unreliable output.**  
strong retrieval, tool checks, and verification reduce hallucination risk.
