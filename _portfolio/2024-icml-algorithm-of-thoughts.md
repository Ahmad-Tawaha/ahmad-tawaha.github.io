---
title: "Algorithm of Thoughts: Enhancing Exploration of Ideas in Large Language Models"
collection: portfolio
authors: "Bilgehan Sel, **Ahmad Al-Tawaha**, Vanshaj Khattar, Lu Wang, Ruoxi Jia, Ming Jin"
venue: "ICML, 2024"
venue_short: "ICML 2024"
image: "/images/projects/icml-2024-aot.png"
paper_url: "https://arxiv.org/pdf/2308.10379"
---
Some tasks — like planning problems — cannot be solved linearly. Chain-of-Thought works for step-by-step reasoning but fails when you need to explore multiple paths. Tree-of-Thoughts solves this but requires many separate LLM queries per problem plus external code to manage the tree. AoT's insight is simpler: show the model examples of complete search trajectories — including backtracking and dead ends — and it learns to internalize the search itself. **No external tree management. One query.**
