---
layout: page
title: Planning for Single/Multiple Agents 
---

## Project description

The top layer of the proposed system's supervision software includes a computational intelligence system with multi-agent and single-agent planners. This layer is responsible, among other things, for scheduling tasks between agents, abstracting the agent's view of the world, monitoring the execution of the agents' actions, etc.

There are many situations in which we cannot previously describe what is the best sequence of actions to be executed by one or more agents, as that would lower the flexibility and quality of the plans by not taking advantage of each situation. Thus, it is necessary to describe actions (how and when the transitions occur in the world) and tasks (or goals) to be achieved by the agents from the current state that is obtained through the agents' sensors. Planning for a single agent focuses in obtaining the lowest cost plans and highest chance of success, usually providing centralised solutions. Whilst multi-agent planning focuses on coordinating agents and the exchange of information between them, often providing distributed solutions.

The development of the single agent planner is in an initial stage, we are modifying and testing a hierarchical task planner to support costs and probabilities, in order to return plans with the highest chance of success. The next step is to describe the actions that the agents can execute using not only predicates from the discretization, but also from continual elements.

A prototype of the multi-agent planner is already in testing, and a demonstration version is available in the link [https://github.com/smart-pucrs/DOMAP](https://github.com/smart-pucrs/DOMAP). We published three papers [1, 2, 3] that describe some of the technicques used in our planner. The experiments reported in [4] show that our multi-agent planner surpasses the state of the art in many ways. Currently we are trying to integrate the planner with the simulation environment from the overall project. 

| | | 
| --- | --- | 
| ![AI](../images/icons/ia.png "AI") |  ![planning](../images/icons/planning.png "planning") | 

### Goals

 - Goal 1: brief description

### Milestones

 - Milestone 1: brief description; status (%)


## People

### Coordinator

 - ???

### Academic Collaborators

 - Rafael Bordini, PUCRS.
 - Felipe Meneguzzi, PUCRS.
 - Jomi Hübner, UFSC.

### Students

 - Anderson Nascimento, Master student on Computer Science/PUCRS, advised by Felipe Meneguzzi.
 - Guilherme  Villagran Barreto de Azevedo, Master student on Computer Science/PUCRS, advised by Felipe Meneguzzi.
 - Maurício Cecílio Magnaguagno,  PhD student on Computer Science/PUCRS, advised by Felipe Meneguzzi.
 - Rafael Cauê Cardoso,  PhD student on Computer Science/PUCRS, advised by Rafael Bordini.
 - Tulio Lima Basegio,  PhD student on Computer Science/PUCRS, advised by Rafael Bordini.
 - Tabajara Krausburg Rodrigues,  Master student on Computer Science/PUCRS, advised by Rafael Bordini.
 - Marcelo Sousa Menegol, Master student UFSC, advised by Jomi Hübner.
 
## Papers

 - [1] [Allocating Social Goals Using the Contract Net Protocol in Online Multi-Agent Planning](http://ieeexplore.ieee.org/document/7839586/)
 - [2] [A Distributed Online Multi-Agent Planning System](https://smart-pucrs.github.io/publications/DOMAPS-DMAP16.pdf)
 - [3] [A Multi-Agent Extension of Hierarchical Task Network](https://smart-pucrs.github.io/publications/MAHTN-WESAAC16.pdf)
 - [4] [A Modular Framework for Decentralised Multi-Agent Planning](http://dl.acm.org/citation.cfm?id=3091338)

## Repositories

 - [DOMAP - Distributed Online Multi-Agent Planning framework](https://github.com/smart-pucrs/DOMAP)

## Media 

videos and photos.

