---
layout: page
title: Autonomous UAV -- Aerial platform for photography and photogrammetry
---

## Project description

Multi-agent applications involving multiple robots (in this case, multiple UAVs) often requires  coordination the agent's actions in order to perform a collective plan and achieve a common goal. With each agent embedded in a geographically distributed robot, a strategy that allows agents to exchange information at a distance is necessary for coordination. The strategy has to consider what kind of information agents exchange, when they exchange it, and common procedures and protocols to deal with edge cases, such as when another agent is unreachable.

Mobile robots not rarely engage in exploration-like missions, that has the goal of finding an object or points of interest, finding and acquiring a piece of information. This sort of activity is often qualify as *active perception*: the agents need to act in order to perceive the information they are after, and the perceived information helps them to better perform further actions. When a team of robots needs to collectively gather that information, a proper coordination strategy can improve the overall performance of the activity. For example, a single robot might not have enough battery to finish it's activity and, instead of aborting it entirely, the robot can request its substitution by another agent. When provided with spacial and temporal information about their objective, they can also reason and select the best suited agent to pursue the objective, instead of having multiple agents acting redundantly.

| | | |
| --- | --- | --- |
| ![rescue](../images/icons/rescue.png "for rescue") |  ![drone](../images/icons/drone.png "drone") | ![AI](../images/icons/ia.png "AI")  |

### Goals

 - Goal 1: MAS platform to coordinate distributed UAV using radio for communication. The coordination is based on JaCaMo tools.


### Milestones

 - Milestone 1: Embeded JaCaMo agent into UAV
 - Milestone 2: Several agents collaborating in a shared mission

## People

### Coordinator

 - Luiz Marcos, UFRN.
 - [Jomi Hübner](http://jomi.das.ufsc.br), UFSC.
 - Mario Reiss, UFRGS.

### Academic Collaborators

 - name, university, main role, links.

### Students

 - Marcelo Menegol, UFSC, master student. Allocated to Goal 1.

## Papers

 - title and link. full bibio data is already available at ...

## Repositories

 - [JaCaMo for UAVs](https://github.com/msmenegol/JasonArchEmb)

## Main Hardware Resources

 - [BeagleBone Black](https://beagleboard.org/black)
 - [PixHawk controller board](https://pixhawk.org/)
 - WiFi module ESP8266
 - SK450 Quad Copter

## Media 

videos and photos.

