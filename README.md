# Polyu_AAE2004_group3
<!-- TABLE OF CONTENTS -->
<details>
  <summery>Table of contents</summary>
  <ol>
    <li><a href="## Member">Member</a> 
    <li><a href="## Introduction">Introduction</a>  
    <li><a href="## Background of Path Planning to Aviation Engineering">Background of Path Planning to Aviation Engineering</a></li>
    <li><a href="Theory of Path Planning Algorithm">Theory of Path Planning Algorithm</a></li>
    <li><a href="## Introduction of the Engineering Tools">Introduction of the Engineering Tools</a>
        <ul>
          <li><a href= "### Python">Python</a></li>
          <li><a href= "### Github">Github</a></li>
        </ul>  
    <li><a href="## Task1">Task1</a></li>
        <ul>
          <li><a href= "### Methodology">Methodology</a></li>
          <li><a href= "### Results">Results</a></li>
          <li><a href= "### Discussion">Discussion</a></li>
        </ul>
    <li><a href="## Task2">Task2</a></li>
        <ul>
          <li><a href= "### Methodology">Methodology</a></li>
          <li><a href= "### Results">Results</a></li>
          <li><a href= "### Discussion">Discussion</a></li>
        </ul>
    <li><a href="## Task3">Task3</a></li>
        <ul>
          <li><a href= "### Methodology">Methodology</a></li>
          <li><a href= "### Results">Results</a></li>
          <li><a href= "### Discussion">Discussion</a></li>
        </ul>
    <li><a href="## Reflective Essay">Reflective Essay</a></li>
    <li><a href="## Refreneces">References</a></li>
  </ol>
</details>

## Member
CHEUNG Tin Lam [rrrrachelll]

CHEUNG Wing Hin [cwhhhhh]

CHU Chenyi [chuchenyi2]

Chui Lung Kwun Bonald [ayase101]

GUO Qiuxi [QUECIE]

HO Tsz Hin Matthew [Hin-Zz]

HO Yan Chak [Enzidayo]

