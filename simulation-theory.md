# Are we living in a simulation?

## The simulation argument
The simulation hypothesis proposes a fascinating question: could our universe be a computer-generated simulation? This idea, inspired by technological advancements, suggests that future civilizations might create simulations of their past or similar universes, leading to numerous nested virtual worlds. The intriguing question arises: Are we, in fact, inhabitants of such a simulation?

Nick Bostrom's seminal paper posits that one of three possibilities is true: (1) humanity is likely to become extinct before reaching a posthuman stage; (2) posthuman civilizations would probably not run significant numbers of simulations of their evolutionary history; or (3) we are almost certainly living in a computer simulation. This essay examines these propositions, exploring the likelihood of physics-based and mind-based simulations, and concludes by addressing some potential implications of living in a simulated world.

## Should we expect posthuman civilizations to be rare?
Simulations might be rare for two reasons: simulation-capable civilizations almost never come into existence, or simulation-capable civilizations almost never run a significant number of simulations. If either of these cases is true, for (almost) every mind wondering whether it exists in a simulated universe, the correct answer would be “No”.

The Fermi Paradox provides some evidence to suspect that posthuman civilizations are rare in our universe: if they were common, we would have seen some Dyson spheres or other signs of such advanced civilizations. However, a number of theories have been proposed that explain this observation while assuming that multiple civilizations will reach a posthuman stage: these theories include the [grabby alien model](https://grabbyaliens.com/) and the [dark forest hypothesis](https://en.wikipedia.org/wiki/Dark_forest_hypothesis).

Overall, I think it is unlikely that no posthuman civilization will ever exist, mainly because a small portion of the time has passed in which our universe allows life to form, and humans or human-built AI seem pretty close (>10% chance) to becoming a posthuman civilization within the next millennium already. In addition to that, we wouldn’t know if the parent universe follows the same laws of physics as ours, and therefore, even if simulations were unlikely to be built in our universe, we could not conclude our that universe is also unlikely to be simulated.

## Types of simulations
We can think of two different types of simulations: physics-based and mind-based. In a physics-based simulation, all of the fundamental particles and waves are simulated, and minds like ours can emerge through evolution if physics allows for sufficiently complex structures. In contrast, a mind-based simulation does not simulate all the unobserved details of the universe and instead focuses mostly or only on what is needed in order to produce experiences like ours.

## Computational limits of physics-based simulations
Let’s consider the information storage and computational resources needed to run a physics-based simulation. For any two distinguishable states of a simulation, there must be at least two distinguishable states of the computer running the simulation. Therefore, the bits needed to describe the state of the computer in its universe must be at least as many as the total entropy of the simulated universe. Similarly, if the simulation can compute function x, the parent universe also computes x via the simulation. Therefore, the total computational power of the simulation is smaller than that of its parent. Note that this does not rely on any specific physical laws of our universe, it follows purely from information-theoretic arguments.

As a consequence, any civilization running a physics simulation can only simulate a universe with smaller total computational power and entropy than available to them in their own universe. If we make the assumption that the root universe is unlikely to spend most of its computational power and entropy on running simulations, we should conclude that much more is happening in the root universe than in all simulated ones combined.

The simulation argument hinges not on the ratio of expected simulations to root universes, it hinges on the expected ratio of simulated minds to minds that exist in the root universe. If a physics simulation and its parent use a similar percentage of their respective computations to produce minds that ponder the simulation argument, this ratio strongly favors the hypothesis that we are in the root universe - where most of the entropy and computations happen.

However, this is a strong assumption - it is plausible that a posthuman civilization is running a simulation of specifically life-friendly universes, and seed them with simulated life from the beginning. This increases the number of minds per entropy and compute, and could favor the simulation hypothesis if the average posthuman civilization spends more compute on ancestor simulations than their actual ancestors used up for their existence. We can’t rule out this possibility entirely, but it seems very unlikely - what convergent goal of posthumans would all those simulators be optimizing for? Why wouldn’t they spend their compute on “future simulations”, or “happiness simulations”, or optimize for any other goal that does not involve running a large number of ancestor simulations? Note that our universe also seems like the kind that wastes most computation on dead stars, rather than being optimized for mind density.

Overall, I think we should expect the total number of minds that exist within physics-based ancestor simulations to be tiny compared to the number of minds existing in the root universe or non-ancestor simulations - potentially in the range of 1:10^12-1:10^100.

## Are mind-based simulations more likely?
Maybe posthumans look for a more efficient way to run ancestor simulations. They might explore running mind-based simulations, in which they only simulate our minds and the world around us - abstracting away all the individual atoms and details that are not perceived.

One could argue that autoregressive language models like [GPT produce a world simulation](https://www.lesswrong.com/posts/vJFdjigzmcXMhNTsx/simulators) of some kind. If agent simulacra pondering the simulation hypothesis produce subjective experiences sufficiently similar to ours, we should include these simulacra when we count the minds that exist in and outside of simulations - we might be one after all. In this situation, object permanence, the continuity of time, and our entire reality might be an illusion, our experience would not be governed by the laws of physics or a very close approximation of it, but by the state transition function of the algorithm that is GPT, and we might not have a past or future beyond the short moment in which the simulator predicts how agents like us behave. We would be akin to Boltzmann brains, not existing in an empty real universe, but being a temporary emergent property of a model trying to predict agents.

For the sake of this essay, I will ignore this possibility, even though it’s interesting. It is not what we usually think of when we speak about ancestor simulations, and very hard to reason about.

Here, I want to focus on simulations in which object permanence and time progression exist in the way we usually assume about our universe. This would be the case for a computer game world populated with simulated minds, whose computation happens outside of the physics engine, and whose physics engine is cleverly implemented to not compute unnecessary details. This is something humans are doing already, and if the AI used for NPCs becomes as intelligent as humans, they might also wonder whether their game environment is the root universe or not. At this point, they should be counted in the ratio of expected simulated minds to expected root universe minds. However, by default, their observation about their environment would differ in at least one important way from ours: they could not locate their own brain. We can observe the effects of brain surgery, brain injuries, drug consumption, etc. and thereby identify the brain - an object within our physical universe - as the source of our cognition. An NPC in a game will be in a different situation unless the game is specifically designed to simulate this effect, which remains a possibility.

Would it be possible to simulate our experiences using much less computation and entropy than our world appears to have? In order for this to happen, every observation of every mind must be consistent with each other and the physical laws we have detected. Whenever a mind interacts with the world, the engine must be able to come up with observations that satisfy all the constraints created by previous mind-world interactions. It is unclear to me if this is possible without also simplifying the observable rules of physics, but my bet is that this is not possible, fo the reasons explained below.

There are some ways in which we can test if our environment performs a lot of computations outside of our brains: processes that are computationally hard to simulate but easy for us to verify. Some processes that we observe that fit into this category include:
- Fluid dynamics - we can perform repeated experiments of fluids and observe that they behave in a consistent way that is computationally hard to simulate
- We can build a large number of chaotic pendula, run them for a long time, and randomly check on one of them later to validate that the simulators didn’t cheat and just set the pendulum to a random state that looks plausible enough to us
- Evolution - however, simulators might be able to seed a simulation with the outcome of an evolutionary process of their home universe
- Actual computers built from silicon - these computers can run proof-of-work algorithms, or train AI models, or run all the other computationally intense programs we run on them. A simulation that spends little computation on physics would not allow many such computers.
- Probably a lot of other processes in quantum mechanics, microbiology, or chaotical system

All in all, our universe seems to be full of processes that are computationally hard to simulate to the level of consistency as we observe it. Our universe appears to not be the result of a mind-simulation that is optimized for a high mind density per compute or entropy.

## Are we living in a simulation?
In the previous sections, I argued that we should expect posthuman civilizations to exist in the future and that these civilizations might run various types of simulations. However, we should expect orders of magnitudes fewer minds to exist within physics-based simulations, and we should expect mind-based simulations to look different than the observed universe. Conditioned on object permanence being real, this gives us the following estimates:
- P(no posthumans, no simulation) in [10^-100, 10^-1]
- P(physics simulation | posthumans) in [10^-12,10^-100]
- P(mind simulation | posthumans) in [10^-10, 10^-3]

The high upper bound for my estimate of P(mind simulation | posthumans) is mostly because the arguments against the mind-based simulations rely on more assumptions and inference steps that might be wrong. However, we can still note that the combined probability of us living inside of a simulation should be below (10^-3 + 10^-12), i.e. roughly 1:1000.

Where does that put us in Nick Bostrom’s framework?
It depends on what you consider to be an ancestral simulation: if it is required for the simulation to be similar to our universe in the sense that it is full of computationally hard phenomena, these arguments point towards (2) being true - we will never be able to build them at scale.
If one also considers computationally simpler universes to count as ancestral simulation, these arguments point towards (1), (2), and (3) all being false at the same time.

## What if we are living in a simulation?

Finally, let’s consider the practical implications of this question. How should our credence of living in a simulation affect our actions? Broadly speaking, we should act more myopic if we knew we were living in a simulation, we might want to try to initiate trade or communication with the simulators, and we might learn new facts about computational physics and sentience.

The reason to act more myopic is simple: a simulation could be turned off. In particular, longtermist arguments should be discounted more the higher the chance of us living in a simulation. For any utility function we might be optimizing for, we would need to discount future utility by the probability of the simulation being turned off by then. Mathematically, this resembles the expected discounted reward formulation that we use to train RL agents:

E[utility | simulation] = Integral_t E[utility(t) | no simulation] * p(simulation keeps running one more day)^t

It would, however, be difficult to reason about the adequate likelihood of the simulation being turned off per year: how should we know for how long the simulators typically run a simulation?

We might also try to initiate communication with the simulators and convince them not to turn off the simulation, or initiate trade. The one thing we know about our simulators is that they are technologically advanced and more likely than not to pursue goals that make them run simulations. Plausible reasons for an advanced civilization to run simulations of our universe include:
- The simulators value complexity or sentience, or some other property that our universe has. Our universe has intrinsic value to them because it produces these valued properties.
- (On a side note, I give higher credence to this explanation in moments of extreme happiness - those seem like the experiences I would simulate if I had the ability.) 
- The simulators want to learn something - this seems like a plausible reason for a posthuman civilization to run ancestor simulations

In both cases, our actions can affect the value of our simulation to the simulators. A very speculative consequence might be that we should try to keep any rate of change low: if the universe right now is to the simulator's satisfaction, and we don’t know anything else about them, maybe we should not change it too much and risk that they lose interest in keeping it running.

Another plausible (but not necessarily probable) goal of the simulators might be to learn about how e.g. AI alignment will turn out. That can again be viewed as a reason to keep change rates low and slow down AI research because as soon as the simulators find out what they want, continuing to simulate us may no longer be in their interest.

However, it’s also possible to make a plausible argument for the opposite case: they might turn us off if our simulation turns out to be inefficient. The best course of action might even be to try to ask them what they want from us. On the other hand, if they thought we should know they might as well tell us directly. Due to the highly speculative nature of these arguments, I would put very little weight on them and rather view them as potential starting points for further research and discussion.

Besides acting more myopic, and trying to reason about the simulators’ intentions, we would also learn that consciousness can arise from computation. While there is plenty of reason to believe this regardless of the simulation hypothesis, [we cannot prove it](https://en.wikipedia.org/wiki/Hard_problem_of_consciousness), and [competing theories](https://miro.com/app/board/uXjVMtbLEJw=/?share_link_id=755750042563) exist. If we were certain that we live in a simulation that produces our consciousness, we could be certain that consciousness is computational. As a result, some people including me would be inclined to replicate this and directly optimize for happiness - we could mind-simulate a universe tiled with rats on heroin, for example.

## A note on computability and physics
The dominant paradigms of computability are Turing machines, Lambda calculus, and other equivalent models. All of them work on discrete inputs and outputs and can be implemented using discrete intermediate states and state transitions. It is currently unclear whether or not the physical laws of our universe are also discrete. If space and time are in fact continuous, no Turing machine could ever be able to simulate our physical universe: they could not even represent the initial conditions, as they would require an infinite number of bits.

However, a continuous universe would not prove that we are not being simulated: our simulators might be using a different type of computer. If we try to extend the concept of a Turing machine to a computational model powerful enough to simulate physics, it could look similar to this:
- the state of the continuous Turing machine contains real-valued vectors
- the state transition function is a set of differential equations with respect to a continuous state index t

Exploring the implications of this computational model could yield insights that affect the computation- and entropy-based arguments presented earlier - we know for example that differential entropy behaves quite differently than entropy.
