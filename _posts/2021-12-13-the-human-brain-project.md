---
title:  "Brain in-silico? The Human Brain Project and why full-on brain simulation is a bad idea."
header:
  image: "/assets/images/scaffold_model.jpeg"
  caption: "Photo credit: [**EBRAINS**](https://ebrains-cls-interactive.github.io/)"
categories: 
  - science
tags:
  - opinion
  - simulation
---

One of my biggest aspiration in science had been to simulate the brain in its full glory -- an intelligent automata in silico. If science fictions and forward-thinking scientists and entrepreneurs have taught us anything, it is that artificial intelligence is the future, and when our robot overlords inevitably rule over the world, they would certainly think in favor of those who created them.

Just kidding, the root of my brain-mania had been a philosophical one: to understand myself in the deepest way possible. As Dr. Feynman famously decreed, in a stereotypical physicist / engineer fashion:
# “What I cannot create, I do not understand”
Being able to create something is the pinnacle form of understanding. There are different ways in which this quote could be interpreted. Did Dr. Feynamn mean **when we understand something, we could then create it** or **in order to understand something, we have to try to create it first** ? Bear this question in mind as you read on.

# The Human Brain Project
The Human Brain Project, and its predecessor the Blue Brain Project, are aimed at simulating the brain in the human brain in the most biologically-detailed fashion. To achieve that, the scientists first simulated small chunks of rat brain. They aspire to model the entire brain in the same way. Sounds fun, right? However, the approach was controversial and caused quite a debate back in the days.

The inception and controversy around these simulation projects had accompanied me throughout my academic journey: in late 2000s when I started middle school, the Blue Brain Project launched; around the time I finished high school, the Human Brain Project launched, and later received massive criticism from the neuroscience community; now, as I embark on neuroscience research, the project quietly wraps up to an end. Since the goal of the HBP perfectly aligns with my early scientific interests, it was particularly hard for me to process the community backlash on the project.

Why, you might ask, would such an interesting project receive so much criticism? Let us first examine the premise of the project: to model single neurons and their connections on a biophysical level, and observe the phenomenon that emerge. Critics see the idea as fundamentally flawed. Here is why:

# It is inaccurate
Simulation, even at its finest, is not replication. The simulation performed in the HBP is mainly based on cable models of single-cell morphology. It basically says: the neurons are a bunch of electric wires, and their electrophysiological properties are mainly determined by their shapes. However, this kind of simplification omits many key biological processes that govern the activity and connectivity of neurons. Unfortunately, the majority of these mechanisms are still poorly understood, despite the rapid progression of the field in general.

In addition, simulations beyond single neurons rely on rough and inaccurate connectomes that do not faithfully represent neural interactions. In practice, many of the circuit-level parameters have to be tuned (guessed) in order for the network to properly function. The process induces so much subjectivity that it could hardly be called realistic.

The brain is a complex system. Although it appears to be well-organized on different levels (networks, circuits, neurons), there is no guarantee that these abstractions would preserve its function. It could be argued that the neural system is very resilient to noise and disturbances, but omission and distortion at the most fundamental level could be fatal nonetheless. This is not to say that neuron-level simulations cannot provide interesting findings, but that they are unlikely to reproduce brain functionality on any broader level.

# It is costly
If that is all the problem with the HBP, it probably would not have caused a public outcry. After all, advances in science is all about risk-taking. All the visionary projects in scientific history have been heroic adventures or terrible mistakes. However, the failure of the original HBP is no small mistake -- it would have been a costly mistake. The European Commission allegedly granted the project 1 billion euros, money which could have kept hundreds of small labs afloat for years. The level of opportunity cost, added to the wild and unpredictable nature of the project, made the missteps in the HBP so unforgivable.

Where did the money go then? To quell your potential doubts: no, it was not embezzled, although the leadership of the project had been called to question. The answer is that simulation is costly! The computer resources needed to simulate a single neuron (from a simple voltage model to a multi-compartmental model) is already a lot. A network model with thousand of neurons, plus their connections is at the cutting-edge of computer resource usage currently. The HBP used exascale supercomputers to run its simulation algorithm. To simulate a network with the size of the human brain, (depending on the algorithm) all the computers in the world piled together could be far from enough. The cost of the machines, their maintenance and the electric bill is astronomical already. The lack of computation power is, and will continue to be, the major obstacle of large-scale simulations.

