# Polyu_AAE2004_group3
<!-- TABLE OF CONTENTS -->
<details>
  <summery>Table of contents</summary>
  <ol>
    <li><a href="## Member">Member</a> 
    <li><a href="## Introduction">Introduction</a></li>
    <li><a href="## Task1">Task1</a></li>
        <ul>
          <li><a href= "### Scenario-1">Scenario 1</a></li>
          <li><a href= "### Scenario-2">Scenario 2</a></li>
          <li><a href= "### Scenario-3">Scenario 3</a></li>
        </ul>  
    <li><a href="## Task2">Task2</a></li>
    <li><a href="## Task3">Task3</a></li>
  </ol>
</details>

## Member
CHEUNG Tin Lam

CHEUNG Wing Hin

CHU Chenyi

Chui Lung Kwun Bonald

GUO Qiuxi

HO Tsz Hin

HO Yan Chak

## Introduction
Since the invention of the aircraft, navigation always is an important part of aviation. To solve the navigation problem effectively, people try to use AI technology, also known as Path planning. Path planning is the computational problem to find a sequence of valid configurations that moves the object from the source to the destination. 

According to the air traffic statistics provided by AAHK, HKIA recorded approximately 145,000 air traffic movements in 2021. The airspace is fully in-used to handle all the flights. To balance flight efficiency and cost, path planning is important to generate the maximum benefit in a flight operation. By path planning, the designer can fulfill all the constraints to ensure the best use of the crowded airspace and designs an optimized route for aircraft operation. 

In the project, we are going to practice path planning by writing a Python program that helps us to design and calculate the optimized path with the lowest cost and choose the best aircraft model under given scenarios in each task.

## Task1
Goal: Find the shortest route from departure point to the arrival point and determine the aircraft type for each scenario

The shortest path

![abc](https://user-images.githubusercontent.com/116060401/200479713-8ce624a1-2d1f-4e88-a3b2-7cbec7a2e828.jpg)

Total Trip time required ->  102.50966799187796

### Scenario 1
<li>3000 passengers need to travel within this week</li>
<li>12 flights maximum for one week</li>
<li>Time cost is medium and fuel cost is 0.76$/kg</li>


Result:

A321: (0.76*54* 102.50966799187796+15* 102.50966799187796+1800)*15 = cant fit requirement 

A330: (0.76*84* 102.50966799187796+21* 102.50966799187796+2000) *10=$106969.2 

A350:(0.76*90* 102.50966799187796+27* 102.50966799187796+2500)*9= $110514.8 

A330 is the most suitable flight.

### Scenario 2
<li>1250 passengers need to travel within this month</li>
<li>5 flight maximum for one week</li>
<li>Time cost is high and fuel cost is 0.88$/kg</li>


Result:

A321: (0.88*54* 102.50966799187796+20* 102.50966799187796+1800)*7 =  $61050.16948 

A330:( 0.88*84* 102.50966799187796+27* 102.50966799187796+2000 )*5=  $6172637847 

A350:(0.88*90* 102.50966799187796+34* 102.50966799187796+2500)*4= $ $56416.37767 

A350 is the most suitable flight.

### Scenario 3
<li>2500 passenger need to travel within this week</li>
<li>25 flights maximun for one week</li>
<li>time cost is low and fuel cost is 0.95$/kg</li>


Result:

A321: (0.76*54* 102.50966799187796+10* 102.50966799187796+1800)*13 = $105089.9 

A330:( 0.76*84* 102.50966799187796+15* 102.50966799187796+2000) *9=  $105461.2 

A350:(0.76*90* 102.50966799187796+20* 102.50966799187796+2500)*8= $106518.15 

A321 is the most suitable flight.

## Task2
Goal: recreate a jet stream that could benefit the flight route the most

Plan after adding a jet stream


## Task3
Goal: 
