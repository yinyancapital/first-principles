# token.

## start with the basic truths
i. **language can be segmented.**  
   long sequences can be split into smaller units.

ii. **models process units, not wholes.**  
   computation scales by operating on manageable pieces.

iii. **units can represent variable text spans.**  
   a unit may be a character, subword, word, or symbol.

iv. **sequence and probability drive generation.**  
   models predict one unit after another.

---

## what is a token?

**token** = **a unit of text representation that a language model reads or generates during processing.**  
it is a computational piece of language.

---

## how tokens work

1. **tokenize input**  
   split text into model-recognized units.

2. **map units to ids**  
   convert tokens into numeric form.

3. **process sequence context**  
   use surrounding tokens to estimate next-token probabilities.

4. **generate token by token**  
   produce output as a sequence of predicted units.

5. **decode to text**  
   turn generated token ids back into readable language.

---

## why tokens matter

- they **make language computable**  
- they **define context window limits**  
- they **shape cost and latency**  
- they **govern generation granularity**  

---

## a simple example

question: *why can one word become multiple tokens?*

first principles:
- tokenization uses model-specific units  
- units are optimized for efficient representation  
- rare or complex words may split into subparts

so one word can map to many tokens because **tokens are computational units, not strict word boundaries.**

---

## token summary

**token = text unit for model computation.**  
when language is split for prediction, tokens appear.
