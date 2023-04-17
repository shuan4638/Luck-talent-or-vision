# Talent, Luck or Vision?

An simple python reproduction and modification of the 2022 Ig Nobel Prize for Economics 
<br>**"Which Is More Important: Talent or Luck?"**<br>
<img src="https://i.imgur.com/h3TOqKD.png" width="600px">

## Rules

### Original rules
1. There are *N* people in the town with different talent. Each person has a starting capital 10
2. There are *N_E/2* luck events and *N_E/2* unlucky events randomly occur in the town at every iteration
3. When a person meets a lucky event, the capital is doubled based on talent
4. When a person meets an unlucky event, the capital becomes half

### Extra rules:
5. Unlucky event does not occurs if an individual's has high caution
6. Lucky event occurs if it is within an individual's vision

## Experiments:
For simplicity, I make the town to one-dimension

N = 100, N_E= 50, town_size = 4000 <br>

- People with higher **talent** have more chances to seize the luck
- People with higher **caution** have fewer chances to meet unlucky events
- People with higher **vision** have more chances to meet lucky events


Distribution of Talent and vision :
<br><img src="https://i.imgur.com/koifqfr.png" width="300px"><img src="https://i.imgur.com/ELr5Baf.png" width="300px"> <img src="https://i.imgur.com/RrILMvV.png" width="300px">

*Note: Distributions of  talent, caution and vision are independent*


### Scenario 1: Different talent (similar to the original experiment)
The final capital is not so relevent to talent. Color indicates the talent of each person in town.

<br><img src="https://i.imgur.com/x4ciqpo.png" width="300px">


### Scenario 2: Different talent and caution

The final capital is relevent to caution. Color indicates the talent of each person in town.

<br><img src="https://i.imgur.com/hIHDQmb.png" width="300px">


### Scenario 3: Different talent and vision
The final capital is more relevent to vision. Color indicates the talent of each person in town.

<br><img src="https://i.imgur.com/Py3h9Wu.png" width="300px">


## Credits
The ideas of adding caution and vision come from my understanding of an YouTube video made by [老高與小茉](https://www.youtube.com/watch?v=qzIfQ5_gYzc)

## Reference
```bibtex
@article{biondo2018talent,
  title={Talent vs Luck: the role of randomness in success and failure},
  author={Biondo, A Pluchino and Rapisarda, A and others},
  journal={arXiv preprint arXiv:1802.07068},
  year={2018}

```