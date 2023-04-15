# Talent, Luck or Vision?

An easy python reproduction and modification of the 2022 Ig Nobel Prize for Economics 
<br>**"Which Is More Important: Talent or Luck?"**<br>
<img src="https://i.imgur.com/h3TOqKD.png" width="600px">

## Rules

### Original rules
1. There are *N_people* people in the town with different talent. Each person has a starting property 10
2. There are *N_luck* luck events and *N_unluck* unlucky events randomly occur in the town at every iteration
3. When a person meets a lucky event, the property is doubled based on talent
4. When a person meets an unlucky event, the property becomes half

### Extra rules:
5. Lucky event cannot occur if unlucky event occurs
6. Lucky event occurs if it is within an individual's vision

## Experiments:
N_people = 1000<br>
N_luck = 250<br>
N_unluck = 250<br>

Distribution of Talent and vision :
<br><img src="https://i.imgur.com/koifqfr.png" width="300px"><img src="https://i.imgur.com/CxTnKS3.png" width="300px">

*Note: Talent distribution and Vision distribution are independent*

### Scenario 1: Different talent + Same vision (similar to the original experiment)
The final property is not so relevent to talent.
<br><img src="https://i.imgur.com/v9mH1CC.png" width="300px">


### Scenario 2: Same talent + Different vision
The final property is very relevent to vision.
<br><img src="https://i.imgur.com/MeJsBqC.png" width="300px">


### Scenario 3: Different talent + Different vision
The final property is not so relevent to talent*vision
<br><img src="https://i.imgur.com/qLJTVQj.png" width="300px">

## Credits
The idea of adding vision factor comes from my understanding of an YouTube video made by [老高與小茉](https://www.youtube.com/watch?v=qzIfQ5_gYzc)