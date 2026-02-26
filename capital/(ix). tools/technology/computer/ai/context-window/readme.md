# context window.

## start with the basic truths
i. **models process finite context.**  
   an ai system can only attend to a bounded amount of input and prior output at once.

ii. **attention is a scarce resource.**  
   adding more text can dilute focus on important details.

iii. **history competes with instructions.**  
   long conversations can crowd out critical constraints.

iv. **truncation changes behavior.**  
   dropped context can reduce accuracy and consistency.

---

## what is a context window?

**context window** = **the maximum amount of tokens a model can consider in a single inference pass, including prompt, retrieved context, and generated text.**  
it is the model's working memory boundary.

---

## how context windows affect output

1. **allocate input budget**  
   split available space across instructions, data, and examples.

2. **reserve output budget**  
   leave room for the expected response length.

3. **prioritize high-value context**  
   keep what is most relevant to the objective.

4. **compress or summarize history**  
   reduce low-signal text while preserving key facts.

5. **monitor truncation risk**  
   detect when important constraints are being dropped.

---

## why context windows matter

- they **limit how much a model can reason over at once**  
- they **shape prompt design and retrieval strategy**  
- they **directly affect quality, cost, and latency**  
- they **determine when summarization is required**  

---

## a simple example

question: *why can a long support chat suddenly lose consistency?*

first principles:
- conversation length grows over time
- older constraints may be truncated
- missing constraints change next-step prediction

so consistency drops because the model **cannot use context that falls outside its context window.**

---

## context window summary

**context window = finite token capacity + prioritization tradeoffs → bounded model awareness.**  
better context management improves reliability.
