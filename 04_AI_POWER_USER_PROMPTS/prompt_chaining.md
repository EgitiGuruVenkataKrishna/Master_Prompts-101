# Prompt Chaining

Prompt chaining means solving a task through **multiple smaller prompts** rather than one large prompt.

This improves clarity and reasoning.

---

# 1. Problem Breakdown Chain

Prompt 1:

Act as an analyst.

Problem:
[PROBLEM]

Task:
Break this problem into smaller components.

Output:
List of subproblems.

---

Prompt 2:

Act as a subject expert.

Subproblem:
[SUBPROBLEM]

Task:
Provide a solution for this subproblem.

Output:
Explanation and solution.

---

Prompt 3:

Act as a synthesis expert.

Task:
Combine the solutions of the subproblems.

Output:
Final integrated solution.

---

# 2. Research Chain

Prompt 1 – Topic Exploration

Act as a research assistant.

Topic:
[TOPIC]

Task:
Identify key areas related to this topic.

Output:
List of research areas.

---

Prompt 2 – Deep Analysis

Act as a domain expert.

Research Area:
[AREA]

Task:
Explain this area in detail.

Output:
Structured explanation.

---

Prompt 3 – Summary

Act as a knowledge synthesizer.

Task:
Summarize the research findings.

Output:
Key insights and conclusions.

---

# 3. Content Creation Chain

Prompt 1 – Idea Generation

Act as a creative strategist.

Topic:
[TOPIC]

Generate:
10 content ideas.

---

Prompt 2 – Content Structure

Act as a content planner.

Selected Idea:
[IDEA]

Create an outline.

---

Prompt 3 – Content Development

Act as a professional writer.

Outline:
[OUTLINE]

Write the full content.
