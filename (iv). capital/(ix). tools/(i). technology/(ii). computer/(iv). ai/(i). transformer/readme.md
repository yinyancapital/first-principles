# transformer.

## start with the basic truths
i. **sequence understanding needs context.**  
   meaning depends on relationships between units, not isolated tokens.

ii. **parallel computation improves scale.**  
   processing many positions at once enables larger training workloads.

iii. **attention selects relevance.**  
   each position can weight other positions by importance.

iv. **stacked layers build abstractions.**  
   repeated transformation turns surface text into deeper representations.

---

## what is a transformer?

**transformer** = **a neural network architecture that models sequences by using self-attention to relate tokens across context, enabling efficient large-scale language learning.**  
it is the core architecture behind modern llms.

---

## how a transformer works

1. **embed tokens and positions**  
   map token ids into vectors with positional information.

2. **apply self-attention**  
   compute how strongly each token should attend to others.

3. **mix through feedforward layers**  
   transform attended representations into richer features.

4. **repeat across many layers**  
   stack blocks to capture increasingly abstract patterns.

5. **project to token probabilities**  
   convert final states into next-token likelihoods.

---

## why transformers matter

- they **scale effectively with data and compute**  
- they **capture long-range language dependencies**  
- they **support transfer across many tasks**  
- they **enable state-of-the-art generative ai systems**  

---

## a simple example

question: *why can a transformer resolve pronouns like "it" in long sentences?*

first principles:
- self-attention links distant tokens directly  
- each token representation includes global context  
- layered refinement improves referent disambiguation

so transformers resolve pronouns well because **attention lets tokens pull meaning from relevant context anywhere in the sequence.**

---

## transformer summary

**transformer = token embeddings + self-attention + layered transformation → context-aware sequence modeling.**  
when attention is stacked at scale, language capability rises sharply.
