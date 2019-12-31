---
title: "Novel Approach for Distributed Task Allocation in Heterogeneous Teams"
collection: research
type: ""
permalink: /research/HeterogeneousTaskAllocation
venue: "University of Nevada, Reno, Computer Science and Engineering"
date: 2017-11-18
location: "Reno, Nevada"
---
Role: Lead graduate researcher.

<!-- Real-world tasks are not only a series of sequential steps, but typically exhibit a combination of multiple types of constraints. These tasks pose significant challenges, as enumerating all the possible ways in which the task can be performed can lead to large representations and it is difficult to keep track of the task constraints during execution. Previously we developed an architecture that provides a compact encoding of such tasks and validated it in a single robot domain. We recently extended this architecture to address the problem of representing and executing tasks in a collaborative multi-robot setting. Firstly, the architecture allows for on-line, dynamic allocation of robots to various steps of the task. Secondly, our architecture ensures that the collaborative robot system will obey all of the task constraints. Thirdly, the proposed architecture allows for opportunistic and flexible task execution given different environmental conditions. We demonstrated the performance of our architecture on a team of two humanoid robots (a Baxter robot and a PR2 robot) performing hierarchical tasks. Further extensions of this architecture are currently being explored.

Due to the adaptability of our multi-robot control architecture, this work has become the foundation for several ongoing extensions. The first extension is to modify the architecture to allow for a human to collaborate with the multi-robot team in order to complete the joint task. To allow the human and robots to communicate, this work augments the control architecture with a third robot “brain” which utilizes intent recognition to determine which objects the human is interacting with and updates the state of the task held by the other robots accordingly. Secondly, this architecture is being adapted to allow a human to train a robot to complete a task through natural speech commands. The multi-robot team is then able to complete the newly trained task. The third extension focuses on learning generalized task sequences utilizing the types of hierarchical constraints defined by this control architecture. The last extension to this work is to modify the architecture to allow heterogenous grasp affordances for each item in the task. These affordances allow the robots to incorporate how well they can grasp a specific object based on their gripper and arm mechanics into the task allocation architecture. Each of these extensions emphasize the generalizability of this control architecture and together illustrate the vast applications in which further extensions of this architecture can be adapted to.  -->


Real-world tasks are not only a series of sequential steps, but typically exhibit a combination of multiple types of constraints. These tasks pose significant challenges, as enumerating all the possible ways in which the task can be performed can lead to large representations and it is difficult to keep track of the task constraints during execution. We have developed an architecture that provides a compact encoding of tasks with complex constraints for collaborative multi-robot systems. The architecture allows for on-line, dynamic allocation of robots to steps of the task while ensuring the robots obey all of the task constraints. The architecture allows for opportunistic and flexible task execution given different environmental conditions.

Additionally, this architecture has been extended to incorporate heterogenous robot teams. A real-time distributed architecture enables collaborative execution of tasks with hierarchical representations and multiple types of execution constraints by teams of robots with variable heterogeneity. The architecture provides a novel pipeline that is able to handle automatic grasping of objects with unknown initial locations. This is motivated by the need for multiple robots to dynamically coordinate their execution during hierarchical tasks, in situations when the robots’ capabilities are not simply binary (skill exists: yes/no), but when the degree to which a skillcan be performed varies continuously based on the environmental conditions. 

Associated Publications: 
<!-- * <https://jblankenburg.github.io/publication/2019-ICSR> -->
<!-- * <https://jblankenburg.github.io/publication/2019-Computers> -->
<!-- * <https://jblankenburg.github.io/publication/2019-ICSV> -->
<!-- * <https://jblankenburg.github.io/publication/2019-Humanoids> -->
* In Preparation Conference Proceedings: 
	* Janelle Blankenburg, Mariya Zagainova*, S. Pourya Hoseini A., Monica Nicolescu, Mircea Nicolesu, David Feil-Seifer. “Dynamic Task Allocation in Heterogeneous Robot Teams.” In International Conference on Intelligent Robots and Systems (IROS), Las Vegas, Nevada, Oct 2020 (in prep).
* Refereed Conference Proceedings
	* Janelle Blankenburg, Santosh Balajee Banisetty, Seyed P. Hoseini, Luke Fraser, David Feil-Seifer, Monica Nicolescu, and Mircea Nicolescu. “A Distributed Control Architecture for Collaborative Multi-Robot Task Allocation.” In International Conference on Humanoid Robots (Humanoids), Birmingham, UK, Nov 2017. <https://jblankenburg.github.io/publication/2017-Humanoids>
