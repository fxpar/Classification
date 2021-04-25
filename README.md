
https://user-images.githubusercontent.com/11584406/115980568-00113980-a58e-11eb-9129-4007997978c8.mp4

# Classification
Educational classification game activity project. (no right / wrong)
Proof of concept for a possible future H5P activity.
*(Check the technicals below for details)*

## Purpose
Before learning theories, student need to get accustomed with the material. 
By manipulating pieces of the next topic, they start to figure the problem the class will try to solve.
By trying to connect the topics, student start to question their understanding, and provide material for the teacher to start with.
This activity is "free" for the students, no right /wrong answer: it is about opening the box in the attic, and discovering what is inside.
Helps memorizing because trying to find links is a great way to fix topic and remember things.



## How to play
1. Participants drag and drop cards from a given deck
2. ORGANIZING: Cards can be grouped when droped on top of one another
3. NAMING: Names can be given to cards / groups
4. CREATIVITY: A set of empty cards can be used to add new topics by the students
5. Would be great to be able to reuse the deck, augmented by students additions, for next activity

# Examples
* Countries https://codepen.io/frapar/full/gOgqMZp
* Questions (in french) https://codepen.io/frapar/full/ExZrwqX

## Educational scenario
### Animals (step 1)
> With your team buddy, organize these animals in 2 groups

This is a guided question, with a precise number of grouping. (better as a first step than a free grouping).
Helps discover the set of animals.

> Try giving a name to each group

* with legs / without
* with wings
* eggs or not
* on earth or water (what about in between?)
* eat meat or not

> Add an empty card to each group and write on it the name of another animal you think about and could be in this group

### Animals (step 2)
> Use the deck (including the animals you added *not yet implemented*) to try and organize in categories and sub-categories


# Technical aspects
## Pros
This solution uses fieldset which looks quite ok.
## Cons
I used the fieldset of the destination card as group legend... which make impossible to ungroup this card.
## Improvement needed
Make the groups by adding a fieldset independant from the cards
