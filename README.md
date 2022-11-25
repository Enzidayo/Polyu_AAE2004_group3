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

GUO Qiuxi

HO Tsz Hin [Hin-Zz]

HO Yan Chak [Enzidayo]

## Introduction
Since the invention of the aircraft, navigation always is an important part of aviation. To solve the navigation problem effectively, people try to use AI technology, also known as Path planning. Path planning is the computational problem to find a sequence of valid configurations that moves the object from the source to the destination. 

According to the air traffic statistics provided by AAHK, HKIA recorded approximately 145,000 air traffic movements in 2021. The airspace is fully in-used to handle all the flights. To balance flight efficiency and cost, path planning is important to generate the maximum benefit in a flight operation. By path planning, the designer can fulfill all the constraints to ensure the best use of the crowded airspace and designs an optimized route for aircraft operation. 

In the project, we are going to practice path planning by writing a Python program that helps us to design and calculate the optimized path with the lowest cost and choose the best aircraft model under given scenarios in each task.

## Background of Path Planning to Aviation Engineering
Aircraft flying is all about 'value for money'. The best way to fly a complete route in the shortest possible time and with the least amount of fuel is based on cost-effectiveness. The first thing that comes to mind when forming such an optimal route is that the shorter the route, the better!

From the passenger's point of view, it is essential to plan the shortest possible flight path. Suppose a passenger is travelling on a multi-transfer flight. In that case, flight time is generally one of the decisive factors in the passenger's choice, and more passengers prefer a combination of shorter flights. For airlines and airports, planning the shortest possible multi-route route can help attract passengers.

The value of the shortest distance route is the cost savings. For airlines, shorter flight distances can help them to reduce their overheads if the cost per unit of distance is fixed. This idea of saving costs by planning the shortest route can be applied to passenger and cargo transport.

## Theory of Path Planning Algorithm
Path planning is a calculation problem. It can find an effective sequence of configurations to move the object from its source to its destination. For a given situation, the flight can choose the best aircraft model with an optimised route based on this algorithm, finding the optimal or near-optimal path from the starting state to the target state for obstacle avoidance, minimising the operational cost of the aircraft.

When the tough competitive environment is forcing airlines to consider every aspect of their operating costs, airlines want to minimise the cost of flying by choosing the right route, altitude and speed, and by loading the least amount of necessary fuel on board so that path planning is invented. It can provide optimum economic benefits by calculating the direct operating costs when fuel, time, distance flown, number of passengers, etc. are all important factors to consider. By the formula: C = CF x F + CT x T + Cc, we can easily understand, without resorting to complex mathematics, that the total cost of a particular trip is the sum of fixed and variable costs.

##Introduction of the Engineering Tools

### Python

### Github

## Task1

### Methodology
 
### Results

The shortest path

![abc](https://user-images.githubusercontent.com/116060401/200479713-8ce624a1-2d1f-4e88-a3b2-7cbec7a2e828.jpg)

Total Trip time required ->  103.075

Equation to calculate the cost:

![Cost plane](https://user-images.githubusercontent.com/116060401/201833649-1aebf860-7c2f-4fc9-94c3-f28ecac8d739.jpg)

### Scenario 1
<li>3000 passengers need to travel within this week</li>
<li>12 flights maximum for one week</li>
<li>Time cost is medium and fuel cost is 0.76$/kg</li>

A321: (0.76*54* 103.075+15* 103.075+1800)*15 = cant fit requirement 

A330: (0.76*84* 103.075+21* 103.075+2000) *10=$107448.83

A350:(0.76*90* 103.075+27* 103.075+2500)*9= $111000.195

A330 is the most suitable flight.

### Scenario 2
<li>1250 passengers need to travel within this month</li>
<li>5 flight maximum for one week</li>
<li>Time cost is high and fuel cost is 0.88$/kg</li>

A321: (0.88*54* 103.075+20* 103.075+1800)*7 =  $61317.368

A330:( 0.88*84* 103.075+27* 103.075+2000 )*5=  $62011.645

A350:(0.88*90* 103.075+34* 103.075+2500)*4= $56672.36

A350 is the most suitable flight.

### Scenario 3
<li>2500 passenger need to travel within this week</li>
<li>25 flights maximun for one week</li>
<li>time cost is low and fuel cost is 0.95$/kg</li>

A321: (0.76*54* 103.075+10* 103.075+1800)*13 = $91792.324

A330:( 0.76*84* 103.075+15* 103.075+2000) *9=  $91137.897

A350:(0.76*90* 103.075+20* 103.075+2500)*8= $92894.64

A321 is the most suitable flight.

### Discussion

## Task2

### Methodology 

###Results 

Plan after adding a jet stream

![Figure_jetarea](https://user-images.githubusercontent.com/116060401/201840762-6d383a5f-26f2-4416-bffe-ea89878d7e95.png)

Time required= 102.268

### Discussion

## Task3

### Methodology 

### Results

![Cost plane](https://user-images.githubusercontent.com/116060401/201833649-1aebf860-7c2f-4fc9-94c3-f28ecac8d739.jpg)

Plane name : A-grade plane 

Passanger :250 CT $18/min 

Engine count :2 so fixed cost CC is $2000 

Fuel consumption rate CF 40 kg/min 

Fuel cost F :$ 0.8823/kg  

Cost= $7462.9 

### Discussion

## Reflective Essay

### Enzi's reflection:

In this project, I was stuck in the coding session. Before starting this project, I do not have any coding experience by myself. I just tried to copy and paste the code into other lessons. Therefore, coding is a difficult part for me. Using task 1 as an example, I can change the cost-intensive area and the obstacle referring to the template. However, as the mark bonus for calculating by coding, I tried three lessons to make it and I am still not able to build the code. Finally, I calculate the cost manually. Communicating is another challenge for me. This is my first group project in my university life. It is so difficult to divide jobs among my groupmates as I do not know my groupmates at first.

Overall, this group project gives me more experience in different aspects. The knowledge of path planning, choosing aircraft, etc. is also interesting.

### Rachel's reflection:

Participating in this project has broaden my horizon in the coding field, before getting to the university, I was totally a noob who know nothing about coding, hence, in the beginning, I was afraid to write code since this is the very first time I have ever wrote. Fortunately, our groupmates are good at coding therefore we assigned the job-coding to them and others are responsible for another work such as writing report. During the past few lessons, I had reckoned my groupmate was struggling in this project, at that moment, I had a glance at the task we were trying to figure out, I wanted to solve the issue with them but I do not have the ability to do so as I do not have enough intelligence in this field. Even so, I never give up in participating in this project, I would like to improve my coding skill and also I found the sense of accomplishment after I solved one of the issues with my groupmates due to I did not avoid the obstacle, thus, I appreciate myself have tried to get away from my comfort zone and tried something new.

### Bonald's reflection:

Honestly, I had yet to learn about path planning and coding before I joined this lecture. In my experience, flying an aircraft is so straightforward that the flight passes from one country to another. But during this lecture, I discovered a whole new world in this lecture by learning. I find that private pilots do the path plan before the flight to ensure the navigation aid is available. It is also the best way to fly a complete route in the shortest possible time and with the least amount of fuel. However coding is also of great importance in this project, but it is also a weakness of mine. Luckily, my teammates could go due the coding so that I could focus on the paragraph planning. When I was doing the part on the Theory of Path Planning Algorithms and Background of Path Planning in Aviation Engineering, I also learned more about path planning which can provide the best solution to passengers and airlines. Passengers can get lower prices and shorter flights; airlines can also get better cost-effectiveness during daily operations.

## References
