# PrimacyRL
Reset the last layer for exploration in RL.

# Abstract of the original paper
"The Primacy Bias in Deep Reinforcement Learning"

Evgenii Nikishin, Max Schwarzer, Pierluca D’Oro, Pierre-Luc Bacon, Aaron Courville

This work identifies a common flaw of deep reinforcement learning (RL) algorithms: a tendency
to rely on early interactions and ignore useful evidence encountered later. Because of training on
progressively growing datasets, deep RL agents
incur a risk of overfitting to earlier experiences,
negatively affecting the rest of the learning process. Inspired by cognitive science, we refer to
this effect as the primacy bias. Through a series
of experiments, we dissect the algorithmic aspects
of deep RL that exacerbate this bias. We then propose a simple yet generally-applicable mechanism
that tackles the primacy bias by periodically resetting a part of the agent. We apply this mechanism
to algorithms in both discrete (Atari 100k) and
continuous action (DeepMind Control Suite) domains, consistently improving their performance.

"Your assumptions are your windows on the world. Scrub
them off every once in a while, or the light won’t come in.”
–Isaac Asimov

# Useful links
* Dopamine Notebooks: https://github.com/google/dopamine/tree/master/dopamine/colab
