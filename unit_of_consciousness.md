# What is the unit of utility?

This question is relevant for utilitarians who need to aggregate happiness (or positive valence, utility, whatever) among different beings.

A year ago I would have said something like:
- $ utility = sum happiness(being) for all beings $
- $ happeniss(being) = integral_t valence(being, t) dt $
It basically shifts the problem from defining utility into defining valence, and then finding a unit for valence that can compare different beings.
From revealed preferences etc, we can approximately infer the utility function of a single being. This allows us to further decompose:
- $ valence(being, t) = c * integral_t relative valence(being, t) dt $
Where relative valence is 0 if the being is indifferent if it experiences more such moments or less, and 1 in the global utility maximum of that being. 
Great, now we reduced the problem of defining utility into observing preferences (which is emperically possible) and then defining a constant c that holds all the trouble now.
Of course, it is not a coincidence that this `c` can be short for consciousness. This is how I believe many people intuitively think about moral dillemas that involve animals and humans. Saving 1 human from torture is worth saving N pigs, etc.
It has some more nice intuitive properties:
- we can trade off a shorter very happy time against a longer slightly less happy time, which we frequently do
- it is the only form any coherent utility function can take, see coherence axioms. (despite defining the dimension we integrate over, but more on that later). If we say happiness is utility, and we want to be able act coherently towards more happiness, we must assume this form

 Since I thought more about wether or not time is continuous and if digitl computers can have consciousness, I have a few doubts about this:
 - the integral assumes time is continuous, and qualia happens in the transition rather than in a resting state. This model does not work for digitsl computers, which can computationally not experience time continuously
 - if we don't want to make assumptions about wether or not AI can experience happiness, we must also allow a discrete form:
    $ valence(AI, t) = c * sum_t relative valence(AI, t) $
   Now the unit is totally different: for the AI we have a sum of how it felt at different discrete steps, but for humans we have 
