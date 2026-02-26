# agent.

## start with the basic truths
i. **goals require ongoing action.**  
   one-shot outputs are useful, but many tasks need multi-step execution over time.

ii. **actions need feedback.**  
   each step changes the environment, so the next step must adapt to new information.

iii. **tools extend capability.**  
   reasoning alone is limited; agents become useful when they can call tools and use memory.

iv. **coordination needs constraints.**  
   autonomy must stay bounded by rules, permissions, and objective checks.

---

## what is an agent?

**agent** = **an ai system that can plan and take multi-step actions toward a goal by using [prompt](../prompt/readme.md), [tool](../../../../readme.md), memory, and feedback from results.**  
it is goal-directed execution, not just one response.

---

## how an agent works

1. **receive objective**  
   parse the goal, constraints, and success criteria.

2. **plan next action**  
   choose the highest-value step from current context.

3. **act with tools or outputs**  
   run a tool call, query data, or generate user-facing content.

4. **observe results**  
   read outcomes, errors, and environment changes.

5. **update state and iterate**  
   refine the plan until success, stop condition, or escalation.

---

## why agents matter

- they **turn model intelligence into execution loops**  
- they **handle multi-step workflows with adaptation**  
- they **connect language reasoning to real-world tools**  
- they **increase throughput on repetitive cognitive tasks**  

---

## a simple example

question: *why is a travel-booking assistant with tool use an agent?*

first principles:
- it has a goal (book the best itinerary)
- it takes multiple actions (search, compare, confirm)
- each action depends on prior results
- it uses tools and constraints to finish the task

so it is an agent because it **iteratively plans and acts toward a goal using feedback.**

---

## agent summary

**agent = goal + plan + tool actions + feedback loop → autonomous task progress.**  
when ai can repeatedly decide and act, it behaves like an agent.
