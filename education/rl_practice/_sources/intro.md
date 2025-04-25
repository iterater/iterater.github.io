# Front matter

## Introduction

Reinforcement Learning (RL) has evolved far beyond its foundational algorithms like Q-learning and policy gradients. While introductory texts often focus on single-agent Markov Decision Processes (MDPs) and tabular methods, this book takes a different approach: it assumes familiarity with RL basics and instead explores adjacent and advanced topics that are increasingly critical in both research and industry applications.  

This is not a book that introduce basic concepts and ideas of RL. Instead, it is designed for readers who already understand RL’s core principles and want to:  
- Implement and experiment with less commonly taught RL variants (e.g., inverse RL, multi-agent systems).  
- Understand how RL interacts with human input (preference learning, feedback loops).  
- Gain hands-on experience with emerging RL paradigms that bridge theory and real-world deployment.  

Most RL textbooks and courses follow a predictable trajectory: dynamic programming → Q-learning → Deep Q-Networks (DQN) → policy gradients → perhaps a brief mention of multi-agent RL or imitation learning. However, many modern RL challenges—such as reward specification, decentralized learning, and human-AI collaboration—require going beyond these basics. This book fills that gap by:  

1. *Providing executable, modular code* (Jupyter notebooks) for each topic, allowing both active experimentation and passive reading.  
2. *Focusing on adjacent RL methods* that are often omitted from introductory material but are increasingly relevant (e.g., inverse RL for reward learning).  
3. *Encouraging critical analysis* by discussing practical limitations, failure cases, and open research questions.  

## Structure and topics

The book is organized into four self-contained but complementary sections:  

1. *Basics of Reinforcement Learning: The CartPole Model.* Covers basics ideas and concepts of RL, value iteration, and policy gradient methods.  
2. *Inverse Reinforcement Learning (IRL): Inferring Reward Functions.* Examines the problem of reward shaping from expert trajectories, demonstrates maximum entropy IRL.  
3. *Multi-Agent Reinforcement Learning (MARL): Cooperation and Competition.* Introduces interaction and decentralized training. Case studies on more complex muti-agent environments.  
4. *Reinforcement Learning with Human Feedback (RLHF).* Provides a simplified RLHF pipeline for fine-tuning LLMs or robotic policies.  

Each section is includes basic introduction and problem definition (subsection "Poblem definition"); initial setup instruction and implementation details (subsection "Implementation"); experimental setup, running, and interpretation (subsection "Experiments"); basic conclusions and take-aways (subsection "Conclusion").

This book is designed for two complementary modes of engagement:  

1. *As an interactive coding guide.* All the codes were implemented as Jupyter notebooks. A reader can run the provided notebooks, tweak hyperparameters, and observe how changes affect performance. Extend implementations with custom environments or alternative algorithms.  
2. *As a conceptual reference.* Read through the problem formulations and discussions without running code. Use the notebooks as annotated case studies in advanced RL techniques.  

The book is distributed in several forms with the same content:
1. As printed or electronically distributed book.
2. As online practical materials available at: https://iterater.github.io/education/rl_practice/
3. As source code repository at: https://github.com/iterater/abm_book_rl_practice

## Education trajectory integration 

The book is developed as a practical training text book available in MSc programs "Big Data and Machine Learning" (courses "Machine Learning", "Reinforcement Learning"), "Artificial Intelligence and Behavioral Economics" (courses "Agent behavior modelling and prediction in financial systesm"), and others. However, the book can be used in free-form and self education for practical training in reinforcement learning topics and applications.

**Prerequisites.** Readers should have:  
- Intermediate Python skills (NumPy, PyTorch/TensorFlow).  
- Basic machine learning knowledge (gradient descent, neural networks).  
- Prior exposure to RL fundamentals (MDPs, Q-learning, policy gradients).  

**Contributions and Unique Perspective.** Unlike most RL books, this work:  
- Skips introductory material in favor of adjacent and emerging topics.  
- Balances implementability with depth - code is simple enough to run on a laptop but sophisticated enough to be research-relevant.  
- Encourages critical thinking by highlighting where methods fail or require careful tuning.  

**Review:** The book was reviewed by **XXXXX**

```{bibliography}
```