# gradient descent.

## start with the basic truths
i. **error landscapes have direction.**
   gradients indicate how parameters affect loss.

ii. **small steps accumulate improvement.**
   iterative updates can find useful minima.

iii. **step size controls stability.**
   too large diverges; too small stalls progress.

iv. **optimization is approximate.**
   practical training seeks good-enough basins, not perfect minima.

---

## what is gradient descent?

**gradient descent** = **an optimization method that updates parameters in the direction that most reduces loss, step by step.**

---

## how gradient descent works

1. **compute gradients**
   estimate how each parameter changes loss.

2. **choose learning rate**
   set update magnitude.

3. **update parameters**
   move weights opposite gradient direction.

4. **re-evaluate loss**
   check whether error decreases.

5. **repeat over batches**
   iterate across data until convergence.

---

## why gradient descent matters

- it **enables scalable training of large networks**
- it **translates loss signals into learning updates**
- it **supports many optimizer variants (adam, sgd, etc.)**
- it **is foundational to modern deep learning**

---

## gradient descent summary

**gradient descent = iterative parameter updates guided by loss slopes.**