## Introduction
![zeroe-concept-aircraft-patrol-flight](https://user-images.githubusercontent.com/116060401/204120158-c22cd715-cbe7-46ab-b0d2-febd66fff48c.jpg)

Since the invention of the aircraft, navigation always is an important part of aviation. To solve the navigation problem effectively, people try to use AI technology, also known as Path planning. Path planning is the computational problem to find a sequence of valid configurations that moves the object from the source to the destination. 

According to the air traffic statistics provided by AAHK, HKIA recorded approximately 145,000 air traffic movements in 2021. The airspace is fully in-used to handle all the flights. To balance flight efficiency and cost, path planning is important to generate the maximum benefit in a flight operation. By path planning, the designer can fulfill all the constraints to ensure the best use of the crowded airspace and designs an optimized route for aircraft operation. 

In the project, we are going to practice path planning by writing a Python program that helps us to design and calculate the optimized path with the lowest cost and choose the best aircraft model under given scenarios in each task.

## Background of Path Planning to Aviation Engineering
Aircraft flying is all about 'value for money'. The best way to fly a complete route in the shortest possible time and with the least amount of fuel is based on cost-effectiveness. The first thing that comes to mind when forming such an optimal route is that the shorter the route, the better!

From the passenger's point of view, it is essential to plan the shortest possible flight path. Suppose a passenger is travelling on a multi-transfer flight. In that case, flight time is generally one of the decisive factors in the passenger's choice, and more passengers prefer a combination of shorter flights. For airlines and airports, planning the shortest possible multi-route route can help attract passengers.

The value of the shortest distance route is the cost savings. For airlines, shorter flight distances can help them to reduce their overheads if the cost per unit of distance is fixed. This idea of saving costs by planning the shortest route can be applied to passenger and cargo transport.

## Theory of Path Planning Algorithm
Path planning is a calculation problem. It can find an effective sequence of configurations to move the object from its source to its destination. For a given situation, the flight can choose the best aircraft model with an optimised route based on this algorithm, finding the optimal or near-optimal path from the starting state to the target state for obstacle avoidance, minimising the operational cost of the aircraft.

When the tough competitive environment is forcing airlines to consider every aspect of their operating costs, airlines want to minimise the cost of flying by choosing the right route, altitude and speed, and by loading the least amount of necessary fuel on board so that path planning is invented. It can provide optimum economic benefits by calculating the direct operating costs when fuel, time, distance flown, number of passengers, etc. are all important factors to consider. By the formula: C = Cf x F x T + CT x T + Cc, we can easily understand, without resorting to complex mathematics, that the total cost of a particular trip is the sum of fixed and variable costs.

## Introduction of the Engineering Tools

### Python
![Python-Symbol](https://user-images.githubusercontent.com/116060401/204120024-3d5c51ff-8a2f-4f1d-8c16-f4391a72c11a.png)
Python is an effective programming language that many companies are using it nowadays. For example, google, Instagram, Netflix. Also, Python is a multipurpose language. It can be used for data analysis, automation, path planning, etc.

### Github
![GitHub-Logo](https://user-images.githubusercontent.com/116060401/204120089-ef548a36-1ef1-48c1-8b3b-a00ef122fc31.png)

Github is a social network for software developer. It is a place for software developer to share, communicate with others. Also, it is easy for developer to collaborate. In a repository, developer can safely make changes to the code in different branches and they can be merge when the code is finished.

## Task1

### Methodology
We modified the programme code based on the sample code. We changed the position of the obstacles, cost intensive areas and change the additional flight time in the cost intensive area into 20% and 40%. therefore, we are able to get the required flight time for our route. First, we consider if the aircraft type A321-neo, A330-900neo, and A350-900 can carry all the passenger in the scenarios. Then, we calculate the trip cost of the three aircraft type in three different scenarios manually to find the lowestcost of operating (Using the formula: C = CF x F + CT x T + Cc).
 
### Results

The shortest path:

![abc](https://user-images.githubusercontent.com/116060401/200479713-8ce624a1-2d1f-4e88-a3b2-7cbec7a2e828.jpg)

Total Trip time required ->  103.075

Equation to calculate the cost:

![Cost plane](https://user-images.githubusercontent.com/116060401/201833649-1aebf860-7c2f-4fc9-94c3-f28ecac8d739.jpg)

### Scenario 1
<li>3000 passengers need to travel within this week</li>
<li>12 flights maximum for one week</li>
<li>Time cost is medium and fuel cost is 0.76$/kg</li>

A321: (0.76* 54* 103.075+15* 103.075+1800)*15 = cant fit requirement 

A330: (0.76* 84* 103.075+21* 103.075+2000) *10=$107448.83

A350: (0.76* 90* 103.075+27* 103.075+2500)*9= $111000.195

Answer is 10 flights of A330

### Scenario 2
<li>1250 passengers need to travel within this month</li>
<li>5 flight maximum for one week</li>
<li>Time cost is high and fuel cost is 0.88$/kg</li>

A321: (0.88* 54* 103.075+20* 103.075+1800)*7 =  $61317.368

A330: ( 0.88* 84* 103.075+27* 103.075+2000 )*5=  $62011.645

A350: (0.88* 90* 103.075+34* 103.075+2500)*4= $56672.36

Answer is 4 flights of A350

### Scenario 3
<li>2500 passenger need to travel within this week</li>
<li>25 flights maximun for one week</li>
<li>time cost is low and fuel cost is 0.95$/kg</li>

A321: (0.76* 54* 103.075+10* 103.075+1800)*13 = $91792.324

A330: ( 0.76* 84* 103.075+15* 103.075+2000) *9=  $91137.897

A350: (0.76* 90* 103.075+20* 103.075+2500)*8= $92894.64

Answer is 9 flights of A330

### Discussion
Path planning is an important component in aviation industry. The purpose of path planning is to find a shortest route that can minimise the operating cost. By considering the cost of fuel, time cost, fixed cost to selected the aircraft type that have the lowest cost.

## Task2

### Methodology
The cost along the jet stream is reduced by 5%. Using the scenario 1 of Task1 as the background, setting up the jet stream that the most of the path pass through it is the best choice. After finding the new required time cost, use the formula(C = CF x F + CT x T + Cc) to calsulate the new cost.

### Results 

Plan after adding a jet stream

![Figure_jetarea](https://user-images.githubusercontent.com/116060401/201840762-6d383a5f-26f2-4416-bffe-ea89878d7e95.png)

Time required= 102.268

Cost of 10 A330: (0.76* 84* 102.268+21* 102.268+2000) *10 =106764.17

The cost have reduced:107448.83-136764.17=$684.66

### Discussion
Jet stream is a high speed flowing that can reduce the cost of fuel when passing through it. Therefore, flying through the jet stream may have a lower cost than following the shortest path.

## Task3

### Methodology 
In  this task, we need to design a new aircraft to best fit Scenario 1 in task 1. In order to fit the requirement, we use the data we get in the program. In order to meet the requirement of making the most efficiency plane, we choose twin-engine plane instead of 4-engine aircraft since the passenger capacity we designed is 250. Twin-engine already fit our basic need. Apart from that, twin-engine has a lower fixed cost compare to 4-engine. 
### Results

![Cost plane](https://user-images.githubusercontent.com/116060401/201833649-1aebf860-7c2f-4fc9-94c3-f28ecac8d739.jpg)

Plane name : A-grade plane 

Passanger :250 CT $18/min 

Engine count :2 so fixed cost CC is $2000 

Fuel consumption rate CF 40 kg/min 

Fuel cost F :$ 0.8823/kg  

Cost= $7462.9 

### Discussion
By designing a new aircraft model, the minimum cost can be achieved. However, the model have to match the task requirement such as A380 are for large global transport hubs.

## Reflective Essay

### Enzi's reflection:

In this project, I was stuck in the coding session. Before starting this project, I do not have any coding experience by myself. I just tried to copy and paste the code into other lessons. Therefore, coding is a difficult part for me. Using task 1 as an example, I can change the cost-intensive area and the obstacle referring to the template. However, as the mark bonus for calculating by coding, I tried three lessons to make it and I am still not able to build the code. Finally, I calculate the cost manually. Communicating is another challenge for me. This is my first group project in my university life. It is so difficult to divide jobs among my groupmates as I do not know my groupmates at first.

Overall, this group project gives me more experience in different aspects. The knowledge of path planning, choosing aircraft, etc. is also interesting.

### Rachel's reflection:

Participating in this project has broaden my horizon in the coding field, before getting to the university, I was totally a noob who know nothing about coding, hence, in the beginning, I was afraid to write code since this is the very first time I have ever wrote. Fortunately, our groupmates are good at coding therefore we assigned the job-coding to them and others are responsible for another work such as writing report. During the past few lessons, I had reckoned my groupmate was struggling in this project, at that moment, I had a glance at the task we were trying to figure out, I wanted to solve the issue with them but I do not have the ability to do so as I do not have enough intelligence in this field. Even so, I never give up in participating in this project, I would like to improve my coding skill and also I found the sense of accomplishment after I solved one of the issues with my groupmates due to I did not avoid the obstacle, thus, I appreciate myself have tried to get away from my comfort zone and tried something new.

### Bonald's reflection:

Honestly, I had yet to learn about path planning and coding before I joined this lecture. In my experience, flying an aircraft is so straightforward that the flight passes from one country to another. But during this lecture, I discovered a whole new world in this lecture by learning. I find that private pilots do the path plan before the flight to ensure the navigation aid is available. It is also the best way to fly a complete route in the shortest possible time and with the least amount of fuel. However coding is also of great importance in this project, but it is also a weakness of mine. Luckily, my teammates could go due the coding so that I could focus on the paragraph planning. When I was doing the part on the Theory of Path Planning Algorithms and Background of Path Planning in Aviation Engineering, I also learned more about path planning which can provide the best solution to passengers and airlines. Passengers can get lower prices and shorter flights; airlines can also get better cost-effectiveness during daily operations.
 
### Matthew's reflection:
In this project, we were stuck on the coding part for quite a long time, since no one in our team was familiar with the programming. At first, we tried to write a program to help us fulfil the requirement on task 1, but we failed to do it. So, we list all the data, do the calculations manually, and solve the problem we have faced. For task 2, we meet the requirement by modifying the program, it relies on communication between me and my team. We have discussed serval times on how to change the program so that to do the task successfully. Although we are not successful in the coding part of the project, we’ve learnt a lot in both aviation and programming. For example, using an a-star path-finding algorithm to find the shortest route between two points. Moreover, I’ve also known more about the factors in choosing a suitable plane to fly the route, like the number of passengers, fuel consumption rate and trip time. To summarize, I think this project help me to learn the importance of corporate with others. Without the efforts of each member, It is impossible to finish the project, no matter the coding part or the present part.

### Hinson's reflection:
I was a complete beginner when I first arrived at the university, so being a part of this project has broadened my horizons in the world of coding. As a result, at first, I was hesitant to write any code because it was the first time I had ever written. Fortunately, some of our group members are skilled coders, so we assigned them the responsibility of coding while others were tasked with other parts like the report, presentation,etc. In earlier courses, I saw that one of my group members was having trouble with this assignment. I saw the issue we were attempting to resolve at the time and wanted to assist, but I lacked the skills to do so. But I've always wanted to take part in this project. I want to get better at coding, and after working with my group to overcome a problem, I felt proud of myself for not just ignoring it. Because I made an effort to expand myself, I'm pleased of myself.

### John's reflection:
I've never before used Github. To be completely honest, some Github features are challenging to grasp at first. such as how to post my code or modify a group member's code. However, every issue was resolved within the first week. Even if we all perform our tasks, occasionally we run into issues. My hardest task is actually the first one. I was unable to comprehend the code at that point. Finding the areas where I need to change is difficult for me. I gained a lot of knowledge throughout the project, which has helped us use github more easily. The second and third tasks are more challenging. My task two code can execute at first, but the outcome is not what I expected. although the answer is incorrect, Finding the source of the issue took a lot of time. I don't have the ability to complete some tasks, but I'm eager to learn and improve my coding skills. I've gained more experience in a variety of areas thanks to the project. It's a pleasure to be there.


## References

AAHK. (2021). Finalized Civil International Air Traffic Statistics at HKIA Year 2021. Hong Kong International Airport - Passenger Home. https://www.hongkongairport.com/iwov-resources/file/the-airport/hkia-at-a-glance/facts-figures/2021e.pdf
