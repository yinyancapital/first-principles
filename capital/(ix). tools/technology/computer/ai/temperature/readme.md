# temperature.

## start with the basic truths
i. **models output probability distributions.**
   multiple next tokens are usually plausible.

ii. **selection policy changes behavior.**
   choosing from the distribution controls style and risk.

iii. **uncertainty can be amplified or damped.**
   logits can be sharpened or flattened before sampling.

iv. **creativity and reliability trade off.**
   higher randomness can increase novelty and error simultaneously.

---

## what is temperature?

**temperature** = **a decoding control that reshapes token probability sharpness, trading off determinism versus randomness in generation.**

---

## how temperature works

1. **produce logits**
   model outputs raw next-token scores.

2. **rescale by temperature**
   divide logits by temperature value.

3. **apply softmax**
   convert scaled scores into probabilities.

4. **sample token**
   select next token using adjusted distribution.

---

## why temperature matters

- it **controls consistency vs diversity**
- it **helps tune outputs to task needs**
- it **reduces variance for factual tasks at low values**
- it **increases exploration for brainstorming at higher values**

---

## temperature summary

**temperature = decoding randomness control over next-token probabilities.**
