# 📈 Complex Scheduling Optimization with Meta-heuristics

**Academic Project (B.Eng) | Feb 2025 – Jun 2025**

This project tackles the classic operational research problem of creating fair schedules for Single Round Robin (SRR) tournaments.

## 🎯 The Challenge

In SRR tournaments, where every participant plays every other participant once, the schedule's structure can create significant imbalances. Factors like home-field advantage in sports or playing with the "white" pieces in chess provide a measurable edge.

An unfair schedule might, for example, pit one player against all the strongest opponents while they are "away" (or playing "black"). Our project's goal was to model this problem and build a scheduler that distributes the competitive advantage in a just and equitable way, especially in relation to opponent strength.

## 🥅 Project Goals

1.  **Model the Problem:** Define the variables, constraints, and objective functions needed to represent a "fair" tournament.
2.  **Solve for Small Cases:** Use exact methods (like Linear Programming) to find optimal solutions for small instances (e.g., 4 or 6 players) to verify the model.
3.  **Develop a Meta-heuristic:** For larger, more complex instances where exact methods fail, we were required to implement a meta-heuristic (like a **Genetic Algorithm** or **Simulated Annealing**) from scratch to find high-quality solutions.
4.  **Evaluate & Analyze:** Compare the performance of our algorithms based on solution quality (fairness), convergence speed, and computation time.

## ⚖️ Defining "Fairness"

A key part of the project was quantifying "fairness." We focused on three main criteria:

* **Opponent Strength Balance:** A player's home/away matches should be balanced against strong vs. weak opponents.
* **Alternation Pattern:** Avoid long, fatiguing streaks of home or away matches (e.g., `HAHAHA` is far better than `HHHAAA`).
* **Player Homogeneity:** The home/away patterns should be comparable across all players in the tournament.

---

## 👥 Collaborators

This was a team project for the INFO-H-3000 course at ULB.

* **Milena Paques**
* **Nicholas Birch**
* **Gabriel Badan**

## 🔒 Code Availability

As per ULB academic regulations, the source code for this project is not publicly available. Please contact me if you would like to discuss the algorithmic design or mathematical modeling in more detail.
