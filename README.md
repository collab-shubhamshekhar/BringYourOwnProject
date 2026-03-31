# Reinforcement Learning for Dynamic Resource Allocation in Cloud Computing

**Author:** Shubham Shekhar
**Registration No:** 23BAI11164


---
## Project Overview

This project focuses on applying **Reinforcement Learning (RL)** to optimize resource allocation in cloud computing environments. The system dynamically allocates CPU resources to incoming tasks to improve efficiency and reduce waiting time.

---

## Objective

* Optimize CPU resource allocation
* Minimize task waiting time
* Maximize resource utilization
* Reduce resource wastage

---

## Key Concept

The project uses **Q-Learning**, a reinforcement learning algorithm, where an agent learns optimal decisions through interaction with the environment.

---

## Problem Statement

Design an intelligent system that dynamically allocates CPU resources to tasks in a cloud environment while balancing:

* Efficient resource usage
* Reduced task delays

---

## Methodology

* A custom simulation environment is created
* Tasks arrive randomly and are queued
* The RL agent observes the system state
* The agent decides CPU allocation (Low / Medium / High)
* The agent learns using rewards and penalties

---

## Environment Design

* Fixed CPU capacity
* Dynamic task queue
* Continuous task arrival
* State updates after each action

---

## Reward Function

* Positive reward → Fast task completion
* Penalty → Idle resources & long waiting time

---

## Tech Stack

* Python
* NumPy
* Matplotlib
* Reinforcement Learning (Q-Learning)

---

## Results

* RL agent improves over time
* Achieves better performance than random allocation
* Higher resource utilization
* Reduced waiting time

---

## Future Scope

* Use Deep Reinforcement Learning (DQN)
* Add real-world cloud simulation
* Multi-resource allocation (CPU + Memory + Storage)

---

## Conclusion

This project demonstrates how Reinforcement Learning can efficiently solve dynamic resource allocation problems in cloud computing. The model learns intelligent strategies and outperforms traditional methods.

---



