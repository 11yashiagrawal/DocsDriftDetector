# HACKATHON.md
 
## Team name
Team Dot Dev
## Team members
- Yashi Agrawal - NST, RU
- Soham Goel - NST, ADYPU
## Problem statement
Problem <5>: Automated Documentation Drift Detection
 
## Models we use and why
- Qwen2.5-Coder 7B Instruct: judges whether a documentation sentence is still
  accurate after a code change (renamed flags, changed defaults, modified API
  parameters, removed features). It is a code-specialised open-weight model
  (Apache-2.0), so it reads diffs and signatures better than a general model
  of the same size, and it is small enough to run on a laptop.