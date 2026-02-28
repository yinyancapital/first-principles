# rlhf (reinforcement learning from human feedback).

## start with the basic truths
i. **likelihood training alone misses preference quality.**
   fluent text is not always helpful, safe, or truthful.

ii. **humans can rank better vs worse outputs.**
   preference signals can supervise behavior shaping.

iii. **rewards can guide policy updates.**
   learned reward models approximate human judgment.

iv. **post-training can meaningfully redirect behavior.**
   models can become more useful without full retraining.

---

## what is rlhf?

**rlhf** = **reinforcement learning from human feedback, a training approach that uses human preference signals to shape model behavior after pretraining.**

---

## how rlhf works

1. **collect preference data**
   humans compare and rank model responses.

2. **train a reward model**
   learn to predict preferred outputs.

3. **optimize policy model**
   use reinforcement learning to maximize reward.

4. **constrain drift**
   keep behavior near stable pretrained capabilities.

5. **evaluate and iterate**
   test for helpfulness, harmlessness, and honesty.

---

## why rlhf matters

- it **improves practical usefulness and tone**
- it **aligns outputs with human preferences**
- it **reduces undesirable behaviors in deployment**
- it **forms a core stage of modern llm post-training**

---

## rlhf summary

**rlhf = human preference data + reward modeling + policy optimization.**