# It is lazy
So the project is risky and costly. What of it? During the cold war, the US and the USSR had launched people into space, repeatedly, just to get a kick out of it. If you are an explorer like me, sometimes all the admonitions in the world would not keep you from diving into the unknown. But consider this: what did the HBP hope to find by the simulation?

Let us revisit the question at the beginning: did Dr. Feynman mean simulation is required to further understanding, or that a good understanding precedes successful simulation? Advocates for large-scale brain simulations would argue it is the former. But the answer is both, probably. Good simulation is founded on solid understanding of the system to be simulated, and its goal is to inspire better understandings. In many ways, the HBP simulations had been premature: they lack a solid foundation of understanding, and predict no specific finding. The philosophy was kind of "let's just do this and see if anything happens". Granted, from an engineering perspective it is something to behold. However, as a research project, it is ill-conceived at best and intellectually lazy at worst.

As the saying goes, 'Let he who is without sin cast the first stone'. I will take a moment to repent. I have taken part in many 'exploratory' projects that are obscure about potential findings. Sometimes life feels like a big exploratory project, and I am merely bumping around trying to find something. But that is what communities are for -- a collective of intellectual people who generate a direction through opinions and feedback. There are people in my life (and online) that continue to direct and motivate my research, and help me better frame my questions.

Large directives like the HBP particularly need community feedbacks. In 2014, an open letter, cosigned by ~750 renowned scientists forced the HBP to change its course from extravagant simulations to smaller, goal-driven simulations, and to build the public simulation platform EBRAIN that could benefit studies in the field. On the other hand, the frenzy for "Big Science" is just beginning to sweep over the global science community. Collaboration is an unstoppable trend in science. However, it seems that focused, hypothesis-driven research will continue to be the most important form of scientific investigation.

# Do not despair
Hopefully I have convinced you, at least a little, that at the current stage of neuroscience, large-scale brain simulation is a bad idea. It is interesting, but compared to the vast mysteries of the brain, it is uneconomic to pursue such a question. Simulations will develop on par with the theories. And when the time is ripe, maybe this approach could be revisited.

The lessons from the HBP should be carefully considered for everyone seeking to work with single-neuron models or network models based on connectomes (more of a reevaluation than a discouragement). First, think of possible hypothesis and outcomes. Know what to expect. Second, start small, not big. Do not go full super computer unless there is a solid reason for it. Third, dive deep into the nitty gritty of molecular, systems and cognitive neuroscience to seek theoretical foundations for the work.

Theories are hard, and computational theories are even harder. But ultimately, technology and theory are the two indispensable wheels that keep the field in motion.

Is simulating the brain with a computer theoretically possible? What current models are there neuroscientists currently toying with? More on this later. Remember to come back and check out the latest posts!

# Bibliography
[Human Brain Project Home](https://www.humanbrainproject.eu/en/)

[Human Brain Project - EBRAINS  interactive simulation platform](https://ebrains-cls-interactive.github.io/)

[The Scientific Case for Brain Simulations](https://www.sciencedirect.com/science/article/pii/S0896627319302909) Science. 2019.

[The Human Brain Project Hasn’t Lived Up to Its Promise](https://www.theatlantic.com/science/archive/2019/07/ten-years-human-brain-project-simulation-markram-ted-talk/594493/) The Atlantic. 2019.

[Why the Human Brain Project Went Wrong—and How to Fix It](https://www.scientificamerican.com/article/why-the-human-brain-project-went-wrong-and-how-to-fix-it/) Scientific American. 2015.

[The Big Problem With “Big Science” Ventures—Like the Human Brain Project](https://nautil.us/blog/the-big-problem-with-big-science-ventureslike-the-human-brain-project) Nautilus. 2015.

[Rethinking the brain](https://www.nature.com/articles/519389a) Nature. 2015.

[Rat brain—or a smidgeon of it—is modeled in a computer](https://www.science.org/content/article/rat-brain-or-smidgeon-it-modeled-computer) Science. 2015.