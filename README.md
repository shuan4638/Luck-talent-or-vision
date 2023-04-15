# Talent, Luck or Vision?

An easy python reproduction and modification of the 2022 Ig Nobel Prize for Economics **"Which Is More Important: Talent or Luck?"**

## Rules

### Default rules
1. There are *N_people* in the town with different talent  and each person has a starting property 10
2. There are *N_luck* luck events and *N_unluck* unlucky events randomly occur in the town at every iteration
3. When a person meets a lucky event, the property is doubled based on talent
4. When a person meets an unlucky event, the property becomes half

### Extra rules:
5. Lucky event cannot occur if unlucky event occurs
6. Lucky event is can still occurs if a person has larger vision

## Experiments:
N_people = 1000
N_luck = 250
N_unluck = 250

Distribution of Talent and vision :
<br><img src="https://i.imgur.com/5vE0FKR.png" width="300px"><img src="https://i.imgur.com/DWSmqE1.png" width="300px">

*Note: Talent distribution and Vision distribution are independent*

### Scenario 1: Different talent + Same vision
The final property is not relevent to talent
<br><img src="https://i.imgur.com/Wp8chQd.png" width="300px">


### Scenario 2: Same talent + Different vision
The final property is very relevent to vision

<br><img src="https://i.imgur.com/W6G3PWB.png" width="300px">


### Scenario 3: Different talent + Different vision
The final property is relevent to both talent and vision
<br><img src="https://i.imgur.com/jv0YmO1.png" width="300px">
