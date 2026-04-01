---
title: "Robot Hand Codesign"
summary: "Codesign of robot hands hardware and control policy"
coverImage: "/assets/codesign_prev.gif"
order: 2
---
### Cross-embodied Co-design for Dexterous Hands
International Conference on Representation Learning (ICLR) 2026

Kehlani Fay, Darin Anthony Djapri, *Anya Zorin*, James Clinton, Ali El Lahib, Hao Su, Michael T. Tolley, Sha Yi, Xiaolong Wang

[Project Website](https://an-axolotl.github.io/HouseofDextra/)

<details>
    <summary>Abstract</summary>
    While vision-based learning from demonstrations has achieved remarkable success in enabling robots to perform manipulation tasks and high-level semantic reasoning, it remains insufficient for complex, contact-rich manipulation. These fine-grained, low-level tasks are still bottlenecked by the inherent limitations of visual feedback, which cannot capture the dynamics essential for precise physical interactions. Despite broad agreement that tactile sensing improves manipulation, there is no empirical guidance on which tactile sensors are best suited for which manipulation tasks. In this paper, we provide a systematic, task-driven evaluation of tactile sensors for robot manipulation and propose a framework for selecting and evaluating sensors based on manipulation policy performance. Separate manipulation policies are trained for tactile sensors of four distinct modalities: visual, acoustic, magnetic, and resistive, across three tasks: pick-and-place with unknown mass, object reorientation, and plug insertion. For each task, an analysis of how sensor properties such as spatial resolution, shear sensing, and tactile representation, and the inherent material friction affect task performances is done. Rather than tactile sensing being universally beneficial in the same way, our results show that the usefulness of tactile information depends strongly on sensor modality, material properties, and the specific manipulation tasks. All of the tactile sensors, code, data, and hardware setup for sensor characterization will be publicly available on the project website.
</details>
 
 For this project I implemented baselines and ran experiments. The baselines include [RoboGrammar](https://people.csail.mit.edu/jiex/papers/robogrammar/index.html), and implementing MPPI in our own reinforcement learning environment.  