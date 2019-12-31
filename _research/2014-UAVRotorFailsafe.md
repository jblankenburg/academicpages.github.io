---
title: "Failsafe Algorithms for Stabilization and Control of UAS Platforms"
collection: research
type: ""
permalink: /research/UAVRotorFailsafe
venue: "University of Nevada, Reno, Computer Science and Engineering"
date: 2014-08-28
location: "Reno, Nevada"
---
Role: Lead undergraduate researcher.

Rapid increase in the use of Unmanned Autonomous Systems (UAS) has caused the safety of these platforms to become a high priority. One main safety issue with UAS platforms is motor failure. In order to increase the safety of these platforms in the event of such a failure, a failsafe mechanism can be used to stabilize and control the UAS platform.

Without a failsafe mechanism, the loss of a motor will cause the platform to fall out of the sky. This can cause serious injury to the people and property in the vicinity of the UAS. Using a failsafe mechanism would prevent these types of falls from occurring thereby increasing the safety of UAS during flight and minimizing damage to the surroundings.

With the loss of a motor, the dynamics of a UAS platform will change. By taking advantage of these new dynamics, a failsafe algorithm can use the reduced attitude to return partial control to the platform. This partial control can be used to stabilize the platform and maneuver it a short distance in order to bring it safely to the ground. We have developed failsafe algorithms to deal with motor failure on two different types of UAS: asymmetrical quadrocopters and hexacopters.
The algorithm for a quadrocopter is adapted from a feedback linearization approach. One of the hexacopter algorithms is also adapted from this approach. The other hexacopter algorithm is adapted from a redistributed pseudo inverse method. The quadrocopter algorithm maintains control for a long enough period of time that a safe landing is possible. The first hexacopter algorithm maintains control by shutting off the opposing motor, thus allowing the platform to fly as a quadrocopter and land safely. The second hexacopter algorithm maintains control with five motors, but it’s much less stable than the feedback linearization based algorithm.

Associated Publications: 
* <https://jblankenburg.github.io/publication/2014-NVSGC>