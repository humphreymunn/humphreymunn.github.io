---
title: "Publications"
permalink: /publications/
layout: single
---

## Sim-to-Real, Safety, and Deployment

**RAPT: Model-Predictive Out-of-Distribution Detection and Failure Diagnosis for Sim-to-Real Humanoid Robots**  
*Under review*  
H. Munn, B. Tidd, P. Böhm, M. Gallagher, D. Howard  

We introduce **RAPT**, a lightweight, self-supervised deployment-time monitor for 50 Hz humanoid control. RAPT learns a probabilistic spatio-temporal model of nominal execution and detects predictive deviations with calibrated, per-dimension signals, enabling reliable online OOD detection under strict false-positive constraints. Beyond detection, RAPT supports post-hoc root-cause diagnosis via gradient-based temporal saliency and zero-shot LLM reasoning, providing actionable interpretability for real-world humanoid failures.

[arXiv] · [Video] · [Code]

---

## Whole-Body Control and Real-Robot Reinforcement Learning

**Whole-Body Dynamic Throwing with Legged Manipulators**  
*Australasian Conference on Robotics and Automation (ACRA), 2025*  
H. Munn, B. Tidd, P. Böhm, M. Gallagher, D. Howard  

We study dynamic throwing with legged robots, requiring tight coordination between manipulation and locomotion. By optimising full-body reinforcement learning policies rather than arm-only control, our approach exploits whole-body momentum, counter-balancing, and coordinated dynamics. We demonstrate improved throwing range, accuracy, and stability on both a humanoid and an armed quadruped, with successful sim-to-real transfer to a physical humanoid platform.

[Paper] · [Video]

---

## Reinforcement Learning Algorithms and Optimisation

**Scalable Multi-Objective Robot Reinforcement Learning through Gradient Conflict Resolution**  
*Accepted to ICRA 2026*  
H. Munn, B. Tidd, P. Böhm, M. Gallagher, D. Howard  

We propose **GCR-PPO**, a scalable multi-objective extension to actor–critic reinforcement learning that explicitly resolves conflicts between objective-wise gradients. Using a multi-headed critic and priority-based gradient resolution, GCR-PPO improves scalability and robustness without significant computational overhead. Across IsaacLab manipulation and locomotion benchmarks, GCR-PPO achieves an average performance improvement of 9.5%, with larger gains on high-conflict tasks.

[arXiv] · [Code]

---

## Neuroevolution and Learning Structure

**Towards Understanding the Link Between Modularity and Performance in Neural Networks for Reinforcement Learning**  
*International Joint Conference on Neural Networks (IJCNN), 2023*  
H. Munn, M. Gallagher  

We investigate the relationship between network modularity and performance in reinforcement learning, using neuroevolution to jointly explore architectures and weights. Through quality-diversity optimisation with MAP-Elites, we show that optimal modularity depends on complex interactions between network structure, task, and optimisation dynamics, suggesting that directly optimising for modularity may not reliably yield performance gains.

[Paper]

---

## Curriculum Learning and Environment Design

**Assessing Evolutionary Terrain Generation Methods for Curriculum Reinforcement Learning**  
*Genetic and Evolutionary Computation Conference (GECCO), 2022*  
D. Howard, H. Munn, D. Dolcetti, J. Kannemeyer, N. Robinson  

We analyse how terrain generation methods influence curriculum learning for humanoid locomotion. Comparing noise-based generators with indirect encodings (CPPNs and GANs), we evaluate learning performance using representation-agnostic MAP-Elites descriptors computed directly from terrain geometry. Our results highlight systematic differences between generators and provide practical guidance for terrain design in curriculum RL.

[Paper]
