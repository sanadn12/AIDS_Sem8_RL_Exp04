# ❄️ Experiment 4: Policy Iteration & Value Iteration on FrozenLake Environment

**Name:** Sanad Naqvi
**Roll No:** 221A023

---

## 🎯 Aim

To implement and compare **Policy Iteration** and **Value Iteration** algorithms on the FrozenLake environment to determine the optimal policy and maximize rewards.

---

## 📌 Problem Statement

The objective is to train an agent to navigate a slippery frozen lake and reach the goal while avoiding holes, using reinforcement learning techniques.

---

## 📖 Theory

### 🔹 FrozenLake Environment

* Grid-based environment
* Start → Goal path
* Some tiles are holes (failure states)
* Agent must learn safest and optimal path

### 🔹 Policy Iteration

* Starts with a random policy
* Repeatedly performs:

  * Policy Evaluation
  * Policy Improvement
* Stops when policy becomes stable

### 🔹 Value Iteration

* Directly computes optimal value function
* Uses Bellman optimality update
* Derives optimal policy from values

---

## 🛠️ Implementation

### 🔹 Libraries Used

* gym / gymnasium
* numpy

### 🔹 Steps

1. Created FrozenLake environment
2. Implemented:

   * Policy Evaluation
   * Policy Iteration
   * Value Iteration
3. Used one-step lookahead for action evaluation
4. Derived optimal policy
5. Tested policy over multiple episodes (10,000)
6. Compared performance metrics

---

## 📊 Results

### 🔹 Policy Iteration

* Wins: **8207 / 10000**
* Average Reward: **0.8207**

### 🔹 Value Iteration

* Wins: **8238 / 10000**
* Average Reward: **0.8238**

### 🔹 Observations

* Both algorithms perform very well
* Value Iteration slightly outperforms Policy Iteration
* High success rate indicates optimal policy learning

---

## 📈 Analysis

* The agent successfully learns to avoid holes and reach the goal
* Exploration of states helps improve decision-making
* Convergence achieved after multiple iterations

---

## ✅ Conclusion

* Both Policy Iteration and Value Iteration effectively solved the FrozenLake problem
* Value Iteration showed slightly better performance
* Reinforcement learning algorithms can solve complex decision-making problems in uncertain environments

---

## 📚 References

* Gymnasium Documentation
* Reinforcement Learning Notes
* Bellman Equation Theory

---

## 📦 requirements.txt

```id="9x2l3d"
gymnasium
numpy
```
