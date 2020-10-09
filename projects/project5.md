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
 - Goal 2: Model areas to asses the risk of landslide 


### Milestones

 - Milestone 1: Embeded JaCaMo agent into UAV
 - Milestone 2: Several agents collaborating in a shared mission

## People

### Coordinator

 - Luiz Marcos, UFRN.
 - [Jomi Hübner](http://jomi.das.ufsc.br), UFSC, associated to Goal 1.
 - [Mario Reiss](https://www.ufrgs.br/lafoto/), UFRGS, associated to Goal 2.
 - Alexandre Amory, PUCRS.

### Collaborators

 - [Márcio Roberto Magalhães de Andrade](http://lattes.cnpq.br/4500089773487570), [CEMADEN](http://www.cemaden.gov.br/author/marcio/), Evaluating landslide risk in Blumenau using UAVs, associated to Goal 2.
 - [DragronFly drones](http://www.dragonflydrones.com.br/)

### Students

 - Fernando Rodrigues Santos. AVALIAÇÃO DO USO DE AGENTES NO DESENVOLVIMENTO DE APLICAÇÕES COM VEÍCULOS AÉREOS NÃO- TRIPULADOS. 2015. - UFSC. Orientador: Jomi Fred Hübner.
 - Marcelo Sousa Menegol. Multi-Agent Coordination Applied to UAVS. 2018. Mestrado em Engenharia de Automação e Sistemas - UFSC. Orientador: Jomi Fred Hübner.
 - Gustavo Rezende Silva. ACTIVE PERCEPTION WITHIN BDI AGENTS REASONING CYCLE WITH APPLICATIONS IN MOBILE ROBOTS  - UFSC. Orientador: Jomi Fred Hübner.


## Papers

    @Article{isprs-archives-XLII-2-W13-567-2019,
    AUTHOR = {Reiss, M. L. L. and Mendes, T. S. G. and Andrade, M. R. M. and Amory, A. M. and de Lara, R. and Souza, S. F.},
    TITLE = {RPAS IN THE SUPPORT FOR PHOTOGRAMMETRY EDUCATION: CASES IN TOPOGRAPHIC MAPPING AND DOCUMENTATION OF HISTORICAL MONUMENTS},
    JOURNAL = {ISPRS - International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
    VOLUME = {XLII-2/W13},
    YEAR = {2019},
    PAGES = {567--574},
    URL = {https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLII-2-W13/567/2019/},
    DOI = {10.5194/isprs-archives-XLII-2-W13-567-2019}
    }
    
    @inproceedings{menegol18b,
        Author = {Marcelo Souza Menegol and Jomi Fred H\"ubner and Leandro Buss Becker},
        Booktitle = {Proc. of 16th International Conference International Conference on Practical Applications of Agents and Multi-Agent Systems (PAAMS 2018)},
        Doi = {10.1007/978-3-319-94580-4_33},
        Editor = {Yves Demazeau and Bo AnJavier Bajo and Antonio Fern{\'a}ndez-Caballero},
        Pages = {335-338},
        Series = {LNCS},
        Title = {Coordinated {UAV} Search and Rescue Application with {JaCaMo}},
        Volume = {10978},
        Year = {2018}}


    @inproceedings{menegol18a,
        Author = {Marcelo Souza Menegol and Jomi Fred H\"ubner and Leandro Buss Becker},
        Booktitle = {Proc. of 16th International Conference International Conference on Practical Applications of Agents and Multi-Agent Systems (PAAMS 2018)},
        Doi = {10.1007/978-3-319-94580-4_17},
        Editor = {Yves Demazeau and Bo AnJavier Bajo and Antonio Fern{\'a}ndez-Caballero},
        Pages = {212-223},
        Series = {LNCS},
        Title = {Evaluation of Multi-Agent Coordination on Embedded Systems},
        Volume = {10978},
        Year = {2018}}

    

## Repositories

 - [JaCaMo for UAVs](https://github.com/msmenegol/JasonArchEmb)

## Main Hardware Resources

### UFSC UAV
 - [BeagleBone Black](https://beagleboard.org/black)
 - [PixHawk controller board](https://pixhawk.org/)
 - WiFi module ESP8266
 - SK450 Quad Copter


### PUCRS UAV
 - [Raspberry Pi 4](https://beagleboard.org/black)
 - [Navio2 autopilot](https://cdn.emlid.com/navio/)
 - FrSky 2.4GHz ACCST TARANIS X9D PLUS
 - SK450 Quad Copter
 - SK550 Hexa Copter
 - Tarot 680 Hexa Copter


## Media 

 - [youtube](https://www.youtube.com/watch?v=FcS4QDtrBCI) A single UAV controlled by an embedded JaCaMo agent.
 - [youtube](https://www.youtube.com/watch?v=EoVd2ZPDw-M) Simulation of search and rescue with drones.

![Alt text](../images/projects/drone-pucrs-1.png?raw=true "testing drones at PUCRS")
![Alt text](../images/projects/drone-pucrs-2.png?raw=true "testing drones at PUCRS")
