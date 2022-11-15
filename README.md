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
Path planning is computatuonal problem to find a sequence of a valid configurations that moves the object from the source to destination. It is important in aviation engineering. Path planning can help consider suitable aircraft models, reduce flight time, and reduce flight costs. 

## Task1
Goal: Find the shortest route from departure point to the arrival point and determine the aircraft type for each scenario

The shortest path

![abc](https://user-images.githubusercontent.com/116060401/200479713-8ce624a1-2d1f-4e88-a3b2-7cbec7a2e828.jpg)

Total Trip time required ->  102.50966799187796

Equation to calculate the cost:

![Cost plane](https://user-images.githubusercontent.com/116060401/201833649-1aebf860-7c2f-4fc9-94c3-f28ecac8d739.jpg)


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
Goal: Design a new aircraft to best fit scenario 1 in task 1

![Cost plane](https://user-images.githubusercontent.com/116060401/201833649-1aebf860-7c2f-4fc9-94c3-f28ecac8d739.jpg)

Plane name : A-grade plane 

Passanger :250 CT $18/min 

Engine count :2 so fixed cost CC is $2000 

Fuel consumption rate CF 40 kg/min 

Fuel cost F :$ 0.8823/kg  

Cost= $7462.9 
