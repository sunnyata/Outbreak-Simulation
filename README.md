# Outbreak-Simulation

A simple flu outbreak simulation implementation in Python using the following scenario:

A classroom of 31 elementary school kids. 30 of the kids are healthy on Day 1. Jonny walks in with the flu and starts interacting with the other kids. He comes to school every day (whether or not he’s sick) and stays infectious for 3 days. Thus, there are 3 chances for him to infect the other kids with an independent probability p = 0.02. Each newly infected kid becomes infectious for 3 days as well, starting on the next day.

Questions:
- What is the distribution of the number of kids that Jonny infects on Day 1?
- What is the expected number of kids that Jonny infects on Day 1?
- What is the expected number of kids that are infected by Day 2?
- Simulate the epidemic multiple iterations. Find the (estimated) expected numbers of kids that are infected on each successive day and produce a histogram detailing how long the epidemic lasts.
- What if each kid has a 50–50 chance of already being immunized?
