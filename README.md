# Machine Learning Workshop

In this repository, I am going to provide resources and materials in the machine learning workshop series that I am going to organize.
The topic and format of each session is not fixed and the format can be different in each session. You can find some of the topics and formats
that I have in mind in the following list, but this list is not exhaustive and other formats can be added to this list.

- Reading a paper carefully and discussing about it.

- Reading and talking about a concept. E.g., we can organize a session to talk about program induction. In this kind of sessions, we will
review some of the important papers and contributions in that research area.

- Implemneting a paper and even deploy a toy model.

- Learning about a framework or well-known package and trying to gain some hands-on experience.

- Working with released frameworks for reinforcement learning. E.g., Trying to learn more about "OpenSpiel: A framework for reinforcement learning in games"
or other similar frameworks.

- Becoming familiar with game engines to design an environment for RL agent.

- Inspecting and examining a problem, interface, programmin language from design perspective. Trying to write and propose suitable design
solution for different kind of problems.

As I mentioned, the list can be expanded and the format is not limited to the aforementioned items.

## Resources and materials

After each session, I am going to write a pdf file. This file summarize the main topic of the session, some side topics that we pointed out in the
meeting and we didn't talk about them thoroughly, and some code bases, frameworks and useful materials for further reading.

You can find the pdf file in the Topics folder.

### Week 1

- Main topic: Knowledge Distillation
- Tag : Reading a paper and discussion about it.
- Main paper: [Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)

### Week 2

- Main topic: Lottery ticket hypothesis
- Tag : Reading a paper and discussion about it.
- Main paper: [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/abs/1803.03635)

### Week 3

- Main topic: Computational learning theory (PAC Learning)
- Tag : Reading a theoretical topic (book chapter) and discussion about it.
- Main reference: Chapter 2 of [Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf)

### Week 4

- Main topic: Causality (Part 1)
- Tag : Introdoction to causality and its importance in decision and policy making.
- Main reference: I have covered some chapters of [Causality: Models, Reasoning and Inference: Judea Pearl](https://www.amazon.com/Causality-Reasoning-Inference-Judea-Pearl/dp/052189560X) book. You can refer to the outline of week 4 to know what topics I have covered in details.

### Week 5

- Main topic: Causality (Part 2)
- Tag : Structural equations models and counterfactuals.
- Main reference: I have covered some chapters of [Causality: Models, Reasoning and Inference: Judea Pearl](https://www.amazon.com/Causality-Reasoning-Inference-Judea-Pearl/dp/052189560X) book. You can refer to the outline of week 5 to know what topics I have covered in details.

### Week 6

- Main topic: Gaussian process
- Tag : Introduction to gaussian process, gaussian process regression
- Main reference: I have used [this](https://www.youtube.com/watch?v=92-98SYOdlY) amazing tutorial from Richard Turner as the main resource for this session.
In addition, I think the best resource that covers this topic is "gaussian process for machine learning" book by Rasmussen and Williams.

### Week 7

- Main topic: Successor Representation in Reinforcement Learning
- Tag : Introducing successor representation paradigm and how it differs from model-based and model-free in terms of efficiency and flexibility.
- Main reference: There is a very nice blog [post](https://medium.com/@awjuliani/the-present-in-terms-of-the-future-successor-representations-in-reinforcement-learning-316b78c5fa3) by Arthur Juliani

### Week 8

- Main topic: Distributional RL
- Tag : What is the differences between classical RL and distributional RL
- Main reference: The main paper that we discuss about is [A Distributional Perspective on Reinforcement Learning](https://deepmind.com/research/publications/distributional-perspective-reinforcement-learning)
from DeepMind. In this paper they argue for the fundamental importance of the value distribution. Also, there is a good blog [post](https://deepmind.com/blog/article/going-beyond-average-reinforcement-learning) from DeepMind
, and an in-depth [video](https://www.youtube.com/watch?v=ba_l8IKoMvU) from Marc G. Bellemare.  

### Week 9

- Main Topic: Bayesian Interpolation
- Tag: Bayesian inference and bayesian model comparisson. Different levels of bayesian inference.
- Mian reference: [MacKay, 1992. Bayesian interpolation.](https://authors.library.caltech.edu/13792/1/MACnc92a.pdf) and [
Probabilistic machine learning and artificial intelligence](https://www.nature.com/articles/nature14541)

## Lectures

| Week            | Lecture Date   |  Topic      |  References               |
| --------------- |----------------| ------------|---------------------------|
| 1 | 9/2/2019    | Knowledge Distillation [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/01_outline_knowledge%20Distillation.pdf) |  [References](doc/refs.md#week1)  |
| 2 | 9/12/2019   | Lottery ticket hypothesis [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/02_ouline_lottery_ticket_hypothesis.pdf) |  [References](doc/refs.md#week2)  |
| 3 | 9/26/2019   | Computational learning theory (PAC Learning) [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/03_outline_computational_learning_theory.pdf)  |  [References](doc/refs.md#week3)  |
| 4 | 10/3/2019   | Causality (Part 1) [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/04_outline_causality(part1).pdf) |  [References](doc/refs.md#week4)  |
| 5 | 10/10/2019  | Causality (Part 2) [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/05_outline_causality(part2).pdf) |  [References](doc/refs.md#week5)  |
| 6 | 10/24/2019  | Gaussian process [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/06_outline_gaussian_process.pdf) |  [References](doc/refs.md#week6)  |
| 7 | 11/06/2019  | Successor Representation in Reinforcement Learning [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/07_outline_successor_representation.pdf) |  [References](doc/refs.md#week7)  |
| 8 | 12/18/2019  | Distributional RL [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/08_outline_distributional_rl.pdf) |  [References](doc/refs.md#week8)  |
| 9 | 3/18/2020   | Bayesian Interpolation [Outline](https://github.com/HFooladi/ml_workshop/blob/master/Topics/09_outline_bayesian_interpolation.pdf) | [References](doc/refs.md#week9)  |