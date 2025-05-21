# SFC Deployment Environment with Security Constraints

## 🧠 Overview

This project implements a custom reinforcement learning environment using [OpenAI Gym](https://www.gymlibrary.dev/) for the intelligent deployment of **Virtual Network Functions (VNFs)** across a physical network. It focuses on optimizing **Service Function Chain (SFC)** deployments while considering **security constraints**, **resource demands**, and **network capacity**.

---

## 🚀 Features

- ✅ **Dynamic Physical Network Generation**  
  Each simulation instance creates a network with tunable parameters such as node capacities, security levels, and operational costs.

- 🔗 **SFC Chain Management**  
  Supports multiple chains of VNFs with customizable demands and security requirements.

- 🤖 **Reinforcement Learning Integration (DDPG)**  
  Uses **Deep Deterministic Policy Gradient (DDPG)** to learn and optimize VNF placement over time.

- 🔒 **Security-Aware Deployment**  
  Ensures that each VNF is only placed on nodes that meet or exceed its security requirements.

- 📊 **Visualization Tools**  
  Visualizes physical network, VNF deployments, and SFC flows using `NetworkX` and `Matplotlib`.

---

