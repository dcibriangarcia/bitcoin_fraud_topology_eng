# Fraud Detection in Complex Networks (Bitcoin OTC) using Algebraic Topology Tools
The problem to solve consists of analyzing the network as a graph, searching for potential scammers without using black-box predictive models. 

## 📌 The Problem
First, we scan the data from the Stanford University database, identifying rating pairs as edges, and extract their vertices by defining a bijection that indexes the vector space in order to study the directed graph they form.

## ♾️ Mathematical Approach and Topological & Algebraic Tools
Next, we study the Krylov subspaces resulting from the matrix weighted by the edge weights using Arnoldi iterations, and observe that the dominant left eigenvector represents a potential case of fraud.

Based on this analysis, we apply path algebra and the Hadamard product to observe how the subject interacts with other users, uncovering their potential collusion ring.

Finally, we conduct a strict topological audit to verify that, indeed, the identified user exhibits fraudulent behavior.

## 📄 Conclusions
Upon completion, we conclude that the approach used, apart from being efficient, offers absolute interpretability and mathematical rigor.
