# sub-agent.

## start with the basic truths
i. **complex goals need decomposition.**  
   large tasks are easier when split into smaller units.

ii. **specialization improves quality.**  
   a focused worker can perform better on a narrow objective.

iii. **coordination preserves coherence.**  
   parallel work only helps if outputs are merged under shared constraints.

iv. **delegation needs boundaries.**  
   each helper must have a clear scope, permissions, and handoff format.

---

## what is a sub-agent?

**sub-agent** = **a delegated, scoped agent invoked by a parent [agent](../agent/readme.md) to complete a specific part of a broader goal.**  
it is specialized execution inside a larger orchestration loop.

---

## how sub-agents work

1. **parent defines the sub-task**  
   specify objective, context, constraints, and completion criteria.

2. **sub-agent executes locally**  
   plan and run steps within its assigned scope.

3. **sub-agent returns structured output**  
   send findings, artifacts, and status back to the parent.

4. **parent integrates results**  
   compare outputs across sub-agents and resolve conflicts.

5. **system iterates or finalizes**  
   delegate further if needed, or assemble final answer.

---

## why sub-agents matter

- they **parallelize complex workflows**  
- they **improve reliability through specialization**  
- they **reduce parent-agent context overload**  
- they **enable modular, reusable execution patterns**  

---

## a simple example

question: *why use a sub-agent in code review?*

first principles:
- one agent can focus on security
- another can check style and conventions
- the parent compares both reports before deciding

so sub-agents help because they **split one complex review into focused checks with coordinated synthesis.**

---

## sub-agent summary

**sub-agent = delegated scope + specialized execution + parent integration → scalable agent orchestration.**  
when a parent agent delegates focused work and recombines results, it is using sub-agents.
